# Decision Intelligence: From Mathematical Optimization to Causal Reason

Welcome to the official repository for the Faculty Development Program (FDP) masterclass on deploying Causal AI and Structural Interventions in Enterprise Operations. 

This program dismantles traditional predictive machine learning paradigms and introduces Judea Pearl's Structural Causal Models from first principles, grounding complex classical mathematics into real-world supply chain scenarios.

## 🚀 Interactive Masterclass Notebook

Click the badge below to instantly launch the complete, command-by-command interactive workshop environment in Google Colab. No local configuration or library installation required:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MLDreamer/Decision-Intelligence-FDP-2026/blob/main/Decision_Intelligence_Masterclass.ipynb)

---

## 📚 Masterclass Architecture & Key Takeaways

### 🛑 Module 1: The Observational Illusion
* **Focus:** Deconstructing why highly precise predictive models ($R^2 = 0.94$) fail when utilized to dictate corporate strategy.
* **Core Simulation:** Building a confounded ERP dataset for **Surf Excel** where environmental noise (Monsoon Intensity) corrupts historical promotion vectors.
* **Takeaway:** Traditional machine learning acts as a passive observer ($P(Y|X)$), blending operational signals with environmental noise indistinguishably.

### 📐 Module 2: The Structural Paradigm Shift
* **Focus:** Moving from data-centric correlation to mechanism-centric blueprints using Directed Acyclic Graphs (DAGs).
* **Core Simulation:** Modeling the operational topology in Python and implementing automated backdoor path identification (`d-separation`).
* **Takeaway:** DAGs provide a mathematically rigorous language to explicitly declare operational dependencies before writing downstream optimization code.

### 🔬 Module 3: Structural Estimation Toolkits
* **Focus:** Harnessing the power of machine learning as an unconfounded structural scalpel.
* **Core Simulation:** Implementing **Double Machine Learning (DML)** via Microsoft's EconML to strip out environmental noise, paired with a statistical *Placebo Treatment Refuter* to stress-test invariance.
* **Takeaway:** Causal engines can recover true physical operational elasticity parameters from entirely passive historical data.

### 🎛️ Module 4: Enterprise Production Systems
* **Focus:** Translating structural parameters into a live, interactive prescriptive simulation layer for executive decision-making.
* **Core Simulation:** Building an optimization loop that decouples pricing levers from exogenous environment fluctuations.
* **Takeaway:** Shifting from forecasting what *will* happen to securely isolating how to *make* it happen under novel policy updates.

---

## 🛠️ Stack Architecture & Prerequisites
The hosted notebook handles environment initialization automatically upon execution. If you choose to deploy locally, ensure your target workspace has the following dependencies initialized:

```bash
pip install dowhy econml xgboost scikit-learn pandas numpy matplotlib seaborn



