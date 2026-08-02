These fit well into your ontology. Below are example note templates for **Entities** and **Processes** using the same YAML and structure you've standardized.

---

# HPHT Reservoir.md

```markdown
---
id: ENT-0001
title: HPHT Reservoir
aliases:
  - High-Pressure High-Temperature Reservoir

class: Evergreen
type: Entity

domain: Petroleum Engineering
subdomain: Reservoir Engineering

status: permanent
maturity: growing

created:
updated:

tags:
  - reservoir
  - hpht

source: []

parents: []
children: []

related:
  - Pressure
  - Temperature
  - Hydraulic Fracturing

review: quarterly
---

# Definition

A High-Pressure High-Temperature (HPHT) reservoir is a subsurface hydrocarbon reservoir whose pressure and temperature exceed conventional operating conditions.

# Description

HPHT reservoirs present challenging environments due to extreme pressure and temperature, requiring specialised drilling, completion, and stimulation techniques.

# Characteristics

- High pressure
- High temperature
- Complex fluid behaviour
- High operational risk

# Components

- Reservoir rock
- Formation fluids
- Natural fractures

# Importance

HPHT conditions significantly influence fluid properties, foam stability, and hydraulic fracturing performance.

# Applications

- Deep reservoirs
- Offshore fields
- Hydraulic fracturing studies

# Related Notes

- [[Pressure]]
- [[Temperature]]
- [[Hydraulic Fracturing]]
- [[Foam Rheology]]
```

---

# CO₂.md

```markdown
---
id: ENT-0002
title: Carbon Dioxide (CO₂)

class: Evergreen
type: Entity

domain: Petroleum Engineering
subdomain: Fracturing Fluids

status: permanent
maturity: growing

tags:
  - gas
  - co2

related:
  - Energised Foam
  - Foam Quality
---

# Definition

Carbon dioxide is a compressible gas commonly used to generate energised foams for hydraulic fracturing.

# Description

CO₂ reduces water consumption and improves cleanup after stimulation.

# Characteristics

- Compressible
- High density
- Soluble under pressure

# Applications

- Energised foams
- Enhanced oil recovery
- Carbon storage

# Related Notes

- [[Energised Foam]]
- [[Foam Rheology]]
```

---

# Nitrogen.md

```markdown
---
id: ENT-0003
title: Nitrogen

class: Evergreen
type: Entity

domain: Petroleum Engineering
subdomain: Fracturing Fluids
---

# Definition

Nitrogen is an inert gas widely used to create energised foams for hydraulic fracturing.

# Characteristics

- Chemically inert
- Low density
- Compressible

# Applications

- Foam generation
- Well stimulation

# Related Notes

- [[Energised Foam]]
- [[Foam Rheology]]
```

---

# Proppant.md

```markdown
---
id: ENT-0004
title: Proppant

class: Evergreen
type: Entity

domain: Petroleum Engineering
subdomain: Hydraulic Fracturing
---

# Definition

A proppant is a solid material injected into fractures to keep them open after hydraulic fracturing.

# Characteristics

- High strength
- Spherical or angular
- Crush resistant

# Importance

Maintains fracture conductivity after pumping stops.

# Applications

- Hydraulic fracturing

# Related Notes

- [[Proppant Transport]]
- [[Fracture Conductivity]]
```

---

# Experimental Data Compilation.md

```markdown
---
id: PRO-0001
title: Experimental Data Compilation

class: Evergreen
type: Process

domain: Research Methodology
subdomain: Data Collection
---

# Purpose

Collect, organise, clean, and standardise experimental data for analysis.

# Inputs

- Experimental measurements
- Laboratory records
- Published datasets

# Activities

1. Gather data
2. Verify quality
3. Remove errors
4. Standardise units
5. Store dataset

# Outputs

- Clean dataset

# Applications

- Machine learning
- Statistical analysis

# Related Notes

- [[Predictive Modelling]]
```

---

# Model Validation.md

```markdown
---
id: PRO-0002
title: Model Validation

class: Evergreen
type: Process

domain: Machine Learning
subdomain: Model Evaluation
---

# Purpose

Determine whether a predictive model accurately represents real-world behaviour.

# Inputs

- Trained model
- Validation dataset

# Activities

1. Make predictions
2. Compare with observations
3. Calculate metrics
4. Assess accuracy

# Outputs

- Validation report
- Performance metrics

# Related Notes

- [[RMSE]]
- [[MAE]]
- [[Cross Validation]]
```

---

# Feature Engineering.md

```markdown
---
id: PRO-0003
title: Feature Engineering

class: Evergreen
type: Process

domain: Machine Learning
subdomain: Data Preparation
---

# Purpose

Transform raw data into informative features that improve model performance.

# Inputs

- Raw dataset

# Activities

1. Select variables
2. Create derived features
3. Encode categories
4. Scale values

# Outputs

- Feature matrix

# Related Notes

- [[Machine Learning]]
- [[Predictive Modelling]]
```

---

# Operating Window Identification.md

```markdown
---
id: PRO-0004
title: Operating Window Identification

class: Evergreen
type: Process

domain: Petroleum Engineering
subdomain: Process Optimisation
---

# Purpose

Identify the combination of operating conditions that delivers the desired engineering performance.

# Inputs

- Predictive model
- Pressure
- Temperature
- Foam quality

# Activities

1. Define objectives
2. Evaluate candidate conditions
3. Apply optimisation
4. Verify constraints
5. Select acceptable operating region

# Outputs

- Recommended operating window

# Applications

- Hydraulic fracturing
- Reservoir optimisation

# Related Notes

- [[Operating Window]]
- [[Bayesian Optimisation]]
- [[Uncertainty Quantification]]
```

## One refinement I'd recommend

Your current **Entity** note structure is very good for physical objects, but it will scale better if you distinguish between **natural entities** and **engineered entities**:

```text
02_Entities
│
├── Natural
│   ├── Reservoir
│   ├── Rock Formation
│   ├── Crude Oil
│
└── Engineered
    ├── Proppant
    ├── Energised Foam
    ├── Surfactant
    ├── Nanoparticle
```

This distinction reflects whether the entity exists naturally or has been designed or introduced by humans, making your ontology more expressive as it expands across petroleum engineering and related fields.