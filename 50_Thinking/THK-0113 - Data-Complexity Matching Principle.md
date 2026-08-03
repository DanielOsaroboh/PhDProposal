---
id: THK-0113
title: Data-Complexity Matching Principle
type: principle
domain: Petroleum Engineering
topic: Machine Learning Methodology
status: developed
source_context: PhD Data Requirements and Feasibility
---
## Principle

The complexity of the predictive model should be proportionate to the
size, quality, structure, and variable coverage of the available
dataset.

## Core Idea

More complex machine-learning architectures are not automatically more
appropriate.

Their justification depends on whether the available evidence can
support their estimation and validation.

## Relationship

```text
Dataset Characteristics
        ↓
Size
Quality
Structure
Variable Coverage
Experimental Diversity
        ↓
Supported Model Complexity
```

## Weak Evidence Condition

```
Small / Sparse / Limited Dataset
        ↓
Restricted information content
        ↓
Complex model difficult to justify
        ↓
Prefer constrained modelling scope
```

## Stronger Evidence Condition

```
Larger / Richer / Diverse Dataset
        ↓
Greater information content
        ↓
Potential support for more flexible models
```

## Governing Principle

> **Model sophistication should follow evidence capacity, not precede  
> it.**

## Why It Matters

Excessive model complexity relative to available data can create:

- unstable estimation;
- overfitting;
- misleading apparent accuracy;
- poor generalisation;
- unreliable uncertainty estimates.

## Methodological Response

The research therefore evaluates candidate ML and uncertainty methods  
after determining the characteristics of the compiled master dataset.

## Relationship to Progressive Modelling

This principle supports:

[[THK-0087 - Progressive ML Modelling Strategy]]

where modelling complexity can increase only where the evidence  
justifies it.

## Research Significance

The principle prevents the PhD contribution from becoming dependent on  
the use of unnecessarily complex algorithms.

The methodological priority remains:

Reliable Engineering Information

Algorithmic Complexity

## Evidence

Ogbidi and Oteh (2023) is cited in the research in relation to adapting  
the modelling and uncertainty strategy to available data  
characteristics.

## Related Notes

- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0087 - Progressive ML Modelling Strategy]]
- [[THK-0109 - HPHT Foam Data Availability Constraint]]
- [[THK-0112 - HPHT Foam Dataset Adequacy]]
- [[THK-0115 - Evidence-Constrained Modelling Scope]]

## Hubs

- [[HUB-T02 - Principles]]