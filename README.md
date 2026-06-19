# Explainable Intrusion Detection System Using Guided SHAP and Hybrid CNN–ViT Architecture

## Overview

This repository contains the implementation and experimental artifacts accompanying the paper:

**"Guided and Correlation-Aware SHAP for Explainable Intrusion Detection Systems"**

The project proposes a hybrid Intrusion Detection System (IDS) that combines Convolutional Neural Networks (CNNs), Vision Transformers (ViTs), and Explainable Artificial Intelligence (XAI) techniques. The primary contribution is **Guided SHAP**, a novel SHAP-based explanation framework that integrates:

* Information Gain-guided coalition sampling
* Correlation-aware feature filtering
* Batched SHAP value computation

The framework is evaluated using multiple explainability metrics, including fidelity, sparsity, robustness, stability, completeness, and computational efficiency.

---

## Repository Structure

```text
.
├── preprocess/
│   └── Data preprocessing and feature engineering notebooks
│
├── model_training/
│   └── CNN model training notebooks
│   └── Vision Transformer training notebooks
│
├── Xai/
│   └── Guided SHAP implementation and explanation generation
│   └── LIME-based explanation notebooks
│
├── ablation_study/
│   └── Ablation experiments and analysis
│
├── models/
│   └── Saved trained models and checkpoints
│
└── README.md
```

---

## Datasets

Experiments were conducted using:

* CICIDS2017
* CIC-IDS2018
* UNSW-NB15

Please download the datasets from their official sources and update the paths in the notebooks accordingly.


## Main Features

* Hybrid CNN–Vision Transformer IDS
* Guided SHAP explainability framework
* Correlation-aware feature attribution
* Information Gain-guided coalition generation
* LIME explanations
* Ablation studies
* Reproducible experimental pipeline


This project is released under the MIT License.
