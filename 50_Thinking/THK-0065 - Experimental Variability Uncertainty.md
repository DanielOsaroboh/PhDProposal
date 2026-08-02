---
id: THK-0065
title: Experimental Variability Uncertainty
type: mechanism
domain: Petroleum Engineering
topic: Predictive Uncertainty
status: developed
source_context: PhD Knowledge Gap
---

# THK-0065 - Experimental Variability Uncertainty

## Definition

Experimental variability uncertainty is the component of predictive
uncertainty arising from variation, noise, measurement limitations, and
uncontrolled differences within experimental observations.

## Core Idea

Experimental measurements are not perfectly deterministic
representations of the underlying physical system.

Repeated observations obtained under nominally similar conditions may
contain variation.

## Mechanism

```text
Experimental Process
        ↓
Measurement variation
+
Operational variation
+
Uncontrolled experimental variation
        ↓
Observed data variability
        ↓
Model learns from variable observations
        ↓
Uncertainty in predicted response

```

## Sources

Potential sources can include:

- measurement error;
- instrument precision;
- preparation variability;
- environmental variation;
- sample variability;
- differences in experimental execution.

The specific sources should be established from the experimental  
datasets used in the research rather than assumed.

## Difference from Sparse-Data Uncertainty

[[THK-0029 - Sparse-Data Uncertainty]] concerns insufficient  
observations in parts of the input domain.

Experimental variability concerns variation **within the observations  
that do exist**.

Thus:

```
Sparse Data
→ How much evidence exists?

Experimental Variability
→ How variable is the observed evidence?
```

## Difference from Extrapolation Uncertainty

[[THK-0030 - Extrapolation Uncertainty]] arises when prediction extends  
beyond the observed training domain.

Experimental variability can exist even inside a densely sampled domain.

## Engineering Significance

If experimental variability is ignored, predictions may appear more  
precise than the underlying evidence supports.

This can create excessive confidence when predictions are used for  
formulation or operating-condition assessment.

## Research Relevance

Experimental variability is one of the uncertainty sources that an  
uncertainty-aware predictive framework should recognise when  
interpreting model reliability.

## Related Notes

- [[THK-0028 - Predictive Uncertainty]]
- [[THK-0029 - Sparse-Data Uncertainty]]
- [[THK-0030 - Extrapolation Uncertainty]]
- [[THK-0047 - Uncertainty Propagation]]
- [[THK-0052 - Uncertainty-Aware Foam Prediction]]

## Hubs

- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T03 - Mechanisms]]

