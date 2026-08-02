---
id: THK-0024
title: "Machine Learning for Foam Rheology"
type: "method"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0024 - Machine Learning for Foam Rheology

## Definition

A data-driven modelling approach for learning nonlinear mappings between operating/formulation inputs and foam rheological outputs.

## Purpose

ML can complement empirical equations when interactions are numerous and nonlinear.

## General Procedure

```text
Prepare data → select predictors/targets → train/validate nonlinear learner → evaluate predictions.
```

## Inputs

Experimental operating conditions, formulation variables, and measured target properties.

## Outputs

Predicted rheological or stability properties, model-performance information, and—where designed—uncertainty estimates.

## Strengths

Can represent multivariable nonlinear relationships that may be difficult to capture with simple constitutive equations.

## Limitations

Performance depends on data quality, sample size, domain coverage, validation design, and treatment of uncertainty.

## Research Relevance

Provides the broad analytical method for nonlinear prediction.

## Evidence

Al-Darweesh et al. (2024).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.

### Current Application and Evidence Constraint

Machine-learning approaches including Random Forest, XGBoost, and
Artificial Neural Networks have increasingly been applied to represent
nonlinear foam-rheology relationships.

Their principal advantage is the ability to learn complex mappings
without requiring the response to conform to a predetermined simple
constitutive equation.

However:

Nonlinear learning capability
        ≠
Guaranteed generalisation

Predictive capability remains constrained by the experimental domain
represented in the training data.

Where available datasets are predominantly laboratory-scale,
formulation-specific, or sparsely representative of coupled HPHT
conditions, the learned model remains correspondingly dependent on
those conditions.

Machine learning therefore addresses part of the **nonlinearity
problem**, but does not automatically solve the **generalisation** or
**uncertainty problem**.

**Evidence:** Al-Darweesh et al. (2024); Ghassemzadeh et al. (2021).

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

## Related Notes

- [[THK-0025 - XGBoost Foam Prediction]]
- [[THK-0026 - ANN Foam Prediction]]
- [[THK-0027 - Deterministic Foam Prediction]]
- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0052 - Uncertainty-Aware Foam Prediction]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
