---
id: THK-0075
title: Constraint-Based Foam Operating Window
type: decision process
domain: Petroleum Engineering
topic: HPHT Foam Design
status: developed
source_context: PhD Aim Objectives and Research Questions
---

# THK-0075 - Constraint-Based Foam Operating Window

## Definition

A constraint-based foam operating window is a region of formulation and
operating conditions identified as potentially suitable by evaluating
predicted foam performance, predictive uncertainty, and defined
reservoir and treatment constraints.

## Core Idea

An operating window should not be identified from predicted performance
alone.

It emerges from the intersection of:

Predicted Foam Performance
        +
Prediction Reliability
        +
Reservoir Constraints
        +
Treatment Constraints

## Decision Structure

HPHT Formulation / Operating Conditions
        ↓
ML Prediction
        ↓
Viscosity + Stability
        ↓
Uncertainty Assessment
        ↓
Apply Reservoir Constraints
        +
Apply Treatment Constraints
        ↓
Accept / Reject / Further Evaluate
        ↓
Candidate Operating Window

## Constraint Types

Potential constraints can include:

### Reservoir Constraints

- pressure range;
- temperature range;
- formation conditions.

### Treatment Constraints

- required rheological behaviour;
- stability requirements;
- proppant-transport requirements;
- operational limits.

The exact constraints must be defined by the research methodology and
engineering application.

## Why Uncertainty Matters

Two conditions may have similar predicted foam performance but different
levels of prediction reliability.

Therefore:

Predicted Suitability
        ≠
Equivalent Decision Confidence

## Output

The process identifies **candidate** operating windows.

It does not automatically establish field-safe operating conditions
without further experimental and engineering validation.

## Research Role

This decision process directly operationalises the fourth research
objective.

## Related Notes

- [[THK-0048 - Candidate Operating Window]]
- [[THK-0049 - Operating-Window Identification]]
- [[THK-0052 - Uncertainty-Aware Foam Prediction]]
- [[THK-0060 - Prediction Reliability–Fluid Design Link]]
- [[THK-0068 - Data-Domain-Dependent Predictive Performance]]
- [[THK-0074 - Uncertainty-Based Model Reliability Assessment]]
- [[THK-0076 - Engineering Evaluation of Foam Model Outputs]]

## Hubs

- [[HUB-05 - Engineering Performance]]
- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T16 - Decision Processes]]