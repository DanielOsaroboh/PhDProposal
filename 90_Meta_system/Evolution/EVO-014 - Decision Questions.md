Exactly. A **decision question** is a question whose purpose is **to choose among alternatives**. It doesn't ask for a definition or explanation—it asks **"What should I do?"** or **"Which option is best?"**

For example, in your ontology:

|Question Type|Example|Primary Notes Used|
|---|---|---|
|Definition|What is Machine Learning?|Concept|
|Relationship|How is Pressure related to Foam Rheology?|Concept + Variable|
|Process|How is Model Validation performed?|Process|
|Mechanism|Why does pressure increase viscosity?|Mechanism|
|**Decision**|**Which model should I use?**|Models + Metrics + Parameters|

## Structure of a Decision Question Note

```markdown
---
id: QST-0001
title: Which Machine Learning Model Should I Use?
type: Decision Question
---

# Decision

The choice depends on the characteristics of the problem, dataset, and objectives.

# Decision Criteria

| Criterion | Random Forest | XGBoost | Gaussian Process Regression |
|-----------|---------------|----------|-----------------------------|
| Small dataset | ✓ | ✓ | ✓✓✓ |
| Large dataset | ✓✓ | ✓✓✓ | ✗ |
| Highest accuracy | ✓✓ | ✓✓✓ | ✓ |
| Uncertainty estimation | ✗ | Limited | ✓✓✓ |
| Easy interpretation | ✓✓ | ✓ | ✓ |

# Recommendation

Choose:

- **Random Forest** for robust general-purpose prediction.
- **XGBoost** for maximum predictive accuracy on large datasets.
- **Gaussian Process Regression** when uncertainty estimation is essential.

# Supporting Notes

- [[Random Forest]]
- [[XGBoost]]
- [[Gaussian Process Regression]]
- [[RMSE]]
- [[Cross Validation]]
- [[Bayesian Optimisation]]
```

---

## General Pattern for Decision Questions

Every decision note can follow the same structure:

1. **Decision Problem**
    
    - What decision needs to be made?
        
2. **Available Options**
    
    - What are the alternatives?
        
3. **Decision Criteria**
    
    - How will the options be evaluated?
        
4. **Comparison**
    
    - Compare the options against the criteria.
        
5. **Recommendation**
    
    - Which option is preferable under which conditions?
        
6. **Supporting Evidence**
    
    - Links to ontology notes.
        

---

## Examples in Different Domains

**Petroleum Engineering**

- Which foam formulation should I use?
    
- Which proppant is most suitable?
    
- Which operating window is optimal?
    

**Machine Learning**

- Which model should I choose?
    
- Which hyperparameters should I tune?
    
- Which evaluation metric should I use?
    

**Research**

- Which research method should I adopt?
    
- Which theoretical framework best fits my study?
    
- Which sampling technique is appropriate?
    

---

### Decision Questions vs Decision Notes

I would make one distinction in your system:

- **Decision Question**: The question itself (e.g., _"Which model should I choose?"_).
    
- **Decision Note**: The curated answer to that question, synthesizing information from multiple ontology notes.
    

Your ontology provides the building blocks, while a **Decision Note** integrates them to support an actual choice. This makes decision notes one of the most valuable types of notes because they transform isolated knowledge into actionable guidance.