```
id: THK-0057
title: Multivariable Control of Foam Performance
type: mechanism
domain: Petroleum Engineering
topic: HPHT Energised Foam
status: developed
source_context: PhD Research Problem
```


# THK-0057 - Multivariable Control of Foam Performance

## Phenomenon

The rheological and stability behaviour of nanoparticle-stabilised
energised foams is controlled by multiple interacting operating and
formulation variables.

## Core Idea

Foam performance should not be interpreted as the independent response
to pressure, temperature, or any single formulation variable.

Instead, performance emerges from their combined influence.

## Governing Variables

The research problem identifies:

- pressure;
- temperature;
- [[THK-0015 - Foam Quality]];
- surfactant chemistry;
- nanoparticle concentration;
- salinity;
- shear rate;
- gas-phase characteristics.

## Interaction Structure

```text
Pressure
+
Temperature
+
Foam Quality
+
Surfactant Chemistry
+
Nanoparticle Concentration
+
Salinity
+
Shear Rate
+
Gas-Phase Characteristics
        ↓
Coupled nonlinear interactions
        ↓
Foam structure and physicochemical behaviour
        ↓
Apparent viscosity + Foam stability
        ↓
Engineering performance
```


rather than a collection of independent one-variable relationships.

## Engineering Significance

Multivariable control explains why a formulation performing well under  
one experimental condition cannot automatically be assumed to perform  
equally well elsewhere.

## Research Relevance

This mechanism provides a physical justification for using modelling  
approaches capable of representing nonlinear multivariable behaviour.

It also supports the need for [[THK-0052 - Uncertainty-Aware Foam Prediction]]  
because sparsely represented combinations of variables may carry greater  
predictive uncertainty.

## Evidence

Al-Darweesh et al. (2024) and Ghorbani (2025) identify multiple  
operating and formulation variables governing foam behaviour.

## Research Investigation

The research explicitly investigates which formulation and operating
variables most strongly influence apparent viscosity and foam stability.

Variables of interest include:

- pressure;
- temperature;
- fluid composition;
- salinity;
- foam quality;
- chemical formulation;
- shear conditions.

The analytical problem is therefore:

Multiple Candidate Variables
        ↓
Relative and interacting influence
        ↓
Apparent viscosity
        +
Foam stability

This moves the research beyond establishing that variables affect foam
behaviour toward determining which variables provide the strongest
predictive and engineering information under HPHT conditions.

## Related Notes

- [[THK-0007 - HPHT Foam Performance]]
- [[THK-0012 - Coupled HPHT Effects]]
- [[THK-0015 - Foam Quality]]
- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0029 - Sparse-Data Uncertainty]]
- [[THK-0039 - Nonlinear Formulation Response]]
- [[THK-0056 - HPHT Foam Performance Degradation Processes]]
- [[THK-0058 - Condition-Dependent Foam Formulation Performance]]

## Hubs

- [[HUB-02 - Foam Rheology]]
- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T03 - Mechanisms]]