# Credit Card Fraud Detection using Machine Learning

## Overview
This project focuses on building a machine learning–based fraud detection system
to identify fraudulent financial transactions from highly imbalanced transaction data.
The goal is to minimize false negatives (missed frauds) while maintaining strong overall
model performance.
The project emphasizes classical machine learning techniques, proper data
preprocessing, and evaluation metrics suitable for real-world fraud detection problems.

## Dataset
PaySim – a simulated mobile money transaction dataset reflecting real-world fraud
patterns.
Key characteristics:
Millions of transaction records
Extremely imbalanced target variable (isFraud)
Multiple transaction types and balance-related features

## Key Challenges
- Extreme class imbalance
- High cost of false negatives
- Feature preprocessing for ML models

## Machine Learning Models
- Logistic Regression (Baseline, class-weighted)
 Used as an interpretable baseline model.
Applied class-weighted learning to handle imbalance.
Helped establish minimum acceptable fraud recall.
- Random Forest (Core model)
 Captures non-linear transaction patterns
Robust to feature scaling
Significantly improved fraud recall and ROC-AUC
Provided feature importance insights

## Techniques Used
- Stratified train-test split
- Feature scaling (Logistic Regression)
- Class-weighted learning
- ROC-AUC and Recall-based evaluation

## Results
-Logistic Regression served as a strong baseline but struggled with complex patterns
-Random Forest significantly improved fraud detection performance
-Random Forest achieved higher fraud recall and ROC-AUC, making it more suitable
for real-world fraud detection scenarios

## Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

##Conclusion
This project demonstrates how classical machine learning techniques can be effectively
applied to fraud detection problems when combined with proper preprocessing, imbalance
handling, and evaluation strategies. Random Forest emerged as the most effective model
for detecting fraudulent transactions in this dataset.
