E-commerce Customer Analytics and Modeling 

Overview

This project analyzes e-commerce transaction data to build customer-level features, perform exploratory data analysis (EDA), and develop machine learning models for:

Customer Lifetime Value (CLV Proxy) Prediction (Regression)
Customer Churn Prediction (Classification)
Dataset
Source: Kaggle E-commerce Dataset
File: data.csv
Key fields: InvoiceNo, CustomerID, Quantity, UnitPrice, InvoiceDate, Country
Project Workflow
Data Preparation
Removed missing values and duplicates
Filtered invalid stock codes and non-positive prices
Converted dates and cleaned transaction records
Feature Engineering

Created customer-level metrics including:

Recency (Days_Since_Last_Purchase)
Total Transactions
Total Products Purchased
Total Spend
Average Transaction Value
Unique Products Purchased
Average Days Between Purchases
Monthly Spending Statistics
Country Indicator (UK vs Non-UK)
Modeling
CLV Prediction
Linear Regression
Random Forest Regressor
Churn Prediction
Logistic Regression
Random Forest Classifier
Evaluation
Regression: MAE, RMSE, R²
Classification: Precision, Recall, F1-Score, ROC-AUC
Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
