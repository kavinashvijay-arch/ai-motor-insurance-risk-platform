# 🚗 Motor Insurance Claim Prediction & Pricing Engine

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-red)
![SHAP](https://img.shields.io/badge/Explainable-AI-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🚀 Run the Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/137Par_xwUsxOTNi_aLf3EwXeT4DGlCuO?usp=drive_link)

---

# 📌 Project Overview

Motor insurers must estimate the likelihood of future claims to price insurance policies accurately and manage underwriting risk. This project develops an end-to-end machine learning system that predicts claim probability, assigns driver risk scores, and recommends insurance premiums based on individual risk profiles.

---

# 🎯 Business Problem

Traditional underwriting relies on predefined pricing rules that may not fully capture driver risk. This project demonstrates how machine learning can support more accurate underwriting by predicting claim probability and generating explainable premium recommendations.

---

# 📂 Dataset

- 58,592 insurance policies
- 39 predictor variables
- Binary classification
- Target Variable:
  - 0 = No Claim
  - 1 = Claim

---

# ⚙ Project Workflow

```
Insurance Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
SMOTE Balancing
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
SHAP Explainability
      │
      ▼
Risk Scoring
      │
      ▼
Premium Pricing Engine
```

---

# 🤖 Machine Learning Models

- Logistic Regression
- Random Forest
- Balanced Random Forest
- XGBoost

Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

# 💰 Insurance Analytics

The pricing engine produces:

- Claim Probability
- Driver Risk Score (0–100)
- Risk Category
- Recommended Premium
- Underwriting Decision

---

# 🔍 Explainable AI

SHAP identifies the most influential variables affecting claim predictions, allowing underwriters to understand and justify premium pricing decisions.

---

# 📊 Key Features

✔ Claim Prediction

✔ Premium Pricing Engine

✔ Driver Risk Score

✔ Risk Segmentation

✔ SHAP Explainability

✔ Class Imbalance Handling (SMOTE)

---

# 📁 Repository Structure

```
Motor-Insurance-Pricing/
│
├── notebook.ipynb
├── README.md
├── dataset.csv
├── images/
└── requirements.txt
```

---

# 🛠 Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- SMOTE
- Matplotlib

---

# 🚀 Future Improvements

- Streamlit Dashboard
- Real-Time Underwriting API
- Fraud Detection Module
- Hyperparameter Optimisation
- Telematics Integration

---

# 👨‍💻 Author

**Kavinash Vijay**
