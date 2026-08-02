---
id: HUB-THK
title: "THK Knowledge Object Types"
type: "meta-hub"
domain: "Knowledge System"
status: "active"
---

# HUB-THK - Knowledge Object Types

## Purpose

This meta-HUB defines how atomic THK notes are classified and structured.

> **Classify the knowledge claim by the question it answers, not merely by the noun in its title.**

Different kinds of knowledge require different note architectures. A concept should not be forced into a mechanism template, and a gap should not be written like a model.

## Type Directory

| THK Type | Core Question | Typical Architecture |
|---|---|---|
| Concept | What is it? | Definition; Core Idea; Why It Matters; Structure/Characteristics; Governing Conditions; Application; Boundaries |
| Property | What characteristic is measured or observed? | Definition; What It Represents; Governing Variables; Measurement/Interpretation; Engineering Significance; Boundaries |
| Mechanism | How and why does it happen? | Phenomenon; Starting Condition; Causal Chain; Governing Variables; Outcome; Boundaries |
| Relationship | How are variables connected? | Variables; Direction/Pattern; Mechanism; Moderators; Boundaries; Significance |
| Threshold | At what point does behaviour change? | Threshold; Below/Near/Above behaviour; Transition mechanism; Conditions; Significance |
| Model | How is the phenomenon represented? | Purpose; Equation/Architecture; Variables; Assumptions; Strengths; Limitations; Validity domain |
| Method | How is something done analytically? | Purpose; Inputs; Procedure; Outputs; Strengths; Limitations |
| Model Application | How is a model used for this problem? | Target problem; Inputs; Outputs; Training/validation; Suitability; Limitations |
| Problem | What prevents the desired outcome? | Definition; Context; Causes; Consequences; Persistence; Research implication |
| Limitation | Where does an approach stop working well? | What is limited; Cause; Boundary; Consequence; Mitigation |
| Gap | What important knowledge/capability is missing? | What is known; What is missing; Evidence; Consequence; Research need |
| Failure Mechanism | How does performance deteriorate? | Desired state; Trigger; Failure chain; Consequence; Mitigation; Boundaries |
| Strategy | What deliberate approach addresses a problem? | Objective; Problem; Strategic logic; Benefits; Conditions; Trade-offs |
| Engineering Function | What job must the system perform? | Function; Objective; Upstream properties; Indicators; Failure conditions |
| Engineering Relationship | How does a property affect engineering outcome? | Upstream property; Outcome; Mechanism; Conditions; Design implication |
| Decision Process | How is evidence converted into a decision? | Objective; Inputs; Criteria; Process; Uncertainty; Output; Validation |
| Approach | What general way addresses the problem? | Problem; Central idea; Principles; Inputs; Outputs; Advantages; Limitations |
| Principle | What rule guides interpretation/action? | Statement; Meaning; Rationale; Application; Boundaries; Implications |
| Framework | How are multiple objects integrated? | Purpose; Components; Architecture; Inputs; Outputs; Assumptions; Validation; Contribution |
| System | How do interacting components produce behaviour? | System boundary; Inputs; components/states; interactions; outputs; feedback; boundaries |

## Atomicity Rule

One THK note should represent one primary knowledge object. Split a note when it begins answering a materially different question.

Example:

- [[THK-0015 - Foam Quality]] asks **what is it?**
- [[THK-0016 - Foam Quality–Viscosity Relationship]] asks **how are two variables connected?**
- [[THK-0017 - Critical Foam Quality]] asks **where does the behaviour change?**

These belong to the same subject area but are different knowledge objects.

## Selection Logic

```text
What is it?                         → Concept
What characteristic is observed?  → Property
How/why does it happen?            → Mechanism
How are variables connected?       → Relationship
Where does behaviour change?       → Threshold
How is it represented?             → Model
How is it done?                    → Method
What is wrong?                     → Problem
Where does an approach fail?       → Limitation
What is missing?                   → Gap
How does failure occur?            → Failure Mechanism
What deliberate response is used? → Strategy
What job must the system perform?  → Engineering Function
How does a property affect output? → Engineering Relationship
How is a decision made?            → Decision Process
What general way addresses it?     → Approach
What rule guides interpretation?   → Principle
How are objects integrated?        → Framework
How do components interact?        → System
```

## Knowledge Development Chain

```text
Concept / Property
        ↓
Relationship
        ↓
Mechanism
        ↓
Threshold
        ↓
Model / Method
        ↓
Prediction
        ↓
Limitation / Problem
        ↓
Gap
        ↓
Approach / Strategy
        ↓
Framework
        ↓
Decision Process
        ↓
Engineering Application
```

## Subject Hubs

- [[HUB-01 - Fracturing Context]]
- [[HUB-02 - Foam Rheology]]
- [[HUB-03 - Rheological Modelling]]
- [[HUB-04 - Nanoparticle Stabilisation]]
- [[HUB-05 - Engineering Performance]]
- [[HUB-06 - Prediction & Uncertainty]]