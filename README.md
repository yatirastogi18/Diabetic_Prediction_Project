# 🩺 Diabetes Risk Prediction using Machine Learning

## Project Overview

Diabetes is one of the most common chronic diseases worldwide. Early prediction of diabetes risk can help individuals take preventive measures and assist healthcare professionals in making informed decisions.

This project uses the CDC BRFSS 2015 Diabetes Health Indicators dataset to predict whether an individual is Healthy, Prediabetic, or Diabetic. Multiple machine learning and transformer-based models were trained and compared to identify the most effective approach for diabetes classification.

---

## Dataset

The project uses the CDC BRFSS 2015 dataset, which contains health, lifestyle, and demographic information collected from adults across the United States.

Key features include:

- High Blood Pressure
- High Cholesterol
- BMI
- Smoking Habits
- Physical Activity
- Age
- Income
- General Health

Target Variable:
- 0 = Healthy
- 1 = Prediabetic
- 2 = Diabetic

---

## Methodology

The project follows a complete machine learning pipeline:

1. Data preprocessing and cleaning
2. Handling class imbalance using SMOTE and Tomek Links
3. Exploratory Data Analysis (EDA)
4. Feature scaling and train-test split
5. Model training and evaluation
6. Performance comparison using multiple metrics

---

## Models Implemented

To compare different approaches, the following models were used:

- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- FT-Transformer
- TabTransformer

Traditional machine learning models were compared with transformer-based architectures designed specifically for tabular data.

## Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

These metrics helped assess both overall performance and class-wise prediction quality.
---

## Contributors

- Yati Rastogi
- Tanushi Taparia
- Anushka
