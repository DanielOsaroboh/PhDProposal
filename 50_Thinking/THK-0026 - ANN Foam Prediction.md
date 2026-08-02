---
id: THK-0026
title: "ANN Foam Prediction"
type: "model application"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0026 - ANN Foam Prediction

## Definition

Application of Artificial Neural Networks to nonlinear foam-property prediction.

## Target Problem

ANNs learn complex mappings through interconnected nonlinear transformations.

## Application Logic

```text
Inputs → hidden nonlinear transformations → predicted foam property.
```

## Inputs

HPHT operating variables, foam-quality information, formulation variables, and other predictors supported by the dataset.

## Outputs

Predictions of target foam properties such as apparent viscosity or stability.

## Why It May Be Suitable

A candidate ML implementation for nonlinear rheological data.

## Training and Validation Requirements

Model selection, hyperparameter tuning, validation, and leakage control should be designed around the size and structure of the experimental dataset.

## Limitations and Uncertainty

Predictive performance within training-like conditions does not by itself establish reliability under sparse or extrapolated conditions.

## Evidence

Al-Darweesh et al. (2024).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.

### Interpretability and Uncertainty Limitation

Artificial Neural Networks can learn complex nonlinear relationships
among foam operating and formulation variables.

However, two limitations become particularly relevant for engineering
application:

1. limited interpretability of complex learned relationships;
2. absence of explicit uncertainty estimation in deterministic
   implementations.

The resulting problem is:

Complex nonlinear prediction
        ↓
Potentially strong numerical performance
        ↓
Limited transparency
        +
No explicit prediction uncertainty
        ↓
Reduced confidence in engineering interpretation

ANN performance should therefore be evaluated not only through
predictive accuracy but also through domain coverage, reliability,
uncertainty, and engineering interpretability.

## Related Notes

- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0025 - XGBoost Foam Prediction]]
- [[THK-0027 - Deterministic Foam Prediction]]
- [[THK-0028 - Predictive Uncertainty]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
