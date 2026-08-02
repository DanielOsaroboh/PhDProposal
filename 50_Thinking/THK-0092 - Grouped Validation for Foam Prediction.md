---
id: THK-0092
title: Grouped Validation for Foam Prediction
type: method
domain: Petroleum Engineering
topic: Machine Learning Validation
status: developed
source_context: PhD Proposed Methodology
---

# THK-0092 - Grouped Validation for Foam Prediction

## Definition

Grouped validation is a model-validation strategy in which observations
that belong to the same meaningful experimental, formulation, study, or
operating-condition group are kept together when dividing data into
training and validation sets.

Its purpose is to test whether a predictive model can generalise beyond
closely related observations rather than merely reproduce patterns from
nearly identical data points.

## Core Idea

Conventional random splitting can place highly related observations in
both the training and validation datasets.

For heterogeneous HPHT foam data, observations may share:

- the same experimental study;
- the same formulation;
- the same nanoparticle–surfactant system;
- closely related pressure–temperature conditions;
- similar operating ranges.

If related observations occur on both sides of the split, validation
performance may provide an overly favourable representation of model
generalisation.

## Validation Logic

```text
Heterogeneous HPHT Dataset
        ↓
Identify meaningful groups
        ↓
Keep related observations together
        ↓
Training Groups
        │
        └──────────────→ Model Development
                               ↓
Held-Out Group
        └──────────────→ Independent Evaluation
                               ↓
                     Generalisation Assessment
                     ```
                     