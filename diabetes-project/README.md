Diabetes Prediction Model

Project Overview
This project is developing a machine learning model to predict diabetes in patients based on diagnostic measurements. Early detection of diabetes is crucial for preventing serious health complications and enabling timely medical intervention. This predictive model will assist healthcare professionals in identifying at-risk individuals using readily available clinical data.
Project Status: In Progress ⚙️
Medical Context
Diabetes is a chronic metabolic disorder characterised by elevated blood glucose levels. Early identification of diabetes risk factors enables:

Preventive lifestyle interventions
Timely medical treatment
Reduction in long-term complications (cardiovascular disease, neuropathy, retinopathy)
Improved patient outcomes and quality of life

Dataset
Source: Kaggle Diabetes Dataset (diabetes.csv)
Dataset Characteristics:

Size: 2,000 patient records
Features: 8 diagnostic measurements
Target Variable: Outcome (binary: 0 = No Diabetes, 1 = Diabetes)
Class Distribution:

No Diabetes: 65.8% (1,316 cases)
Diabetes: 34.2% (684 cases)

Progress So Far


1. Data Exploration

Loaded and examined the diabetes dataset (2,000 patient records)
Conducted exploratory data analysis (EDA)
Analysed statistical summaries of all features
Assessed class distribution and balance
Identified no missing values in the dataset

2. Data Preprocessing

Applied feature scaling using StandardScaler
Split data into training and testing sets (80-20 ratio with stratification)
Prepared data for model training

3. Model Training and Evaluation
Multiple machine learning algorithms have been evaluated:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier (best performer so far)
Gradient Boosting Classifier
Support Vector Machine (SVM)
K-Nearest Neighbours (KNN)

4. Initial Model Testing

Implemented 5-fold cross-validation
Trained final Random Forest model with 100 estimators
Achieved initial performance metrics

Current Results
Random Forest Classifier Performance:

Cross-Validation Accuracy: 95.94% (±0.0068%)
Test Set Accuracy: 98.00%

The model shows strong performance and good generalisation, with consistent results across validation folds.
