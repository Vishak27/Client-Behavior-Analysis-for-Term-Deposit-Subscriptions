# Client Behavior Analysis for Term Deposit Subscriptions
## Overview
This project analyzes client behavior to predict term deposit subscriptions using **machine learning models**. The analysis uses the Bank Marketing dataset from the UCI Machine Learning Repository to identify key factors that influence a client's decision to subscribe to a term deposit, providing actionable insights for more effective marketing strategies.
## Dataset
- **Source**: UCI Machine Learning Repository – Bank Marketing dataset
- **Records**: 4,521 client entries
- **Features**: 16 input variables + 1 target variable (subscription status: yes/no)
- **Feature Types**: Mix of categorical, binary, and numeric data
- **Key Variables**:
  - Demographics: Age, job, marital status, education
  - Financial: Account balance, housing and personal loans
  - Marketing Interaction: Contact type, day/month of last contact, campaign details
## Features
- **Exploratory Data Analysis (EDA)** with visualizations for age distribution, job distribution, marital status vs. subscription, and call duration analysis
- **Multiple ML Models** implementation and comparison:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
- **Feature Engineering** including log-transform of balance, age and duration binning
- **Model Performance Evaluation** using accuracy, ROC-AUC, and F1 scores
- **Correlation Analysis** to identify key subscription drivers
## Technologies Used
- Python 3.x
- Libraries:
  - Pandas & NumPy for data manipulation
  - Scikit-learn for machine learning models
  - Matplotlib & Seaborn for data visualization
  - Jupyter for interactive analysis
## Implementation
### Data Preprocessing
- Label encoding of categorical features
- Standardization using StandardScaler
- Train-test split (70/30)
### Feature Engineering
- Log-transform of Balance
- Age and duration binning
- Removal of non-informative fields (e.g., Day, Month)
## Model Performances
- **Best AUC**: Random Forest (0.88)
- **Best Accuracy**: SVM (89.76%)
- **Most Interpretable**: Logistic Regression
- **Most Transparent**: Decision Tree
## Key Findings
- **Age** (higher subscription rates with older clients)
- **Job Type** (retired individuals and students show higher subscription rates)
- **Account Balance** (positive correlation with subscription)
- **Call Duration** (longer calls associated with successful subscriptions)
## Marketing Insights
- Prioritize marketing campaigns toward older and retired clients
- Utilize call duration insights after customer interactions
- Combine behavioral and demographic features for targeted marketing
- Consider longer, more detailed conversations with promising prospects
## Future Work
- Implement ensemble and boosted models for performance improvement
- Evaluate real-time deployable variables
- Refine client personas for more targeted campaigns
- Test model performance in real-world marketing scenarios
