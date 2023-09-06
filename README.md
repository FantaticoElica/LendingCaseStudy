# Project Name
> # Lending Club Loan Default Analysis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project involves the analysis of Lending Club's loan dataset to identify factors contributing to loan defaults.
## What is the background of your project?
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
## What is the business probem that your project is trying to solve?
- The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- The project aims to uncover insights into borrower attributes and loan characteristics associated with a higher likelihood of loan defaults
## What is the dataset that is being used?
- The analysis is based on the Lending Club dataset containing loan application information and loan performance data


## Conclusions
Key Factors that can be considered are 
  1. State has an good co-relation with the Purpose which can be another factor to be considered. While approving loans this combination can be taken into consideration
  2. Higher Annual Income tends to default less
  3. Higher Interest rate or Higher Loan Amount among Low Income group tend to have more defaults
  4. Loan Grades are another good factor to consider especially among Low Income Groups
  5. Employment Length and Annual Income combination is also another factor that can be looked into. If the Employment Length is higher but their Annual Income is less than the median then their defaulting is higher which 
     could mean that their living expenses are significantly more thus leading to more defaults.
  6. Borrowers Home Ownership is also another important factor to understand their monthly expenses which can lead to higher defaults

## Technologies Used
- Python - version 3.9.5
- Pandas - version 1.3.3
- NumPy - version 1.21.2
- Matplotlib - version 3.4.3
- Seaborn - version 0.11.2
