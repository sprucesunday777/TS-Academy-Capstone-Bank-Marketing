# Bank Marketing — Term Deposit Subscription Prediction
### TS Academy Capstone Project | Group 18

## Overview
An end-to-end machine learning pipeline built on the Bank Marketing dataset.
The goal was to predict whether a customer would subscribe to a term deposit,
using clustering, classification, and imbalance handling techniques.

## Pipeline Summary
- Data loaded directly from Kaggle via kagglehub
- SQLite database querying for business insights
- Feature engineering (age bins, balance flags, contact recency)
- K-Means clustering — customer segmentation without using the label
- 4 classifiers: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting
- Imbalance handling: class weights, threshold tuning, SMOTE
- Cross-validation to confirm model stability

## Final Model
Gradient Boosting + SMOTE at threshold 0.3
Chosen because missing a true subscriber costs more than an unnecessary call.

## Tools
Python | pandas | scikit-learn | SQLite | matplotlib | seaborn | imbalanced-learn

## Author
Nsisong Sunday — Team Lead
Food Engineering Graduate | Data Science & ML Learner
LinkedIn: https://www.linkedin.com/in/john-sunday-9a73b93ab
