Credit Risk Modeling Project
This project focuses on predicting loan default risk using advanced machine learning techniques. The aim is to assess credit risk and distinguish between high-risk and low-risk borrowers based on key features.

Key Highlights:
High Accuracy Model: Developed a credit risk prediction model with 93% accuracy to identify potential loan defaulters.
Imbalanced Data Handling: Effectively managed the class imbalance problem using SMOTE-Tomek (a hybrid technique for over-sampling and under-sampling), which helped achieve a 94% recall and an F1-score of 0.71 for defaulters (class 1).
Feature Engineering:
Conducted extensive feature engineering to enhance model performance, including:
VIF (Variance Inflation Factor) analysis to check for multicollinearity.
IV (Information Value) calculation to determine the most significant predictors of credit risk.
Model Building and Optimization:
Developed and optimized classification models like Logistic Regression.
Utilized Weight of Evidence (WOE) transformation to handle categorical variables effectively and improve model interpretability.
Model Evaluation:
Evaluated model performance using key metrics, demonstrating strong predictive power:
AUC (Area Under the Curve): 0.98
Gini Coefficient: 0.96
KS Statistic (Kolmogorov-Smirnov): A high value that further shows the model’s ability to separate high-risk from low-risk borrowers.
Feature Importance:
Created a feature importance plot to highlight the most impactful variables influencing credit default risk, providing insights into key drivers of risk.
Tools and Techniques Used:
SMOTE-Tomek: To balance the dataset and improve recall for defaulters.
Logistic Regression & WOE: For model building and feature transformation.
AUC, Gini, KS Statistics: For model evaluation.# Credit_Risk_Modelling_Clasification
