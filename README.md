# Customer-churn-analysis
# 📉 Customer Churn Prediction | Lloyds Banking Group

![Churn Analysis Banner](https://imgur.com/your-banner-placeholder.png)

## 🔍 Project Overview

This project focuses on building a machine learning pipeline to **predict customer churn** for **Lloyds Banking Group**, one of the leading financial institutions. Early identification of customers likely to churn empowers the business to launch targeted retention strategies, ultimately reducing revenue loss and improving customer satisfaction.

---

## 🧠 Problem Statement

Customer churn has a direct impact on profitability. Lloyds needed a predictive model to:
- Identify high-risk customers before they leave.
- Understand **why** they churn (feature importance).
- Enable **actionable business strategies** for retention.

---

## 📦 Dataset

The dataset (spread across multiple Excel sheets) included:
- Customer demographics and account info  
- Transaction history  
- Service usage data  
- Customer interaction logs  
- Churn status (target variable)  

All files were merged, cleaned, and engineered into a unified dataset for modeling.

---

## ⚙️ Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- **Jupyter Notebook / Google Colab**
- **SMOTE** for handling imbalanced data
- **Matplotlib & Seaborn** for EDA and visualizations
- **GridSearchCV** for hyperparameter tuning

---

## 🔁 Workflow

### ✅ Task 1: Data Preprocessing & EDA
- Merged 5 raw data sheets
- Cleaned missing/inconsistent values
- Feature engineering (e.g., usage metrics, engagement score)
- Visualized churn trends, correlations, and feature distributions

### ✅ Task 2: Model Development & Evaluation
- Handled class imbalance with **SMOTE**
- Tried multiple models: Logistic Regression, Random Forest, XGBoost
- Final Model: **XGBoost** with hyperparameter tuning via GridSearchCV
- Cross-validation (5-fold) for generalization

---

## 📊 Evaluation Metrics

| Metric         | Score |
|----------------|-------|
| Accuracy       | 87.2% |
| Precision      | 78%   |
| Recall         | 72%   |
| F1-Score       | 75%   |
| ROC-AUC Score  | **0.89** |

> ❗ Accuracy alone is misleading on imbalanced data. F1 and ROC-AUC were primary indicators of model success.

---

## 🌟 Key Business Insights

- Customers with fewer service interactions and lower digital engagement were more likely to churn.
- Complaints and negative interactions correlated strongly with churn.
- Early detection of at-risk customers is possible through behavioral patterns.

---


