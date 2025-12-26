# Credit Risk Prediction

## Objective
The objective of this project is to predict whether a loan applicant is likely to default on a loan using historical credit data. This task focuses on data cleaning, exploratory data analysis, binary classification, and model evaluation using accuracy and a confusion matrix.

---

## Dataset
The dataset used in this project is a **Loan / Credit Risk Prediction dataset from Kaggle**.  
It contains applicant demographic information, loan details, credit history, and loan status.

Key features include:
- `person_income` – Applicant income  
- `loan_amnt` – Loan amount  
- `person_emp_length` – Employment length  
- `loan_int_rate` – Loan interest rate  
- `loan_intent` – Purpose of the loan  
- `loan_status` – Target variable (0 = Non-default, 1 = Default)

The dataset was provided in separate files (`train.csv` and `test.csv`). Only the **training dataset** was used, as it contains the target variable required for model training and evaluation.

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Approach

### 1. Data Loading & Inspection
- Loaded the dataset using Pandas
- Examined structure using `.shape`, `.columns`, `.head()`, and `.info()`

### 2. Data Cleaning
- Identified missing values in numerical columns
- Handled missing values using **median imputation**
- Ensured the dataset was clean before modeling

### 3. Exploratory Data Analysis (EDA)
- Visualized loan amount distribution using histograms
- Analyzed relationships between income and loan status using boxplots
- Examined categorical features such as loan intent and home ownership

### 4. Feature Preparation
- Encoded categorical variables using one-hot encoding
- Scaled numerical features using `StandardScaler` to improve model convergence

### 5. Model Training
- Trained a **Logistic Regression** model for binary classification
- Split the data into training and testing sets

### 6. Model Evaluation
- Evaluated performance using:
  - Accuracy score
  - Confusion matrix
  - Classification report (precision, recall, F1-score)

---

## Results

- **Accuracy:** 86%
- The model performed very well in identifying non-default cases.
- Performance on default cases was lower, which is expected due to class imbalance.
- Overall, the model provides a strong baseline for credit risk prediction.

---

## Conclusion
This project demonstrates a complete machine learning workflow for credit risk prediction, including data cleaning, visualization, feature engineering, model training, and evaluation. The results highlight the importance of exploratory analysis and proper preprocessing when building classification models for real-world financial data.

---
