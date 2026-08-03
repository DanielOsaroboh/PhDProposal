This section has already generated several of your important boundary notes, so I would **not duplicate them**. I would process it into **4 core notes plus enrichments**.

### Knowledge-object extraction

|Action|THK|Knowledge Object|Type|
|---|---|---|---|
|Existing|`THK-0122`|HPHT Foam Research Scope Boundary|Scope|
|Existing|`THK-0123`|Primary Predictive Target–Downstream Application Distinction|Principle|
|Existing|`THK-0124`|Foam Half-Life as Stability Operationalisation|Operationalisation|
|Existing|`THK-0125`|Hydraulic-Fracturing Simulation Exclusion Boundary|Scope Limitation|
|Enrich|`THK-0103`|Uncertainty-Bounded Operating Window|Decision Object|
|Enrich|`THK-0108`|Laboratory-to-Field Validation Boundary|Boundary|
|Enrich|`THK-0109`|HPHT Foam Data Availability Constraint|Limitation|
|Enrich|`THK-0115`|Evidence-Constrained Modelling Scope|Principle|

Here is the **linked synthesis note** I would put above those atomic notes.

# Scope and Limitations — Knowledge Synthesis

## Core Scope

The research is bounded to the evaluation and prediction of [[THK-0001 - Energised Fracturing Foam|nanoparticle-stabilised energised fracturing foams]] under [[THK-0008 - HPHT Conditions|HPHT conditions]].

The overall research boundary is captured in:

[[THK-0122 - HPHT Foam Research Scope Boundary]]

---

## Primary Predictive Targets

A fundamental distinction is maintained between properties that are **predicted directly** and engineering applications that are **informed by those predictions**.

The [[THK-0024 - Machine Learning for Foam Rheology|machine-learning framework]] directly predicts two primary targets:

1. [[THK-0005 - Foam Apparent Viscosity|Apparent viscosity]]
    
2. [[THK-0006 - Foam Stability|Foam stability]]
    

The distinction between direct predictive targets and downstream applications is formalised in:

[[THK-0123 - Primary Predictive Target–Downstream Application Distinction]]

The predictive architecture is therefore:

```text
HPHT + Formulation Variables
        ↓
Machine-Learning Framework
        ↓
PRIMARY PREDICTIVE TARGETS
        │
        ├── Apparent Viscosity
        └── Foam Stability
```

---

## Foam Stability Operationalisation

[[THK-0006 - Foam Stability|Foam stability]] is operationalised primarily through [[THK-0124 - Foam Half-Life as Stability Operationalisation|foam half-life]].

This creates the measurement chain:

```text
Foam Stability
        ↓
Physical Construct
        ↓
Foam Half-Life
        ↓
Measurable Response
        ↓
Machine-Learning Target
```

The word **primarily** is important because foam half-life represents the principal stability indicator within this research rather than necessarily representing every possible dimension of foam stability.

---

## Downstream Engineering Applications

[[THK-0041 - Proppant Transport|Proppant transport assessment]] and [[THK-0103 - Uncertainty-Bounded Operating Window|operating-window identification]] are not treated as equivalent primary ML prediction targets.

Instead, they are **downstream engineering applications** informed by predicted rheology and stability.

The research logic is:

```text
[[THK-0005 - Foam Apparent Viscosity|Apparent Viscosity]]
                +
[[THK-0006 - Foam Stability|Foam Stability]]
                ↓
[[THK-0028 - Predictive Uncertainty|Predictive Uncertainty]]
                ↓
[[THK-0074 - Uncertainty-Based Model Reliability Assessment|Reliability Assessment]]
                ↓
        ENGINEERING APPLICATION
          ↙                 ↘
[[THK-0103 - Uncertainty-Bounded Operating Window|Operating Windows]]
                            [[THK-0041 - Proppant Transport|Proppant Assessment]]
```

This distinction controls the strength of the research claims.

The framework **predicts foam properties directly** but uses those predictions to **inform downstream engineering assessment**.

---

## Proppant Transport Boundary

The research evaluates the engineering implications of [[THK-0005 - Foam Apparent Viscosity|foam rheology]] and [[THK-0006 - Foam Stability|stability]] for [[THK-0042 - Foam-Assisted Proppant Suspension|proppant suspension]] and [[THK-0041 - Proppant Transport|proppant transport]].

The causal logic is:

```text
Foam Rheology
        +
Foam Stability
        ↓
Proppant Suspension
        ↓
Proppant Transport Assessment
```

Proppant transport therefore represents an **engineering consequence/application of the primary predictions**, rather than the central response predicted by the ML framework.

---

## Hydraulic-Fracturing Simulation Exclusion

The research explicitly excludes development of a fully coupled three-dimensional hydraulic-fracturing simulator.

This boundary is represented by:

[[THK-0125 - Hydraulic-Fracturing Simulation Exclusion Boundary]]

Therefore:

