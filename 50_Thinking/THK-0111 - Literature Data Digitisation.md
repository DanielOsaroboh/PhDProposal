---
id: THK-0111
title: Literature Data Digitisation
type: method
domain: Petroleum Engineering
topic: HPHT Foam Data Acquisition
status: developed
source_context: PhD Data Requirements and Feasibility
---

# THK-0111 - Literature Data Digitisation

## Definition

Literature data digitisation is the conversion of relevant experimental
measurements reported in published research into structured numerical
records suitable for subsequent analysis and modelling.

## Core Problem

Relevant HPHT foam evidence may exist in the literature without being
provided as a directly downloadable machine-readable dataset.

The information may therefore require systematic extraction and
structuring.

## Method Pattern

```text
Published Experimental Study
        ↓
Identify Relevant Measurements
        ↓
Extract / Digitise Data
        ↓
Record Experimental Context
        ↓
Standardise Variables and Units
        ↓
Quality Check
        ↓
Structured Dataset
```

## Target Information

Digitisation may capture measurements relating to:

- pressure;
- temperature;
- foam quality;
- shear rate;
- salinity;
- surfactant concentration;
- nanoparticle concentration;
- apparent viscosity;
- foam stability indicators.

## Why Context Matters

A numerical measurement without its experimental context may have  
limited modelling value.

Therefore, extraction should preserve relevant metadata describing the  
conditions under which the measurement was obtained.

## Relationship to Harmonisation

Digitisation produces structured observations.

Those observations subsequently enter:

[[THK-0085 - Heterogeneous Foam Dataset Harmonisation]]

where differences in:

- units;
- terminology;
- scales;
- variable definitions;
- study conventions

are addressed.

## Quality Principle

Digitisation should preserve the evidence contained in the original  
source rather than creating artificial precision unsupported by the  
published material.

## Research Role

Literature digitisation expands the usable empirical base where  
machine-readable HPHT foam datasets are limited.

## Evidence

Tran et al. (2023) is cited in the research's data strategy in relation  
to the systematic extraction and structuring of relevant HPHT foam  
measurements.

## Related Notes

- [[THK-0072 - HPHT Foam Dataset Compilation and Structuring]]
- [[THK-0085 - Heterogeneous Foam Dataset Harmonisation]]
- [[THK-0110 - Published-Data-First Acquisition Strategy]]
- [[THK-0112 - HPHT Foam Dataset Adequacy]]

## Hubs

- [[HUB-T07 - Methods]]

