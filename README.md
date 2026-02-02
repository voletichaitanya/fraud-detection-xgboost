# Fraud Detection in Transactions using XGBoost

## Problem
Fraud detection is a critical task due to highly imbalanced transaction data.

## Dataset
Credit Card Fraud Detection Dataset (Kaggle)

## Approach
- Stratified train-test split
- Handle imbalance using scale_pos_weight
- Train XGBoost classifier

## Evaluation Metrics
- ROC-AUC
- Recall (Fraud class)

## Conclusion
The model effectively detects fraudulent transactions while minimizing missed fraud cases.
