This is actually the next stage of your knowledge system. Right now you've built an **ontology** (what kinds of knowledge you have). What you're asking about is **how to retrieve knowledge**. You don't create separate notes for these questions. Instead, you answer them by **querying and linking your existing notes**.

Think of it like this:

- **Ontology = Database Schema**
    
- **Notes = Database Records**
    
- **Questions = Queries**
    

For example, suppose you have these notes:

```
Concepts/
    Machine Learning.md
    Foam Rheology.md
    Fracture Conductivity.md

Entities/
    Pressure.md
    Proppant.md

Methods/
    Cross Validation.md

Models/
    Random Forest.md
    XGBoost.md
    Gaussian Process Regression.md
```

Then the question:

> What is Machine Learning?

does **not** need its own note.

It simply opens

```
Machine Learning.md
```

because that note contains

- Definition
    
- Explanation
    
- Characteristics
    
- Applications
    

---

## Relationship questions

Question

> How is Pressure related to Foam Rheology?

Answer by traversing links.

Pressure.md

```
Related
• Foam Rheology
• HPHT Reservoir

Influences
• Apparent Viscosity
• Foam Stability
```

Foam Rheology.md

```
Influenced by
• Pressure
• Temperature
• Salinity
```

The relationship is discovered from both notes.

---

## Process questions

Question

> How is Model Validation performed?

Open

```
Processes/
    Model Validation.md
```

because that note contains

- Purpose
    
- Inputs
    
- Activities
    
- Outputs
    

---

## Cause questions

Question

> Why do nanoparticles improve foam stability?

This is answered by

```
Mechanisms/
    Nanoparticles Stabilise Foam.md
```

because mechanisms answer

> How and Why.

---

## Comparison questions

This is where many people create unnecessary notes.

Don't make

```
Random Forest vs XGBoost.md
```

Instead, each model already contains structured fields.

Random Forest

```
Strengths
Weaknesses
Applications
Inputs
Outputs
```

XGBoost

```
Strengths
Weaknesses
Applications
Inputs
Outputs
```

The comparison is produced by reading both notes.

Only create a comparison note if it is something you expect to revisit frequently, for example:

```
Comparisons/
    Random Forest vs XGBoost.md
```

---

## Dependency questions

Question

> What does Bayesian Optimisation require?

Bayesian Optimisation.md

```
Prerequisites

• Probability
• Gaussian Process Regression
• Acquisition Function
```

The answer comes directly from the note.

---

## Application questions

Question

> Where is Foam Rheology applied?

Foam Rheology.md

```
Applications

• Hydraulic Fracturing
• Enhanced Oil Recovery
• Laboratory Testing
```

---

## Evaluation questions

Question

> Which metric should I use?

Each metric explains itself.

RMSE

```
Best for:
Large errors

Sensitive to outliers
```

MAE

```
Best for:
Average error

Easy interpretation
```

R²

```
Best for:
Explained variance
```

The decision comes from comparing those notes.

---

## Decision questions

Question

> Which model should I choose?

No single note answers that.

Instead you combine

```
Random Forest
XGBoost
Gaussian Process Regression
```

using fields like

```
Strengths

Weaknesses

Assumptions

Best Used When
```

---

## Navigation questions

These are answered automatically if every note has good links.

Pressure.md

```
Related

Foam Rheology
Foam Quality
Temperature
HPHT Reservoir
```

Then Obsidian's graph and backlinks answer

> What concepts are related to Pressure?

without any extra work.

---

# The final layer: Question Notes

This is the piece I think you're missing.

After building your ontology, create one more folder:

```
13_Questions
│
├── Definitions
├── Relationships
├── Comparisons
├── Decisions
├── Applications
├── Research Questions
└── FAQs
```

A **question note** is very small. It doesn't duplicate knowledge—it points to the notes that answer the question.

Example:

```markdown
# Which model should I use?

## Short Answer

It depends on the data size, interpretability requirements, computational resources, and the need for uncertainty estimation.

## Read

- [[Random Forest]]
- [[XGBoost]]
- [[Gaussian Process Regression]]
- [[RMSE]]
- [[Cross Validation]]

## Decision Criteria

| Situation | Recommended Model |
|-----------|-------------------|
| Small dataset with uncertainty estimates | Gaussian Process Regression |
| Large nonlinear dataset | XGBoost |
| Balanced accuracy and interpretability | Random Forest |
```

Notice that **the knowledge still lives in the ontology notes**. The question note acts as an **index** or **guide**, pulling together the relevant concepts, entities, methods, models, metrics, and processes to answer a specific question.

This creates a three-layer architecture:

```text
Knowledge Layer (Ontology)
    Concepts
    Entities
    Processes
    Mechanisms
    Principles
    Methods
    Models
    Variables
    Parameters
    Metrics
    Functions

↓

Question Layer
    Definition Questions
    Comparison Questions
    Decision Questions
    Research Questions
    FAQs

↓

Output Layer
    Essays
    Literature Reviews
    Research Papers
    Thesis Chapters
    Presentations
```

This architecture is particularly powerful because the **ontology remains stable and reusable**, while the **question layer** changes depending on what you're trying to learn, teach, or write. It also mirrors how experts think: they maintain a structured understanding of a domain and then answer different questions by drawing connections across that knowledge rather than rewriting it each time.