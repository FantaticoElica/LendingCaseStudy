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
- Approximately 38% of defaulters had loans that were not verified, while only 25% of defaulters had verified loans. This suggests that thorough verification plays a crucial role in reducing default rates
- About 50% of defaulters had either "RENT" or "MORTGAGE" as their home ownership status, and they often used the loan for debt consolidation. These factors are strongly associated with higher default rates
- Borrowers with employment lengths of 10+ years who chose a loan term of 60 months tend to have higher default rates. In contrast, borrowers with employment lengths between 0 to 5 years who opted for a 36-month term are more prone to defaults
- Borrowers residing in certain states, namely CA, FL, NY, NJ, and NV, are more likely to default. This trend is particularly pronounced for borrowers in specific zip codes, such as CA-945xx, NY-100xx, FL-331xx, NJ-070xx, and NV-891xx
- Approximately 8.60% of defaulters did not provide an employment title in their loan applications. This lack of an employment title appears to be associated with a higher default rate
- Borrowers falling within grade ranges B2-C2 and D2-D3 are at a higher risk of default, indicating the importance of loan grading in assessing default probabilities
- Borrowers with loan amounts between Rs5,000 and Rs1,0000 exhibit a higher tendency to default. This suggests that the loan amount may influence default rates


## Technologies Used
- Python - version 3.9.5
- Pandas - version 1.3.3
- NumPy - version 1.21.2
- Matplotlib - version 3.4.3
- Seaborn - version 0.11.2