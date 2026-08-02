---
id: THK-0051
title: "Model Reliability under Unfamiliar Conditions"
type: "problem"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0051 - Model Reliability under Unfamiliar Conditions

## Problem Definition

The problem of whether a model remains trustworthy for sparse, novel or out-of-domain inputs.

## Context

Strong in-domain fit does not demonstrate dependable extrapolation.

## Problem Logic

```text
Domain shift/sparsity → unsupported model behaviour → reliability uncertainty.
```

## Why It Matters

Central reason for explicit uncertainty assessment.

## Causes / Drivers

The problem arises from interacting experimental, physical, formulation, data, or modelling constraints represented in the linked notes.

## Consequences

It limits comparison, prediction, transferability, or confidence in engineering assessment.

### Condition-Dependent Reliability

A foam formulation that performs adequately under one experimental or
operating condition may not exhibit the same behaviour under another
HPHT condition.

This creates a reliability problem when models are used across changing
combinations of:

- pressure;
- temperature;
- foam quality;
- surfactant chemistry;
- nanoparticle concentration;
- salinity;
- shear rate;
- gas-phase characteristics.

The problem can be represented as:

Known experimental domain
        ↓
Model learns observed relationships
        ↓
Operating conditions change
        ↓
Input combination becomes less familiar
        ↓
Model support from observed data decreases
        ↓
Prediction reliability may decrease

Therefore, good predictive performance within familiar experimental
conditions does not by itself demonstrate reliable performance across
the wider HPHT operating domain.



## Why It Persists

Available studies and models often address only parts of the wider system or operate within restricted data domains.

## Research Implication

The problem should be addressed explicitly rather than hidden behind aggregate model-performance metrics.

## Evidence

Ogbidi and Oteh (2023); Zhang et al. (2025).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.


### Reliability as a Function of Data Support

Model reliability should be interpreted partly in relation to the
degree of empirical support available for a prediction.

A useful conceptual relationship is:

Data-domain familiarity ↑
        ↓
Empirical support ↑
        ↓
Prediction confidence potentially ↑

whereas:

Sparse / unfamiliar / extrapolated conditions
        ↓
Empirical support ↓
        ↓
Prediction uncertainty potentially ↑

This means that predictive reliability is not necessarily uniform
across the HPHT operating domain.

A model may be highly reliable in one region and considerably less
supported in another.

This spatial or domain-dependent view of reliability is important for
candidate operating-window identification.

## Explicit Reliability Test Domain

The doctoral research specifically evaluates model reliability under:

- sparse HPHT conditions;
- extrapolated HPHT conditions.

This creates a stronger test than overall predictive accuracy alone.

Model evaluation therefore asks two distinct questions:

1. How accurately does the model predict?
2. How reliable is the prediction when empirical support becomes weak?

This distinction is central to determining whether a predictive model
can support engineering interpretation beyond well-represented regions
of the dataset.
## Related Notes

- [[THK-0022 - Rheological Model Transferability]]
- [[THK-0027 - Deterministic Foam Prediction]]
- [[THK-0029 - Sparse-Data Uncertainty]]
- [[THK-0030 - Extrapolation Uncertainty]]
- [[THK-0040 - Formulation-Specific Thresholds]]
- [[THK-0052 - Uncertainty-Aware Foam Prediction]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
- [[HUB-06 - Prediction & Uncertainty]]
