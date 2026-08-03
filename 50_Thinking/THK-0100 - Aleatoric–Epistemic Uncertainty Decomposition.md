---
id: THK-0100
title: Aleatoric–Epistemic Uncertainty Decomposition
type: method
domain: Petroleum Engineering
topic: Predictive Uncertainty
status: developed
source_context: PhD Proposed Methodology
---

# THK-0100 - Aleatoric–Epistemic Uncertainty Decomposition

## Definition

Aleatoric–epistemic uncertainty decomposition is the analytical
separation of total predictive uncertainty into uncertainty associated
with inherent data variability and uncertainty associated with limited
model knowledge.

## Core Structure

Total Predictive Uncertainty
        ↓
┌─────────────────────────────┐
│                             │
↓                             ↓
Aleatoric                 Epistemic
Uncertainty               Uncertainty
│                             │
↓                             ↓
Data / physical            Model / knowledge
variability                limitation


## Component 1 — Aleatoric Uncertainty

[[THK-0098 - Aleatoric Uncertainty in Foam Prediction]]

Represents uncertainty associated with:

- measurement noise;
- experimental variability;
- inherent response variation.

Core question:

> How variable is the system or observation?

## Component 2 — Epistemic Uncertainty

[[THK-0099 - Epistemic Uncertainty in Foam Prediction]]

Represents uncertainty associated with:

- sparse data;
- unfamiliar conditions;
- extrapolation;
- incomplete model knowledge.

Core question:

> How much does the model not know?

## Why Decomposition Matters

A single uncertainty value does not explain **why** a prediction is  
uncertain.

For engineering interpretation, the source matters.

### Case A

High aleatoric uncertainty  
+  
Low epistemic uncertainty

Interpretation:

The model may understand the region reasonably well, but the underlying  
response is intrinsically variable.

### Case B

Low aleatoric uncertainty  
+  
High epistemic uncertainty

Interpretation:

The physical response may be relatively consistent, but the model lacks  
sufficient evidence about that region.

### Case C

High aleatoric uncertainty  
+  
High epistemic uncertainty

Interpretation:

Both experimental variability and limited model knowledge reduce  
prediction confidence.

## Engineering Response

Different uncertainty sources may require different responses.

```
High Aleatoric Uncertainty
        ↓
Improve measurement / experimental control where possible
        +
Accept irreducible variability

High Epistemic Uncertainty
        ↓
Acquire additional data
        +
Target new experiments
        +
Restrict extrapolation
        +
Improve model knowledge
```

## Relationship to Model Reliability

Reliability assessment becomes more informative when uncertainty is not  
treated as a single undifferentiated quantity.

Instead:

Prediction  
+  
Aleatoric Uncertainty  
+  
Epistemic Uncertainty  
↓  
Richer Reliability Interpretation

## Relationship to Operating Windows

A candidate condition may have favourable predicted viscosity and  
stability but high epistemic uncertainty.

That condition should not necessarily receive the same engineering  
confidence as an equally favourable prediction supported by dense  
experimental evidence.

Therefore:

Performance Suitability  
+  
Uncertainty Type  
+  
Uncertainty Magnitude  
↓  
Operating-Window Confidence

## Research Significance

This decomposition transforms uncertainty quantification from a  
statistical reporting exercise into an engineering diagnostic tool.

It helps distinguish:

> uncertainty caused by the behaviour of the system

from

> uncertainty caused by limitations in what the model knows.

## Related Notes

- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0065 - Experimental Variability Uncertainty]]
- [[THK-0074 - Uncertainty-Based Model Reliability Assessment]]
- [[THK-0098 - Aleatoric Uncertainty in Foam Prediction]]
- [[THK-0099 - Epistemic Uncertainty in Foam Prediction]]
- [[THK-0103 - Uncertainty-Bounded Operating Window]]

## Hubs

- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T07 - Methods]]