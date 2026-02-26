# data-analytics-internship-tasks
# Task 1: Exploring and Visualizing Iris Dataset

## Objective
To understand dataset structure and visualize relationships between variables.

## Approach
- Loaded dataset using seaborn
- Used pandas for inspection
- Created scatter plot, histogram, and box plot

## Key Insights
- Petal measurements clearly separate species
- Dataset has no missing values
- Distribution appears normal for most features


# Task 2: Credit Risk Prediction

## Objective
To predict whether a loan applicant will be approved based on financial and personal details.

## Dataset Features 
- Age
- Income
- Credit_Score
- Loan_Amount
- Loan_Term
- Employment_Status
- Loan_Approved (Target Variable)

## Approach

1. Data inspection (no missing values found)
2. Label encoding for categorical variable (Employment_Status)
3. Exploratory Data Analysis (histograms and box plots)
4. Feature scaling using StandardScaler
5. Logistic Regression model training
6. Model evaluation using Accuracy and Confusion Matrix

## Key Insights

- Credit score and income significantly impact loan approval.
- Feature scaling improved model convergence.
- The model achieved an accuracy of 0.9125%.
- Logistic Regression performs well for this binary classification problem.

## Tools Used
- Python
- Pandas
- Seaborn & Matplotlib
- Scikit-learn

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

## Key Insights

- Older customers with high balances are more likely to churn.
- Inactive members have higher churn probability.
- Customers with fewer products tend to leave more often.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn