---
id: THK-0066
title: Laboratory-Scale Data Dependence
type: limitation
domain: Petroleum Engineering
topic: Foam Predictive Modelling
status: developed
source_context: PhD Knowledge Gap
---

# THK-0066 - Laboratory-Scale Data Dependence

## What Is Limited

Predictive models of energised-foam behaviour are frequently developed
using laboratory-scale experimental datasets.

## Nature of the Limitation

Laboratory experiments provide essential controlled evidence but may
represent only part of the conditions, interactions, and variability
relevant to broader HPHT engineering applications.

## Limitation Pathway

```text
Laboratory Experimental Design
        ↓
Controlled range of conditions
        ↓
Training dataset
        ↓
Model learns laboratory-domain relationships
        ↓
Application to broader HPHT conditions
        ↓
Potential domain mismatch
        ↓
Uncertain generalisation

```

## Why It Matters

Machine-learning models learn the relationships contained in the  
available data.

They do not automatically acquire knowledge about operating conditions  
that are absent from those data.

Therefore:

> **Model flexibility cannot compensate automatically for missing  
> experimental-domain coverage.**

## Engineering Consequence

Strong performance on laboratory data does not alone establish reliable  
performance under wider or field-relevant HPHT conditions.

## Important Boundary

This limitation does not mean laboratory data are unsuitable.

Laboratory data remain essential for controlled investigation.

The limitation concerns **generalisation beyond the domain represented  
by those data**.

## Mitigation Direction

Potential responses include:

- explicit definition of the training domain;
- domain-aware validation;
- uncertainty quantification;
- identification of unsupported regions;
- targeted additional experiments;
- cautious engineering interpretation.

## Research Relevance

The limitation strengthens the case for combining prediction with  
explicit assessment of model reliability.

## Evidence

The knowledge-gap section identifies laboratory-scale datasets as a  
dominant characteristic of existing data-driven foam studies.

## Related Notes

- [[THK-0014 - Limited HPHT Experimental Coverage]]
- [[THK-0029 - Sparse-Data Uncertainty]]
- [[THK-0030 - Extrapolation Uncertainty]]
- [[THK-0051 - Model Reliability under Unfamiliar Conditions]]
- [[THK-0067 - Formulation-Specific Data Dependence]]
- [[THK-0068 - Data-Domain-Dependent Predictive Performance]]

## Hubs

- [[HUB-03 - Rheological Modelling]]
- [[HUB-06 - Prediction & Uncertainty]]
- [[HUB-T10 - Limitations]]
