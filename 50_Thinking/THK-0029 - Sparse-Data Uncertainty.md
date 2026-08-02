---
id: THK-0029
title: "Sparse-Data Uncertainty"
type: "mechanism"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0029 - Sparse-Data Uncertainty

## Phenomenon

Uncertainty arising where too few observations constrain model behaviour in a region of the input space.

## Starting Condition

Poorly sampled regions provide weaker empirical support for predictions.

## Causal Chain

```text
Low local data density → weak learned constraint → uncertainty ↑.
```

## Why the Mechanism Matters

Important because HPHT experiments can be limited and expensive.

## Governing Variables

The strength and direction of the mechanism can depend on pressure, temperature, shear, foam quality, salinity, concentration, and formulation chemistry as relevant.

## Observable Outcome

The mechanism becomes visible through changes in foam structure, apparent viscosity, stability, drainage, or downstream engineering behaviour.

## Boundary Conditions

The causal pathway should not be assumed to have identical strength across formulations or outside tested operating ranges.

## Evidence

Sinha et al. (2019); Ogbidi and Oteh (2023).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.

### HPHT Data Context

Sparse-data uncertainty is especially relevant to energised-foam
prediction because experimental datasets may contain limited
representation of the multidimensional HPHT operating domain.

Consider the combined input space:

Pressure × Temperature × Shear × Foam Quality
× Chemistry × Nanoparticle Concentration
× Salinity × Gas Characteristics

Even where the total number of observations appears reasonable, some
combinations within this multidimensional space may remain poorly
represented.

Therefore:

Dataset size
        ≠
Uniform domain coverage

Sparse local coverage can create regions in which the model has weaker
empirical support despite having been trained on the overall dataset.

## Related Notes

- [[THK-0014 - Limited HPHT Experimental Coverage]]
- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0030 - Extrapolation Uncertainty]]
- [[THK-0051 - Model Reliability under Unfamiliar Conditions]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
- [[HUB-06 - Prediction & Uncertainty]]
