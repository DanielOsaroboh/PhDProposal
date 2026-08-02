---
id: THK-0084
title: HPHT Foam Feature Matrix
type: structure
domain: Petroleum Engineering
topic: HPHT Foam Data
status: developed
source_context: PhD Proposed Methodology
---

# THK-0084 - HPHT Foam Feature Matrix

## Definition

The HPHT foam feature matrix is the structured representation of input
variables and target outputs used to model nanoparticle-stabilised
energised-foam behaviour.

## Input Architecture

### Operating Inputs

- system pressure;
- reservoir temperature;
- rotational shear rate.

### Foam-State Inputs

- foam quality;
- gas fraction;
- gas type.

### Chemical Inputs

- surfactant concentration;
- nanoparticle concentration;
- brine salinity.

## Primary Predictive Outputs

- apparent viscosity;
- foam half-life.

## Secondary / Engineering Outputs

- drainage rate;
- proppant transport performance indicator.

## Structural Representation

Operating Variables
        +
Foam Variables
        +
Chemical Variables
        ↓
Feature Matrix
        ↓
Predictive Model
        ↓
Rheological Outputs
+
Stability Outputs
+
Engineering Indicators

## Why It Matters

The feature matrix translates physical and chemical knowledge of the
foam system into computational variables.

It therefore forms the bridge between:

Engineering Understanding
        ↓
Data Representation
        ↓
Machine Learning

## Selection Principle

Features should not be selected merely because they exist in a dataset.

Their inclusion should be supported by their physical, chemical,
rheological, or engineering relevance to the foam system.

## Related Notes

- [[THK-0057 - Multivariable Control of Foam Performance]]
- [[THK-0072 - HPHT Foam Dataset Compilation and Structuring]]
- [[THK-0085 - Heterogeneous Foam Dataset Harmonisation]]
- [[THK-0077 - ML as Engineering Decision-Support Tool]]

## Hubs

- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T13 - Structures]]