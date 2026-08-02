---
id: PAR-0001
title: Learning Rate
aliases:
  - Step Size
  - η (Eta)

class: Evergreen
type: Parameter

domain: Machine Learning
subdomain: Model Training

status: permanent
maturity: growing

created:
updated:

tags:
  - machine-learning
  - optimisation
  - hyperparameter

source: []

parents: []

children: []

related:
  - Gradient Descent
  - XGBoost
  - Neural Networks
  - Bayesian Optimisation

prerequisites:
  - Machine Learning

used_in:
  - Model Training
  - Hyperparameter Optimisation

see_also:
  - Epochs
  - Batch Size

keywords:
  - learning rate
  - eta
  - optimisation

review: quarterly
---

# Definition

The learning rate is a hyperparameter that controls the size of each update made to a model's parameters during training.

# Purpose

Control how quickly a machine learning model learns from data.

# Role

The learning rate determines the magnitude of each optimisation step.

- Large learning rate → faster learning but may overshoot the optimum.
- Small learning rate → slower learning but may achieve more stable convergence.

# Characteristics

- Hyperparameter
- User-defined
- Controls convergence speed
- Influences model accuracy

# Typical Values

Examples include:

- 0.1
- 0.01
- 0.001

The optimal value depends on the algorithm and dataset.

# Advantages

- Faster training when appropriately chosen.
- Can improve model performance.

# Limitations

- Too large may prevent convergence.
- Too small may require excessive training time.

# Applications

- Neural Networks
- XGBoost
- Gradient Boosting
- Deep Learning

# Example

During XGBoost training, a learning rate of 0.05 causes each new tree to make only a small correction to the predictions produced by previous trees.

# Related Notes

- [[CON-0006 - Machine Learning]]
- [[XGBoost]]
- [[Bayesian Optimisation]]
- [[Gradient Descent]]