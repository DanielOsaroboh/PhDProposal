I actually think that's a better place for them.

From our previous discussions, your knowledge system already separates **knowledge** from **application**. Decision notes are **application**—they use knowledge to make a recommendation.

Your structure could look like this:

```text
04_Decision Systems
│
├── Decision Frameworks
├── Decision Criteria
├── Decision Trees
├── Decision Notes      ← Recommended
├── Decision Templates
└── Decision Logs
```

Then a decision note might be:

```text
Decision Notes
│
├── Which Machine Learning Model Should I Use.md
├── Which Evaluation Metric Should I Use.md
├── Which Operating Window Is Optimal.md
├── Should I Use Random Forest or XGBoost.md
├── Which Research Method Fits My Study.md
└── Which Statistical Test Should I Use.md
```

Notice that these are **not knowledge notes**. They are **decision-support documents**.

For example:

```
Decision Note
│
├── Decision
├── Context
├── Options
├── Decision Criteria
├── Comparison
├── Recommendation
├── Risks
├── Supporting Knowledge
└── References
```

where **Supporting Knowledge** simply links to your ontology:

```
Supporting Knowledge

[[Random Forest]]
[[XGBoost]]
[[RMSE]]
[[Cross Validation]]
[[Machine Learning]]
```

---

### Think of your system as three layers

```text
Layer 1 — Knowledge
01_Concepts
02_Entities
03_Mechanisms
...
11_Functions
12_Parameters

        ↓

Layer 2 — Decision Systems
Decision Notes
Decision Frameworks
Decision Trees
Decision Criteria

        ↓

Layer 3 — Output
Research Papers
Reports
Essays
Projects
Presentations
```

The flow becomes:

- **Knowledge Layer** → stores facts and concepts.
    
- **Decision Layer** → synthesizes knowledge to answer "What should I do?"
    
- **Output Layer** → communicates the decision in a thesis, report, presentation, or article.
    

---

### This aligns well with your overall vision

From our earlier conversations, your system isn't just a note-taking vault; it's intended to become a **Decision Clarity System**. In that context:

- **Ontology** answers **"What do I know?"**
    
- **Decision Notes** answer **"Given what I know, what should I do?"**
    
- **Projects and Outputs** answer **"How do I apply or communicate that decision?"**
    

That separation keeps your evergreen knowledge stable while allowing your decisions to evolve as new evidence or requirements emerge.