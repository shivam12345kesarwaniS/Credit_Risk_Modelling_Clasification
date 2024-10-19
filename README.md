# Credit Risk Modeling Project

This project focuses on predicting loan default risk using advanced machine learning techniques. The goal is to assess credit risk and distinguish between high-risk and low-risk borrowers based on key features.

## Project Overview
- **Objective**: The goal is to predict credit risk by leveraging customer, loan, and bureau data.
- **Datasets**:
  - `customers.csv`: Contains customer demographics and other relevant features.
  - `loans.csv`: Provides details about loans and their performance.
  - `bureau_data.csv`: Contains external financial data related to customers from other financial institutions.

## Key Highlights
- **High Accuracy Model**: Developed a credit risk prediction model with **93% accuracy** to identify potential loan defaulters.
- **Imbalanced Data Handling**: Managed class imbalance using **SMOTE-Tomek** (a hybrid technique for over-sampling and under-sampling), achieving **94% recall** and an **F1-score of 0.71** for defaulters (class 1).

## Feature Engineering
- Performed **extensive feature engineering**, including:
  - **Variance Inflation Factor (VIF)** analysis to check for multicollinearity.
  - **Information Value (IV)** calculation to identify significant predictors of credit risk.

## Model Building and Optimization
- Developed and optimized classification models such as **Logistic Regression**.
- Used **Weight of Evidence (WOE)** transformation to handle categorical features and improve model interpretability.

## Model Evaluation
- Evaluated model performance using key metrics:
  - **AUC (Area Under the Curve)**: 0.98
  - **Gini Coefficient**: 0.96
  - **KS Statistic (Kolmogorov-Smirnov)**: Demonstrated strong separation between high-risk and low-risk borrowers.

## Feature Importance
- Created a **feature importance plot** to highlight the most impactful variables influencing credit default risk, providing valuable insights into key risk drivers.

## Tools and Techniques Used
- **SMOTE-Tomek**: For balancing the dataset and improving recall for defaulters.
- **Logistic Regression & WOE**: For model building and feature transformation.
- **AUC, Gini, KS Statistics**: For evaluating model performance.
