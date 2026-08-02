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