# Employee Retention Analysis

## Project Overview
This project focuses on analyzing employee attrition data to identify key factors that influence employee turnover and to build a predictive model that helps HR teams take proactive retention measures.

## Objective
- Analyze employee data to understand attrition patterns
- Perform data cleaning and exploratory data analysis (EDA)
- Build and evaluate machine learning models to predict employee attrition
- Provide actionable business insights for HR decision-making

## Dataset
- Source: Institutional project dataset
- Type: HR / Employee Attrition Data
- File: employee_attrition_raw.csv

## Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Joblib

## Project Workflow
1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering and preprocessing pipelines  
4. Model training and evaluation  

## Key Insights
- Employee experience, company size, and training hours play a major role in attrition
- Employees with fewer training opportunities showed higher churn
- Predictive models can help HR teams identify high-risk employees early

## Project Structure
Employee-retention-Prediction/
├── data/
│   └── employee_attrition_raw.csv
├── notebooks/
│   └── employee_retention_analysis.ipynb
├── images/
│   ├── 01_data_initial_inspection.png
│   ├── 02_eda_summary_insights.png
│   ├── 03_eda_univariate_analysis.png
│   ├── 04_eda_multivariate_analysis.png
│   ├── 05_model_selection_training.png
│   ├── 06_model_decision_tree_results.png
│   ├── 07_model_random_forest_results.png
│   ├── 08_model_xgboost_results.png
│   ├── 09_model_comparison_insights.png
│   ├── 10_roc_curve_comparison.png
│   └── 11_conclusion_future_scope.png
└── README.md

## Project Visuals
--Data & Initial Inspection
    ![Data](images/01_data_initial_inspection.png)
--EDA Summary
    ![EDA Summary](images/02_eda_summary_insights.png)
--Univariate Analysis
    ![Univariate](images/03_eda_univariate_analysis.png)
--Multivariate Analysis
    ![Multivariate](images/04_eda_multivariate_analysis.png)
--Model Selection & Training
   ![Model Selection](images/05_model_selection_training.png)
--Model Comparison & ROC Curve
   ![Comparison](images/09_model_comparison_insights.png)
   ![ROC](images/10_roc_curve_comparison.png)
--Conclusion & Future Scope
   ![Conclusion](images/11_conclusion_future_scope.png)