```text
IN SCOPE

HPHT Foam Behaviour
        ↓
Rheology + Stability Prediction
        ↓
Uncertainty Quantification
        ↓
Reliability Assessment
        ↓
Candidate Operating Windows
        ↓
Engineering Assessment


OUTSIDE DIRECT SCOPE

Fully Coupled 3D
Hydraulic-Fracturing Simulation
```

The proposed framework is therefore not intended to reproduce the entire fracture-generation, propagation and treatment process.

---

## Candidate Operating Windows

Rather than developing a complete fracture simulator, the research identifies:

[[THK-0103 - Uncertainty-Bounded Operating Window|uncertainty-bounded candidate operating windows]]

These represent candidate combinations of formulation and operating conditions associated with acceptable predicted foam behaviour and acceptable predictive confidence under defined engineering constraints.

The important qualifier is **candidate**.

```text
Candidate Operating Window
        ≠
Field-Validated Operating Envelope
```

The operating windows are intended to support:

- further laboratory evaluation;
    
- engineering assessment;
    
- existing fracture-design workflows.
    

This boundary also connects to:

[[THK-0108 - Laboratory-to-Field Validation Boundary]]

---

## Empirical Modelling Limitation

The predictive framework is constrained by the characteristics of accessible [[THK-0116 - Structured HPHT Foam Data Resource|HPHT foam data]].

Important constraints include:

- availability;
    
- dataset size;
    
- heterogeneity;
    
- variable coverage;
    
- formulation specificity.
    

These limitations are captured more broadly by:

[[THK-0109 - HPHT Foam Data Availability Constraint]]

The relationship is:

```text
Available HPHT Evidence
        ↓
Dataset Size + Quality
        ↓
Variable + Formulation Coverage
        ↓
Supported Modelling Complexity
        ↓
Predictive Reliability
        ↓
Permissible Engineering Interpretation
```

Consequently, the modelling scope must remain consistent with:

[[THK-0115 - Evidence-Constrained Modelling Scope]]

---

# Scope Architecture

The complete scope can therefore be remembered as:

```text
                RESEARCH DOMAIN
                      ↓
[[THK-0001 - Energised Fracturing Foam|Nanoparticle-Stabilised Energised Foam]]
                      +
[[THK-0008 - HPHT Conditions|HPHT Conditions]]
                      ↓
              DIRECT PREDICTION
                ↙           ↘
[[THK-0005 - Foam Apparent Viscosity|Viscosity]]
                         [[THK-0006 - Foam Stability|Stability]]
                                  ↓
                         [[THK-0124 - Foam Half-Life as Stability Operationalisation|Half-Life]]
                      ↓
              UNCERTAINTY
                      ↓
              RELIABILITY
                      ↓
        DOWNSTREAM APPLICATIONS
              ↙               ↘
[[THK-0103 - Uncertainty-Bounded Operating Window|Candidate Operating Windows]]
                       [[THK-0041 - Proppant Transport|Proppant Assessment]]
              ↓
        ENGINEERING SUPPORT
              ↓
Laboratory Evaluation
Engineering Assessment
Existing Fracture-Design Workflows
```

## Explicit Boundaries

The research therefore establishes four major boundaries:

**Predictive boundary:**  
[[THK-0005 - Foam Apparent Viscosity|Apparent viscosity]] and [[THK-0006 - Foam Stability|foam stability]] are the primary predictive targets.

**Application boundary:**  
[[THK-0041 - Proppant Transport|Proppant transport]] and [[THK-0103 - Uncertainty-Bounded Operating Window|operating windows]] are downstream applications.

**Simulation boundary:**  
[[THK-0125 - Hydraulic-Fracturing Simulation Exclusion Boundary|Fully coupled 3D hydraulic-fracturing simulation]] is outside the direct scope.

**Evidence boundary:**  
The strength and breadth of modelling are constrained by [[THK-0109 - HPHT Foam Data Availability Constraint|available HPHT foam evidence]].

---

# One-Sentence Mastery Statement

> This research predicts [[THK-0005 - Foam Apparent Viscosity|apparent viscosity]] and [[THK-0006 - Foam Stability|foam stability]] of [[THK-0001 - Energised Fracturing Foam|nanoparticle-stabilised energised foams]] under [[THK-0008 - HPHT Conditions|HPHT conditions]], quantifies [[THK-0028 - Predictive Uncertainty|predictive uncertainty]], and uses reliability-aware predictions to identify [[THK-0103 - Uncertainty-Bounded Operating Window|candidate operating windows]] and inform [[THK-0041 - Proppant Transport|proppant-transport assessment]], without claiming to replace experimental validation, engineering judgement, or full hydraulic-fracturing simulation.

The deepest structure to remember is simply:

**Predict directly:** `Viscosity + Stability` → **Quantify:** `Uncertainty + Reliability` → **Apply downstream:** `Operating Window + Proppant Assessment` → **Do not claim:** `Full fracture simulation or field-ready design`.