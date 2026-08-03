This section should be processed somewhat differently from the technical sections. It is primarily an **alignment/capability map**: what capabilities you already bring, what transfers into the PhD, where the boundary of that competence lies, and what knowledge must be developed.

I would **not turn every qualification or experience into a THK**. The reusable knowledge objects are the relationships and principles behind the alignment.

### Knowledge-object extraction

|Action|THK|Knowledge Object|Type|
|---|---|---|---|
|**New**|`THK-0126`|Researcher–Problem Capability Alignment|Framework|
|**New**|`THK-0127`|AI–HPHT Foam Methodological Transfer|Relationship|
|**New**|`THK-0128`|Engineering Systems–HPHT Foam Transferability|Relationship|
|**New**|`THK-0129`|Transferability–Domain Equivalence Distinction|Principle|
|**New**|`THK-0130`|Petroleum Engineering Domain-Knowledge Gap|Knowledge Gap|
|**New**|`THK-0131`|Domain-Grounded Computational Modelling|Principle|
|**New**|`THK-0132`|Interdisciplinary Capability Development|Development Process|

I would treat the specific **MRes, KTP experience and SPE membership as evidence within these notes**, rather than separate knowledge objects.

---

# THK-0126 — Researcher–Problem Capability Alignment

````markdown
---
id: THK-0126
title: Researcher–Problem Capability Alignment
type: framework
domain: Research Methodology
topic: Research Capability
status: developed
source_context: PhD Alignment with My Background
---

# THK-0126 - Researcher–Problem Capability Alignment

## Definition

Researcher–problem capability alignment describes the relationship
between the capabilities already possessed by the researcher and the
technical capabilities required to investigate the doctoral research
problem.

## Core Idea

The research sits at the intersection of:

- predictive analytics;
- engineering systems;
- petroleum engineering.

The researcher enters this intersection with stronger existing
capabilities in the first two areas while requiring deliberate
development in the petroleum-engineering domain.

## Alignment Architecture

```text
EXISTING CAPABILITY
        │
        ├── Artificial Intelligence
        ├── Predictive Modelling
        ├── Uncertainty Quantification
        └── Engineering Systems
                 ↓
         TRANSFERABLE TO
                 ↓
HPHT Foam Predictive Research
                 ↑
                 │
        DOMAIN DEVELOPMENT
                 │
        ├── Petroleum Engineering
        ├── Foam Rheology
        └── Fracturing-Fluid Design
````

## Existing Computational Foundation

The researcher's Master of Research in Artificial Intelligence provides  
background relevant to:

- Bayesian optimisation;
    
- uncertainty quantification;
    
- time-series data modelling.
    

These capabilities provide a foundation for the computational aspects  
of the proposed research.

## Existing Engineering-Systems Foundation

Experience with IoT-enabled predictive monitoring of high-pressure  
subsea hydraulic networks provides transferable experience involving:

- pressure;
    
- operating variability;
    
- monitoring;
    
- uncertainty;
    
- complex engineering systems.
    

## Capability Gap

Existing competence does not remove the need to develop specialised  
knowledge in:

- petroleum engineering;
    
- foam rheology;
    
- hydraulic fracturing-fluid design.
    

## Alignment Principle

The research therefore does not begin from:

```text
Complete Domain Expertise
```

It begins from:

```text
Strong Computational Capability
        +
Relevant Engineering-Systems Experience
        +
Deliberate Petroleum-Engineering Development
        ↓
Interdisciplinary Research Capability
```

## Related Notes

- [[THK-0127 - AI–HPHT Foam Methodological Transfer]]
    
- [[THK-0128 - Engineering Systems–HPHT Foam Transferability]]
    
- [[THK-0129 - Transferability–Domain Equivalence Distinction]]
    
- [[THK-0130 - Petroleum Engineering Domain-Knowledge Gap]]
    
- [[THK-0131 - Domain-Grounded Computational Modelling]]
    
- [[THK-0132 - Interdisciplinary Capability Development]]
    

## Hub

- [[HUB-T20 - Research Capability and Alignment]]
    

````

# THK-0127 — AI–HPHT Foam Methodological Transfer

```markdown
---
id: THK-0127
title: AI–HPHT Foam Methodological Transfer
type: relationship
domain: Research Methodology
topic: Interdisciplinary Transfer
status: developed
source_context: PhD Alignment with My Background
---

# THK-0127 - AI–HPHT Foam Methodological Transfer

## Definition

AI–HPHT foam methodological transfer is the application of existing
artificial-intelligence and predictive-modelling capabilities to the
analysis of HPHT energised-foam behaviour.

## Source Capabilities

The researcher's AI background includes experience relevant to:

- predictive modelling;
- Bayesian optimisation;
- uncertainty quantification;
- time-series data modelling.

## Target Research Tasks

These capabilities are relevant to:

