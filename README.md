# bankChurnAnalysis
Project Overview
This project focuses on analyzing and predicting customer churn for a retail bank using supervised machine learning techniques. The goal is to identify key factors influencing customer churn and build a predictive model to help the bank proactively improve customer retention.

Objectives
✔ Explore customer data to uncover patterns behind churn behavior
✔ Perform data cleaning and visualization for actionable insights
✔ Identify relevant features influencing customer churn
✔ Build and evaluate machine learning models to predict churn
✔ Suggest data-driven recommendations to reduce churn

Dataset Details
Source: Kaggle 

Feature	Description:
CreditScore	: Customer's credit score (numeric)
Geography : Country of residence (categorical)
Gender	: Gender of the customer (categorical)
Age	: Age in years
Tenure	: Years as a bank customer
Balance	: Account balance
NumOfProducts	: Number of products used by the customer
HasCrCard	: Has credit card (0 = No, 1 = Yes)
IsActiveMember	: Active membership status (0 = No, 1 = Yes)
EstimatedSalary	: Estimated annual salary
Exited : (Target)	1 = Customer churned, 0 = Retained

Project Workflow

Data Cleaning & Preprocessing
1) Removed irrelevant columns: RowNumber, CustomerId, Surname
2) Encoded categorical variables (Gender, Geography)
3) Handled missing values and data types

Exploratory Data Analysis (EDA)
1) Univariate and bivariate visualizations:

Churn Distribution
1) Age, Balance, and CreditScore vs. Churn
2) Geography & Gender influence on Churn
3) Correlation heatmap to assess feature relationships

Feature Selection
1) Based on EDA insights and feature importance from models

Model Building
1) Trained models using:Random Forest Classifier
2) Evaluated with accuracy, precision, recall, F1-score, and confusion matrix

