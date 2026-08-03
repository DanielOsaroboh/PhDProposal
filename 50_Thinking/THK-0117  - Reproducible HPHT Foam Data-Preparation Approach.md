---
id: THK-0117
title: Reproducible HPHT Foam Data-Preparation Approach
type: contribution
domain: Petroleum Engineering
topic: HPHT Foam Data
status: expected
source_context: PhD Expected Contributions
---

# THK-0117 - Reproducible HPHT Foam Data-Preparation Approach

## Contribution Statement

The research is expected to provide a reproducible approach for
preparing heterogeneous HPHT foam rheology and stability data for
subsequent analysis and predictive modelling.

## Core Idea

The contribution extends beyond the final dataset.

It also concerns the process through which heterogeneous experimental
evidence is transformed into a model-ready form.

## Preparation Architecture

```text
Source Identification
        ↓
Data Extraction
        ↓
Digitisation
        ↓
Variable Definition
        ↓
Unit Standardisation
        ↓
Terminology Harmonisation
        ↓
Data Quality Assessment
        ↓
Structured Model-Ready Dataset
```


## Reproducibility Principle

The transformation from published evidence to analytical dataset should  
be sufficiently documented that the major preparation decisions can be  
understood and reproduced.

## Why This Is a Contribution

Heterogeneous literature-derived datasets require methodological  
decisions concerning:

- variable definitions;
- units;
- terminology;
- missing observations;
- duplicate records;
- experimental metadata;
- data-quality assessment.

Making these decisions systematic and transparent provides value beyond  
the final predictive models.

## Difference from the Data Resource

[[THK-0116 - Structured HPHT Foam Data Resource]] is the resulting  
research asset.

This note concerns the reproducible **approach used to produce that  
asset**.

Therefore:

```
THK-0117
Reproducible Preparation Approach
        ↓
produces
        ↓
THK-0116
Structured HPHT Foam Data Resource
```

## Research Value

The approach can support:

- traceability;
- methodological transparency;
- future data expansion;
- replication;
- subsequent modelling studies.

## Important Boundary

Reproducibility does not remove limitations inherited from the original  
experimental literature.

Poorly reported or unavailable information cannot automatically be  
recovered through data preparation.

## Related Notes

- [[THK-0072 - HPHT Foam Dataset Compilation and Structuring]]
- [[THK-0085 - Heterogeneous Foam Dataset Harmonisation]]
- [[THK-0111 - Literature Data Digitisation]]
- [[THK-0116 - Structured HPHT Foam Data Resource]]

## Hubs

- [[HUB-T17 - Contributions]]

````

````

# THK-0119 — Reliability-Aware Foam Prediction Capability

```markdown
---
id: THK-0119
title: Reliability-Aware Foam Prediction Capability
type: contribution
domain: Petroleum Engineering
topic: Predictive Uncertainty
status: expected
source_context: PhD Expected Contributions
---

# THK-0119 - Reliability-Aware Foam Prediction Capability

## Contribution Statement

The research is expected to extend deterministic HPHT foam prediction
by incorporating predictive uncertainty and model-reliability
assessment into the interpretation of apparent-viscosity and
foam-stability predictions.

## Core Advancement

The progression is:

```text
Deterministic Prediction
        ↓
Predicted Value
````

extended to:

```
Prediction
        +
Predictive Uncertainty
        +
Reliability Assessment
        ↓
Reliability-Aware Prediction
```

## Conditions of Particular Interest

Reliability assessment is especially important under:

- sparse conditions;
- unfamiliar conditions;
- extrapolated HPHT conditions.

## Contribution Question

The capability helps answer not only:

> What does the model predict?

but also:

> How much confidence should be placed in that prediction given the  
> available evidence?

## Information Produced

A reliability-aware prediction may therefore contain:

### Property Information

Predicted:

- apparent viscosity;
- foam stability.

### Uncertainty Information

Information about the uncertainty associated with the prediction.

### Reliability Information

Interpretation of whether the prediction occurs under strongly or  
weakly supported conditions.

## Engineering Value

This allows model predictions to be interpreted with greater awareness  
of their:

- confidence;
- limitations;
- domain support;
- suitability for subsequent engineering evaluation.

## Relationship to Uncertainty Decomposition

Where supported by the methodology, uncertainty may be interpreted  
through:

- [[THK-0098 - Aleatoric Uncertainty in Foam Prediction]]
- [[THK-0099 - Epistemic Uncertainty in Foam Prediction]]
- [[THK-0100 - Aleatoric–Epistemic Uncertainty Decomposition]]

## Difference from Prediction Alone

[[THK-0118 - HPHT Foam Predictive Capability]]  
answers:

> What foam behaviour is predicted?

This contribution additionally addresses:

> How reliable is the prediction?

## Downstream Role

Reliability-aware predictions provide the information foundation for:

[[THK-0103 - Uncertainty-Bounded Operating Window]]

## Related Notes

- [[THK-0027 - Deterministic Foam Prediction]]
- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0051 - Model Reliability under Unfamiliar Conditions]]
- [[THK-0052 - Uncertainty-Aware Foam Prediction]]
- [[THK-0074 - Uncertainty-Based Model Reliability Assessment]]
- [[THK-0100 - Aleatoric–Epistemic Uncertainty Decomposition]]
- [[THK-0118 - HPHT Foam Predictive Capability]]

## Hubs

- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T17 - Contributions]]