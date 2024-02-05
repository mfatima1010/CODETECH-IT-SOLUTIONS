# Credit Card Fraud Detection

## Overview

This project is dedicated to developing a credit card fraud detection model using machine learning, specifically Logistic Regression. The objective is to automate the identification of suspicious credit card transactions and mitigate the risks associated with fraudulent activities.

## Dataset

The dataset (`CreditCard.csv`) contains information about credit card transactions, with features including transaction amount, time, and other relevant details. The target variable is `Class`, indicating whether a transaction is fraudulent (1) or legitimate (0).

## Workflow

1. **Load and Preprocess Data:**

   - The dataset is loaded using pandas (`pd.read_csv`).
   - Missing values are dropped for simplicity.
   - Features (`X`) and target variable (`y`) are defined.

2. **Split Data:**

   - The data is split into training and testing sets using `train_test_split` from `sklearn.model_selection`.

3. **Standardize Features:**

   - Standardization is performed on the features using `StandardScaler` from `sklearn.preprocessing`.

4. **Train Logistic Regression Model:**

   - A Logistic Regression model is trained using `LogisticRegression` from `sklearn.linear_model`.

5. **Evaluate Model:**
   - Model performance is evaluated on the test set using accuracy, confusion matrix, and classification report.

Happy coding!
