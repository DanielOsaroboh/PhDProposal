---
id: THK-0114
title: Dataset Adequacy Gate
type: decision gate
domain: Petroleum Engineering
topic: Research Methodology
status: developed
source_context: PhD Data Requirements and Feasibility
---

# THK-0114 - Dataset Adequacy Gate

## Definition

The dataset adequacy gate is a methodological decision point at which
the compiled HPHT foam dataset is evaluated before progression to the
intended predictive modelling stage.

## Decision Question

> Is the available dataset sufficiently adequate to support the intended
> modelling scope?

## Gate Structure

```text
Dataset Compilation
        ↓
Dataset Adequacy Assessment
        ↓
        ◇
       / \
     YES  NO
      ↓    ↓
Proceed   Broaden Data Search
to ML       +
          Adjust Modelling Scope
```

## Evaluation Criteria

The gate considers:

- dataset size;
- completeness;
- variable coverage;
- experimental diversity.

## If the Gate Is Passed

The research proceeds to model development using methods appropriate to  
the available dataset.

## If the Gate Is Not Passed

Two responses are available:

### Response 1 — Broaden Data Acquisition

Expand:

- literature search;
- data extraction;
- digitisation;
- supplementary-material search;
- eligible additional data sources.

### Response 2 — Adjust Modelling Scope

Reduce or modify:

- number of predictors;
- number of outputs;
- model complexity;
- operating domain;
- formulation domain;
- strength of engineering claims.

## Stage-Gate Relationship

This is a specific implementation of:

[[THK-0083 - Engineering Stage-Gate Methodology]]

It represents the gate between:

Data Preparation  
↓  
Predictive Modelling

## Important Principle

Failure to pass the gate does not necessarily mean research failure.

Instead, it provides information about what the available evidence can  
realistically support.

## Research Significance

The gate prevents the methodology from assuming predictive feasibility  
before data adequacy has been demonstrated.

## Related Notes

- [[THK-0083 - Engineering Stage-Gate Methodology]]
- [[THK-0109 - HPHT Foam Data Availability Constraint]]
- [[THK-0112 - HPHT Foam Dataset Adequacy]]
- [[THK-0113 - Data-Complexity Matching Principle]]
- [[THK-0115 - Evidence-Constrained Modelling Scope]]

## Hubs

- [[HUB-T15 - Decision Gates]]

