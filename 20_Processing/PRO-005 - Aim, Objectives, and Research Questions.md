Section 5 is structurally different from Sections 2–4. It contains less new **domain knowledge** and much more **research architecture**: aim → questions → objectives → deliverables → framework outputs.

We should therefore avoid turning every research question into a THK. Most of them point back to knowledge objects already in the vault.

### 1. Extraction decision

|Action|THK|Knowledge object|Type|
|---|---|---|---|
|Enrich|`THK-0054`|Integrated HPHT Foam Prediction Framework|Framework|
|Enrich|`THK-0057`|Multivariable Control of Foam Performance|Mechanism|
|Enrich|`THK-0024`|Machine Learning for Foam Rheology|Method|
|Enrich|`THK-0028`|Predictive Uncertainty|Concept|
|Enrich|`THK-0051`|Model Reliability under Unfamiliar Conditions|Problem|
|Enrich|`THK-0049`|Operating-Window Identification|Decision Process|
|Enrich|`THK-0053`|Engineering Interpretation of Predictions|Principle|
|Enrich|`THK-0041`|Proppant Transport|Engineering Function|
|**New**|`THK-0072`|HPHT Foam Dataset Compilation and Structuring|Method|
|**New**|`THK-0073`|Comparative ML Model Evaluation for Foam Prediction|Method|
|**New**|`THK-0074`|Uncertainty-Based Model Reliability Assessment|Method|
|**New**|`THK-0075`|Constraint-Based Foam Operating Window|Decision Process|
|**New**|`THK-0076`|Engineering Evaluation of Foam Model Outputs|Method/Decision Process|

I would **not create separate THKs for the Aim or each Research Question**. Those belong in a **research architecture HUB**, because they organise the research rather than constitute reusable domain knowledge.

---

# Existing-note enrichments

## `THK-0054 - Integrated HPHT Foam Prediction Framework`

Add:

```markdown
## Research Aim Alignment

The doctoral research operationalises this framework through the aim of
developing an uncertainty-aware predictive framework for HPHT energised
foam design.

The framework is intended to integrate four principal capabilities:

1. prediction of apparent viscosity;
2. prediction of foam stability;
3. quantification of predictive uncertainty;
4. identification of candidate operating windows.

## Research Architecture

The framework can be represented as:

HPHT Foam Data
        ↓
Variable and Relationship Analysis
        ↓
Machine-Learning Prediction
        ↓
Apparent Viscosity + Foam Stability
        ↓
Uncertainty Quantification
        ↓
Model Reliability Assessment
        ↓
Operating-Window Identification
        ↓
Engineering Interpretation
        ↓
Fracturing-Fluid Design
        +
Proppant-Transport Assessment

## Research Questions Supported

The framework addresses four linked questions:

### Control

Which formulation and operating variables most strongly control foam
viscosity and stability?

### Prediction

How accurately can machine-learning models predict these properties?

### Reliability

How uncertain are those predictions, particularly under sparse or
extrapolated HPHT conditions?

### Engineering Use

How can reliability-aware predictions support operating-window
identification and subsequent engineering assessment?

## Intended Framework Output

The intended contribution is therefore not a prediction model alone.

It is an integrated decision-support structure connecting:

Prediction
+
Uncertainty
+
Reliability
+
Operating Window
+
Engineering Interpretation
```

---

## `THK-0057 - Multivariable Control of Foam Performance`

Add:

```markdown
## Research Investigation

The research explicitly investigates which formulation and operating
variables most strongly influence apparent viscosity and foam stability.

Variables of interest include:

- pressure;
- temperature;
- fluid composition;
- salinity;
- foam quality;
- chemical formulation;
- shear conditions.

The analytical problem is therefore:

Multiple Candidate Variables
        ↓
Relative and interacting influence
        ↓
Apparent viscosity
        +
Foam stability

This moves the research beyond establishing that variables affect foam
behaviour toward determining which variables provide the strongest
predictive and engineering information under HPHT conditions.
```

---

## `THK-0024 - Machine Learning for Foam Rheology`

Add:

```markdown
## Role in the Doctoral Research

Machine learning is used as the principal nonlinear predictive approach
for modelling apparent viscosity and foam stability.

The methodological role is:

Structured HPHT Dataset
        ↓
Selected ML Models
        ↓
Model Development
        ↓
Comparative Evaluation
        ↓
Viscosity + Stability Prediction
        ↓
Uncertainty and Reliability Assessment

Importantly, the research does not assume that one machine-learning
algorithm is inherently optimal.

Selected models are to be developed and compared empirically using
appropriate predictive-performance and reliability criteria.
```

---

## `THK-0028 - Predictive Uncertainty`

Add:

