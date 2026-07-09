# customer-churn

# Customer Churn Prediction

## Overview
This project predicts whether a customer is likely to leave a bank using machine learning classification algorithms. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, handling class imbalance, model training, and evaluation.

## Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling with MinMaxScaler
- One-Hot Encoding for categorical variables
- Class balancing using SMOTE
- Training multiple classification models:
  - Random Forest
  - Decision Tree
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
- Model evaluation using Cross Validation and Confusion Matrix

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

## Dataset
The dataset contains customer information such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card Status
- Active Membership
- Estimated Salary

Target variable:
- **Exited** (Customer Churn)

## Project Workflow
1. Load and clean the dataset.
2. Perform exploratory data analysis.
3. Scale numerical features.
4. Encode categorical features.
5. Split data into training and testing sets.
6. Balance the training data using SMOTE.
7. Train multiple machine learning models.
8. Compare model performance using Cross Validation and Confusion Matrix.

## Results
The project compares several classification algorithms to identify the best-performing model for customer churn prediction.

