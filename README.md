# Heart Disease Prediction

A machine learning project that predicts the likelihood of heart disease using the K-Nearest Neighbors (KNN) classification algorithm and an interactive Streamlit application.

## Project Overview

This project applies data preprocessing, categorical feature encoding, feature scaling, and KNN classification to predict heart disease based on patient health-related features.

## Dataset

The dataset contains patient information such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak
- ST Slope

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Streamlit
- Jupyter Notebook

## Machine Learning Workflow

The project includes:

1. Data loading and understanding
2. Data preprocessing
3. Categorical feature encoding
4. Feature scaling using StandardScaler
5. Train-test splitting
6. KNN model training
7. Model evaluation
8. Model saving using Joblib
9. Interactive prediction using Streamlit

## Machine Learning Model

**K-Nearest Neighbors (KNN)** is used as the classification algorithm for heart disease prediction.

## Streamlit Application

An interactive Streamlit application was developed to allow users to enter patient information and receive a model-based prediction.

## Project Structure

```text
Heart-Disease-Prediction/
│
├── Heart (3).ipynb
├── heart.xlsx
├── app.py
├── KNN_heart.pkl
├── scaler.pkl
├── columns.pkl
└── README.md
