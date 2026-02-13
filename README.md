# Employee Retention Analysis Project

📌 Project Overview

This project analyzes employee retention data to identify key factors influencing employee turnover. Using Exploratory Data Analysis (EDA), Data Visualization, and Logistic Regression, predicting whether employees are likely to leave the company based on features like salary, department, job satisfaction, and promotions.

🔍 Key Questions Answered

What factors most influence employee turnover?
How do salary levels impact retention?
Which departments have the highest attrition rates?
Can we predict employee retention using machine learning?

📝 Google Colab Notebook Name

EmployeeRetentionAnalysis.ipynb

🔧 Technologies & Libraries Used

Python (Pandas, NumPy, Matplotlib, Seaborn)
Machine Learning (Scikit-learn, Logistic Regression)
Data Visualization (Bar Charts)

📊 Key Steps & Methodology

1️⃣ Data Loading & Preprocessing
Loaded the dataset using pandas.
Checked for missing values .
Encoded categorical variables (salary, department) using .cat.codes 

2️⃣ Exploratory Data Analysis (EDA)
Analyzed retention rates by salary, department, and job satisfaction.
Identified key trends influencing employee turnover.

3️⃣ Data Visualization
Bar Charts: Salary vs. Retention, Department vs. Retention.

4️⃣ Logistic Regression Model
Split data into training & testing sets.
Trained a logistic regression model to predict retention.
Evaluated model performance using accuracy matrix.

📈 Results & Insights
Employees with lower salaries are more likely to leave.
Certain departments (e.g., Sales, HR) show higher attrition.
Job satisfaction and promotions significantly impact retention.
Model Accuracy: 75.97% (can be improved with feature engineering).

