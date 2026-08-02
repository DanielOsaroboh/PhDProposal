---
id: THK-0085
title: Heterogeneous Foam Dataset Harmonisation
type: method
domain: Petroleum Engineering
topic: HPHT Foam Data Preparation
status: developed
source_context: PhD Proposed Methodology
---

# THK-0085 - Heterogeneous Foam Dataset Harmonisation

## Definition

Heterogeneous foam dataset harmonisation is the process of transforming
data obtained from different experimental studies into a consistent,
comparable, and computationally usable dataset.

## Problem

Independent studies may report data using different:

- units;
- terminology;
- concentration scales;
- measurement scales;
- experimental protocols;
- metadata structures.

## Harmonisation Process

Multiple Experimental Studies
        ↓
Heterogeneous Raw Data
        ↓
Unit Conversion
+
Terminology Harmonisation
+
Missing-Data Treatment
+
Duplicate Removal
+
Scaling / Normalisation
+
Outlier Assessment
        ↓
Harmonised Dataset

## Proposed Standardisation

### Pressure

Convert to MPa.

### Temperature

Convert to °C.

### Chemical Concentration

Convert to wt% where appropriate.

### Missing Metadata

Imputation where justified or record removal.

### Duplicate Observations

Identify and remove duplicate records.

### Measurement Scales

Apply appropriate normalisation or scaling where required.

### Outliers

Combine statistical anomaly detection with physical engineering review.

### Terminology

Harmonise variable names across studies.

## Important Principle

Data preprocessing should not be treated as a purely computational
cleaning exercise.

Changes to engineering data must preserve physical meaning.

## Output

The result is a:

> **harmonised, quality-assured, model-ready HPHT foam dataset.**

## Related Notes

- [[THK-0072 - HPHT Foam Dataset Compilation and Structuring]]
- [[THK-0084 - HPHT Foam Feature Matrix]]
- [[THK-0086 - Engineering-Guided Outlier Assessment]]
- [[THK-0066 - Laboratory-Scale Data Dependence]]

## Hubs

- [[HUB-T07 - Methods]]