- [[THK-0118 - HPHT Foam Predictive Capability]]
- prediction of [[THK-0005 - Foam Apparent Viscosity]];
- prediction of [[THK-0006 - Foam Stability]];
- [[THK-0028 - Predictive Uncertainty]];
- [[THK-0074 - Uncertainty-Based Model Reliability Assessment]];
- [[THK-0103 - Uncertainty-Bounded Operating Window]].

## Transfer Structure

```text
AI Capability
        ↓
Predictive Modelling
        ↓
HPHT Foam Prediction

Uncertainty Quantification
        ↓
Prediction Reliability

Predictive + Reliability Information
        ↓
Candidate Operating Windows
````

## Important Boundary

Possessing computational capability does not automatically establish  
domain competence in foam rheology or petroleum engineering.

The computational methods must therefore be constrained and informed by  
physical knowledge.

See:

[[THK-0129 - Transferability–Domain Equivalence Distinction]]

## Related Notes

- [[THK-0024 - Machine Learning for Foam Rheology]]
    
- [[THK-0028 - Predictive Uncertainty]]
    
- [[THK-0103 - Uncertainty-Bounded Operating Window]]
    
- [[THK-0118 - HPHT Foam Predictive Capability]]
    
- [[THK-0126 - Researcher–Problem Capability Alignment]]
    
- [[THK-0131 - Domain-Grounded Computational Modelling]]
    

## Hub

- [[HUB-T20 - Research Capability and Alignment]]
    

````

# THK-0128 — Engineering Systems–HPHT Foam Transferability

```markdown
---
id: THK-0128
title: Engineering Systems–HPHT Foam Transferability
type: relationship
domain: Engineering Systems
topic: Interdisciplinary Transfer
status: developed
source_context: PhD Alignment with My Background
---

# THK-0128 - Engineering Systems–HPHT Foam Transferability

## Definition

Engineering systems–HPHT foam transferability describes how experience
with predictive monitoring of high-pressure engineering systems can
provide transferable systems-level reasoning for HPHT foam research.

## Source Experience

Relevant previous engineering experience involved IoT-enabled
predictive monitoring systems for high-pressure subsea hydraulic
networks.

This involved consideration of:

- pressure;
- operating variability;
- monitoring;
- uncertainty;
- complex engineering behaviour.

## Transferable Pattern

```text
Complex Engineering System
        ↓
Variable Operating Conditions
        ↓
Measured System Behaviour
        ↓
Predictive Modelling
        ↓
Uncertainty / Reliability
        ↓
Engineering Interpretation
````

The same broad systems logic appears within the proposed HPHT foam  
research.

## Transfer to HPHT Foam Research

```text
HPHT Foam System
        ↓
Variable P–T–Formulation Conditions
        ↓
Rheology + Stability
        ↓
Predictive Modelling
        ↓
Uncertainty Assessment
        ↓
Engineering Interpretation
```

## What Transfers

The transferable element is primarily an:

> **engineering-systems perspective**

rather than direct hydraulic-fracturing-fluid expertise.

## Important Boundary

High-pressure hydraulic-network experience is not equivalent to:

- petroleum engineering expertise;
    
- foam-rheology expertise;
    
- hydraulic-fracturing-fluid design expertise.
    

That distinction is represented by:

[[THK-0129 - Transferability–Domain Equivalence Distinction]]

## Related Notes

- [[THK-0008 - HPHT Conditions]]
    
- [[THK-0057 - Multivariable Control of Foam Performance]]
    
- [[THK-0126 - Researcher–Problem Capability Alignment]]
    
- [[THK-0129 - Transferability–Domain Equivalence Distinction]]
    
- [[THK-0132 - Interdisciplinary Capability Development]]
    

## Hub

- [[HUB-T20 - Research Capability and Alignment]]
    

````

# THK-0129 — Transferability–Domain Equivalence Distinction

```markdown
---
id: THK-0129
title: Transferability–Domain Equivalence Distinction
type: principle
domain: Research Methodology
topic: Interdisciplinary Research
status: developed
source_context: PhD Alignment with My Background
---

# THK-0129 - Transferability–Domain Equivalence Distinction

## Principle

Experience or expertise acquired in one technical domain may provide
transferable methods and reasoning capabilities without being
equivalent to specialist expertise in another domain.

## Core Distinction

```text
Transferable Experience
        ≠
Domain Equivalence
````

For this research:

```text
AI Expertise
        ≠
Foam-Rheology Expertise

High-Pressure Engineering Experience
        ≠
Hydraulic-Fracturing Expertise

Predictive-Modelling Capability
        ≠
