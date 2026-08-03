---
id: THK-0096
title: Interpolation–Extrapolation Validation Distinction
type: principle
domain: Petroleum Engineering
topic: Machine Learning Validation
status: developed
source_context: PhD Proposed Methodology
---

# THK-0096 - Interpolation–Extrapolation Validation Distinction

## Principle

Model performance should be interpreted differently depending on whether
a prediction is made within a region supported by the training data or
outside that represented domain.

This creates a fundamental distinction between:

- interpolation;
- extrapolation.

## Interpolation

Interpolation occurs when prediction is made within a region represented
by the training data.

Conceptually:

```text
Observed Training Conditions
●       ●       ●
    X
●       ●       ●

X = prediction within represented domain


```

The model is using learned relationships within an empirically supported  
region.

## Extrapolation

Extrapolation occurs when prediction is required outside, or materially  
beyond, the domain represented during training.

```
Observed Training Conditions
●   ●   ●   ●

                    X
              Extrapolated
              prediction
```

The model must extend learned relationships into a region where direct  
empirical support is weaker or absent.

## Why the Distinction Matters

Machine-learning models can return numerical predictions in both cases.

The existence of a numerical output does not establish equivalent  
reliability.

Therefore:

```
Model produced prediction
        ≠
Prediction equally supported by data
```

## HPHT Context

The distinction is particularly important because the model input space  
is multidimensional:

Pressure  
× Temperature  
× Shear Rate  
× Foam Quality  
× Salinity  
× Nanoparticle Concentration  
× Surfactant Chemistry  
× Gas Characteristics

A prediction can therefore become unfamiliar because of the  
**combination of variables**, even when individual values appear within  
their observed ranges.

## Example

Suppose the training data contain:

- high pressure at moderate temperature;
- high temperature at moderate pressure.

This does not necessarily mean that:

> high pressure + high temperature

is strongly represented.

The combination itself may occupy a sparsely supported region.

## Validation Implication

Model evaluation should distinguish:

### Interpolation Performance

How accurately does the model predict within well-represented regions?

### Extrapolation Performance

How does model behaviour change as predictions move toward or beyond  
poorly represented regions?

## Expected Reliability Relationship

```
Strongly Represented Domain
        ↓
Greater empirical support
        ↓
Generally stronger confidence

Moving away from represented domain
        ↓
Reduced empirical support
        ↓
Increasing epistemic uncertainty
        ↓
Greater interpretive caution
```

## Important Boundary

Interpolation does not automatically mean a prediction is reliable.

Poor data quality, experimental variability, inadequate features, or  
model misspecification can still produce unreliable interpolation.

Similarly, extrapolation is not automatically incorrect.

The issue is that extrapolated predictions generally have weaker direct  
empirical support.

## Engineering Significance

The distinction provides engineers with information about **where**  
predictions are being made relative to available evidence.

This is critical when identifying operating windows because an  
apparently favourable predicted condition may lie outside the region  
where the model has strong empirical support.

## Research Role

The principle connects:

[[THK-0029 - Sparse-Data Uncertainty]]  
↓  
[[THK-0030 - Extrapolation Uncertainty]]  
↓  
[[THK-0068 - Data-Domain-Dependent Predictive Performance]]  
↓  
[[THK-0074 - Uncertainty-Based Model Reliability Assessment]]  
↓  
[[THK-0103 - Uncertainty-Bounded Operating Window]]

## Related Notes

- [[THK-0029 - Sparse-Data Uncertainty]]
- [[THK-0030 - Extrapolation Uncertainty]]
- [[THK-0051 - Model Reliability under Unfamiliar Conditions]]
- [[THK-0068 - Data-Domain-Dependent Predictive Performance]]
- [[THK-0092 - Grouped Validation for Foam Prediction]]
- [[THK-0099 - Epistemic Uncertainty in Foam Prediction]]

## Hubs

- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T02 - Principles]]