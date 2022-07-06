# Lending Club Case Study

We work for a consumer finance company which specialises in lending various types of loans to urban customers. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

    - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

    - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
    
- When a person applies for a loan, there are two types of decisions that could be taken by the company:

    - Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

        - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

        - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

        - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
    
    - Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
    
### Business Objectives

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

 

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 



## Steps for Analysis approach
- Data Cleaning and Data Preparaiton
- Univariate Analysis
- Bivariate Analysis/Multivariate Analysis
- Observations/Summary


## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?


## Conclusions

- Borrower taking loan for 'home improvement' and have income of 60k -70k
- When grade is F and loan amount is between 15k-20k
- When the loan is verified and loan amount is above 16k
- When employment length is 10yrs and loan amount is 12k-14k 
- For grade G and interest rate above 20%
- Borrower who receive interest at the rate of 21-24% and have an income of 70k-80k
- Borrower whose home ownership is 'MORTGAGE and have income of 60-70k
- Borrower whose home ownership is 'MORTGAGE and have loan of 14-16k
- Applicants who have taken a loan in the range 30k - 35k and are charged interest rate of 15-17.5 %
- Borrower who have taken a loan for small business and the loan amount is greater than 14k


## Technologies Used
- Anaconda 2020.07
- Python 3.9
- Pandas 21.5.0
- Numpy 1.20.2
- Seaborn 0.11.2 
- Matplotlib 3.5.2 


## Acknowledgements
Give credit here.
- This project was done in order to complete Upgrad's Lending Club Case Study Assignment
- References :
    - https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html
    - https://seaborn.pydata.org/
    - https://pandas.pydata.org/docs/
    - https://www.jigsawacademy.com/understanding-credit-risk-analytics/



## Contact
Created by @ivermahimanshu - feel free to contact me!
