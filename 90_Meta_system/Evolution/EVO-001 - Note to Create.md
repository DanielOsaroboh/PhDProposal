No. **Not everything deserves its own note.** This is one of the most important principles of building a sustainable knowledge system.

Think of it this way:

> **Only create notes that have long-term value and can be reused independently.**

Instead of asking _"Can this be a note?"_, ask:

> **"Will I ever want to find, understand, expand, or link to this again?"**

If the answer is yes, create a note.

## What should become a note?

### ✅ Concepts

Always.

```
Hydraulic Fracturing

Foam Rheology

Machine Learning

Operating Window
```

These are foundational.

---

### ✅ Entities

Usually.

```
HPHT Reservoir

CO₂

Nitrogen

Proppant
```

These are important domain objects.

---

### ✅ Processes

When they are substantial.

```
Experimental Data Compilation

Model Validation

Feature Engineering

Operating Window Identification
```

Not tiny actions like "collect data."

---

### ✅ Mechanisms

Yes, if they explain causality.

```
Pressure affects bubble structure

Temperature accelerates liquid drainage

Foam stability improves proppant transport
```

Mechanisms explain **how** something works.

---

### ✅ Principles

Definitely.

```
Engineering judgement should guide AI.

Prediction uncertainty should be considered.
```

Principles are reusable across many projects.

---

### ⚠️ Problems

Usually **only** if they are recurring.

```
Data Scarcity

Nonlinear Behaviour

Model Generalisation
```

These appear in many AI and engineering papers, so they're worth keeping.

---

### ⚠️ Solutions

Only if they are general methods.

```
Uncertainty-aware Machine Learning

Bayesian Optimisation

Ensemble Learning
```

Not "Solution to my PhD proposal."

---

### ❌ Pipelines

Usually **no**.

The pipeline

```
Data
↓
Model
↓
Validation
↓
Optimisation
```

is **not** a separate note.

Instead, store it inside:

```
Predictive Modelling.md
```

or

```
Research Methodology.md
```

---

### ❌ Outcomes

Usually no.

```
Improved decision making

Field application
```

These belong inside your research project note.

---

## A Good Rule

For every section you decompose, you'll probably create:

- 5–15 Concept notes
    
- 3–10 Entity notes
    
- 2–5 Process notes
    
- 2–5 Mechanism notes
    
- 2–5 Principle notes
    

Everything else can simply enrich those notes instead of becoming standalone files.

## Your Knowledge System Has Two Layers

### Layer 1: Permanent Knowledge (Evergreen)

```
Hydraulic Fracturing.md

Foam Rheology.md

Pressure.md

Machine Learning.md

Uncertainty Quantification.md

Feature Engineering.md
```

These grow over years.

---

### Layer 2: Project Knowledge

```
PhD Proposal.md

Research Questions.md

Methodology.md

Proposal Summary.md
```

These are specific to your PhD.

The permanent notes are **linked from** the project notes.

So your proposal summary might look like:

```
Proposal Summary

This study investigates:

• [[Hydraulic Fracturing]]
• [[HPHT Reservoir]]
• [[Foam Rheology]]
• [[Machine Learning]]
• [[Uncertainty Quantification]]
• [[Operating Window]]
```

The detailed knowledge lives in the linked notes, not in the summary itself.

This distinction keeps your vault clean: **evergreen notes capture enduring knowledge, while project notes assemble and apply that knowledge to a specific research question.**