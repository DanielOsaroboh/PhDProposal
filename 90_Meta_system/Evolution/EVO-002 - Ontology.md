This is actually the most important part of your knowledge system. **The ontology should classify knowledge based on what it _is_, not where you found it.**

Here's how I would classify the notes from the proposal summary.

|Note|Ontology Type|Reason|
|---|---|---|
|Hydraulic Fracturing|**Concept**|A broad engineering concept/process.|
|HPHT Reservoir|**Entity**|A real engineering object/system.|
|Energised Foam|**Entity**|A physical material used in hydraulic fracturing.|
|Foam Rheology|**Concept**|A scientific concept describing flow behaviour.|
|Rheological Behaviour|**Concept**|An abstract property of materials.|
|Proppant Transport|**Process**|Describes movement of proppant through fractures.|
|Fracture Conductivity|**Concept**|An engineering performance property.|
|Machine Learning|**Concept**|A field/discipline of AI.|
|Predictive Modelling|**Process**|A workflow for building predictive models.|
|Uncertainty Quantification|**Method**|A methodological approach for estimating uncertainty.|
|Operating Window|**Concept**|An engineering concept defining acceptable operating conditions.|
|Engineering Decision Support|**Function**|Describes the purpose of a system.|
|Experimental Data Compilation|**Process**|A sequence of activities for gathering data.|
|Laboratory Validation|**Process**|A validation workflow.|
|Engineering Assessment|**Process**|An engineering evaluation workflow.|

---

## Where are the Principles?

Notice that **none of those notes are principles**.

Instead, principles should be extracted **from the statements** in the proposal.

For example:

### Principle 1

```text
Machine learning should support engineering judgement rather than replace it.
```

↓

```
06_Principles/
    AI Supports Engineering Judgement.md
```

---

### Principle 2

```text
Prediction uncertainty should be incorporated into engineering decisions.
```

↓

```
06_Principles/
    Engineering Decisions Should Account for Uncertainty.md
```

---

### Principle 3

```text
Stable foams are required for effective proppant transport.
```

↓

```
06_Principles/
    Foam Stability Enables Proppant Transport.md
```

---

## Where are the Mechanisms?

Mechanisms explain **how something works**.

Example:

```
Pressure
        ↓
Changes Bubble Structure
        ↓
Changes Foam Rheology
        ↓
Changes Proppant Transport
```

This becomes

```
04_Mechanisms/
Pressure Influences Foam Rheology.md
```

---

Another

```
Temperature
        ↓
Liquid Drainage
        ↓
Foam Stability
```

↓

```
Temperature Accelerates Foam Drainage.md
```

---

## Where are the Relationships?

Relationships simply connect knowledge.

Example

```
Machine Learning
        supports
Engineering Decision Making
```

or

```
Foam Stability
        affects
Proppant Transport
```

These don't necessarily become notes. They are often represented through Obsidian links or a graph.

---

## A Better Ontology

I would slightly refine your ontology to distinguish **objects** from **ideas**.

```
01_Concepts
    Foam Rheology
    Machine Learning
    Fracture Conductivity
    Operating Window

02_Entities
    Energised Foam
    HPHT Reservoir
    Proppant
    Surfactant
    Nanoparticle

03_Frameworks
    (later)

04_Mechanisms
    Pressure Influences Foam Rheology
    Nanoparticles Stabilise Foam

05_Processes
    Hydraulic Fracturing
    Predictive Modelling
    Data Compilation
    Laboratory Validation

06_Principles
    AI Supports Engineering Judgement
    Stable Foams Improve Transport
    Engineering Decisions Should Consider Uncertainty

07_Methods
    Uncertainty Quantification
    Bayesian Optimisation
    Cross Validation

08_Models
    Random Forest
    XGBoost
    Gaussian Process Regression

09_Variables
    Pressure
    Temperature
    Salinity
    Foam Quality

10_Metrics
    RMSE
    MAE
    R²

11_Functions
    Engineering Decision Support
```

I think this ontology is a much stronger fit for the kind of interdisciplinary research you're doing because it separates **what something is** (Concept, Entity), **how it works** (Mechanism, Process), **how to study it** (Method, Model), and **how to evaluate it** (Metric, Variable). As we decompose papers and textbooks, each piece of knowledge will naturally fall into one of these categories rather than being forced into a generic note.