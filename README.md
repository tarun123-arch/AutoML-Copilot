# 🤖 AutoML Copilot

An end-to-end automated Machine Learning pipeline capable of preprocessing, feature engineering, model training, evaluation, and automatic best model selection for both classification and regression problems.

Instead of manually writing preprocessing code for every dataset, the pipeline automatically performs all required steps and returns the highest-performing machine learning model.

---

# Why this project?

Machine learning projects usually require repetitive preprocessing before model training.

This project automates the complete workflow so users only need to:

• Provide a CSV dataset
• Select the target column

Everything else is handled automatically.

---

# Features

## 📂 Dataset Processing

✔ Load any CSV dataset

✔ Display dataset information

✔ Automatic target column selection

✔ Automatic feature/target separation

---

## 📊 Automatic Exploratory Data Analysis

✔ Dataset shape

✔ Missing value analysis

✔ Data type inspection

✔ Statistical summary

✔ Duplicate detection

---

## 🧹 Data Preprocessing

✔ Missing value handling

✔ One-Hot Encoding

✔ Numerical feature scaling

✔ Automatic preprocessing pipeline

---

## 🧠 Intelligent Task Detection

The pipeline automatically detects whether the selected target belongs to

- Classification
- Regression

No manual configuration required.

---

## 🤖 Machine Learning Models

Depending on the task, multiple algorithms are trained.

Examples include:

Classification

• Logistic Regression

• Decision Tree

• Random Forest

• KNN

• SVM

Regression

• Linear Regression

• Decision Tree Regressor

• Random Forest Regressor

---

## 📈 Model Evaluation

Every trained model is evaluated.

The pipeline compares all scores and automatically selects the highest-performing model.

Returned information includes:

• Best Model

• Accuracy / R² Score

• Model Comparison

---

# Workflow

Dataset
↓

EDA
↓

Missing Value Handling
↓

Encoding
↓

Scaling
↓

Model Training
↓

Evaluation
↓

Best Model Selection

---

# Technologies

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Jupyter Notebook

---

# Future Improvements

FastAPI Backend

React Dashboard

Model Download

Auto Prediction API

Docker Deployment

Cloud Hosting
