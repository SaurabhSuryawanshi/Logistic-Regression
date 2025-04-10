Heart Attack Predictions

This repository contains a dataset and machine learning models for predicting the likelihood of coronary heart disease (CHD) within a 10-year period. The dataset includes various features such as demographic information, medical history, and health metrics.
Features
The dataset includes the following independent variables:
- Demographics: male, age, education
- Lifestyle: currentSmoker, cigsPerDay
- Health History: BPMeds, prevalentStroke, prevalentHyp, diabetes
- Health Metrics: totChol (cholesterol), sysBP (systolic blood pressure), diaBP (diastolic blood pressure), BMI, heartRate, glucose
The target variable is TenYearCHD (binary: 1 = high risk, 0 = low risk).

Models Used
- K-Nearest Neighbors (KNN): Used to classify individuals based on proximity in feature space.
- Decision Tree Classifier: Helps identify key risk factors and make interpretable predictions.

Results
The models were trained and evaluated on accuracy, recall, and other metrics to minimize false negatives and improve predictive performance.

