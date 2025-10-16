# Interpretable AI Models

This project explores **model interpretability** and **privacy-preserving learning** in neural networks.  
It implements **Differentially Private Logistic Regression** and a **Concept-Interpretable CNN**, integrating key techniques like **Shapley value analysis** and **Testing with Concept Activation Vectors (TCAV)**.

---

## Overview

Machine learning models often operate as black boxes, making it difficult to understand how they make decisions or how private the training data remains.  
This project aims to:
- Ensure **data privacy** using noise-injected optimization.
- Improve **model interpretability** using feature- and concept-level attribution methods.

---

## Features

### Differentially Private Logistic Regression
- Introduces **gamma-distributed noise** to gradient updates for differential privacy.
- Preserves model utility while preventing sensitive data leakage.
- Trained and evaluated on tabular datasets for binary classification tasks.

### CNN Interpretability
- Trains a **3-layer CNN** for image classification.  
- Applies:
  - **Shapley Value Analysis (SHAP):** Quantifies each feature’s contribution to model output.  
  - **Testing with Concept Activation Vectors (TCAV):** Identifies which learned concepts influence specific model decisions.  
- Helps visualize what the CNN “pays attention to” during inference.

---


- **Language:** Python  
- **Libraries:** PyTorch, NumPy, Matplotlib, SHAP, TensorFlow (for TCAV)  
- **Tools:** Jupyter Notebook, Git  

---

##  Results

| Module | Technique | Key Outcome |
|:--------|:-----------|:------------|
| Logistic Regression | Differential Privacy (Gamma noise) | Privacy preserved with minimal accuracy loss |
| CNN Interpretability | SHAP, TCAV | Clear concept and feature attribution visualizations |

Visual examples:
- SHAP summary plots show feature importance for classification.
- TCAV results highlight concept sensitivity across CNN layers.

---

- Demonstrated the trade-off between **privacy and model accuracy**.  
- Understood how **concept activation vectors** can make neural networks more explainable.  
- Gained hands-on experience with **interpretable ML pipelines** and **privacy-aware model training**.

---


```bash
# Clone the repository
git clone https://github.com/Seetrax/ResponsibleAI.git
cd ResponsibleAI

# Install dependencies
pip install -
