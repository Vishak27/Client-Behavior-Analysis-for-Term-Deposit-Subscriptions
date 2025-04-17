Client Behavior Analysis for Term Deposit Subscriptions
Overview
This project analyzes client behavior to predict term deposit subscriptions using machine learning models. The analysis uses the Bank Marketing dataset from the UCI Machine Learning Repository to identify key factors that influence a client's decision to subscribe to a term deposit, providing actionable insights for more effective marketing strategies.
Dataset

Source: UCI Machine Learning Repository – Bank Marketing dataset
Records: 4,521 client entries
Features: 16 input variables + 1 target variable (subscription status: yes/no)
Feature Types: Mix of categorical, binary, and numeric data
Key Variables:

Demographics: Age, job, marital status, education
Financial: Account balance, housing and personal loans
Marketing Interaction: Contact type, day/month of last contact, campaign details



Features

Exploratory Data Analysis (EDA) with visualizations for age distribution, job distribution, marital status vs. subscription, and call duration analysis
Multiple ML Models implementation and comparison:

Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)


Feature Engineering including log-transform of balance, age and duration binning
Model Performance Evaluation using accuracy, ROC-AUC, and F1 scores
Correlation Analysis to identify key subscription drivers

Technologies Used

Python 3.x
Libraries:

Pandas & NumPy for data manipulation
Scikit-learn for machine learning models
Matplotlib & Seaborn for data visualization
Jupyter for interactive analysis
