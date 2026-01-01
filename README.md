Employee Attrition Prediction Model

Project Overview
This project analyses the IBM HR Employee Attrition dataset to identify key factors influencing employee turnover and builds an effective predictive model to forecast employee attrition. Understanding and predicting employee attrition is crucial for organisations to develop retention strategies, reduce recruitment costs, and maintain workforce stability.
Business Problem
Employee attrition represents a significant cost to organisations, affecting:

Productivity and operational continuity
Recruitment and training expenses
Team morale and organisational knowledge retention
Overall corporate performance and reputation

This analysis aims to answer critical questions such as:

What factors most strongly influence employee attrition?
Can we predict which employees are at risk of leaving?
How can organisations proactively address attrition risks?

Dataset
Source: IBM HR Analytics Employee Attrition & Performance Dataset
Characteristics:

Sample size: 1,470 employees
Features: 35 variables including demographic, job-related, and satisfaction metrics
Target variable: Attrition (binary classification - Yes/No)
Dataset type: Managed dataset suitable for HR analytics research

Key Features Include:

Employee demographics (Age, Gender, Marital Status)
Job-related factors (Job Role, Department, Job Level, Years at Company)
Compensation and benefits (Monthly Income, Stock Option Level)
Work-life balance metrics (Overtime, Work-Life Balance, Distance from Home)
Performance indicators (Performance Rating, Training Times Last Year)
Satisfaction scores (Job Satisfaction, Environment Satisfaction, Relationship Satisfaction)

Methodology
1. Data Exploration and Preprocessing

Exploratory Data Analysis (EDA) to understand data distributions and patterns
Handling missing values and outliers
Feature engineering and transformation
Addressing class imbalance in the target variable

2. Model Development

Implementation of multiple machine learning algorithms
Model comparison and selection based on performance metrics
Hyperparameter tuning using GridSearchCV
Cross-validation for robust performance estimation

3. Model Evaluation

Comprehensive evaluation using multiple metrics:

Accuracy
Precision
Recall
F1-Score
ROC-AUC


Confusion matrix analysis
Feature importance interpretation

Key Findings
The analysis revealed that the following factors are most influential in predicting employee attrition:

Overtime work patterns
Job satisfaction levels
Work-life balance
Monthly income
Years at company
Distance from home

Model Performance
The final model achieved:

Cross-validation Accuracy: ~95.94% (±0.0068%)
Test Set Accuracy: 98.00%
Strong generalisation capability with consistent performance across validation folds

Technologies Used

Python 3.x
Libraries:

pandas - Data manipulation and analysis
numpy - Numerical computing
scikit-learn - Machine learning algorithms and evaluation
matplotlib/seaborn - Data visualisation
GridSearchCV - Hyperparameter optimisation
ShuffleSplit - Cross-validation