Petroleum-Engineering Judgement
```

## What Can Transfer

Capabilities that may transfer include:

- systems thinking;
    
- predictive modelling;
    
- uncertainty reasoning;
    
- analysis of operating variability;
    
- engineering-data interpretation.
    

## What Requires Domain Development

Specialist knowledge must still be developed in:

- petroleum engineering;
    
- foam rheology;
    
- energised fracturing fluids;
    
- hydraulic-fracturing-fluid design;
    
- interpretation of HPHT foam behaviour.
    

## Why It Matters

Ignoring this distinction creates the risk of applying computational  
methods without sufficient understanding of the physical system.

## Governing Principle

> **Transfer methods and reasoning across domains, but do not assume  
> that methodological competence substitutes for domain expertise.**

## Related Notes

- [[THK-0126 - Researcher–Problem Capability Alignment]]
    
- [[THK-0127 - AI–HPHT Foam Methodological Transfer]]
    
- [[THK-0128 - Engineering Systems–HPHT Foam Transferability]]
    
- [[THK-0130 - Petroleum Engineering Domain-Knowledge Gap]]
    
- [[THK-0131 - Domain-Grounded Computational Modelling]]
    

## Hubs

- [[HUB-T02 - Principles]]
    
- [[HUB-T20 - Research Capability and Alignment]]
    

````

# THK-0130 — Petroleum Engineering Domain-Knowledge Gap

```markdown
---
id: THK-0130
title: Petroleum Engineering Domain-Knowledge Gap
type: knowledge-gap
domain: Petroleum Engineering
topic: Researcher Development
status: active
source_context: PhD Alignment with My Background
---

# THK-0130 - Petroleum Engineering Domain-Knowledge Gap

## Definition

The petroleum-engineering domain-knowledge gap is the difference between
the researcher's existing computational and engineering-systems
capabilities and the specialist domain knowledge required to investigate
HPHT nanoparticle-stabilised energised fracturing foams appropriately.

## Existing Strengths

The researcher's existing strengths lie primarily in:

- artificial intelligence;
- predictive modelling;
- uncertainty quantification;
- engineering systems.

## Knowledge Requiring Development

The proposed research requires deeper knowledge of:

- petroleum engineering;
- [[THK-0001 - Energised Fracturing Foam]];
- [[THK-0005 - Foam Apparent Viscosity]];
- [[THK-0006 - Foam Stability]];
- [[THK-0008 - HPHT Conditions]];
- non-Newtonian foam rheology;
- nanoparticle-stabilised foam systems;
- hydraulic fracturing-fluid design;
- proppant suspension and transport.

## Gap Structure

```text
Existing Capability
AI + Predictive Modelling + UQ
        ↓
        GAP
        ↓
Required Domain Understanding
Petroleum Engineering
+
Foam Physics
+
Fracturing Engineering
````

## Research Response

The gap is addressed through deliberate domain-specific learning during  
the early stages of candidature.

## Why It Matters

Without sufficient domain understanding, computational models may be:

- physically poorly specified;
    
- based on inappropriate variables;
    
- incorrectly interpreted;
    
- disconnected from engineering meaning.
    

## Development Objective

The goal is not simply to learn petroleum-engineering terminology.

It is to develop sufficient physical understanding to determine:

> what should be predicted, why it behaves as it does, which variables  
> matter, and what engineering conclusions can legitimately be drawn.

## Related Notes

- [[THK-0126 - Researcher–Problem Capability Alignment]]
    
- [[THK-0129 - Transferability–Domain Equivalence Distinction]]
    
- [[THK-0131 - Domain-Grounded Computational Modelling]]
    
- [[THK-0132 - Interdisciplinary Capability Development]]
    

## Hub

- [[HUB-T20 - Research Capability and Alignment]]
    

````

# THK-0131 — Domain-Grounded Computational Modelling

```markdown
---
id: THK-0131
title: Domain-Grounded Computational Modelling
type: principle
domain: Research Methodology
topic: Physics-Informed Engineering Analysis
status: developed
source_context: PhD Alignment with My Background
---

# THK-0131 - Domain-Grounded Computational Modelling

## Principle

Computational methods applied to engineering problems should be
informed and constrained by relevant physical principles, experimental
evidence, and engineering judgement.

## Core Idea

Machine learning should not operate as an isolated computational layer.

For this research:

