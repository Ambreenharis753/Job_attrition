# 👥 Employee Attrition Analysis & Predictive Modeling

## 📌 Project Overview

This project focuses on analyzing employee attrition patterns and developing machine learning models to predict employee turnover.

The objective of the project was to identify the key organizational, behavioral, and demographic factors contributing to attrition and provide actionable insights to improve employee retention and workforce stability.

The project combines:

<B> exploratory data analysis (EDA)

interactive business intelligence dashboards

machine learning model comparison

predictive analytics </B>

to support data-driven HR decision-making.

## 🎯 Project Objectives

The main objectives of this project were to:

Analyze factors influencing employee attrition

Identify workforce trends and retention patterns

Build interactive dashboards for HR analytics

Compare multiple machine learning classification models

Select the best-performing model for attrition prediction

Provide actionable recommendations for improving employee retention

# 🛠️ Technologies & Tools Used

## Programming & Data Analysis

Python

Pandas

NumPy

## Data Visualization

Matplotlib

Seaborn

Tableau

## Machine Learning

Scikit-learn

XGBoost

## Models Used:

Logistic Regression

Support Vector Machine (SVM)

Decision Tree

K-Nearest Neighbors (KNN)

Random Forest

XGBoost Classifier

# 📂 Project Workflow

## 1️⃣ Data Cleaning & Preprocessing

Performed preprocessing tasks including:

handling missing values

encoding categorical variables

feature scaling

feature selection

preparing data pipelines for model training

## 📊 Exploratory Data Analysis (EDA)

Conducted in-depth analysis to identify patterns influencing employee attrition.

The analysis explored:

compensation trends

job levels

overtime impact

commute distance

managerial relationships

training opportunities

business travel patterns

demographic influences

# 📈 Key Insights from Employee Attrition Analysis

## 👤 Age and Attrition

Attrition rates decline significantly after age 35, indicating stronger retention among older employees.

## 🚗 Distance from Home

Employees living more than 12 km from the workplace showed higher attrition rates, suggesting commute distance impacts retention.

## 📊 Job Level

Attrition was highest among employees at Job Level 1 and decreased sharply after Job Level 3.

## 💰 Monthly Income

Employees earning below $5,000 per month showed substantially higher attrition, while attrition dropped significantly above $10,000.

## ⏰ Overtime Impact

Employees working overtime were considerably more likely to leave compared to employees with regular working hours.

## 📈 Salary Hike Percentage

Salary increases of 18% or more were associated with reduced attrition rates.

## 🏦 Stock Option Level

Employees with stock option levels 3 and 4 demonstrated significantly lower attrition.

## 🧠 Experience & Tenure

Attrition dropped sharply among:

employees with over 10 years at the company

employees with more than 20 years in the industry

## 🎓 Training Opportunities

Employees who attended 3–4 training sessions annually showed improved retention.

## 🤝 Relationship with Manager

Employees working with the same manager for more than 5 years exhibited lower attrition rates.

## 💼 Job Role Insights

Higher attrition was observed among:

Sales Executives

Research Scientists

Laboratory Technicians

Sales Representatives

## 🎓 Education Field

Employees from Life Sciences and Medical fields demonstrated comparatively higher attrition.

## ✈️ Business Travel & Department

Employees who never traveled for business and those in Human Resources showed very low attrition rates.

# 📊 Tableau Dashboard

Developed an interactive Tableau dashboard to visualize:

<B> attrition trends

salary distribution

department-wise turnover

job-level retention

overtime impact

demographic patterns </B>

The dashboard enabled:

<B> interactive HR analysis

dynamic filtering

business-friendly storytelling

executive-level workforce insights </B>

# 🤖 Machine Learning Model Development

Built and evaluated multiple classification models to predict employee attrition.

## Models Compared:

Model	Accuracy:

Logistic Regression	79.64%

SVM	82.35%

Decision Tree	78.73%

KNN	75.11%

Random Forest	85.52%

XGBoost	86.88%

## 🏆 Best Performing Model

✅ XGBoost Classifier

Accuracy 86.88%

Best Parameters

{

    'clf__learning_rate': 0.3,
    
    'clf__max_depth': 5,
    
    'clf__n_estimators': 400
    
}

The XGBoost model achieved the highest predictive performance and demonstrated strong generalization capability for employee attrition prediction.

# Business Recommendations

Based on the analysis, the project recommended:

improving compensation strategies

reducing excessive overtime

increasing employee development opportunities

strengthening managerial relationships

offering long-term financial incentives

addressing commute-related challenges

These measures can help reduce attrition and improve workforce stability.

# 🧠 Skills Demonstrated

Through this project, I demonstrated proficiency in:

exploratory data analysis (EDA)

HR analytics

predictive modeling

classification model comparison

hyperparameter tuning

dashboard development

business intelligence reporting

employee retention analysis

data storytelling

## ▶️ Future Improvements

Potential future enhancements include:

deploying the prediction model as a web application

incorporating deep learning approaches

integrating real-time HR data pipelines

adding explainable AI techniques (SHAP/LIME)

improving workforce forecasting capabilities

📬 Contact

Feel free to connect with me through GitHub or LinkedIn for collaboration, feedback, or professional discussions.
