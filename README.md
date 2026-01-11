# DevelopersHub-Internship-Projects-
Overview

This repository contains my five Data Science & Analytics projects completed during my internship at DevelopersHub Corporation.

These projects demonstrate hands-on skills in:

Data exploration and preprocessing

Data visualization

Machine learning model building

Model evaluation and insights extraction

All projects are implemented in Python using libraries like Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

Projects
1️⃣ Task 1: Exploring & Visualizing a Simple Dataset (Iris Dataset)

Objective: Understand dataset structure and visualize relationships between variables.

Key Steps:

Loaded dataset using Pandas

Summarized data (.shape, .columns, .head())

Created scatter plots, histograms, and boxplots

Insights:

Petal length and petal width are strong indicators for species separation.

No major outliers in most features.

Notebook: Task1_Iris_Exploration/Iris_EDA.ipynb

2️⃣ Task 2: Credit Risk Prediction

Objective: Predict loan approval for applicants.

Key Steps:

Handled missing values (categorical → mode, numeric → median)

Converted Dependents column ('3+' → 3)

Encoded categorical variables using LabelEncoder

Split dataset and scaled numeric features

Trained Logistic Regression and Decision Tree classifiers

Evaluated using accuracy, confusion matrix, and classification report

Insights:

Credit history is the strongest predictor of loan approval.

Higher applicant income slightly increases approval chances.

Decision Trees capture non-linear patterns better than Logistic Regression.

Notebook: Task2_Credit_Risk/Credit_Risk_Prediction.ipynb

3️⃣ Task 3: Customer Churn Prediction (Bank Customers)

Objective: Predict which bank customers are likely to leave.

Key Steps:

Handled missing values and encoded categorical features

Trained classification models (Logistic Regression, Decision Tree)

Analyzed feature importance

Insights:

Customers with low account balance and fewer products are more likely to churn.

Targeted retention strategies can reduce churn risk.

Notebook: Task3_Customer_Churn/Customer_Churn_Prediction.ipynb

4️⃣ Task 4: Predicting Insurance Claim Amounts

Objective: Estimate medical insurance charges based on personal data.

Key Steps:

Trained a Linear Regression model

Visualized relationships of BMI, age, smoking status with charges

Evaluated using MAE and RMSE

Insights:

Smoking status has a major impact on insurance charges.

Older age and higher BMI slightly increase insurance costs.

Notebook: Task4_Insurance_Claim/Insurance_Claim_Prediction.ipynb

5️⃣ Task 5: Personal Loan Acceptance Prediction

Objective: Predict likelihood of customers accepting a personal loan.

Key Steps:

Explored features like age, job, marital status, and income

Encoded categorical features

Trained Logistic Regression and Decision Tree classifiers

Insights:

Younger customers with stable jobs and higher income are more likely to accept loans.

Marketing campaigns can be personalized based on these insights.

Notebook: Task5_Personal_Loan/Personal_Loan_Prediction.ipynb

Technologies & Tools

Programming Language: Python

Data Handling & Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn (Logistic Regression, Decision Tree, Linear Regression)

Environment: Jupyter Notebook
