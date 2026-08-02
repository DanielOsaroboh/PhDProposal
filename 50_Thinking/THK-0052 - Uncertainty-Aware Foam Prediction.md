---
id: THK-0052
title: "Uncertainty-Aware Foam Prediction"
type: "approach"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0052 - Uncertainty-Aware Foam Prediction

## Approach Definition

A modelling approach that reports foam-property predictions together with explicit information about predictive uncertainty.

## Problem Addressed

It asks both what value is predicted and how strongly the evidence supports that prediction.

### Engineering Requirements of the Approach

An uncertainty-aware predictive approach for nanoparticle-stabilised
energised foams should address two questions simultaneously:

1. **What performance is predicted?**
2. **How reliable is that prediction?**

The required architecture is therefore:

HPHT + formulation + flow variables
        ↓
Predictive model
        ↓
┌───────────────────────────────┐
│ Apparent viscosity prediction│
│ Foam stability prediction    │
└───────────────────────────────┘
        +
Predictive uncertainty
        ↓
Reliability-aware interpretation
        ↓
Fracturing-fluid design
        +
Candidate operating conditions
        ↓
Further laboratory / engineering evaluation

The purpose of uncertainty-aware prediction is therefore not simply to
produce more statistical information.

Its engineering purpose is to distinguish predictions that have stronger
empirical/model support from predictions that should be treated with
greater caution.

This distinction can improve the basis on which candidate formulations
and operating conditions are selected for subsequent evaluation.


## Core Architecture

```text
Inputs → predictive model → property estimate + uncertainty → reliability-aware interpretation.
```

## Principles

Prediction and reliability should be considered together; domain coverage and uncertainty must remain visible in interpretation.

## Inputs

HPHT conditions, foam quality, formulation variables, and available experimental observations.

## Outputs

Property predictions, uncertainty information, and reliability-aware inputs to engineering interpretation.

## Advantages

Methodological bridge from ML prediction to defensible engineering use.

## Limitations

The approach cannot create evidence where none exists; uncertainty estimates and conclusions remain dependent on data quality and modelling assumptions.

## Evidence

Zhang et al. (2025); Ogbidi and Oteh (2023).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.

### Scientific Position of the Approach

Uncertainty-aware prediction addresses a limitation that conventional
rheological models and deterministic machine-learning models do not
fully resolve.

The progression is:

Empirical / Mechanistic Models
        ↓
Physical and rheological representation
        ↓
Limited transferability under complex HPHT conditions

Machine Learning
        ↓
Improved nonlinear representation
        ↓
Data-domain dependence remains

Deterministic Prediction
        ↓
Predicted foam property
        ↓
Reliability not explicitly represented

Uncertainty-Aware Prediction
        ↓
Predicted foam property
        +
Prediction uncertainty
        ↓
Reliability-aware engineering interpretation

The proposed approach therefore does not replace physical understanding
or nonlinear prediction.

It adds a missing **reliability layer** to the predictive process.

## Related Notes

- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0027 - Deterministic Foam Prediction]]
- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0048 - Candidate Operating Window]]
- [[THK-0049 - Operating-Window Identification]]
- [[THK-0053 - Engineering Interpretation of Predictions]]
- [[THK-0054 - Integrated HPHT Foam Prediction Framework]]

## Hubs

- [[HUB-06 - Prediction & Uncertainty]]
