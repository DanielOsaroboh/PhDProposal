---
id: THK-0123
title: Primary Predictive Target–Downstream Application Distinction
type: principle
domain: Petroleum Engineering
topic: HPHT Foam Predictive Modelling
status: developed
source_context: PhD Scope and Limitations
---


# THK-0123 - Primary Predictive Target–Downstream Application Distinction

## Principle

A clear distinction must be maintained between properties predicted
directly by the machine-learning framework and engineering applications
that subsequently use those predictions.

## Primary Predictive Targets

The machine-learning framework directly predicts:

### Apparent Viscosity

[[THK-0005 - Foam Apparent Viscosity]]

### Foam Stability

[[THK-0006 - Foam Stability]]

operationalised primarily through foam half-life.

## Downstream Engineering Applications

The predictions subsequently inform:

- proppant suspension assessment;
- proppant transport assessment;
- candidate operating-window identification.

## Architecture

```text
INPUT VARIABLES
Pressure
Temperature
Foam Quality
Salinity
Chemical Formulation
etc.
        ↓
MACHINE-LEARNING FRAMEWORK
        ↓
PRIMARY PREDICTIVE TARGETS
        │
        ├── Apparent Viscosity
        └── Foam Stability
        ↓
UNCERTAINTY / RELIABILITY
        ↓
DOWNSTREAM APPLICATIONS
        │
        ├── Operating-Window Identification
        └── Proppant-Transport Assessment
````

## Why the Distinction Matters

Without this distinction, the research could appear to claim that the  
machine-learning models directly predict complete proppant transport or  
hydraulic-fracturing performance.

That is not the defined scope.

Instead:

> Rheology and stability are predicted directly.

while:

> Proppant transport and operating windows are assessed downstream using  
> those predictions.

## Causal Interpretation

The distinction also reflects the engineering relationship:

Foam Rheology + Stability  
↓  
Influence  
↓  
Proppant Suspension / Transport

The downstream outcome is therefore informed by predicted primary  
properties rather than treated as an equivalent direct response  
variable.

## Methodological Significance

This principle improves alignment between:

- research questions;
- objectives;
- predictive outputs;
- engineering interpretation;
- contribution claims.

## Claim-Control Principle

```
Directly Modelled
        ↓
May support direct predictive claim

Indirectly Informed
        ↓
Requires downstream engineering interpretation
```

## Related Notes

- [[THK-0005 - Foam Apparent Viscosity]]
- [[THK-0006 - Foam Stability]]
- [[THK-0045 - Rheology–Proppant Transport Link]]
- [[THK-0046 - Stability–Proppant Transport Link]]
- [[THK-0076 - Engineering Evaluation of Foam Model Outputs]]
- [[THK-0103 - Uncertainty-Bounded Operating Window]]
- [[THK-0122 - HPHT Foam Research Scope Boundary]]
- [[THK-0124 - Foam Half-Life as Stability Operationalisation]]

## Hubs

- [[HUB-T02 - Principles]]
- [[HUB-T18 - Scope and Boundaries]]