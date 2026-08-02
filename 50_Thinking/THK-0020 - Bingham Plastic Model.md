---
id: THK-0020
title: "Bingham Plastic Model"
type: "model"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0020 - Bingham Plastic Model

## Definition

A yield-stress model with linear stress–shear-rate behaviour after yielding.

## Purpose

It approximates materials requiring finite stress before flow and then behaving with plastic viscosity.

## Model Structure / Equation

```text
τ = τ₀ + μpγ̇.
```

## Variables and Parameters

Symbols and fitted parameters must be defined for the specific dataset and units used in an analysis.

## Assumptions

The model is an empirical constitutive representation and should be applied only where its assumptions and calibration domain are appropriate.

## Strengths

It provides a compact interpretable representation of rheological behaviour and a useful conventional benchmark.

## Limitations

Parameters may be formulation- and condition-specific, and fit within a calibration range does not establish transferability.

## Research Relevance

Useful as a conventional comparator within its calibration domain.

## Evidence

Ahmed et al. (2017).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.


### HPHT Transferability Limitation

The Bingham plastic model provides an interpretable representation of
yield-stress behaviour, but its simplifying assumptions may become
restrictive when foam rheology is governed by strongly nonlinear and
coupled HPHT interactions.

A fitted relationship obtained under one combination of pressure,
temperature, shear, foam quality, and formulation conditions may not
remain valid when those conditions change.

Therefore:

Controlled-condition fit
        ≠
Demonstrated HPHT generalisation

The model is consequently valuable as a baseline constitutive
representation but should not be treated as universally transferable
across formulations or HPHT operating environments.

## Related Notes

- [[THK-0018 - Non-Newtonian Foam Behaviour]]
- [[THK-0019 - Power-Law Model]]
- [[THK-0021 - Herschel–Bulkley Model]]
- [[THK-0022 - Rheological Model Transferability]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
