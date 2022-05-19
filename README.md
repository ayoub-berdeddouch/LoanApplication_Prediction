# LoanApplication_Prediction

---
If you like this project don't forget to star⭐⭐⭐ it.
---


This is application demo of the Datathon form Dphi Machine Learning Bootcamp as Advanced Track [LINK](https://dphi.tech/bootcamps/machine-learning-online-bootcamp/)

![Dphi Bootcamp](https://github.com/ayoub-berdeddouch/LoanApplication_Prediction/blob/main/dphi_bc_advanced.PNG)


[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)


# Demo

[link](https://loan-app-prediciton.herokuapp.com/)   [![Website perso.crans.org](https://img.shields.io/website-up-down-green-red/http/perso.crans.org.svg)](http://perso.crans.org/)

![Loan App](https://github.com/ayoub-berdeddouch/LoanApplication_Prediction/blob/main/loan_app.PNG)
![Loan App Predict](https://github.com/ayoub-berdeddouch/LoanApplication_Prediction/blob/main/make_pred.PNG)

# Content

A loan application is used by borrowers to apply for a loan. Through the loan application, borrowers reveal key details about their finances to the lender. The loan application is crucial to determining whether the lender will grant the request for funds or credit.

![Loan Application](https://dphi-courses.s3.ap-south-1.amazonaws.com/Datathons/loan.png)

# Problem Statement

The director of SZE bank identified that going through the loan applications to filter the people who can be granted loans or need to be rejected is a tedious and time-consuming process. He wants to automate it and increase his bank’s efficiency. After talking around a bit, your name pops up as one of the few data scientists who can make this possible within a limited time. Will you help the director out? 


# Objective

The idea behind this ML project is to build an ML model and web application that the bank can use to classify if a user can be granted a loan or not.

# Evaluation Criteria

Submissions are evaluated using F1 Score.


# Data 

## About the Data
The dataset contains information about Loan Applicants. There are 12 independent columns and 1 dependent column. This dataset includes attributes like Loan ID, gender, if the loan applicant is married or not, the level of education, applicant’s income etc. 

To load the training data in your jupyter notebook, use the below command:

import pandas as pd
```
loan_data  = pd.read_csv("https://raw.githubusercontent.com/dphi-official/Datasets/master/Loan_Data/loan_train.csv" )
```

## Data Description

* Loan_ID: A unique ID assigned to every loan applicant
* Gender: Gender of the applicant (Male, Female)
* Married: The marital status of the applicant (Yes, No)
* Dependents: No. of people dependent on the applicant (0,1,2,3+)
* Education: Education level of the applicant (Graduated, Not Graduated)
* Self_Employed: If the applicant is self-employed or not (Yes, No)
* ApplicantIncome: The amount of income the applicant earns
* CoapplicantIncome: The amount of income the co-applicant earns
* LoanAmount: The amount of loan the applicant has requested for
* Loan_Amount_Term: The  no. of days over which the loan will be paid
* Credit_History: A record of a borrower's responsible repayment of debts (1- has all debts paid, 0- not paid)
* Property_Area : The type of location where the applicant’s property lies (Rural, Semiurban, Urban)

Target:

* Loan_Status: Loan granted or not (Y, N)



## Test Dataset

Load the test data (name it as test_data). You can load the data using the below command.
```
test_data = pd.read_csv('https://raw.githubusercontent.com/dphi-official/Datasets/master/Loan_Data/loan_test.csv')
```
Here the target column is deliberately not there as you need to predict it.


# Author 

[Ayoub Berdeddouch](https://github.com/ayoub-berdeddouch)

# Licence 

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) 2020
