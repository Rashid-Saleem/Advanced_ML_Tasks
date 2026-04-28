# 🎯 Objective: Build a reusable and production-ready machine learning pipeline for predicting customer churn. 

## 📋 Project Overview

A production-ready machine learning project designed to predict customer churn using the Telco Churn Dataset. This project leverages the Scikit-learn Pipeline API to ensure a clean, reusable, and leak-proof workflow from data preprocessing to model deployment.

## 🎯 Pipeline Features
- ✅ **Implement data preprocessing steps (e.g., scaling, encoding) using Pipeline**
- ✅ **Using ColumnTransformer, we handle mixed data types automatically:**
- ✅ **Numerical Features: Handled via SimpleImputer (median) and StandardScaler**
- ✅ **Categorical Features: Handled via SimpleImputer (constant) and OneHotEncoder.** 
- ✅ **Logistic Regression: Used as a baseline linear model.**
- ✅ **Random Forest Classifier: Used to capture non-linear relationships and feature interactions.**
- ✅ **Hyperparameter Tuning using GridSearchCV**
- ✅ **Export & Reusability using joblib**
- ✅ **Production-readiness practices**

## 📊 Dataset

**Source:** (https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

**Size:** 
- Main dataset: 955 KB (Telco-Customer-Churn.csv)
