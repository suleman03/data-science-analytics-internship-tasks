# data-analytics-internship-tasks
# Task 3: Customer Churn Prediction (Bank Customers)

## Objective
To predict whether a bank customer is likely to leave the bank using machine learning techniques.

## Dataset Information
The dataset contains 10,000 bank customers with features such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target Variable)

## Approach

1. Data Cleaning
   - Removed unnecessary columns (RowNumber, CustomerId, Surname)
   - Checked for missing values (none found)

2. Data Preprocessing
   - Label Encoding for Gender
   - One-Hot Encoding for Geography
   - Feature Scaling using StandardScaler

3. Model Training
   - Random Forest Classifier
   - Train-test split (80-20)

4. Model Evaluation
   - Accuracy Score
   - Confusion Matrix

## Results

- Model Accuracy: 0.8665%
- Important features influencing churn:
  - Age
  - Balance
  - Number of Products
  - IsActiveMember