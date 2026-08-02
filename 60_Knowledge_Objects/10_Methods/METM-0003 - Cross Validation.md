---
id: MET-0003
title: Cross Validation

aliases:
  - K-Fold Cross Validation

class: Evergreen
type: Method

domain: Machine Learning
subdomain: Model Evaluation

status: permanent
maturity: growing

created:
updated:

tags:
  - validation
  - evaluation
  - machine-learning

source: []

related:
  - RMSE
  - MAE
  - Predictive Modelling
---

# Purpose

Estimate how well a predictive model generalises to unseen data.

# Procedure

1. Split the dataset into *k* folds.
2. Train the model using *k − 1* folds.
3. Test using the remaining fold.
4. Repeat until every fold has been used as the test set.
5. Average the evaluation metrics.

# Advantages

- Reduces overfitting.
- Uses all available data.
- Produces robust performance estimates.

# Limitations

- Computationally expensive.
- Not suitable for all time-series problems.

# Applications

- Machine learning
- Statistical modelling
- Predictive analytics

# Example

A dataset is divided into five folds. Each fold is used once for testing while the remaining four folds are used for training, producing an average RMSE across all five runs.

# Related Notes

- [[CON-0022 - Predictive Modelling]]
- [[METR-0001 - RMSE]]
- [[METR-0002 - MAE]]
- [[CON-0006 - Machine Learning]]