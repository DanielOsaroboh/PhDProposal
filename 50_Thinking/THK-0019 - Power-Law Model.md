---
id: THK-0019
title: "Power-Law Model"
type: "model"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0019 - Power-Law Model

## Definition

An empirical rheological model expressing shear stress as a power function of shear rate.

## Purpose

It represents shear-dependent flow without an explicit yield-stress term.

## Model Structure / Equation

```text
τ = Kγ̇^n; K is consistency index and n is flow-behaviour index.
```

## Variables and Parameters

Symbols and fitted parameters must be defined for the specific dataset and units used in an analysis.

## Assumptions

The model is an empirical constitutive representation and should be applied only where its assumptions and calibration domain are appropriate.

## Strengths

It provides a compact interpretable representation of rheological behaviour and a useful conventional benchmark.

## Limitations

Parameters may be formulation- and condition-specific, and fit within a calibration range does not establish transferability.

### HPHT Transferability Limitation

Although the Power-law model can provide useful representation of
shear-dependent foam rheology under controlled experimental conditions,
its fitted parameters should not automatically be assumed transferable
across variable HPHT environments.

The limitation becomes important when foam behaviour is simultaneously
influenced by:

Pressure × Temperature × Shear Rate × Foam Quality
× Surfactant Chemistry × Nanoparticle Concentration
× Salinity × Gas-Phase Characteristics

The empirical relationship captured within one experimental domain may
therefore not adequately represent behaviour under another formulation
or operating domain.

The model remains useful as a conventional rheological representation,
but its calibration domain must remain explicit when interpreting HPHT
foam behaviour.

**Evidence:** Al-Darweesh et al. (2024); Ghorbani (2025).

## Research Relevance

Provides a conventional baseline representation of shear-dependent foam behaviour.

## Evidence

Ahmed et al. (2017).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.

## Related Notes

- [[THK-0018 - Non-Newtonian Foam Behaviour]]
- [[THK-0020 - Bingham Plastic Model]]
- [[THK-0021 - Herschel–Bulkley Model]]
- [[THK-0022 - Rheological Model Transferability]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
