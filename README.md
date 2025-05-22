# Fraud Detection Using XGBoost🔍💳
This project aims to detect fraudulent transactions using machine learning, specifically the XGBoost algorithm. We use real-world-like transaction data to build a predictive model that can identify fraud based on patterns in the data.

## 📌 What This Project Does
Analyzes transaction data (like transaction amount, time, customer age, device used, etc.)
Cleans and prepares the data for machine learning
Converts text features (like browser, source, payment method) into numbers
Uses the XGBoost model to train on the data
Predicts whether a transaction is fraudulent (1) or not fraudulent (0)

## Overview
This project uses the XGBoost algorithm to classify whether a transaction is fraudulent or not. It includes data cleaning, preprocessing, model training, and evaluation.
## Dataset
The dataset contains customer information such as transaction amount, age, device, payment method, and fraud label. Sensitive information has been anonymized or masked.

## How It Works
1. Data Cleaning (handling missing/null values)
2. Label Encoding (for categorical columns)
3. Splitting the data into train and test sets
4. Training using XGBoostClassifier
5. Predicting and evaluating the model
   
## Technologies Used
- Python
- Pandas, NumPy
- XGBoost
- Scikit-learn
- Jupyter Notebook

## Conclusion
This project shows how machine learning (XGBoost) can be used to detect fraud effectively by training on real-looking transaction data. It's a great example of how data cleaning, preprocessing, and the right model can provide valuable insights.
