# 💰 Loan Approval Prediction with MLflow

## 📌 About

This project predicts whether a loan application will be approved using a **Random Forest Classifier** and tracks the ML experiment using **MLflow**.

The dataset is simulated using Income, Credit Score, Age, and Loan Amount.

## 🤖 Algorithm

- Random Forest Classifier
- Train-Test Split
- MLflow Experiment Tracking

## 📊 Features

- Income
- Credit Score
- Age
- Loan Amount

## 🎯 Target

`Loan_Status`

- `1` → Loan Approved
- `0` → Loan Not Approved

## 📈 Evaluation

The model is evaluated using **Accuracy Score**.

MLflow records:
- Model parameters
- Accuracy metric
- Trained model

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- MLflow

## ▶️ Run

```bash
pip install mlflow pandas numpy scikit-learn
python loan_prediction.py
