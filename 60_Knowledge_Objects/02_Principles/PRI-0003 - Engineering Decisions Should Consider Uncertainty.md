---
id: PRI-0003
title: Engineering Decisions Should Consider Uncertainty

class: Evergreen
type: Principle

domain: Engineering
subdomain: Decision Making

status: permanent
maturity: growing

created:
updated:

tags:
  - uncertainty
  - decision-making

source: []

related:
  - Uncertainty Quantification
  - Predictive Modelling
---
Practice 
# Statement

Engineering decisions should account for the uncertainty associated with predictions, measurements, and models.

# Meaning

Predictions are never perfectly certain. Engineers should evaluate both the predicted value and the confidence associated with that prediction before making decisions.

# Why It Matters

- Reduces engineering risk.
- Improves decision quality.
- Prevents overconfidence in predictive models.

# Applications

- Machine learning.
- Reservoir engineering.
- Structural design.
- Reliability engineering.

# Examples

A model predicts foam viscosity with a 95% confidence interval. The engineer considers both the predicted value and the uncertainty before selecting the operating conditions.

# Related Notes

- [[CON-0022 - Predictive Modelling]]
- [[CON-0020 - Uncertainty Quantification]]
- [[Operating Window]]