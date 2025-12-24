# Data-Science-Internship-Week10

# Customer Churn Prediction – Data Preprocessing & Feature Engineering

## Project Overview
This project implements a complete data preprocessing and feature engineering pipeline for predicting customer churn. The focus is on data preparation quality, feature transformation, and correct machine learning workflow rather than only model accuracy.

The project follows industry-aligned practices such as preventing data leakage, handling class imbalance, and building interpretable models.

---

## Objectives
- Convert categorical data into numerical formats
- Apply multiple feature scaling techniques
- Detect and handle outliers
- Engineer meaningful features from limited raw data
- Handle imbalanced churn data
- Build and evaluate churn prediction models

---

## Dataset Information
- **File:** customer_churn.csv  
- **Rows:** 500  
- **Columns:** 4  
- **Target Variable:** Churn  
  - 0 → No Churn  
  - 1 → Churn  

The dataset is highly imbalanced, with approximately 10.6% churned customers.

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

---

## Setup Instructions
Install dependencies:
```bash
pip install -r requirements.txt
