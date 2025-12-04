# SFG-DE: An explainable and evolvable differential evolution for learning to generate operator structures

This repository provides the official MATLAB implementation of Structural Fuzzy Generative Differential Evolution (SFG-DE), a novel variant of Differential Evolution (DE) that learns generating operator structures to enhance adaptive performance.


> 📌 This code is part of our research on enhancing the convergence behavior of Differential Evolution (DE) using a structural fuzzy generative strategy, an estimation of univariate Gaussian distribution strategy, and a Metropolis criterion and individual regeneration selection strategy. We developed SFG-DE based on a fundamentally different design philosophy, in contrast to the JADE/SHADE/L-SHADE family, which represents the mainstream DE research.
---

## 📐 Theoretical Highlights

The proposed **SFG-DE** introduces a novel operator-generating mechanism that enhances adaptability while preserving theoretical soundness. SFG-DE automatically generates mutation structures through a fuzzy generative mechanism.

A key theoretical advantage of SFG-DE is its **compatibility with classical DE mutation strategies**. Specifically:

- A key theoretical advantage of SFG-DE is its **broad generative operator space**, which not only **includes classical DE strategies such as DE/rand/1 and DE/current-to-pbest/1 as special cases**, but also **encompasses many novel and classical mutation strategies**. This expansive operator space allows for enhanced exploration and exploitation capabilities.
- Therefore, **the convergence properties associated with these classical schemes can be inherited**, under similar theoretical conditions.
- This design allows SFG-DE to **benefit from both structural flexibility and theoretical interpretability**, bridging the gap between adaptive operator learning and established DE theory.

These properties position SFG-DE not only as an adaptive optimizer but also as a framework that supports theoretical analysis and stability in performance.


## 🛠️ How to Run

### Requirements

- MATLAB R2018a or later

### Instructions

To run the algorithm, simply open MATLAB, navigate to the project directory, and execute:

```matlab
main
```

## 📄 Paper Access

Our paper **"SFG-DE: An explainable and evolvable differential evolution for learning to generate operator structures"** has been published in *Swarm and Evolutionary Computation*.

🔗 **Free 50-day Access (Elsevier Share Link)**  
[https://authors.elsevier.com/c/1mDAa7sfCTOauN](https://authors.elsevier.com/c/1mDAa7sfCTOauN)

Anyone can read or download the final version via this link before **Jan 23, 2026**.


## ⚠️ Notice:

This paper has been accepted for publication in the Elsevier journal *Swarm and Evolutionary Computation*.   
The source code provided in this repository is intended solely for academic reference and may not be used for any other purposes without the authors' explicit prior written permission.