```markdown
## Explicit Research Role

Predictive uncertainty is an explicit research output rather than a
secondary statistical consideration.

The research asks:

> How can prediction uncertainty be quantified and incorporated into
> the interpretation of foam-rheology models?

The intended analytical progression is:

Point Prediction
        ↓
Uncertainty Quantification
        ↓
Reliability Assessment
        ↓
Reliability-Aware Interpretation
        ↓
Engineering Use

Thus uncertainty becomes part of the interpretation of model output
rather than information reported separately from the engineering
problem.
```

---

## `THK-0051 - Model Reliability under Unfamiliar Conditions`

Add:

```markdown
## Explicit Reliability Test Domain

The doctoral research specifically evaluates model reliability under:

- sparse HPHT conditions;
- extrapolated HPHT conditions.

This creates a stronger test than overall predictive accuracy alone.

Model evaluation therefore asks two distinct questions:

1. How accurately does the model predict?
2. How reliable is the prediction when empirical support becomes weak?

This distinction is central to determining whether a predictive model
can support engineering interpretation beyond well-represented regions
of the dataset.
```

---

## `THK-0049 - Operating-Window Identification`

Add:

```markdown
## Role in the Research

Operating-window identification represents a major engineering output
of the predictive framework.

The research seeks to move from:

Prediction
        ↓
Property value

toward:

Prediction
+
Uncertainty
+
Reservoir constraints
+
Treatment constraints
        ↓
Candidate operating window

The operating window therefore represents a decision layer constructed
from model outputs rather than a direct machine-learning output.

Its purpose is to identify combinations of formulation and operating
conditions that warrant further laboratory and engineering evaluation.
```

---

## `THK-0053 - Engineering Interpretation of Predictions`

Add:

```markdown
## Research Application

Engineering interpretation forms the final translation layer of the
research.

Model outputs are evaluated in relation to:

- fracturing-fluid design;
- operating-condition selection;
- proppant transport assessment.

The analytical progression is:

Model Output
        ↓
Uncertainty / Reliability
        ↓
Engineering Criteria
        ↓
Interpretation
        ↓
Candidate Decision Support

This preserves an important boundary:

The predictive framework supports engineering evaluation; it does not
replace complete hydraulic-fracturing design or field validation.
```

---

# New atomic notes

## `THK-0072 - HPHT Foam Dataset Compilation and Structuring`

```markdown
---
id: THK-0072
title: HPHT Foam Dataset Compilation and Structuring
type: method
domain: Petroleum Engineering
topic: HPHT Foam Predictive Modelling
status: developed
source_context: PhD Aim Objectives and Research Questions
---

# THK-0072 - HPHT Foam Dataset Compilation and Structuring

## Definition

HPHT foam dataset compilation and structuring is the systematic process
of identifying, extracting, harmonising, and organising experimental
and literature-derived foam data for subsequent predictive modelling.

## Purpose

The method creates the empirical foundation required for machine-learning
prediction of:

- [[THK-0005 - Foam Apparent Viscosity]];
- [[THK-0006 - Foam Stability]].

## Data Sources

The research proposes to use available:

- experimental datasets;
- published literature data.

## Target Variables

The structured dataset may include:

### Operating Variables

- pressure;
- temperature;
- shear conditions.

### Formulation Variables

- foam quality;
- salinity;
- fluid composition;
- surfactant characteristics;
- nanoparticle concentration;
- gas-phase characteristics.

### Response Variables

- apparent viscosity;
- foam-stability indicators.

## Method Structure

Raw Experimental / Literature Data
        ↓
Identification and Extraction
        ↓
Variable Definition
        ↓
Unit Harmonisation
        ↓
Data Structuring
        ↓
Quality Assessment
        ↓
Model-Ready HPHT Dataset

## Why Structuring Matters

Data obtained from different studies may vary in:

- terminology;
- measurement methods;
- units;
- operating ranges;
- formulations;
- reported outputs.

Without systematic structuring, these differences can reduce
comparability and introduce inconsistencies into predictive modelling.

## Research Role

This method corresponds directly to the first research objective and
provides the input layer for subsequent machine-learning and uncertainty
analysis.

## Related Notes

- [[THK-0013 - Fragmented HPHT Experimental Evidence]]
- [[THK-0014 - Limited HPHT Experimental Coverage]]
- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0066 - Laboratory-Scale Data Dependence]]
- [[THK-0067 - Formulation-Specific Data Dependence]]
- [[THK-0068 - Data-Domain-Dependent Predictive Performance]]

## Hubs

- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T07 - Methods]]
```

---

## `THK-0073 - Comparative ML Model Evaluation for Foam Prediction`

