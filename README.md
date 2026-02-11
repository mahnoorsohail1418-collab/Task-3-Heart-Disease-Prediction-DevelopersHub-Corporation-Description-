Task 3: Heart Disease Prediction - DevelopersHub Corporation
Task Objective
The main objective of this task is to predict whether a person is at risk of heart disease based on health-related features. This is a critical task in healthcare analytics, where early detection can save lives.

Specifically, this task focuses on:

Cleaning and preprocessing the dataset to handle missing values and ensure numeric consistency.

Performing Exploratory Data Analysis (EDA) to identify trends, distributions, and correlations between features.

Training a classification model (Logistic Regression) to predict heart disease risk.

Evaluating the model using accuracy, confusion matrix, and ROC-AUC score.

Identifying the most important features affecting heart disease prediction.

Dataset Used

Name: Heart Disease UCI Dataset

Source: Kaggle Heart Disease UCI Dataset

Samples: 303 patient records

Features: 14 features including:

Age

Sex

Chest Pain Type (cp)

Resting Blood Pressure (trestbps)

Serum Cholesterol (chol)

Fasting Blood Sugar (fbs)

Resting ECG (restecg)

Max Heart Rate (thalach)

Exercise Induced Angina (exang)

ST Depression (oldpeak)

Slope of ST (slope)

Number of Major Vessels (ca)

Thalassemia (thal)

Target: Heart disease presence (1 = disease, 0 = no disease)

Models Applied

Logistic Regression for binary classification.

Model evaluation using:

Accuracy

Confusion Matrix

ROC Curve and AUC

Feature importance analysis to identify which health indicators contribute most to predictions

Tools and Methods Used

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

EDA Techniques:

Histograms: To analyze distributions

Countplots: To check target balance

Data Cleaning:

Handling missing values (? replaced with median)

Conversion of all columns to numeric

Dropping empty or NaN rows

Modeling:

Logistic Regression with feature scaling

Steps Performed

Import Libraries:

Used pandas, numpy, matplotlib, seaborn, and scikit-learn for analysis, visualization, and modeling.

Load Dataset:

Loaded the dataset into a pandas DataFrame.

Displayed the first few rows using .head().

Data Cleaning:

Replaced ? with NaN

Converted columns to numeric

Filled missing values with median

Dropped fully empty or remaining NaN rows

EDA and Visualization:

Countplot of target variable to see distribution of heart disease

Correlation heatmap to identify important relationships

Model Preparation:

Separated features (X) and target (y)

Train-test split (80/20)

Feature scaling with StandardScaler

Model Training:

Trained Logistic Regression classifier

Predicted probabilities and class labels

Evaluation:

Accuracy

Confusion matrix (heatmap)

ROC curve and AUC score

Feature Importance:

Extracted coefficients from Logistic Regression

Ranked features by importance

Key Results and Findings

Accuracy: Typically around 80–85% for Logistic Regression on this dataset

ROC-AUC: ~0.85–0.90, showing strong model discrimination

Important Features:

Chest pain type (cp)

Max heart rate (thalach)

ST depression (oldpeak)

Exercise induced angina (exang)

Number of major vessels (ca)

Insights:

Chest pain type and heart rate are critical indicators of heart disease.

ST depression and exercise-induced angina are strong predictors of risk.
