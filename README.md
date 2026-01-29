# Employee-Attrition-Analysis
📊 Employee Attrition Analysis & Prediction
📌 Project Overview

Employee attrition is a major challenge for organizations, leading to increased hiring costs and loss of experienced talent.
This project focuses on analyzing employee data to understand the key factors that influence employee resignation and to predict employee attrition using machine learning classification models.

The project was developed as part of an internship project, following standard data analytics and machine learning practices.

🎯 Objective

Understand employee turnover patterns

Identify factors influencing attrition (age, salary, department, experience, etc.)

Build a classification model to predict employee attrition

Provide insights useful for HR decision-making

🗂 Dataset

Source: HR Analytics Dataset

File used: general_data.csv

Contains employee information such as:

Age

Department

Monthly Income

Job Role

Years at Company

Work Experience

Attrition (Target Variable)

🛠 Tools & Technologies

Python

Jupyter Notebook

Pandas & NumPy – Data handling

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning models

🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

Attrition distribution analysis

Attrition vs Age

Attrition vs Monthly Income

Attrition across different departments

Identification of missing values and data cleaning

Visualizations were used to better understand trends and patterns influencing employee turnover.

🤖 Machine Learning Approach

Model Used: Logistic Regression

Target Variable: Attrition

Preprocessing Steps:

Handling missing values using median imputation

Encoding categorical variables

Feature scaling using StandardScaler

Stratified train-test split to handle class imbalance

📈 Model Evaluation

Accuracy Score

Classification Report (Precision, Recall, F1-Score)

Confusion Matrix visualization

The model provides a reasonable prediction performance and helps identify employees who are more likely to leave.

📊 Key Insights

Employees with lower monthly income show higher attrition

Certain departments experience higher turnover

Employees with less experience and fewer years at the company are more likely to resign

Attrition is imbalanced, with more employees staying than leaving

🧩 Business Impact

Helps HR teams identify high-risk employees

Supports proactive retention strategies

Improves workforce planning and decision-making

🚀 Future Improvements

Use advanced models like Random Forest or XGBoost

Handle class imbalance using SMOTE

Deploy a real-time Streamlit HR dashboard

Add feature importance and explainability (SHAP/LIME)

👨‍💻 Author

Pranav Garud
Data Analytics & Machine Learning Intern
