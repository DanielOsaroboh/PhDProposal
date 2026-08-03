---
id: THK-0118
title: HPHT Foam Predictive Capability
type: contribution
domain: Petroleum Engineering
topic: HPHT Foam Predictive Modelling
status: expected
source_context: PhD Expected Contributions
---
# THK-0118 - HPHT Foam Predictive Capability

## Contribution Statement

The research is expected to develop and evaluate a data-driven
capability for predicting the apparent viscosity and foam stability of
nanoparticle-stabilised energised foams across varying formulation and
HPHT operating conditions.

## Primary Outputs

The predictive capability focuses principally on:

- [[THK-0005 - Foam Apparent Viscosity]]
- [[THK-0006 - Foam Stability]]

## Input Domain

Predictions may be conditioned on combinations of variables including:

- pressure;
- temperature;
- foam quality;
- salinity;
- surfactant concentration;
- nanoparticle concentration;
- other available formulation and operating variables.

## Predictive Architecture

```text
Structured HPHT Foam Data
        ↓
Relevant Input Variables
        ↓
Machine-Learning Models
        ↓
Model Development and Comparison
        ↓
Apparent-Viscosity Prediction
        +
Foam-Stability Prediction
````

## Contribution Logic

Existing research demonstrates the possibility of data-driven foam  
prediction.

The contribution of this research is therefore not simply:

> machine learning can predict foam behaviour.

Rather, it is the development and evaluation of predictive capability  
within the specific integrated HPHT foam research architecture.

## Relationship to the Framework

This note should be distinguished from:

[[THK-0054 - Integrated HPHT Foam Prediction Framework]]

`THK-0118` represents the **predictive capability**.

`THK-0054` represents the wider architecture connecting:

Prediction  
+  
Uncertainty  
+  
Reliability  
+  
Engineering Interpretation.

## Important Boundary

Predictive capability should be interpreted within the conditions  
supported by the available dataset.

It does not establish universal predictive validity across all HPHT  
foam formulations.

## Related Notes

- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0054 - Integrated HPHT Foam Prediction Framework]]
- [[THK-0073 - Comparative ML Model Evaluation for Foam Prediction]]
- [[THK-0116 - Structured HPHT Foam Data Resource]]
- [[THK-0119 - Reliability-Aware Foam Prediction Capability]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
- [[HUB-T17 - Contributions]]
