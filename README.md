# Diabetes Prediction using Logistic regression
Overview
This project applies supervised machine learning to predict diabetes outcomes based on diagnostic data from the Pima Indians Diabetes Dataset. The goal is to assist in early identification of diabetes risk using interpretable and accurate models.

### Dataset
Source: Kaggle - Pima Indians Diabetes Database

Samples: 768 female patients of Pima Indian heritage

### Features:

Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age

### Target:

Outcome: 0 = No diabetes, 1 = Diabetes

#### Project Workflow
1.  Exploratory Data Analysis (EDA)
Inspected feature distributions, class imbalance, and correlation

Detected biologically implausible zero values in features (e.g., Glucose, Insulin)

Visualizations used: heatmaps, histograms, pair plots

2.  Data Splitting
Manual split: Training (first 650 rows), Test (next 100), Check set (final 18)

Also used train_test_split for validation with 70/30 stratification

