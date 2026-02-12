# Home Credit Default Risk Prediction
## Project Overview

This project is based on the Home Credit Default Risk (HCDR) Kaggle Competition.
The objective is to predict whether a client will default on a loan using structured financial and behavioral data.

Home Credit aims to expand financial inclusion by providing loans to individuals with limited or no credit history. By leveraging alternative data sources such as transactional, bureau, and installment records, we build machine learning models to assess repayment risk.

## Project Workflow
1. Exploratory Data Analysis (EDA)

Distribution analysis

Missing value inspection

Correlation analysis

Outlier detection

2. Feature Engineering

Domain-based ratio features (credit/income, annuity/income, etc.)

Tiered aggregation (Tier 3 → Tier 2 → Tier 1)

Polynomial feature generation

Missing value filtering

Collinearity removal

3. Data Preprocessing

Numerical: Imputation + Standard Scaling

Categorical: One-Hot Encoding

Pipeline integration using scikit-learn

4. Modeling

Logistic Regression (Baseline)

Gradient Boosting

XGBoost

Random Forest

PCA-based Logistic Regression

Neural Networks (PyTorch)

5. Evaluation Metrics
* Accuracy
* ROC-AUC
* F1 Score
* Log Loss
* Confusion Matrix

## Result Summary
| Model               | Test Accuracy | ROC-AUC |
| ------------------- | ------------- | ------- |
| Logistic Regression | ~70%          | ~66%    |
| Gradient Boosting   | ~92%          | ~71%    |
| XGBoost             | ~91%          | ~71%    |
| Random Forest       | ~88%          | ~70%    |
<img width="2776" height="832" alt="image" src="https://github.com/user-attachments/assets/0889b3f6-c871-4e26-b6c4-a2e9aaf5ce3d" />


## Technologies Used
* Scikit-learn
* XGBoost
* Pandas / NumPy
* Matplotlib / Seaborn
* PyTorch
