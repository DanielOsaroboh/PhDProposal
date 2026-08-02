---
id: THK-0030
title: "Extrapolation Uncertainty"
type: "mechanism"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0030 - Extrapolation Uncertainty

## Phenomenon

Uncertainty arising when predictions are made outside or near the boundaries of the training/calibration domain.

## Starting Condition

Relationships learned within observed data may not continue beyond those ranges.

## Causal Chain

```text
Out-of-domain input → unsupported extension → confidence ↓.
```

## Why the Mechanism Matters

Critical when moderate-condition data are used to infer extreme HPHT behaviour.

## Governing Variables

The strength and direction of the mechanism can depend on pressure, temperature, shear, foam quality, salinity, concentration, and formulation chemistry as relevant.

## Observable Outcome

The mechanism becomes visible through changes in foam structure, apparent viscosity, stability, drainage, or downstream engineering behaviour.

## Boundary Conditions

The causal pathway should not be assumed to have identical strength across formulations or outside tested operating ranges.

## Evidence

Zhang et al. (2025).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.

### Training-Range Boundary

Extrapolation uncertainty becomes important when a model is asked to
predict foam behaviour beyond the operating or formulation conditions
represented during training.

Training domain
        ↓
Observed relationships
        ↓
Domain boundary
        ↓
Unobserved / unfamiliar conditions
        ↓
Model extrapolation
        ↓
Increasing uncertainty about relationship validity

This is particularly important for HPHT applications where available
laboratory datasets may not span the full combinations of pressure,
temperature, formulation, and flow conditions encountered in intended
engineering applications.

Uncertainty quantification can therefore help distinguish interpolation
within supported regions from predictions that depend more heavily on
extrapolation.

## Related Notes

- [[THK-0014 - Limited HPHT Experimental Coverage]]
- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0029 - Sparse-Data Uncertainty]]
- [[THK-0051 - Model Reliability under Unfamiliar Conditions]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
- [[HUB-06 - Prediction & Uncertainty]]
