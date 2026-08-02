---
id: THK-0063
title: Carreau Model
type: model
domain: Petroleum Engineering
topic: Foam Rheology
status: developed
source_context: PhD Knowledge Gap
---

# THK-0063 - Carreau Model

## Definition

The Carreau model is a constitutive rheological model used to represent
shear-thinning behaviour in non-Newtonian fluids by describing the
transition between low-shear and high-shear viscosity regimes.

## Core Idea

Unlike a simple Power-law representation, the Carreau model allows
viscosity to approach limiting values at very low and very high shear
rates.

The model therefore represents a transition across different
shear-rate regimes.

## Model Structure

A common form is:

η(γ̇) = η∞ + (η₀ − η∞)[1 + (λγ̇)²]^((n−1)/2)

where:

- η is apparent viscosity;
- η₀ is zero-shear viscosity;
- η∞ is infinite-shear viscosity;
- λ is a characteristic time parameter;
- γ̇ is shear rate;
- n is the flow-behaviour parameter.

## Behavioural Structure

```text
Low Shear Rate
      ↓
Viscosity approaches η₀
      ↓
Transition Region
      ↓
Shear-Thinning Behaviour
      ↓
High Shear Rate
      ↓
Viscosity approaches η∞