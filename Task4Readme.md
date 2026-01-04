# Data-Science-amp-Analytics-Internship-Tasks
DevelopersHub Corporation

## Task 4: Predicting Insurance Claim Amounts

###  Objective
The objective of this task is to predict **medical insurance claim amounts** based on personal and lifestyle information using a **Linear Regression model**. This task demonstrates regression modeling, feature analysis, and model evaluation using error metrics.

---

###  Dataset
**Medical Cost Personal Dataset**

#### Features:
- `age` – Age of the individual  
- `sex` – Gender (male/female)  
- `bmi` – Body Mass Index  
- `children` – Number of children/dependents  
- `smoker` – Smoking status (yes/no)  
- `region` – Residential region  
- `charges` – Medical insurance cost (Target Variable)

---

###  Data Preprocessing
- Verified dataset for missing values (none found)
- Encoded categorical variables:
  - Label Encoding for `sex` and `smoker`
  - One-Hot Encoding for `region`
- Separated features and target variable

---

###  Exploratory Data Analysis
- Correlation analysis using a heatmap
- Visualized relationships between:
  - BMI and insurance charges
  - Age and insurance charges
  - Smoking status and insurance charges

Key insights:
- Smoking status has a strong positive impact on insurance charges
- Higher BMI and increasing age are associated with higher medical costs

---

###  Model Training
- Algorithm Used: **Linear Regression**
- Dataset split into training and testing sets (80/20 split)
- Model trained using scikit-learn

---

###  Model Evaluation
The model performance was evaluated using:

- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  

These metrics measure prediction accuracy and the magnitude of prediction errors.

---

###  Feature Importance
Linear Regression coefficients were analyzed to understand feature influence:
- Smoking status is the most significant contributor to higher insurance charges
- BMI and age also play important roles in cost prediction

---

###  Conclusion
A Linear Regression model was successfully implemented to estimate medical insurance claim amounts. The analysis shows that lifestyle factors, particularly smoking, have a major impact on insurance costs. The model demonstrates reasonable predictive performance and provides clear insights into the factors influencing medical expenses.

---

###  Skills Demonstrated
- Regression Modeling  
- Categorical Feature Encoding  
- Feature Correlation & Visualization  
- Model Evaluation using MAE and RMSE  
- Interpretability of Linear Regression  

---

###  Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
