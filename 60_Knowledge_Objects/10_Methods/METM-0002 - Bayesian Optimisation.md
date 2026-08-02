---
id: MET-0002
title: Bayesian Optimisation

class: Evergreen
type: Method

domain: Machine Learning
subdomain: Optimisation

status: permanent
maturity: growing

created:
updated:

tags:
  - optimisation
  - bayesian
  - machine-learning

source: []

related:
  - Gaussian Process Regression
  - Operating Window
  - Uncertainty Quantification
---

# Purpose

Efficiently find the optimal solution when evaluations are expensive.

# Procedure

1. Build a surrogate model.
2. Estimate uncertainty.
3. Select the next point using an acquisition function.
4. Evaluate.
5. Update the surrogate.
6. Repeat until convergence.

# Advantages

- Requires fewer experiments.
- Handles expensive simulations.
- Naturally incorporates uncertainty.

# Limitations

- Slower for very high-dimensional problems.
- Depends on the quality of the surrogate model.

# Applications

- Hyperparameter tuning
- Engineering design
- Reservoir optimisation
- Foam formulation optimisation

# Example

Instead of experimentally testing thousands of pressure–temperature combinations, Bayesian Optimisation intelligently selects only the most informative experiments.

# Related Notes

- [[Gaussian Process Regression]]
- [[Operating Window]]
- [[CON-0022 - Predictive Modelling]]