```markdown
---
id: THK-0073
title: Comparative ML Model Evaluation for Foam Prediction
type: method
domain: Petroleum Engineering
topic: Machine Learning for Foam Rheology
status: developed
source_context: PhD Aim Objectives and Research Questions
---

# THK-0073 - Comparative ML Model Evaluation for Foam Prediction

## Definition

Comparative ML model evaluation is the systematic development and
comparison of selected machine-learning models for predicting HPHT foam
properties.

## Purpose

The method determines how effectively alternative ML approaches predict:

- apparent viscosity;
- foam-stability indicators.

## Method Pattern

Structured HPHT Dataset
        ↓
Selected ML Algorithms
        ↓
Model Training
        ↓
Model Validation / Testing
        ↓
Performance Comparison
        ↓
Reliability Assessment
        ↓
Model Interpretation

## Candidate Models

The literature reviewed in the research identifies approaches including:

- [[THK-0064 - Random Forest Foam Prediction]];
- [[THK-0025 - XGBoost Foam Prediction]];
- [[THK-0026 - ANN Foam Prediction]].

The final model set should follow the research methodology rather than
assuming that every available algorithm must be used.

## Comparison Principle

Model selection should not rely solely on whether an algorithm can fit
nonlinear data.

The evaluation should consider:

Predictive Accuracy
+
Generalisation
+
Reliability
+
Uncertainty
+
Engineering Interpretability

## Research Question

This method directly addresses:

> How accurately can machine-learning models predict apparent viscosity
> and foam stability across varying HPHT and formulation conditions?

## Research Significance

Comparative evaluation prevents the research contribution from being
defined by allegiance to one algorithm.

The central issue becomes which modelling approach provides sufficiently
useful and reliable predictions for the intended engineering problem.

## Related Notes

- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0025 - XGBoost Foam Prediction]]
- [[THK-0026 - ANN Foam Prediction]]
- [[THK-0064 - Random Forest Foam Prediction]]
- [[THK-0051 - Model Reliability under Unfamiliar Conditions]]
- [[THK-0074 - Uncertainty-Based Model Reliability Assessment]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
- [[HUB-T07 - Methods]]
```

---

## `THK-0074 - Uncertainty-Based Model Reliability Assessment`

```markdown
---
id: THK-0074
title: Uncertainty-Based Model Reliability Assessment
type: method
domain: Petroleum Engineering
topic: Predictive Uncertainty
status: developed
source_context: PhD Aim Objectives and Research Questions
---

# THK-0074 - Uncertainty-Based Model Reliability Assessment

## Definition

Uncertainty-based model reliability assessment is the systematic
evaluation of how confidence in model predictions changes across
different regions of the HPHT data and operating domain.

## Core Question

The method asks:

> How reliable is this prediction given the available evidence and the
> condition at which the prediction is being made?

## Assessment Context

Particular attention is given to:

- sparse conditions;
- unfamiliar conditions;
- extrapolated conditions;
- experimentally variable conditions.

## Method Structure

Model Prediction
        ↓
Prediction Location within Data Domain
        +
Uncertainty Estimate
        ↓
Reliability Assessment
        ↓
Engineering Interpretation

## Reliability Logic

Well-supported region:

Dense / familiar data
        ↓
Stronger empirical support
        ↓
Potentially greater prediction confidence

Poorly supported region:

Sparse / extrapolated data
        ↓
Weaker empirical support
        ↓
Potentially greater predictive uncertainty
        ↓
Greater interpretive caution

## Important Distinction

Predictive accuracy and predictive reliability are related but not
identical.

A model may demonstrate acceptable average accuracy while individual
predictions in poorly represented regions remain comparatively
uncertain.

## Research Role

The method operationalises the third research objective:

> Quantify prediction uncertainty and assess model reliability under
> sparse or extrapolated HPHT conditions.

## Engineering Significance

Reliability information can help distinguish candidate operating
conditions supported strongly by available evidence from conditions
requiring additional experimental evaluation.

## Related Notes

- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0029 - Sparse-Data Uncertainty]]
- [[THK-0030 - Extrapolation Uncertainty]]
- [[THK-0051 - Model Reliability under Unfamiliar Conditions]]
- [[THK-0065 - Experimental Variability Uncertainty]]
- [[THK-0068 - Data-Domain-Dependent Predictive Performance]]
- [[THK-0075 - Constraint-Based Foam Operating Window]]

## Hubs

- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T07 - Methods]]
```

---

## `THK-0075 - Constraint-Based Foam Operating Window`

