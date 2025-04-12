# Loan approval prediction applying machine learning
## Project Overview
This project aims to predict loan approval outcomes using machine learning techniques. By analyzing a dataset containing various applicant features (e.g. Marital Status, Education, Applicant Income, Credit History), we train models to determine whether a loan application is likely to be approved or rejected. The goal is to assist financial institutions in making data-driven decisions while exploring the effectiveness of different machine learning algorithms.

## Dataset

Format: CSV

The dataset contains 13 features : 
1.	**Loan**:	A unique id 
2.	**Gender**:	Gender of the applicant Male/female
3.	**Married**:	Marital Status of the applicant, values will be Yes/ No
4.	**Dependents**:	It tells whether the applicant has any dependents or not.
5.	**Education**:	It will tell us whether the applicant is Graduated or not.
6.	**Self_Employed**:	This defines that the applicant is self-employed i.e. Yes/ No
7.	**ApplicantIncome**:	Applicant income
8.	**CoapplicantIncome**:	Co-applicant income
9.	**LoanAmount**:	Loan amount (in thousands)
10.	**Loan_Amount_Term**:	Terms of loan (in months)
11.	**Credit_History**:	Credit history of individual’s repayment of their debts
12.	**Property_Area**:	Area of property i.e. Rural/Urban/Semi-urban 
13.	**Loan_Status**:	Status of Loan Approved or not i.e. Y- Yes, N- No


## Objectives
1. Preprocessing the dataset by handling missing values, encoding categorical variables.
2. Training and comparing multiple machine learning models to predict loan approval outcomes.
3. Model performance evaluation using metrics like accuracy.

## Dependencies:

1. **Python 3.8**
2. **pandas**
3. **numpy**
4. **scikit-learn**
5. **matplotlib**
6. **seaborn**

## Insights & Findings
1. Correlation analysis showed that Credit_History has a high impact on Loan_Status.
2. For this classification problem the models used are: KNeighborsClassifiers, RandomForestClassifiers, Support Vector Classifiers (SVC) and Logistics Regression
3. Random Forest Classifier is giving the best accuracy with an accuracy score of 82% for the testing dataset.
