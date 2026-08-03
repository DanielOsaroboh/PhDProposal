---
id: THK-0103
title: Uncertainty-Bounded Operating Window
type: decision object
domain: Petroleum Engineering
topic: HPHT Foam Design
status: developed
source_context: PhD Proposed Methodology
---
## Multidimensional Operating Space

The operating window may span combinations of:

- pressure;
- temperature;
- shear rate;
- foam quality;
- salinity;
- nanoparticle concentration;
- surfactant concentration;
- gas characteristics.

Thus, the window is not necessarily a simple two-dimensional range.

It is a region within a multidimensional engineering space.

## Acceptance Logic

A candidate condition may be considered favourable when:

```
Predicted Performance
        satisfies
Engineering Requirements

AND

Predictive Uncertainty
        satisfies
Defined Reliability Requirement
```

## Three Decision Regions

The operating domain can conceptually be divided into:

### Region 1 — Supported Candidate Region

Performance criteria satisfied  
+  
uncertainty acceptable.

```
Suitable Prediction
+
Strong / acceptable reliability
        ↓
Candidate Operating Region
```

### Region 2 — Uncertain Candidate Region

Performance criteria appear satisfied  
but uncertainty is high.

```
Suitable Prediction
+
Weak reliability
        ↓
Further Evaluation Required
```

### Region 3 — Unsuitable Region

Predicted performance does not satisfy the defined engineering  
requirements.

```
Performance criteria not satisfied
        ↓
Reject from candidate window
```

## Why This Matters

Consider two conditions:

### Condition A

Predicted viscosity = acceptable  
Predicted stability = acceptable  
Prediction uncertainty = low

### Condition B

Predicted viscosity = acceptable  
Predicted stability = acceptable  
Prediction uncertainty = high

A deterministic operating-window approach may classify both as equally  
suitable.

An uncertainty-aware approach distinguishes their decision confidence.

## Relationship to Extrapolation

Conditions near or beyond the training domain may have favourable  
predicted properties while carrying high epistemic uncertainty.

Therefore:

Favourable Extrapolated Prediction  
≠  
High-Confidence Operating Condition

This protects the operating-window process from treating unsupported  
predictions as equivalent to well-supported predictions.

## Relationship to Reservoir and Treatment Constraints

Uncertainty alone does not define the operating window.

The final candidate region must consider:

Predicted Foam Performance  
+  
Prediction Reliability  
+  
Reservoir Constraints  
+  
Treatment Constraints  
+  
Engineering Requirements

## Proppant-Transport Relevance

Because apparent viscosity and foam stability influence downstream  
assessment of proppant suspension and transport, the operating window  
can also be interpreted in relation to expected proppant-transport  
requirements.

However, the framework does not directly establish field proppant  
placement without additional engineering validation.

## Engineering Decision Architecture

```
HPHT Operating Space
        ↓
ML Prediction
        ↓
Viscosity + Stability
        ↓
Uncertainty Quantification
        ↓
Reliability Assessment
        ↓
Apply Engineering Constraints
        ↓
┌─────────────────────────────┐
│ Candidate Region            │
│ Further-Evaluation Region   │
│ Unsuitable Region           │
└─────────────────────────────┘
        ↓
Laboratory / Engineering Evaluation
```

## Research Contribution

The concept advances operating-window identification from:

> **Where does the model predict acceptable foam performance?**

to:

> **Where does the model predict acceptable foam performance with  
> sufficient confidence to justify further engineering consideration?**

This is one of the central engineering translations of uncertainty-aware  
machine learning within the research.

## Important Boundary

The term **uncertainty-bounded operating window** should not be  
interpreted automatically as a certified field-safe operating envelope.

It represents a **candidate decision-support region** generated from  
available data, predictive models, uncertainty estimates, and specified  
engineering criteria.

Further experimental and engineering validation remains necessary.

## Research Role

This note represents the downstream integration of:

[[THK-0073 - Comparative ML Model Evaluation for Foam Prediction]]  
↓  
[[THK-0092 - Grouped Validation for Foam Prediction]]  
↓  
[[THK-0096 - Interpolation–Extrapolation Validation Distinction]]  
↓  
[[THK-0100 - Aleatoric–Epistemic Uncertainty Decomposition]]  
↓  
[[THK-0103 - Uncertainty-Bounded Operating Window]]

## Related Notes

- [[THK-0048 - Candidate Operating Window]]
- [[THK-0049 - Operating-Window Identification]]
- [[THK-0052 - Uncertainty-Aware Foam Prediction]]
- [[THK-0053 - Engineering Interpretation of Predictions]]
- [[THK-0060 - Prediction Reliability–Fluid Design Link]]
- [[THK-0068 - Data-Domain-Dependent Predictive Performance]]
- [[THK-0075 - Constraint-Based Foam Operating Window]]
- [[THK-0076 - Engineering Evaluation of Foam Model Outputs]]
- [[THK-0096 - Interpolation–Extrapolation Validation Distinction]]
- [[THK-0100 - Aleatoric–Epistemic Uncertainty Decomposition]]

## Hubs

- [[HUB-05 - Engineering Performance]]
- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T16 - Decision Processes]]
# THK-0103 - Uncertainty-Bounded Operating Window

## Definition

An uncertainty-bounded operating window is a candidate region of HPHT
formulation and operating space in which predicted foam performance
satisfies defined engineering requirements while predictive uncertainty
remains within an acceptable level.

## Core Idea

A conventional operating window may be defined primarily from predicted
performance.

An uncertainty-bounded operating window adds another requirement:

> The prediction must not only appear acceptable; its reliability must
> also be considered.

## Decision Structure

```text
Operating / Formulation Condition
        ↓
Predicted Apparent Viscosity
        +
Predicted Foam Stability
        ↓
Engineering Performance Criteria
        +
Predictive Uncertainty
        ↓
Reliability Assessment
        ↓
Candidate Operating-Window Decision

```



These six now form a particularly strong internal chain in the vault:

```text
THK-0092
Grouped Validation
        ↓
Can the model generalise?
        ↓
THK-0096
Interpolation vs Extrapolation
        ↓
Where is the prediction relative to known evidence?
        ↓
THK-0098 + THK-0099
Aleatoric vs Epistemic Uncertainty
        ↓
Why is the prediction uncertain?
        ↓
THK-0100
Uncertainty Decomposition
        ↓
What kind and magnitude of uncertainty exists?
        ↓
THK-0103
Uncertainty-Bounded Operating Window
        ↓
Which predicted conditions merit engineering consideration?