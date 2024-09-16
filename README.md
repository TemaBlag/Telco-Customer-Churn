Customer Churn Prediction

Project Description

This project focuses on predicting customer churn based on their demographic information and service subscription data. The goal of the project is to help the company develop customer retention programs, reducing the risk of churn.

The dataset used was taken from Kaggle, and each customer is described by several features, such as service usage, payment information, and demographics.

Technologies

  Python – the main language used in the project

  scikit-learn – for traditional machine learning models

  XGBoost – for building classification models

  Pandas and NumPy – for data manipulation

  Matplotlib and Seaborn – for data visualization

  Google Cloud Platform (GCP) – for cloud data processing

  Objective


Predict the probability of customer churn based on demographic data, service usage, and payment information. Key evaluation metrics include model accuracy, F1 score, precision, and recall.

Project Structure
data – contains the dataset
notebooks – Jupyter notebooks with code for data analysis and modeling
models – saved models for predictions
src – main project code
README.md – project description
Dataset
The dataset was taken from open sources (IBM Sample Data Sets). It includes the following features:

Churn – whether the customer left or not
Services – data on services subscribed to by customers (internet, tech support, etc.)
Payment Information – payment method, monthly charges, and total charges
Demographics – gender, age, and marital status
Models
Several models were used in the project:

Logistic Regression
Random Forest
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
XGBoost
Results
The models were evaluated using several metrics:

Accuracy
F1 Score
Precision and Recall
ROC-AUC Curve
The best model achieved an accuracy of around 85%, making it suitable for real-world business tasks.
