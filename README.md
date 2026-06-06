# Heart Disease Prediction

## Goal

The goal of this project was to develop a machine learning model that can predict the likelihood of heart disease using patient demographic and clinical information. By analyzing medical factors such as age, cholesterol, blood pressure, and heart rate, the project aims to identify key predictors of heart disease and evaluate the effectiveness of logistic regression for healthcare risk assessment.

## Objective

Investigate the relationship between patient characteristics and heart disease status while building a predictive model that can classify whether a patient has heart disease. The project also seeks to determine which medical variables have the strongest influence on heart disease risk.

## Data Source

UCI Machine Learning Repository

https://archive.ics.uci.edu/ml/datasets/heart+disease

The dataset contains patient medical records collected from multiple healthcare institutions and includes demographic, clinical, and diagnostic variables related to heart disease.

## Data Type(s)

* Age: Integer (numeric)
* Sex: Categorical (binary)
* Chest Pain Type (CP): Categorical
* Resting Blood Pressure: Numeric
* Cholesterol: Numeric
* Fasting Blood Sugar: Binary
* Resting ECG Results: Categorical
* Maximum Heart Rate Achieved: Numeric
* Exercise-Induced Angina: Binary
* ST Depression (Oldpeak): Numeric
* Slope of Peak Exercise ST Segment: Categorical
* Number of Major Vessels: Integer
* Thalassemia Test Result: Categorical
* Target (Heart Disease): Binary (0 = No Disease, 1 = Disease)

## Restrictions

* Dataset size is relatively small (303 observations).
* Data was collected from specific medical institutions and may not represent all populations.
* The model identifies associations and predictions but does not establish causation.
* Some potentially important health and lifestyle variables are not included.

## Pros

* Well-known and widely used healthcare dataset.
* No major missing value issues after cleaning.
* Contains both demographic and clinical variables.
* Suitable for classification and predictive modeling.
* Easy to interpret using logistic regression.
* Provides meaningful real-world healthcare applications.

## Methods

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Logistic Regression
* Variable Selection
* Cross Validation
* ROC Curve Analysis
* Model Performance Evaluation

## Results

The logistic regression model successfully identified significant predictors of heart disease and achieved a cross-validated error rate of approximately 15.2%. Model performance improved substantially over the null model, demonstrating the usefulness of clinical and demographic variables in predicting heart disease risk.
