---
id: THK-0022
title: "Rheological Model Transferability"
type: "limitation"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0022 - Rheological Model Transferability

## What Is Limited

The restriction that calibrated rheological parameters may not remain valid across different formulations or operating conditions.

## Nature of the Limitation

Good fit inside one calibration domain does not establish general validity elsewhere.

## Limitation Pathway

```text
Condition/formulation change → parameter shift/model mismatch → reduced reliability.
```

## Why It Matters

Separates descriptive fit from transferable prediction.

## Conditions Where It Matters Most

The limitation becomes especially important under sparse, unfamiliar, extrapolated, or formulation-shifted conditions.

## Consequence

Uncritical use can create overconfidence in model transfer, generalisation, or engineering interpretation.

## Mitigation Direction

Use domain-aware validation, uncertainty assessment, explicit reporting of operating ranges, and further experimental evaluation where needed.

## Evidence

Ahmed et al. (2017); Princen and Kiss (1989).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.


### Expanded Transferability Problem

Transferability becomes particularly important under HPHT conditions
because foam behaviour emerges from coupled interactions among:

- pressure;
- temperature;
- shear rate;
- foam quality;
- surfactant chemistry;
- nanoparticle concentration;
- salinity;
- gas-phase characteristics.

A model calibrated under one experimental domain can therefore contain
parameters that reflect that particular combination of conditions.

The transferability problem can be represented as:

Experimental Domain A
        ↓
Model calibration
        ↓
Condition-specific parameters
        ↓
Application to Domain B
        ↓
Changed physical / formulation interactions
        ↓
Potential parameter mismatch
        ↓
Reduced predictive reliability

This establishes an important distinction:

> **Model fit is not model transferability.**

A rheological model may describe the observations used for calibration
well while providing limited evidence that the same parameterisation
remains valid under different HPHT formulations or operating conditions.

**Evidence:** Gonzalez Perdomo and Wan Madihi (2022); Al-Darweesh et al.
(2024); Ghorbani (2025).

## Related Notes

- [[THK-0013 - Fragmented HPHT Experimental Evidence]]
- [[THK-0019 - Power-Law Model]]
- [[THK-0020 - Bingham Plastic Model]]
- [[THK-0021 - Herschel–Bulkley Model]]
- [[THK-0023 - Constitutive Representation of High-Quality Foams]]
- [[THK-0051 - Model Reliability under Unfamiliar Conditions]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
