# End-to-End ML Project
## Customer Churn Prediction — Complete Production Pipeline

---

## Business Problem

Customer churn costs businesses millions every year. When a 
customer leaves, companies lose not just revenue but the 
significant cost already invested in acquiring them.

This project builds a complete, production-quality machine 
learning pipeline to predict which customers are at risk of 
churning — enabling businesses to take targeted retention 
action before it is too late.

This is not just a notebook experiment. Every stage is 
documented, justified, and structured the way a professional 
data scientist would approach a real business problem.

---

## Project Highlights

| | |
|---|---|
| Problem Type | Binary Classification |
| Dataset | Telco Customer Churn — IBM via Kaggle |
| Records | 7,043 customers · 21 features |
| Target Variable | Churn — Yes or No |
| Models Compared | Logistic Regression · Random Forest · XGBoost |
| Final Model | To be determined after training |
| Status | Building from Week 10 |

---

## Complete Pipeline Structure
```
End-to-End-ML-Project/
│
├── data/
│   └── telco_customer_churn.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_feature_engineering.ipynb
│   ├── 04_model_training.ipynb
│   └── 05_model_evaluation.ipynb
│
├── images/
│   └── all charts and visualisations saved here
│
└── README.md
```

---

## Stage Breakdown

**Stage 01 — Data Cleaning**
- Identify and handle all missing values
- Fix incorrect data types
- Remove duplicates
- Detect and treat outliers
- Document every decision made and the reasoning behind it

**Stage 02 — Exploratory Data Analysis**
- Churn rate distribution and breakdown
- Customer demographics analysis
- Service usage patterns among churners vs non-churners
- Correlation heatmap across all features
- Business insight generation from patterns found

**Stage 03 — Feature Engineering**
- Encode all categorical variables correctly
- Scale numerical features appropriately
- Engineer new meaningful features from existing data
- Select most predictive features using importance scores

**Stage 04 — Model Training**
- Logistic Regression as interpretable baseline
- Random Forest for ensemble performance
- XGBoost for gradient boosting comparison
- Cross validation on all three models
- Handle class imbalance with SMOTE if needed

**Stage 05 — Model Evaluation**
- Accuracy, Precision, Recall, F1 Score comparison table
- ROC AUC Curve for all three models
- Confusion Matrix analysis
- Final model selection with full business justification
- What would this mean in a real deployment?

---

## Why This Project Specifically

- Customer churn is a real problem every UK company faces
- The dataset is clean enough to work with but messy enough to be realistic
- The problem requires both technical ML skills and business communication
- Every stage of this project is something a junior data scientist would be asked about in a UK interview

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shoaib-aslam32922)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/imshoaibaslam)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:aslamshoaib197@gmail.com)

