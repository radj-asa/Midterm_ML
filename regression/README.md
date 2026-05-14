# End-to-End Regression Pipeline for Song Release Year Prediction

## Project Overview

This project aims to build an end-to-end machine learning regression pipeline to predict the release year of a song based on its audio features.

The dataset contains multiple numerical audio-related features extracted from music signals such as timbre and other acoustic characteristics. The first column represents the target variable (song release year), while the remaining columns are used as input features.

This project was developed as part of the Machine Learning and Deep Learning individual assignment.

---

# Objectives

The main objectives of this project are:

- Perform data preprocessing and cleaning
- Handle missing values and outliers
- Train a regression model using machine learning
- Perform hyperparameter tuning using Optuna
- Evaluate model performance using regression metrics
- Interpret predictions using LIME
- Track experiments using MLflow

---

# Dataset Information

Dataset Name:
- `midterm-regresi-dataset.csv`

Dataset Characteristics:
- Numerical tabular dataset
- First column = target variable (release year)
- Remaining columns = audio feature values

Example target values:
- 1998
- 2001
- 2010

---

# Machine Learning Workflow

The workflow implemented in this project includes:

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Missing Value Handling
4. Feature and Target Separation
5. Train-Validation Split
6. Regression Model Training
7. Model Evaluation
8. Feature Importance Analysis
9. Hyperparameter Tuning using Optuna
10. Experiment Tracking using MLflow
11. Model Interpretation using LIME

---

# Model Used

The regression model used in this project:

- LightGBM Regressor (`LGBMRegressor`)

Reason for choosing this model:
- Efficient for tabular datasets
- Fast training process
- Good regression performance
- Handles numerical features effectively

---

# Evaluation Metrics

The model performance is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

---

# Libraries and Tools

Main libraries used in this project:

- Python
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- Optuna
- MLflow
- Matplotlib
- Seaborn
- LIME

---
