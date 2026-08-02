---
id: MET-0001
title: Uncertainty Quantification
aliases:
  - UQ

class: Evergreen
type: Method

domain: Machine Learning
subdomain: Predictive Modelling

status: permanent
maturity: growing

created:
updated:

tags:
  - uncertainty
  - statistics
  - machine-learning
  - prediction

source: []

parents: []

children: []

related:
  - Predictive Modelling
  - Engineering Decision Support
  - Bayesian Optimisation
  - Cross Validation

prerequisites:
  - Statistics
  - Probability

used_in:
  - Machine Learning
  - Hydraulic Fracturing

review: quarterly
---

# Purpose

Estimate and communicate the uncertainty associated with model predictions.

# Procedure

1. Train the predictive model.
2. Estimate prediction uncertainty.
3. Produce confidence intervals or probability distributions.
4. Evaluate prediction reliability.
5. Support engineering decisions.

# Advantages

- Improves trust.
- Supports risk-based decisions.
- Identifies unreliable predictions.

# Limitations

- Computationally expensive.
- Depends on model assumptions.

# Applications

- Reservoir engineering
- Medical AI
- Weather forecasting
- Financial forecasting

# Example

A model predicts foam viscosity as **120 cP ± 8 cP**, allowing engineers to evaluate both the prediction and its confidence.

# Related Notes

- [[CON-0022 - Predictive Modelling]]
- [[CON-0030 - Engineering Decision Support]]
- [[Bayesian Optimisation]]
- [[EVO-006 - Methods]]