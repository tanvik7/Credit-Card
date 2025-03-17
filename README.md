# Credit-Card-Fraud Detection
Project Overview

This project aims to detect fraudulent credit card transactions using machine learning techniques. The goal is to develop a predictive model that can accurately classify transactions as fraudulent or legitimate, helping financial institutions prevent fraud and protect customers.

📊 Dataset

The dataset used for this project is the Kaggle Credit Card Fraud Detection dataset, which contains anonymized transaction data with 284,807 records, including 492 cases of fraud (~0.172% of total transactions). The dataset has:

30 numerical features (including PCA-transformed features)

A highly imbalanced class distribution (fraud cases are rare)

🛠️ Tech Stack

Programming Language: Python

Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

Machine Learning Models: Logistic Regression

Evaluation Metrics: Precision, Recall, F1-score, ROC-AUC

🔍 Data Preprocessing

Handling class imbalance using techniques like SMOTE (Synthetic Minority Over-sampling Technique) and undersampling.

Feature scaling using StandardScaler.

Splitting data into training and testing sets (80/20 split).

🚀 Model Training & Evaluation

Baseline Model: Logistic Regression

Advanced Models: Random Forest, XGBoost, and Neural Networks

Hyperparameter Tuning: Performed using Grid Search and Random Search

Evaluation: Used confusion matrix, precision-recall curve, and ROC-AUC score

📈 Results

The best-performing model achieved an ROC-AUC score of 0.98.

Precision-Recall trade-offs were carefully analyzed to balance fraud detection and minimize false positives.
