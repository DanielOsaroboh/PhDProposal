---
id: THK-0007
title: "HPHT Foam Performance"
type: "system"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0007 - HPHT Foam Performance

## System Definition

The emergent behaviour of energised foam under coupled high-pressure and high-temperature conditions.

## System Logic

Performance is produced by interacting reservoir conditions, formulation, foam structure, rheology and engineering requirements.

## System Architecture

```text
HPHT conditions × formulation × foam quality/shear/salinity → rheology/stability → engineering outcome.
```

## Inputs

Reservoir conditions, operating conditions, foam quality, salinity, and formulation variables.

## State / Performance Variables

Foam microstructure, apparent viscosity, stability, drainage behaviour, and downstream proppant behaviour.

## Interactions

The system is governed by coupled rather than purely independent effects.

### Expanded HPHT Performance System

HPHT foam performance can be represented as a multivariable system:

Reservoir Conditions
    │
    ├── Pressure
    └── Temperature

Fluid / Formulation Conditions
    │
    ├── Foam quality
    ├── Surfactant chemistry
    ├── Nanoparticle concentration
    ├── Salinity
    └── Gas-phase characteristics

Flow Conditions
    │
    └── Shear rate
            ↓
    Coupled nonlinear interactions
            ↓
    Foam structure and behaviour
            ↓
    ┌──────────────────────┐
    │ Apparent viscosity   │
    │ Foam stability       │
    └──────────────────────┘
            ↓
    Engineering performance

The important system insight is that foam performance cannot be reliably
understood by considering each variable independently.

A formulation that performs adequately at one combination of conditions
may behave differently when several operating variables change
simultaneously.

**Evidence:** Al-Darweesh et al. (2024); Ghorbani (2025).

## Research Relevance

Frames the study as a coupled system rather than isolated variable effects.

## Boundaries

System behaviour should be interpreted within the experimental and formulation domain represented by evidence.

## Evidence

Gonzalez Perdomo and Wan Madihi (2022); Sinha et al. (2019).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.

## Related Notes

- [[THK-0008 - HPHT Conditions]]
- [[THK-0012 - Coupled HPHT Effects]]
- [[THK-0013 - Fragmented HPHT Experimental Evidence]]
- [[THK-0014 - Limited HPHT Experimental Coverage]]
- [[THK-0054 - Integrated HPHT Foam Prediction Framework]]

## Hubs

- [[HUB-01 - Fracturing Context]]
