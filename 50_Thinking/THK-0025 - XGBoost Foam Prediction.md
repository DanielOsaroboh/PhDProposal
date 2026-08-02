---
id: THK-0025
title: "XGBoost Foam Prediction"
type: "model application"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0025 - XGBoost Foam Prediction

## Definition

Application of gradient-boosted decision trees to foam-property prediction.

## Target Problem

XGBoost is suited to tabular experimental data and can represent nonlinear interactions.

## Application Logic

```text
Experimental predictors → sequential boosted trees → foam-property prediction.
```

## Inputs

HPHT operating variables, foam-quality information, formulation variables, and other predictors supported by the dataset.

## Outputs

Predictions of target foam properties such as apparent viscosity or stability.

## Why It May Be Suitable

A candidate ML implementation for the prediction problem.

## Training and Validation Requirements

Model selection, hyperparameter tuning, validation, and leakage control should be designed around the size and structure of the experimental dataset.

## Limitations and Uncertainty

Predictive performance within training-like conditions does not by itself establish reliability under sparse or extrapolated conditions.

## Evidence

Al-Darweesh et al. (2024).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.

### Data-Domain Dependence

XGBoost can capture nonlinear relationships among multiple foam
operating and formulation variables.

However, its predictive performance remains dependent on the domain
represented by the training data.

Laboratory-scale
+
Formulation-specific
+
Limited coupled HPHT coverage
        ↓
Restricted training domain
        ↓
Strongest predictive support within familiar conditions
        ↓
Increasing uncertainty under unfamiliar conditions

Consequently, good validation performance within the represented
experimental domain should not automatically be interpreted as evidence
of field-scale HPHT generalisation.

Where XGBoost produces only deterministic point predictions, this
domain-dependence may remain hidden unless predictive uncertainty is
assessed explicitly.

## Related Notes

- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0026 - ANN Foam Prediction]]
- [[THK-0027 - Deterministic Foam Prediction]]
- [[THK-0028 - Predictive Uncertainty]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
