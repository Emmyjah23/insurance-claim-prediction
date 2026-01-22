# insurance-claim-prediction
# Insurance Claim Prediction – Capstone Project

## Project Overview
This project focuses on building a predictive model to determine whether a building will have at least one insurance claim during an insured period. The prediction is based on various building characteristics provided in the dataset.

The project was completed as a **Capstone Project Assignment**, following best practices in data cleaning, exploratory data analysis, feature engineering, modeling, and evaluation.

## Problem Statement
The target variable **Claim** is defined as:
- **1** → The building has at least one insurance claim
- **0** → The building has no insurance claim

This is a **binary classification problem**.

## Dataset Description
The dataset contains building-level information including both numerical and categorical features.

Files used:
- `Train_data.csv` – training dataset
- `Variable Description.csv` – description of variables


## Project Workflow
The project followed these key steps:

1. Data Loading and Understanding  
2. Data Cleaning and Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Building  
6. Model Evaluation and Comparison  


## Data Preprocessing
- Missing numerical values were handled using **median imputation**
- Missing categorical values were handled using **mode imputation**
- Categorical variables were encoded using **One-Hot Encoding**
- Numerical features were scaled where necessary


## Exploratory Data Analysis (EDA)
EDA was performed to:
- Understand feature distributions
- Analyze the target variable balance
- Identify relationships between features
- Detect potential multicollinearity using correlation analysis


## Models Implemented
The following models were built and evaluated:

- **Logistic Regression** (Baseline Model)
- **Random Forest Classifier**


## Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC Score

The **Random Forest model** outperformed Logistic Regression, indicating its ability to capture non-linear relationships in the data.


## Results & Conclusion
- Proper preprocessing significantly improved model performance
- Random Forest achieved better predictive performance
- The model can assist insurance companies in risk assessment and pricing decisions


## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab


## Author
**Emmanuel Odey**

Capstone Project – Data Analytics


