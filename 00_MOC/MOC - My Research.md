
### What is it?

Prediction of the [[THK-0005 - Foam Apparent Viscosity|rheology]] and [[THK-0006 - Foam Stability|stability]] of [[THK-0001 - Energised Fracturing Foam|nanoparticle-stabilised energised foams]] under [[THK-0008 - HPHT Conditions|HPHT conditions]].

In other words:

> **HPHT conditions + foam formulation → rheology and stability prediction**

---

### Why does it matter?

Because unreliable [[THK-0007 - HPHT Foam Performance|foam performance]] can affect [[THK-0060 - Prediction Reliability–Fluid Design Link|fracturing-fluid design]] and downstream [[THK-0042 - Foam-Assisted Proppant Suspension|proppant suspension]] and [[THK-0041 - Proppant Transport|proppant transport]].

The engineering chain is:

[[THK-0005 - Foam Apparent Viscosity|Apparent Viscosity]]  
+  
[[THK-0006 - Foam Stability|Foam Stability]]  
↓  
[[THK-0042 - Foam-Assisted Proppant Suspension|Proppant Suspension]]  
↓  
[[THK-0041 - Proppant Transport|Proppant Transport]]  
↓  
Fracturing Performance

---

### How does it work?

[[THK-0008 - HPHT Conditions|HPHT conditions]] and [[THK-0057 - Multivariable Control of Foam Performance|formulation and operating variables]] interact nonlinearly to control [[THK-0005 - Foam Apparent Viscosity|foam viscosity]] and [[THK-0006 - Foam Stability|foam stability]].

[[THK-0024 - Machine Learning for Foam Rheology|Machine learning]] is then used to learn these complex relationships from experimental evidence.

The fundamental relationship is:

[[THK-0057 - Multivariable Control of Foam Performance|Operating + Formulation Variables]]  
↓  
[[THK-0012 - Coupled HPHT Effects|Coupled Nonlinear Interactions]]  
↓  
[[THK-0005 - Foam Apparent Viscosity|Apparent Viscosity]]  
+  
[[THK-0006 - Foam Stability|Foam Stability]]  
↓  
[[THK-0024 - Machine Learning for Foam Rheology|Machine-Learning Prediction]]

---

### What controls it?

Foam performance is controlled primarily by:

- [[THK-0009 - Pressure Effect on Foam Rheology|Pressure]]
- [[THK-0010 - Temperature Effect on Foam Stability|Temperature]]
- [[THK-0011 - Shear Effect on Foam Behaviour|Shear conditions]]
- [[THK-0015 - Foam Quality|Foam quality]]
- salinity
- surfactant chemistry and concentration
- nanoparticle concentration
- gas-phase characteristics
- [[THK-0032 - Nanoparticle–Surfactant Interaction|Nanoparticle–surfactant interactions]]

These variables should not be understood only independently. Their combined behaviour is represented by [[THK-0057 - Multivariable Control of Foam Performance|Multivariable Control of Foam Performance]] and [[THK-0012 - Coupled HPHT Effects|Coupled HPHT Effects]].

---

### How do we measure/model it?

Available experimental foam data are first [[THK-0072 - HPHT Foam Dataset Compilation and Structuring|compiled and structured]], [[THK-0111 - Literature Data Digitisation|digitised]], and [[THK-0085 - Heterogeneous Foam Dataset Harmonisation|harmonised]].

The resulting [[THK-0116 - Structured HPHT Foam Data Resource|structured HPHT dataset]] provides the evidence for [[THK-0024 - Machine Learning for Foam Rheology|machine-learning modelling]].

The models predict:

- [[THK-0005 - Foam Apparent Viscosity|Apparent viscosity]]
- [[THK-0006 - Foam Stability|Foam stability]], operationalised primarily through [[THK-0124 - Foam Half-Life as Stability Operationalisation|foam half-life]]

The models are then subjected to [[THK-0092 - Grouped Validation for Foam Prediction|grouped validation]] to examine [[THK-0068 - Data-Domain-Dependent Predictive Performance|generalisation]].

[[THK-0096 - Interpolation–Extrapolation Validation Distinction|Interpolation and extrapolation]] are distinguished, while [[THK-0028 - Predictive Uncertainty|predictive uncertainty]] is quantified to assess [[THK-0074 - Uncertainty-Based Model Reliability Assessment|model reliability]].

So the methodological chain becomes:

[[THK-0072 - HPHT Foam Dataset Compilation and Structuring|Data Compilation]]  
→ [[THK-0085 - Heterogeneous Foam Dataset Harmonisation|Data Harmonisation]]  
→ [[THK-0024 - Machine Learning for Foam Rheology|ML Modelling]]  
→ [[THK-0092 - Grouped Validation for Foam Prediction|Validation]]  
→ [[THK-0028 - Predictive Uncertainty|Uncertainty Quantification]]  
→ [[THK-0074 - Uncertainty-Based Model Reliability Assessment|Reliability Assessment]]

---

### How does it connect to the research problem?

The research problem is **not simply obtaining predictions** of [[THK-0005 - Foam Apparent Viscosity|apparent viscosity]] and [[THK-0006 - Foam Stability|foam stability]].

The deeper problem is determining **how much confidence can be placed in those predictions**, particularly under [[THK-0029 - Sparse-Data Uncertainty|sparse]], [[THK-0051 - Model Reliability under Unfamiliar Conditions|unfamiliar]], or [[THK-0030 - Extrapolation Uncertainty|extrapolated HPHT conditions]].

This requires moving from:

**Prediction**

to:

[[THK-0052 - Uncertainty-Aware Foam Prediction|Uncertainty-Aware Prediction]]  
↓  
[[THK-0074 - Uncertainty-Based Model Reliability Assessment|Model Reliability]]  
↓  
[[THK-0103 - Uncertainty-Bounded Operating Window|Uncertainty-Bounded Operating Window]]  
↓  
[[THK-0120 - Engineering Decision-Support Contribution|Engineering Decision Support]]

The central research logic is therefore:

> Predict [[THK-0005 - Foam Apparent Viscosity|foam rheology]] and [[THK-0006 - Foam Stability|stability]], quantify [[THK-0028 - Predictive Uncertainty|prediction uncertainty]], assess [[THK-0074 - Uncertainty-Based Model Reliability Assessment|prediction reliability]], and use sufficiently reliable predictions to identify [[THK-0103 - Uncertainty-Bounded Operating Window|uncertainty-bounded candidate operating windows]] for [[THK-0120 - Engineering Decision-Support Contribution|engineering evaluation]].

---

## Deepest Memory Chain

[[THK-0001 - Energised Fracturing Foam|Understand the Foam]]  
→  
[[THK-0057 - Multivariable Control of Foam Performance|Understand What Controls It]]  
→  
[[THK-0024 - Machine Learning for Foam Rheology|Predict Its Behaviour]]  
→  
[[THK-0028 - Predictive Uncertainty|Quantify What We Do Not Know]]  
→  
[[THK-0074 - Uncertainty-Based Model Reliability Assessment|Determine Whether the Prediction Can Be Trusted]]  
→  
[[THK-0103 - Uncertainty-Bounded Operating Window|Identify Candidate Operating Conditions]]  
→  
[[THK-0120 - Engineering Decision-Support Contribution|Support Engineering Decisions]]

Or compressed into **seven words/concepts**:

> **Foam → Controls → Prediction → Uncertainty → Reliability → Operating Window → Decision**

This would make a strong **master synthesis/MOC note** because virtually every major branch of the PhD can be reached from this one page.