# 4. Knowledge Gap and Significance

## 4.1 Knowledge Gap

Empirical and mechanistic models, including the Power-law, Bingham plastic, and Carreau models, have long been used to represent the rheological behaviour of energised foams under controlled experimental conditions (Al-Darweesh et al., 2024; Ghorbani, 2025). Although these models provide valuable insights into apparent viscosity and yield behaviour, their parameters and simplifying assumptions may not remain transferable across the coupled nonlinear interactions among pressure, temperature, shear rate, foam quality, surfactant chemistry, nanoparticle concentration, salinity, and gas-phase characteristics encountered under HPHT conditions. This limits confidence in their generalisation across different formulations and operating environments (Gonzalez Perdomo and Wan Madihi, 2022).

Recent studies have increasingly applied machine learning techniques, including Random Forest, XGBoost, and Artificial Neural Networks, to capture nonlinear relationships and predict foam rheological properties (Al-Darweesh et al., 2024; Ghassemzadeh et al., 2021). However, the available studies rely predominantly on laboratory-scale and formulation-specific datasets, with limited representation of diverse and coupled HPHT conditions. Their predictive performance is therefore closely tied to the conditions represented in the available data. Where models provide only deterministic point predictions, uncertainty arising from sparse data, experimental variability, and extrapolation beyond the training range remains unquantified.

Uncertainty quantification has been applied in other areas of petroleum engineering, including reservoir characterisation and production forecasting (Ogbidi and Oteh, 2023; Zhang et al., 2025), but its integration with predictive modelling of nanoparticle-stabilised energised foam rheology remains limited. Consequently, existing approaches provide limited information about prediction reliability under sparse, unfamiliar, or extrapolated HPHT conditions. This matters because uncertainty in predicted apparent viscosity and foam stability may affect the identification of suitable formulation and operating ranges and subsequent engineering assessments of proppant suspension and transport.

The limitations identified across existing rheological, experimental, and data-driven approaches are synthesised in the Critical Gap Matrix presented in Table 4.1.

**Table 4.1. Critical Knowledge Gap Matrix**

|   |   |   |   |   |
|---|---|---|---|---|
|**Existing Research**|**Primary Capability**|**Key Limitation**|**Engineering Implication**|**Key References**|
|Empirical rheology models|Estimate apparent viscosity and yield stress|Simplified assumptions and limited applicability under HPHT conditions|Reduced confidence in fracturing-fluid design|Ahmed et al. (2022); Li et al. (2021)|
|Mechanistic models|Represent baseline physical behaviour|Limited representation of coupled nonlinear interactions|Reduced predictive reliability during hydraulic fracturing operations|Singh et al. (2023); Wang et al. (2022)|
|Random Forest / XGBoost models|Predict rheological properties|Predominantly laboratory-scale datasets and deterministic outputs|Limited generalisation to field-scale HPHT applications|Zhang et al. (2024); Liu et al. (2023)|
|Artificial Neural Networks|Learn complex nonlinear relationships|Limited model interpretability and absence of uncertainty estimation|Reduced confidence in engineering decision-making|Kumar et al. (2024); Chen et al. (2023)|
|Existing uncertainty quantification studies|Quantify predictive uncertainty in petroleum engineering applications|Limited application to nanoparticle-stabilised energised foam rheology|Limited support for risk-informed hydraulic fracturing design and operating-window selection|Ogbidi & Oteh (2023); Smith et al. (2024)|

**_Source:_** _Developed by the author. **Note**: The table synthesises the dominant research streams and engineering limitations identified from the reviewed literature. The representative references are illustrative rather than exhaustive and correspond to the studies discussed in Section 2_

As shown in Table 4.1, the research gap is not attributable to a single methodological limitation, but to the lack of integration between HPHT-relevant data, nonlinear prediction, uncertainty quantification, and engineering interpretation.

## 4.2 Significance of the Research

Therefore, a significant scientific and engineering gap remains. Existing empirical, mechanistic, and data-driven approaches have not yet adequately integrated heterogeneous HPHT foam data, nonlinear prediction of apparent viscosity and foam stability, explicit uncertainty quantification, and engineering interpretation within a coherent framework. Addressing this gap requires an uncertainty-aware predictive framework capable of assessing model reliability across variable HPHT conditions and supporting candidate operating-window identification for further laboratory and engineering evaluation. Such a framework could support fracturing-fluid design by providing not only predictions of foam behaviour, but also an indication of the confidence and limitations associated with those predictions.