```markdown
---
id: THK-0075
title: Constraint-Based Foam Operating Window
type: decision process
domain: Petroleum Engineering
topic: HPHT Foam Design
status: developed
source_context: PhD Aim Objectives and Research Questions
---

# THK-0075 - Constraint-Based Foam Operating Window

## Definition

A constraint-based foam operating window is a region of formulation and
operating conditions identified as potentially suitable by evaluating
predicted foam performance, predictive uncertainty, and defined
reservoir and treatment constraints.

## Core Idea

An operating window should not be identified from predicted performance
alone.

It emerges from the intersection of:

Predicted Foam Performance
        +
Prediction Reliability
        +
Reservoir Constraints
        +
Treatment Constraints

## Decision Structure

HPHT Formulation / Operating Conditions
        ↓
ML Prediction
        ↓
Viscosity + Stability
        ↓
Uncertainty Assessment
        ↓
Apply Reservoir Constraints
        +
Apply Treatment Constraints
        ↓
Accept / Reject / Further Evaluate
        ↓
Candidate Operating Window

## Constraint Types

Potential constraints can include:

### Reservoir Constraints

- pressure range;
- temperature range;
- formation conditions.

### Treatment Constraints

- required rheological behaviour;
- stability requirements;
- proppant-transport requirements;
- operational limits.

The exact constraints must be defined by the research methodology and
engineering application.

## Why Uncertainty Matters

Two conditions may have similar predicted foam performance but different
levels of prediction reliability.

Therefore:

Predicted Suitability
        ≠
Equivalent Decision Confidence

## Output

The process identifies **candidate** operating windows.

It does not automatically establish field-safe operating conditions
without further experimental and engineering validation.

## Research Role

This decision process directly operationalises the fourth research
objective.

## Related Notes

- [[THK-0048 - Candidate Operating Window]]
- [[THK-0049 - Operating-Window Identification]]
- [[THK-0052 - Uncertainty-Aware Foam Prediction]]
- [[THK-0060 - Prediction Reliability–Fluid Design Link]]
- [[THK-0068 - Data-Domain-Dependent Predictive Performance]]
- [[THK-0074 - Uncertainty-Based Model Reliability Assessment]]
- [[THK-0076 - Engineering Evaluation of Foam Model Outputs]]

## Hubs

- [[HUB-05 - Engineering Performance]]
- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T16 - Decision Processes]]
```

---

## `THK-0076 - Engineering Evaluation of Foam Model Outputs`

```markdown
---
id: THK-0076
title: Engineering Evaluation of Foam Model Outputs
type: method
domain: Petroleum Engineering
topic: HPHT Foam Engineering Interpretation
status: developed
source_context: PhD Aim Objectives and Research Questions
---

# THK-0076 - Engineering Evaluation of Foam Model Outputs

## Definition

Engineering evaluation of foam model outputs is the systematic
interpretation of predicted foam properties and associated uncertainty
in relation to hydraulic-fracturing engineering requirements.

## Purpose

The method bridges the gap between:

> model performance

and

> engineering usefulness.

## Model Outputs

The evaluation begins with:

- predicted apparent viscosity;
- predicted foam stability;
- associated uncertainty;
- model-reliability information.

## Engineering Context

These outputs are interpreted in relation to:

- fracturing-fluid design;
- candidate operating conditions;
- proppant suspension;
- proppant transport.

## Evaluation Chain

Model Predictions
        ↓
Uncertainty + Reliability
        ↓
Engineering Criteria
        ↓
Fluid-Design Interpretation
        ↓
Proppant-Transport Implications
        ↓
Candidate Operating-Window Assessment
        ↓
Further Laboratory / Engineering Evaluation

## Key Principle

A statistically accurate prediction is not automatically an
engineering recommendation.

Engineering usefulness requires consideration of:

Prediction
+
Reliability
+
Physical meaning
+
Operational constraints
+
Downstream consequences

## Scope Boundary

The evaluation does not claim that the predictive framework directly
determines:

- fracture geometry;
- fracture conductivity;
- complete treatment design;
- field treatment success.

Instead, it supports subsequent engineering assessment by improving the
information available about foam rheology and stability.

## Research Role

This method operationalises the fifth research objective:

> Evaluate the engineering implications of model outputs for
> fracturing-fluid design and proppant transport.

## Related Notes

- [[THK-0041 - Proppant Transport]]
- [[THK-0045 - Rheology–Proppant Transport Link]]
- [[THK-0046 - Stability–Proppant Transport Link]]
- [[THK-0049 - Operating-Window Identification]]
- [[THK-0053 - Engineering Interpretation of Predictions]]
- [[THK-0060 - Prediction Reliability–Fluid Design Link]]
- [[THK-0062 - Prediction Reliability–Treatment Performance Link]]
- [[THK-0075 - Constraint-Based Foam Operating Window]]

## Hubs

- [[HUB-05 - Engineering Performance]]
- [[HUB-T07 - Methods]]
```

There is one structural issue in the source that I would flag for the PhD itself: before the numbered objectives, there is an unnumbered objective — **“To investigate the influence of pressure, temperature, fluid composition, and shear conditions…”**. As written, Section 5.3 therefore effectively contains **six objectives**, not five. That should eventually be resolved in the thesis structure.