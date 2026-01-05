# Data-Science-amp-Analytics-Internship-Tasks
DevelopersHub Corporation

## Task 5: Personal Loan Acceptance Prediction

###  Objective
The objective of this project is to predict which customers are **likely to accept a personal loan offer** based on their demographic and financial attributes. The task focuses on data exploration, classification modeling, and extracting business insights from the results.

---

###  Dataset
**Bank Marketing Dataset**  
(Source: UCI Machine Learning Repository)

#### Key Features Used:
- `age` – Customer age  
- `job` – Type of occupation  
- `marital` – Marital status  
- `education` – Education level  
- `balance` – Average yearly balance  
- `housing` – Housing loan status  
- `loan` – Personal loan status  
- `y` – Target variable (Loan Accepted: yes/no)

---

###  Data Loading & Inspection
- Dataset loaded using the Pandas library
- Initial inspection performed using:
  - `.shape`
  - `.columns`
  - `.head()`
  - `.info()`
- Verified dataset for missing values

---

###  Exploratory Data Analysis (EDA)
The following visualizations were created using **Matplotlib** and **Seaborn**:
- Age distribution of customers
- Loan acceptance across different job categories
- Loan acceptance by marital status

#### Key Observations:
- Middle-aged customers show higher loan acceptance rates
- Certain job categories are more responsive to loan offers
- Married customers tend to accept loans more frequently than single customers

---

### Data Preprocessing
- Target variable (`y`) encoded into binary format
- Categorical features encoded using:
  - Label Encoding / One-Hot Encoding
- Dataset split into training and testing sets

---

###  Model Training
- Algorithm Used: **Logistic Regression**  
  *(Decision Tree can also be applied as an alternative model)*
- Model trained on the processed dataset to predict loan acceptance

---

###  Model Evaluation
Model performance was evaluated using:
- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1-score)**

These metrics helped assess the model’s ability to correctly identify customers likely to accept the loan offer.

---

###  Business Insights
- Customers with stable jobs and higher balances are more likely to accept personal loans
- Age and marital status play an important role in customer decision-making
- Marketing efforts can be optimized by targeting high-probability customer segments identified by the model

---

###  Conclusion
A classification model was successfully built to predict personal loan acceptance. The project demonstrates how customer demographic and financial data can be leveraged to support targeted marketing strategies and improve conversion rates for personal loan campaigns.

---

###  Skills Demonstrated
- Data Exploration and Visualization  
- Classification Modeling  
- Logistic Regression  
- Business Insight Extraction  
- Model Evaluation using Confusion Matrix and Accuracy  

---

###  Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
