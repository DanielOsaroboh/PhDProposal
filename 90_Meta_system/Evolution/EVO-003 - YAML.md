Since you're building a **long-term ontology-based knowledge system**, I recommend using one universal YAML template for **every evergreen note**. You only change the values, not the structure.

```yaml
---
id:
title:
aliases: []

type:                # Concept | Entity | Process | Principle | Mechanism | Method | Model | Variable | Metric | Framework | Function

domain:
subdomain:

status: permanent    # permanent | developing | draft | archived
maturity: seed       # seed | growing | mature

created:
updated:

tags: []

source:
  - title:
    author:
    year:
    pages:
    url:

parents: []
children: []

related: []

prerequisites: []

used_in: []

see_also: []

keywords: []

---
```

---

## Example 1 – Concept

```yaml
---
id: CON-0001
title: Foam Rheology
aliases:
  - Foam Flow Behaviour

type: Concept

domain: Petroleum Engineering
subdomain: Foam Mechanics

status: permanent
maturity: growing

created: 2026-07-31
updated: 2026-07-31

tags:
  - petroleum
  - rheology
  - foam

source:
  - title: PhD Proposal
    author: Martins
    year: 2026

parents: []

children: []

related:
  - Energised Foam
  - Apparent Viscosity

prerequisites:
  - Fluid Mechanics

used_in:
  - Hydraulic Fracturing

see_also:
  - Rheological Behaviour

keywords:
  - viscosity
  - shear
  - non-newtonian
---
```

---

## Example 2 – Process

```yaml
type: Process
```

---

## Example 3 – Principle

```yaml
type: Principle
```

---

## Example 4 – Method

```yaml
type: Method
```

---

## Example 5 – Variable

```yaml
type: Variable
```

---

# Inside Every Note

After the YAML, use the same structure for every note.

```markdown
# Definition

# Explanation

# Characteristics

# Importance

# Relationships

# Applications

# Examples

# Related Notes
```

---

# For Processes

```markdown
# Purpose

# Inputs

# Activities

# Outputs

# Decision Points

# Related Notes
```

---

# For Principles

```markdown
# Statement

# Meaning

# Why It Matters

# Applications

# Examples

# Related Notes
```

---

# For Mechanisms

```markdown
# Overview

# Trigger

# Mechanism

# Outcome

# Limitations

# Related Notes
```

---

# My Recommendation

I would make one small enhancement to support your growing knowledge graph: add a **knowledge class** and **permanent ID** that never change.

```yaml
---
id: CON-0042
title: Foam Rheology

class: Evergreen
type: Concept

domain: Petroleum Engineering
subdomain: Foam Mechanics

status: Permanent
maturity: Growing

created: 2026-07-31
updated: 2026-07-31

tags: []

aliases: []

related: []

parents: []

children: []

source: []

review: quarterly
---
```

Using stable IDs (such as `CON-0042`, `ENT-0015`, `PRO-0008`, `MEC-0012`) makes your notes easier to reference, automate, and manage as your Obsidian vault grows into thousands of interconnected knowledge objects.