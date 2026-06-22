# Bank-Customer-Churn-Prediction

## Project Overview
This project predicts whether a bank customer will leave the bank (churn) based on customer demographics, account information, and banking behavior.

## Objective
To identify customers likely to churn and help the bank take preventive actions to improve customer retention.

## Dataset
Source: Kaggle Bank Customer Churn Dataset

Number of Records: 10,000
Features: 14
Target Variable: Exited

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Project Workflow

### 1. Data Cleaning
- Removed unnecessary columns
- Checked missing values
- Checked duplicates

### 2. Exploratory Data Analysis
- Churn Distribution
- Churn by Gender
- Churn by Geography 
- Age Distribution
- Credit Score Analysis
- Account Balance Analysis
- Products Analysis
- Member Analysis
- Tenure Analysis
- Correlation Analysis

### 3. Feature Engineering
- One-Hot Encoding
- Train-Test Split
- Feature Scaling

### 4. Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest Classifier

### 5. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

### 6. Feature Importance
- Identify top churn drivers using feature importance.

### 7. Hyperparameter Tuning
- GridSearchCV used to optimize Random Forest parameters

## Key Insights

- Germany has the highest churn rate.
- Customers aged 40-60 are more likely to churn.
- Inactive members have significantly higher churn.
- Balance and age are important churn indicators.
- Long-term customers show lower churn rates.

## Results

Best Model: Random Forest

Accuracy: 86%
ROC-AUC Score: 85%

## Author

Pakhee Shyamkunwar
B.Tech (IoT), MITS Gwalior
