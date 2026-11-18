# Loan Approval Prediction Using Machine Learning

## Project Overview

This project focuses on predicting loan approval status using machine learning classification techniques. The objective is to analyse applicant information and identify patterns that may influence whether a loan application is approved or rejected.

The project uses Python for data preprocessing, exploratory data analysis, feature encoding, model building, and performance evaluation.

## Objectives

- Understand the factors associated with loan approval.
- Perform exploratory data analysis (EDA) on applicant information.
- Handle missing values and prepare the dataset for modelling.
- Apply different machine learning classification algorithms.
- Compare model performance using test accuracy and 10-fold cross-validation.
- Identify suitable classification models for loan approval prediction.

## Dataset Information

The dataset contains 614 observations and 13 columns.

The dataset includes applicant information such as:

| Variable | Description |
|---|---|
| Loan_ID | Unique loan identification |
| Gender | Applicant's gender |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Education level |
| Self_Employed | Employment status |
| ApplicantIncome | Applicant's income |
| CoapplicantIncome | Co-applicant's income |
| LoanAmount | Requested loan amount |
| Loan_Amount_Term | Loan repayment period |
| Credit_History | Credit history information |
| Property_Area | Property location category |
| Loan_Status | Loan approval outcome (Target) |

**Target Variable:**
- Y – Loan Approved
- N – Loan Rejected

## Tools and Technologies

- Python
- Pandas – Data manipulation
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine learning and model evaluation
- Jupyter Notebook – Development environment

## Project Workflow

### 1. Data Loading and Initial Exploration

- Imported the dataset using Pandas.
- Examined the dataset dimensions and sample observations.
- Checked data types and variable information.
- Identified duplicate records.
- Analysed the distribution of the target variable.

### 2. Data Cleaning and Preprocessing

- Removed duplicate records.
- Dropped the Loan_ID column because it does not provide meaningful predictive information.
- Identified missing values.
- Handled missing categorical values using mode imputation.
- Handled missing numerical values using median imputation.
- Converted categorical variables into numerical format using One-Hot Encoding.
- Encoded the target variable into binary values.

### 3. Exploratory Data Analysis

Explored applicant characteristics and their relationship with loan approval.

The analysis focused on understanding the distribution of applicant information and identifying patterns in the dataset.

### 4. Model Development

The following classification algorithms were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. AdaBoost Classifier
5. Support Vector Machine (SVM)
6. Gaussian Naive Bayes

### 5. Model Evaluation

The models were evaluated using:

- Test Accuracy
- 10-Fold Cross-Validation
- Average Cross-Validation Accuracy

These methods were used to compare the classification performance of different algorithms.

## Model Performance Results

The following results were obtained from the implemented models.

| Algorithm | Test Accuracy | Average 10-Fold CV |
|---|---:|---:|
| Logistic Regression | 78% | 81% |
| Decision Tree | 76% | 79% |
| Random Forest | 78% | 81% |
| AdaBoost | 79% | 81% |

The notebook also implements SVM and Gaussian Naive Bayes. Their results should be added to this table after confirming their output.

## Key Findings

- The classification models were able to identify patterns associated with loan approval.
- Logistic Regression and Random Forest achieved approximately 81% average cross-validation accuracy.
- AdaBoost achieved the highest test accuracy among the four models shown above, at approximately 79%.
- Decision Tree achieved 79% average cross-validation accuracy.

## Conclusion

This project demonstrates how machine learning classification techniques can be applied to loan approval prediction.

By performing data cleaning, exploratory analysis, preprocessing, and model evaluation, the project compares different classification algorithms for predicting loan application outcomes.

The analysis provides a foundation for understanding predictive modelling in financial services and banking analytics.

## Future Improvements

- Apply feature selection to identify important predictors.
- Use a preprocessing pipeline to avoid data leakage.
- Apply hyperparameter tuning to improve model performance.
- Evaluate models using precision, recall, F1-score and ROC-AUC.
- Analyse class imbalance and the cost of incorrect loan decisions.
- Develop an interactive loan prediction dashboard.

## Author

**Aastha Gurav**

M.Sc. Applied Statistics Student

**Area of Interest:** Data Analytics, Statistical Analysis, Machine Learning and Business Analytics.
