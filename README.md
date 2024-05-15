# Project Name - Lending Club Case Study
> This project utilizes the data from banking and financial services and EDA techniques are applied to understand and analyze different factors to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

### Domain Background
The company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss -  the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed).

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

### Business Problem
The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


### Dataset Information
The dataset Loan.csv contains the complete loan data for all loans issued through the time period 2007 t0 2011.
The Data dictionary describes the meaning of all the column variables.
The customers labelled as 'charged-off' are the 'defaulters'. 

## Conclusions

#### Critical factors that should affect the decision making process of the bank

1: Grades & Subgrade
2: Interest rates
3: Purpose
4: Home ownership
5: Annual income
6: Debt to Income ratio
7: Duration of loan
8: Verification status

#### Recommendations to Bank

1: People having higher grades e.g. A being higher than B,C,D have lesser chances of defaulting and can be seen as a profitable strata of loan takers.

2: People getting loans at higher rates of interest (more 10%) are at a greater chance of defaulting. Hence can be identified as a potential risk for the banks.

3: People living in Mortgaged and other sources are more likely to default rather than those having their own accommodations or rented ones.

4: People having a higher annual income (mostly 40K+) are less likely to default and hence can be put in the green zone for the bank while allocating loans.

5: People that are employed are less likely to default.

6: As the duration (term) of the loan increases the risk of loan defaulting also increases hence the bank can take a note of this.

7: The bank should always grant loans to properly verified people as it was seen during this exercise that the people with “NOT Verified” status were the most risky ones as they had the highest charged-off ratios.

8: The bank should be cautious of people purpose for debt consolidation, small buisnesses or credit card payments as risky & more prone to defaulting

## Technologies Used

-Pandas - version 2.0.3
-NumPy - version 1.24.3
-Seaborn - version 0.12.2
-MatplotLib - version 3.4.3
-Python - version 3.11.5 
-Jupyter Notebook- version 6.5.4

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence PG.


## Contact
Created by 
    - Malvika Singhal
    - Lakshaya Sharma