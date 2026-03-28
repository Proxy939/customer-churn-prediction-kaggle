# customer-churn-prediction-kaggle
Goal:
Predict whether a customer will churn (leave) or not.

👉 This is a binary classification problem
Output: 0 (no churn) or 1 (churn)

Dataset is synthetic but realistic (generated using deep learning from real churn data)
Designed for practice + experimentation (not heavy raw data cleaning)

Step-by-step ML pipeline:
EDA (Exploratory Data Analysis)
Data preprocessing
Encoding (categorical → numerical)
Missing values
Feature Engineering
Ratios (charges / tenure)
Contract risk flags
Service count features
Model Training
Start simple → Logistic Regression

Sections:

Environment & Config
Data Loading
Preprocessing
Feature Engineering
Model Training (OOF Pipeline)
Ensembling (Weighted Average + Meta-Model)
Hill Climbing
Submission
