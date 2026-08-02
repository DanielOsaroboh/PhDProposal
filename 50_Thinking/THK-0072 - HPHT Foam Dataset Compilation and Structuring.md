---
id: THK-0072
title: HPHT Foam Dataset Compilation and Structuring
type: method
domain: Petroleum Engineering
topic: HPHT Foam Predictive Modelling
status: developed
source_context: PhD Aim Objectives and Research Questions
---

# THK-0072 - HPHT Foam Dataset Compilation and Structuring

## Definition

HPHT foam dataset compilation and structuring is the systematic process
of identifying, extracting, harmonising, and organising experimental
and literature-derived foam data for subsequent predictive modelling.

## Purpose

The method creates the empirical foundation required for machine-learning
prediction of:

- [[THK-0005 - Foam Apparent Viscosity]];
- [[THK-0006 - Foam Stability]].

## Data Sources

The research proposes to use available:

- experimental datasets;
- published literature data.

## Target Variables

The structured dataset may include:

### Operating Variables

- pressure;
- temperature;
- shear conditions.

### Formulation Variables

- foam quality;
- salinity;
- fluid composition;
- surfactant characteristics;
- nanoparticle concentration;
- gas-phase characteristics.

### Response Variables

- apparent viscosity;
- foam-stability indicators.

## Method Structure

Raw Experimental / Literature Data
        ↓
Identification and Extraction
        ↓
Variable Definition
        ↓
Unit Harmonisation
        ↓
Data Structuring
        ↓
Quality Assessment
        ↓
Model-Ready HPHT Dataset

## Why Structuring Matters

Data obtained from different studies may vary in:

- terminology;
- measurement methods;
- units;
- operating ranges;
- formulations;
- reported outputs.

Without systematic structuring, these differences can reduce
comparability and introduce inconsistencies into predictive modelling.

## Research Role

This method corresponds directly to the first research objective and
provides the input layer for subsequent machine-learning and uncertainty
analysis.

## Related Notes

- [[THK-0013 - Fragmented HPHT Experimental Evidence]]
- [[THK-0014 - Limited HPHT Experimental Coverage]]
- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0066 - Laboratory-Scale Data Dependence]]
- [[THK-0067 - Formulation-Specific Data Dependence]]
- [[THK-0068 - Data-Domain-Dependent Predictive Performance]]

## Hubs

- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T07 - Methods]]