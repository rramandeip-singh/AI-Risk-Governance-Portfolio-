#  Telco Customer Churn Analysis & Prediction

##  Project Overview
This project focuses on analyzing and predicting customer churn using the **Telco Customer Churn dataset**.  
The goal is to identify key factors that influence customer churn and build insights that help improve customer retention strategies.

---

##  Dataset
- Source: IBM Telco Customer Churn Dataset
- Features include:
  - Customer demographics
  - Contract type
  - Payment method
  - Monthly & total charges
  - Tenure information
- Target variable: **Churn (Yes/No)**

---

##  Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

##  Project Workflow

### 1. Data Preprocessing
- Handled missing values
- Converted categorical variables using encoding
- Created tenure and charges groups

### 2. Exploratory Data Analysis (EDA)
- Churn distribution analysis
- Tenure vs Churn
- Payment Method vs Churn
- Contract Type vs Churn
- Internet Service vs Churn

### 3. Feature Engineering
- Converted target variable into binary format
- Applied one-hot encoding for categorical variables

### 4. Model Preparation
- Train-test split
- Feature scaling (if applied)
- Logistic Regression / Classification models

### 5. Evaluation
- Confusion Matrix
- Accuracy, Precision, Recall
- Churn risk analysis

---

##  Key Insights

- Month-to-month customers have the highest churn rate
- New customers (0–6 months) are most likely to churn
- Electronic check users show significantly higher churn
- Fiber optic customers have higher churn compared to DSL users
- Long-term customers are more stable and loyal

---

##  Business Recommendations

- Improve onboarding experience for new customers
- Promote long-term contracts with incentives
- Investigate issues in fiber optic service
- Encourage automatic payment methods
- Use churn prediction models for early retention strategies
