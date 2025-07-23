🔍 Loan Default Prediction using Logistic Regression
This project focuses on predicting whether a customer will default on a loan using a real-world dataset containing financial and demographic information. The goal is to build a reliable classification model that can assist financial institutions in making informed lending decisions.

📁 Dataset Overview
The dataset contains 32,586 rows and 13 columns, including:

customer_age, customer_income, home_ownership, employment_duration, loan_intent, loan_grade, loan_amnt, loan_int_rate, term_years, historical_default, cred_hist_length, and Current_loan_status (target variable).

🧹 Data Preprocessing
Removed irrelevant columns (e.g., customer_id)

Cleaned numeric columns containing special characters (e.g., $, ,, %)

Handled missing values

Converted categorical features into numeric using Label Encoding

📊 Exploratory Data Analysis (EDA)
Performed visual analysis to understand:

Distribution of loan amounts

Distribution of customer income

Relationship between loan purpose and default status

🤖 Model Building
Split the data into training and testing sets (80/20)

Trained a Logistic Regression model to classify customers based on their likelihood of loan default

Evaluated model performance using:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

✅ Outcome
Built a working pipeline from data cleaning to model evaluation

Achieved reliable performance for a basic binary classification task

Laid the foundation for more advanced modeling (e.g., Decision Trees, Random Forest, XGBoost)

📌 Tools & Libraries
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

