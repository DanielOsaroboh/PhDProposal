---
id: THK-0083
title: Engineering Stage-Gate Methodology
type: process
domain: Petroleum Engineering
topic: Research Methodology
status: developed
source_context: PhD Proposed Methodology
---

# THK-0083 - Engineering Stage-Gate Methodology

## Definition

An engineering stage-gate methodology is a research-control process in
which progression between methodological stages depends on satisfaction
of predefined technical or engineering criteria.

## Core Pattern

Stage
        ↓
Output
        ↓
Decision Gate
       ↙ ↘
     NO   YES
     ↓     ↓
Improve  Proceed
     ↓
Repeat Stage

## Application to the Research

### Gate 1 — Data Quality

Does the harmonised dataset satisfy predefined quality criteria?

### Gate 2 — Predictive Performance

Does the predictive model satisfy performance and validation criteria?

### Gate 3 — Uncertainty Reliability

Do the uncertainty estimates satisfy predefined confidence
requirements?

### Gate 4 — Operating-Window Feasibility

Do candidate operating windows satisfy engineering requirements?

### Gate 5 — Engineering Validity

Does the framework demonstrate sufficient engineering validity for
decision support?

## Why Gates Matter

The methodology prevents automatic progression merely because a
computational stage has been completed.

Completion
        ≠
Acceptance

Instead:

Completion
+
Criteria Satisfaction
=
Progression

## Feedback Mechanism

Failed gates trigger:

- additional data acquisition;
- preprocessing revision;
- feature-engineering revision;
- model optimisation;
- uncertainty recalibration;
- operating-window reassessment;
- engineering reassessment.

## Engineering Significance

Stage gates embed quality control and engineering judgement throughout
the predictive workflow.

## Related Notes

- [[THK-0077 - ML as Engineering Decision-Support Tool]]
- [[THK-0080 - Sequential HPHT Foam Research Workflow]]
- [[THK-0082 - Five-Module HPHT Foam Engineering Methodology]]

## Hubs

- [[HUB-T08 - Processes]]