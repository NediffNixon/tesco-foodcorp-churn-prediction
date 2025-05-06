# Customer Churn Prediction Using Machine Learning 📉🧠

This project focuses on developing a churn prediction model using real-world customer transaction data from **Tesco**. The primary goal was to identify patterns and early indicators of customer churn to inform retention strategies.

> Due to a Data Sharing Agreement (DSA), the dataset used in this project **cannot be shared publicly** as it contains real Tesco customer transaction data.

> A detailed explanation of the methodology and results is available in the [coursework_report.pdf](docs/coursework_report.pdf) included in this repository.

> A supporting document is available explaning how to run the model in the [supporting_documentation.pdf](docs/supporting_documentation.pdf) included in this repository.

---

## Project Overview

- Built a machine learning pipeline to predict customer churn using anonymised retail data.
- Feature engineering was conducted directly within **PostgreSQL**, focusing on temporal patterns, transaction recency, frequency, and monetary value.
- Evaluated multiple classifiers including **Decision Tree**, **Random Forest**, and **XGBoost**.
- XGBoost performed best with a 0.71 Balanced Accuracy score, a strong performance for real-world data.

---

## Key Highlights

- ⏳ Time-based features created with SQL window functions and temporal aggregations
- ⚙️ Scikit-learn pipeline with model training and cross-validation
- 📊 Performance evaluated with Balanced Accuracy score, AUC, Precision, Recall, and F1 Score
- 🧪 Model explainability using SHAP

---

## Installation (Conda)

```bash
# Clone this repository
git clone https://github.com/nediffnixon/tesco-foodcorp-churn-prediction.git
cd tesco-foodcorp-churn-prediction

# Create and activate conda environment
conda env create -f environment.yml
conda activate churn_prediction_env
```
---

## Technologies Used
Python

scikit-learn

imbalanced-learn (SMOTE)

XGBoost

SHAP

Optuna

PostgreSQL

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
