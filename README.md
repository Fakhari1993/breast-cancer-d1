# Breast Cancer – D1

Binary classification of **benign** vs **malignant** tumors on the **UCI Breast Cancer (Diagnostic)** dataset using Logistic Regression, Random Forest, and SVM (RBF).
Focus: **maximize malignant recall** while keeping strong AUC.

> Repo: https://github.com/Fakhari1993/breast-cancer-d1  
> Author: <YOUR Mahdieh Fakhari> • Date: <1993-09-14>

---

## 🔍 Overview
- **Dataset:** UCI Breast Cancer (Diagnostic), 569 samples, 30 numeric features.
- **Goal:** Reliable diagnosis with emphasis on **malignant recall** (reducing false negatives).
- **Models:** Logistic Regression, Random Forest, SVM (RBF).
- **Metrics:** AUC (primary), Precision, Recall, F1.
- **Outputs:** Combined ROC curve + Confusion Matrix of best model.

---

## 🧱 Project Structure
```
.
├─ src/
│  └─ Cancer.py
├─ figures/
│  ├─ roc_curves.png
│  └─ confusion_matrix.png
└─ README.md

## 🗂️ Data Source
UCI Machine Learning Repository — Breast Cancer Wisconsin (Diagnostic).  
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

**ROC Curves (Test)**  
![ROC](figures/roc_curves.png)

**Confusion Matrix (Best Model)**  
![CM](figures/confusion_matrix.png)


