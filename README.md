# Customer Churn Prediction Using Machine Learning 📉🧠

This project focuses on developing a churn prediction model using real-world customer transaction data from **Tesco**. The primary goal was to identify patterns and early indicators of customer churn to inform retention strategies.

> 🔒 Due to a Data Sharing Agreement (DSA), the dataset used in this project **cannot be shared publicly** as it contains real Tesco customer transaction data.

> 📘 A detailed explanation of the methodology and results is available in the [coursework_report.pdf](coursework_report.pdf) included in this repository.

---

## 🧠 Project Overview

- Built a machine learning pipeline to predict customer churn using anonymized retail data.
- Feature engineering was conducted directly within **PostgreSQL**, focusing on temporal patterns, transaction recency, frequency, and monetary value.
- Evaluated multiple classifiers including **Decision Tree**, **Random Forest**, and **XGBoost**.
- XGBoost performed best based on AUC and F1 score.

---

## 💡 Key Highlights

- ⏳ Time-based features created with SQL window functions and temporal aggregations
- ⚙️ Scikit-learn pipeline with model training and cross-validation
- 📊 Performance evaluated with AUC, Precision, Recall, and F1 Score
- 🧪 Model explainability using SHAP

---
## 🛠️ Technologies Used
Python

scikit-learn

imbalanced-learn (SMOTE)

XGBoost

SHAP

## 📄 License
This project is licensed under the MIT License.
