# __Customer Churn Prediction__

## __Project Description__

This project focuses on predicting customer churn based on their demographic information and service subscription data. The goal of the project is to help the company develop customer retention programs, reducing the risk of churn.

The dataset used was taken from Kaggle - [__Telco Customer Churn__](https://www.kaggle.com/datasets/blastchar/telco-customer-churn), and each customer is described by several features, such as service usage, payment information, and demographics.

## __Technologies__

- __Python__ – the main language used in the project
- __scikit-learn__ – for traditional machine learning models
- __XGBoost__ – for building classification models
- __Pandas and NumPy__ – for data manipulation
- __Matplotlib and Seaborn__ – for data visualization

## __Objective__


Predict the probability of customer churn based on demographic data, service usage, and payment information. Key evaluation metrics include model accuracy, F1 score, precision, and recall.

## __Project Structure__
- __data__ – contains the dataset
- __notebook__ – notebook with code for data analysis and modeling
- __README.md__ – project description

## __Dataset__
The dataset was taken from open sources (IBM Sample Data Sets). It includes the following features:

- __Churn__ – whether the customer left or not
- __Services__ – data on services subscribed to by customers (internet, tech support, etc.)
- __Payment Information__ – payment method, monthly charges, and total charges
- __Demographics__ – gender, age, and marital status

## __Models__
Several models were used in the project:

- __Logistic Regression__
- __Random Forest__
- __K-Nearest Neighbors (KNN)__
- __Support Vector Machine (SVM)__
- __XGBoost__

## __Fine-Tuning with Optuna__
Fine-tune a Logistic Regression model and CatBoostClassifier using Optuna for hyperparameter optimization. The tuning process involves optimizing key parameters such as C, penalty, and solver for Logistic Regression and iterations, learning_rate, depth and l2_leaf_reg for CatBoost to maximize model performance. Optuna automates the hyperparameter search using a tree-structured Parzen estimator (TPE), making the tuning process efficient and scalable.

## __Results__
The models were evaluated using several metrics:

- __Accuracy__
- __F1 Score__
- __Precision and Recall__
- __ROC-AUC Curve__
  
The best model achieved an accuracy of around 82%, making it suitable for real-world business tasks.
