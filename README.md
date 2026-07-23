# Canadian-Telecom-Customer-Churn-Prediction
Machine learning project for predicting customer churn using Logistic Regression.

# Project Overview

Customer churn is an important issue for telecommunication companies because retaining existing customers is often more cost-effective than acquiring new ones. This project analyzes customer churn using the IBM Telco Customer Churn dataset and builds a machine learning model to predict whether a customer is likely to leave the company.

The project covers the complete machine learning workflow, including data cleaning, exploratory data analysis (EDA), feature encoding, model training, and model evaluation.


# Dataset

- Source: IBM Telco Customer Churn Dataset
- Number of customers: 7,043
- Number of variables: 21

The dataset includes customer demographic information, subscribed services, contract type, payment method, monthly charges, total charges, and customer churn status.



# Exploratory Data Analysis

Several visualizations were created to explore customer churn patterns.

Key findings include:

- Customers with month-to-month contracts had the highest churn rate.
- Fiber optic customers were more likely to churn than DSL customers.
- Customers using electronic check showed the highest churn rate.
- Customers with shorter tenure were more likely to leave the company.

# Machine Learning Model

A Logistic Regression model was used to predict customer churn.

Model evaluation included:

- Accuracy
- Confusion Matrix
- Classification Report


# Results

The Logistic Regression model achieved an accuracy of 82.1% on the test dataset.

The model performed well in identifying customers who remained with the company while providing reasonable performance in predicting customer churn.

# Conclusion

This project demonstrates a complete machine learning workflow from data preprocessing to model evaluation.

The analysis suggests that contract type, tenure, internet service, and payment method are important factors related to customer churn.