```text
Physical Principles
        +
Experimental Evidence
        +
Petroleum-Engineering Knowledge
        ↓
Computational Modelling
        ↓
Physically Meaningful Prediction
        ↓
Engineering Interpretation
````

## Three Grounding Layers

### 1. Physical Principles

Understanding of:

- foam structure;
    
- rheology;
    
- HPHT effects;
    
- nanoparticle–surfactant interactions;
    
- destabilisation mechanisms.
    

### 2. Experimental Evidence

Models must remain connected to:

- measured observations;
    
- dataset coverage;
    
- experimental conditions;
    
- evidence limitations.
    

### 3. Engineering Judgement

Predictions must be interpreted according to their engineering context  
and limitations.

## What This Prevents

Domain grounding reduces the risk of:

- physically meaningless correlations;
    
- inappropriate feature selection;
    
- unjustified extrapolation;
    
- misleading engineering interpretation;
    
- treating ML output as autonomous engineering truth.
    

## Relationship to Decision Support

This principle supports:

[[THK-0077 - ML as Engineering Decision-Support Tool]]

The ML system informs engineering reasoning rather than replacing it.

## Governing Statement

> **Computational sophistication does not compensate for weak physical  
> understanding.**

## Related Notes

- [[THK-0024 - Machine Learning for Foam Rheology]]
    
- [[THK-0077 - ML as Engineering Decision-Support Tool]]
    
- [[THK-0115 - Evidence-Constrained Modelling Scope]]
    
- [[THK-0127 - AI–HPHT Foam Methodological Transfer]]
    
- [[THK-0129 - Transferability–Domain Equivalence Distinction]]
    
- [[THK-0130 - Petroleum Engineering Domain-Knowledge Gap]]
    

## Hubs

- [[HUB-T02 - Principles]]
    
- [[HUB-T20 - Research Capability and Alignment]]
    

````

# THK-0132 — Interdisciplinary Capability Development

```markdown
---
id: THK-0132
title: Interdisciplinary Capability Development
type: development-process
domain: Research Methodology
topic: Doctoral Development
status: active
source_context: PhD Alignment with My Background
---

# THK-0132 - Interdisciplinary Capability Development

## Definition

Interdisciplinary capability development is the deliberate process of
combining existing computational and engineering-systems expertise with
new petroleum-engineering and foam-rheology knowledge required to solve
the research problem.

## Starting Position

```text
Existing Strengths
        │
        ├── Artificial Intelligence
        ├── Predictive Modelling
        ├── Uncertainty Quantification
        └── Engineering Systems
````

## Required Development

```text
Domain Development
        │
        ├── Petroleum Engineering
        ├── Hydraulic Fracturing
        ├── Energised Foams
        ├── Foam Rheology
        ├── HPHT Behaviour
        └── Fracturing-Fluid Design
```

## Integration

The objective is not to maintain these as separate bodies of knowledge.

They must converge:

```text
AI / ML
        \
         \
UQ -------→ HPHT FOAM RESEARCH
         /
Engineering Systems
         \
          \
      Petroleum Engineering
```

## Development Logic

```text
Learn Physical System
        ↓
Understand Governing Mechanisms
        ↓
Understand Experimental Measurements
        ↓
Connect Variables to Physical Meaning
        ↓
Apply Predictive Methods
        ↓
Quantify Uncertainty
        ↓
Interpret Engineering Significance
```

## Why It Matters

The doctoral contribution depends upon the integration of computational  
and domain knowledge.

AI capability alone is insufficient.

Petroleum-engineering knowledge without the proposed predictive and  
uncertainty methods would address a different research problem.

The interdisciplinary contribution emerges from their integration.

## Desired End State

```text
Computational Expertise
        +
Domain Understanding
        +
Engineering-Systems Thinking
        ↓
Domain-Grounded Predictive Modelling
        ↓
Reliable Engineering Interpretation
```

## Related Notes

- [[THK-0126 - Researcher–Problem Capability Alignment]]
    
- [[THK-0127 - AI–HPHT Foam Methodological Transfer]]
    
- [[THK-0128 - Engineering Systems–HPHT Foam Transferability]]
    
- [[THK-0129 - Transferability–Domain Equivalence Distinction]]
    
- [[THK-0130 - Petroleum Engineering Domain-Knowledge Gap]]
    
- [[THK-0131 - Domain-Grounded Computational Modelling]]
    

## Hub

- [[HUB-T20 - Research Capability and Alignment]]
    

````

The most important insight from this section is the **capability-development pathway**:

```text
WHAT YOU ALREADY BRING
        │
        ├── AI
        ├── Predictive Modelling
        ├── UQ
        └── Engineering Systems
        ↓
TRANSFERABLE CAPABILITY
[[THK-0127]]
[[THK-0128]]
        ↓
BUT
        ↓
Transferability ≠ Domain Equivalence
[[THK-0129]]
        ↓
DOMAIN GAP
[[THK-0130]]
        ↓
Petroleum Engineering
Foam Rheology
Hydraulic Fracturing
        ↓
DELIBERATE DEVELOPMENT
[[THK-0132]]
        ↓
DOMAIN-GROUNDED COMPUTATION
[[THK-0131]]
        ↓
HPHT FOAM RESEARCH CAPABILITY
[[THK-0126]]
````

There is also a useful practical consequence: **`THK-0130` can become the bridge between your PhD knowledge base and your learning programme.** Everything underneath that note represents what you need to master in petroleum engineering rather than merely what needs to appear in the thesis.