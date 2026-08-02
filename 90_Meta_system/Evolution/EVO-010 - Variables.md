## A suggestion for your ontology

One useful addition is to distinguish between **variables** and **parameters**:

```
09_Variables
│
├── Independent Variables
│   ├── Pressure
│   ├── Temperature
│   ├── Salinity
│
├── Dependent Variables
│   ├── Apparent Viscosity
│   ├── Foam Stability
│   ├── Fracture Conductivity
│
└── Parameters
    ├── Learning Rate
    ├── Tree Depth
    ├── Number of Trees
```

This reflects common scientific and machine learning practice: variables are quantities that change or are observed in experiments, while parameters are values that configure a model or algorithm. It will make your knowledge graph more precise as it grows.