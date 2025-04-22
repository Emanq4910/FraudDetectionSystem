 Fraud Detection System

A complete end-to-end machine learning project to detect fraudulent credit card transactions. This system uses data preprocessing, class balancing (SMOTE), model training with Random Forest, evaluation metrics, and a command-line interface to predict the legitimacy of new transactions.



Overview

Credit card fraud is a significant issue in the financial industry. Detecting fraudulent transactions early can save money and protect consumers. This project provides a supervised learning pipeline that addresses the **highly imbalanced** nature of credit card transaction data using **SMOTE** and trains a model capable of accurately identifying fraud.



 Objectives

- Load and explore the Credit Card Fraud dataset from here :https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
- Preprocess the data (scaling, cleaning)
- Address class imbalance with **SMOTE**
- Train a **Random Forest** classifier (easily swappable with Gradient Boosting)
- Evaluate model performance using classification metrics
- Provide a simple **CLI interface** to test new transactions manually


 Features

✅ Load and preprocess raw data  
✅ Apply feature scaling on `Amount` and `Time`  
✅ Handle class imbalance using **SMOTE**  
✅ Train a machine learning model (Random Forest)  
✅ Evaluate with precision, recall, F1-score, and confusion matrix  
✅ Test new transactions via command-line input  
✅ Clean and modular Python script  
✅ Easy to extend or deploy



 Project Structure

