
# Summary 

> **I would manage the problem through systematic data extraction and harmonisation, careful quality control, models appropriate to the available sample size, grouped validation, and explicit uncertainty quantification. Most importantly, I would allow the available physical evidence to determine the complexity and scope of the modelling rather than assuming in advance that the dataset can support a complex ML framework.**



# Notes 
### 1. Data Compilation

- I would collect data from **multiple published experimental sources** rather than depend on one dataset.
    
- I would systematically extract and digitise relevant HPHT foam measurements.
    

### 2. Data Harmonisation

- I would **standardise units, variable names, measurement definitions, and experimental conditions**.
    
- I would only combine datasets where they are **scientifically comparable**.
    

### 3. Data Quality

- I would check for **missing values, inconsistencies, duplicates, outliers, and incomplete experimental information**.
    
- I would document the **source and experimental context** of each observation.
    

### 4. Model Complexity

- I would match the **complexity of the ML model to the amount and quality of available data**.
    
- If the dataset is small, I would avoid unnecessarily complex models that are likely to overfit.
    

### 5. Validation

- I would use appropriate validation, including **[[THK-0092 - Grouped Validation|grouped validation]]**, so that observations from the same study or formulation do not create overly optimistic performance estimates.
    
- I would distinguish **[[THK-0096 - Interpolation–Extrapolation Distinction|interpolation from extrapolation]]**.
    

### 6. Uncertainty

- I would explicitly quantify **[[THK-0028 - Predictive Uncertainty|predictive uncertainty]]**.
    
- Sparse or unfamiliar regions of the data should generally lead to **greater caution and potentially greater uncertainty**, rather than unjustified confidence.
    

### 7. Scope Adaptation

- I would assess **dataset adequacy before fixing the final modelling complexity**.
    
- If the available data are insufficient, I would broaden the data search or **reduce the modelling scope to what the evidence can support**.
    

