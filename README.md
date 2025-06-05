# Predicting-Heart-Disease-Using-Machine-Learning

This repository contains a machine learning project aimed at predicting the presence of heart disease in patients based on clinical and demographic data. The project applies classification techniques to medical datasets and evaluates models using appropriate performance metrics to support early diagnosis and healthcare decisions.

## 🧠 Project Overview

Cardiovascular disease is a leading global cause of mortality. Early detection through predictive analytics can significantly reduce risk and aid in clinical decision-making. This project builds and evaluates predictive models to classify patients with and without heart disease using UCI-based datasets.

## 📦 Dataset

- **Source**: [UCI Machine Learning Repository – Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
- **Attributes**: 14 key clinical indicators, including:
  - Age, Sex, Chest Pain Type (cp)
  - Resting Blood Pressure (trestbps)
  - Cholesterol (chol)
  - Fasting Blood Sugar (fbs)
  - Resting ECG (restecg)
  - Max Heart Rate Achieved (thalach)
  - Exercise-Induced Angina (exang)
  - Oldpeak (ST depression), Slope, CA, Thal
  - Target (presence of heart disease)

## 🛠 Methods

- **Data Preprocessing**:
  - Null handling, normalization, encoding categorical variables
- **Exploratory Data Analysis (EDA)**:
  - Correlation heatmaps, histograms, and boxplots
- **Model Training & Testing**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC Curve

## 📈 Results

| Model               | Accuracy | F1-Score | Comments                          |
|--------------------|----------|----------|-----------------------------------|
| Logistic Regression| 85%      | 0.83     | Best trade-off in performance     |
| Random Forest      | 87%      | 0.86     | High accuracy, avoids overfitting |
| SVM                | 82%      | 0.81     | Stable but slightly underperformed|
| KNN                | 78%      | 0.76     | Sensitive to data distribution    |

✅ **Random Forest** showed the best overall performance.  
✅ **Logistic Regression** offered solid interpretability and generalization.

## 🎯 Project Goal

To develop a reliable model that can assist healthcare providers in identifying patients at risk of heart disease using accessible clinical data and enhance preventive healthcare.

## 📌 Tools & Libraries

- Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Excel (for initial data overview)

## 💡 Key Takeaways

- Data preprocessing and feature engineering are critical in healthcare ML.
- Ensemble models like Random Forest offer robust performance.
- Visualizing correlations and decision boundaries helps with model interpretation.
- Heart disease prediction using machine learning is a promising field for clinical support.


