---
id: THK-0027
title: "Deterministic Foam Prediction"
type: "limitation"
domain: "Petroleum Engineering"
topic: "HPHT Energised Foam"
status: "developed"
source_context: "PhD Research - Background and Petroleum Engineering Context"
---

# THK-0027 - Deterministic Foam Prediction

## What Is Limited

The limitation of producing point predictions without explicit information about prediction uncertainty.

## Nature of the Limitation

A plausible numerical output can conceal sparse-data, experimental and extrapolation uncertainty.

## Limitation Pathway

```text
Model inputs → point estimate; reliability remains implicit.
```

## Why It Matters

Establishes why accuracy metrics alone are insufficient for engineering decision support.

## Conditions Where It Matters Most

The limitation becomes especially important under sparse, unfamiliar, extrapolated, or formulation-shifted conditions.

## Consequence

Uncritical use can create overconfidence in model transfer, generalisation, or engineering interpretation.

## Mitigation Direction

Use domain-aware validation, uncertainty assessment, explicit reporting of operating ranges, and further experimental evaluation where needed.

## Evidence

Zhang et al. (2025); Ogbidi and Oteh (2023).

## Evidence Discipline

The cited sources are retained from the supplied thesis background. Before final academic use, bibliographic details and the exact scope of each supporting claim should be checked against the original publications.

### Sources of Hidden Uncertainty

A deterministic prediction can conceal several different sources of
uncertainty.

These include:

Experimental variability
        +
Sparse data
        +
Limited HPHT coverage
        +
Formulation specificity
        +
Extrapolation beyond training range
        ↓
Prediction uncertainty

A deterministic model compresses this situation into:

Input → Single predicted value

without necessarily indicating whether the prediction occurs:

- within a densely represented data region;
- near the edge of the training domain;
- within a sparse region;
- or outside the observed experimental range.

The limitation is therefore not that point predictions are inherently
invalid.

The limitation is that **point prediction alone provides incomplete
information about prediction reliability**.

This becomes important when predictions are subsequently used for
fracturing-fluid design or candidate operating-window identification.

## Related Notes

- [[THK-0024 - Machine Learning for Foam Rheology]]
- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0029 - Sparse-Data Uncertainty]]
- [[THK-0030 - Extrapolation Uncertainty]]
- [[THK-0051 - Model Reliability under Unfamiliar Conditions]]
- [[THK-0052 - Uncertainty-Aware Foam Prediction]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
- [[HUB-06 - Prediction & Uncertainty]]
