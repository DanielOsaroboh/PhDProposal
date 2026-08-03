
### **How uncertainty quantification would be implemented in practice**

In practice, I would implement uncertainty quantification as a structured part of the modelling workflow, rather than as an additional step after prediction. The aim would be to provide not only a predicted value for apparent viscosity or foam stability, but also a measure of how reliable that prediction is under a given HPHT condition.

First, I would distinguish between two main sources of uncertainty:

- **Aleatoric uncertainty**, arising from experimental noise, measurement variability, and natural variation in foam behaviour.
    
- **Epistemic uncertainty**, arising from limited data, model limitations, and predictions made outside well-represented regions of the dataset.
    

The practical implementation would involve the following process.

**1. Develop multiple predictive models**

I would train models such as Random Forest, XGBoost, Support Vector Regression, and Artificial Neural Networks. Using several model classes would help determine whether uncertainty is associated with one particular algorithm or is consistently present across different modelling approaches.

**2. Use ensemble and resampling methods**

For tree-based models, I would use bootstrapping or ensemble approaches. The model would be trained repeatedly on slightly different samples of the dataset. For each operating condition, the spread of the resulting predictions would provide an estimate of prediction uncertainty.

For example, instead of reporting only:

> Predicted apparent viscosity = 120 mPa·s

the model could report:

> Predicted apparent viscosity = 120 mPa·s, with a 95% prediction interval of 105–138 mPa·s.

A narrow interval would indicate relatively high confidence, while a wide interval would show that the prediction is less reliable.

**3. Apply Monte Carlo dropout for neural networks**

Where neural networks are used, dropout would remain active during repeated prediction runs. This is known as Monte Carlo dropout. The same input would be passed through the network many times, producing a distribution of predicted values rather than one deterministic result.

The mean of this distribution would represent the final prediction, while its standard deviation or confidence interval would represent model uncertainty.

**4. Construct prediction intervals**

The models would produce lower and upper prediction bounds for apparent viscosity and foam-stability indicators. These intervals would be evaluated using:

- empirical coverage probability,
    
- interval width,
    
- calibration plots,
    
- and comparison between predicted and observed values.
    

A well-calibrated 95% prediction interval should contain approximately 95% of the observed test values.

**5. Evaluate uncertainty under sparse and extrapolated conditions**

I would specifically examine model behaviour in regions where the data are limited, such as very high temperatures, pressures, foam qualities, or nanoparticle concentrations. Predictions made far from the training-data range should display higher uncertainty.

This is important because a model may produce a numerical prediction under an unfamiliar HPHT condition, but that does not necessarily mean the prediction is dependable. The uncertainty estimate would therefore act as a warning against unsafe extrapolation.

**6. Calibrate and validate the uncertainty estimates**

The estimated uncertainty would be checked against independent test data or laboratory results. Methods such as calibration curves, residual analysis, and interval coverage testing would be used to determine whether the uncertainty bounds are realistic.

Where the intervals are too narrow or too wide, calibration methods could be applied to improve their reliability.

**7. Integrate uncertainty into operating-window identification**

The uncertainty estimates would then be incorporated into hydraulic fracturing-fluid design. A formulation would not be classified as suitable simply because its mean predicted viscosity or foam stability meets an engineering threshold.

Instead, the lower confidence bound would also need to satisfy the required performance criterion.

For example, suppose the required apparent viscosity for adequate proppant transport is 100 mPa·s:

- A predicted viscosity of 120 mPa·s with an interval of 112–130 mPa·s may be considered reliable.
    
- A predicted viscosity of 120 mPa·s with an interval of 70–170 mPa·s would be treated cautiously because the lower bound falls below the required value.
    

This would allow operating windows to be classified as:

- **high-confidence operating regions**, where performance requirements are met with narrow uncertainty;
    
- **cautionary regions**, where predicted performance is acceptable but uncertainty is high;
    
- **unacceptable regions**, where performance requirements are not met or uncertainty is excessive.
    

This approach is consistent with the proposed framework, which treats uncertainty quantification as the link between prediction and engineering decision-making, particularly under sparse or extrapolated HPHT conditions.

Overall, uncertainty quantification would be implemented through repeated model training, prediction distributions, calibrated confidence intervals, extrapolation checks, and uncertainty-based operating-window selection. The purpose is not merely to improve statistical reporting, but to ensure that hydraulic fracturing-fluid decisions are based on both predicted performance and the reliability of those predictions.