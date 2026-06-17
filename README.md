# InternSpark Task 2 - Loan Approval Prediction

## Objective

Build a supervised machine learning model to predict loan approval status using borrower information. The project focuses on data preprocessing, handling class imbalance, model comparison, and business-oriented interpretation.

## Dataset

Loan Approval Prediction Case Study Dataset

## Tools & Libraries Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Matplotlib
* Seaborn
* Google Colab

## Project Workflow

### 1. Data Preprocessing

* Handled missing values
* Encoded categorical variables using Label Encoding
* Scaled numerical features using StandardScaler

### 2. Class Imbalance Handling

* Applied SMOTE (Synthetic Minority Oversampling Technique)
* Balanced the target classes before model training

### 3. Model Building

* Logistic Regression
* Random Forest Classifier

### 4. Model Evaluation

The models were evaluated using:

* Precision
* Recall
* F1-Score
* ROC-AUC

### 5. Visualizations

* Confusion Matrix
* ROC Curve
* Feature Importance Analysis

## Key Findings

* Data preprocessing improved dataset quality.
* SMOTE successfully balanced the classes.
* Random Forest captured complex patterns effectively.
* Important borrower features significantly influenced loan approval predictions.
* Model evaluation metrics helped identify the better-performing model.

## Business Interpretation

The developed model can assist financial institutions in:

* Faster loan approval decisions
* Reduced lending risk
* Improved customer experience
* Data-driven credit assessment

## Suggested Deployment Threshold

A classification threshold between **0.50 and 0.60** is recommended to balance approval rates and risk management.

## Author

P V Sreelekha

## Internship

InternSpark Internship Program
