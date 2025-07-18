# 🧠 Data Science Project: Customer Churn Prediction (BCG X - Forage)

This project simulates a real-world data science task from BCG X, focusing on identifying customer churn drivers and building a predictive model.

## 🚀 Project Overview

Customer churn represents the percentage of users who stop using a company’s product or service. In this project, we aim to:
- **Identify key indicators of churn**
- **Build a churn prediction model**
- **Recommend actions to retain customers**

We use **Random Forest** for classification and base our work on a synthetic dataset provided by BCG X.

## 🧠 Problem Statement

> **"Which customers are most likely to churn, and how can we proactively retain them?"**

Understanding churn helps the business reduce customer acquisition costs and focus on retention strategies.

## 🔍 Tasks Covered

1. **Business Understanding**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering**
4. **Churn Prediction using Random Forest**
5. **Model Evaluation & Recommendations**

## 🧪 Tools & Technologies

- Python (pandas, seaborn, scikit-learn, matplotlib)
- Jupyter Notebook
- Classification Metrics (Accuracy, Precision, Recall)
- Random Forest Classifier

## 📊 Model Evaluation Metrics

| Metric                     | Value         |
|----------------------------|---------------|
| **Accuracy**               | 90.08%        |
| **Precision (Churn = 1)**  | 89%           |
| **Recall (Churn = 1)**     | 6%            |
| **F1-Score (Churn = 1)**   | 10%           |
| **ROC-AUC Score**          | 67.50%        |

> ⚠️ **Note**: While accuracy and precision are high, recall is low due to class imbalance. Consider techniques like class weighting, SMOTE, or threshold tuning to improve churn detection.


## 📊 Key Insight

Customers with higher net margins and lower price sensitivity show reduced churn rates. The model helps prioritize high-risk customers for retention.

## 📁 Dataset

Synthetic dataset provided by BCG X (via Forage).


---

