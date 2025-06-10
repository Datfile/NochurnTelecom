Telecom Churn Prediction Project
Project Overview
This project aims to help a telecom company ("No-Churn Telecom") reduce customer churn by identifying key factors influencing customer migration and predicting at-risk customers. The solution involves machine learning models to predict churn risk and flag high-risk customers for targeted retention campaigns.

Business Context
No-Churn Telecom is facing increasing competition in the European telecom market, with churn rates exceeding 10% despite tariff reductions and promotional offers. The company wants to leverage machine learning to:

Understand variables influencing customer churn

Create churn risk scores to drive retention campaigns

Introduce a predictive "CHURN-FLAG" variable (YES/NO) to identify at-risk customers

Technical Implementation
Data Processing
Cleaned and preprocessed telecom customer data

Handled categorical variables (international_plan, voicemail_plan)

Removed irrelevant columns (phone_number, state)

Converted target variable (churn) to binary format

Exploratory Data Analysis
Analyzed feature distributions and correlations

Examined churn rates across different customer segments

Identified key features influencing churn

Machine Learning Model
Implemented Random Forest classifier

Addressed class imbalance using SMOTE oversampling

Achieved strong performance metrics:

Accuracy: 94%

Precision (churn class): 77%

Recall (churn class): 80%

F1-score (churn class): 78%

Key Features
The model identified these as most influential for churn prediction:

Customer service calls

Day minutes

International plan

Day charge

Voicemail messages

Outputs
Generated churn risk scores (probability of churning)

Created binary CHURN-FLAG predictions (YES/NO)

How to Use
Clone the repository

Install required dependencies (pandas, scikit-learn, imbalanced-learn, etc.)

Run the Jupyter notebook Churn_Project_Full_Updated.ipynb

The model can be deployed to:

Flag high-risk customers in CRM systems

Trigger targeted retention campaigns

Prioritize customer service for at-risk accounts

Business Impact
This solution enables No-Churn Telecom to:

Proactively retain customers likely to churn

Optimize marketing spend by focusing on high-risk segments

Improve customer satisfaction through targeted interventions

Reduce overall churn rate and maintain competitive edge

Future Enhancements
Implement real-time churn prediction

Develop personalized retention offers

Integrate with customer service systems for automatic ticket prioritization

Expand feature set with additional customer behavior data
