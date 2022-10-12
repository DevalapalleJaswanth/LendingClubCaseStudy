# Lending Club Case Study
> Find and understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. And utilise this knowledge for portfolio and risk assessment.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Info
 You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

- What is the background of your project?
 EDA  Analysis

- What is the business probem that your project is trying to solve?
  Find and understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. And utilise this knowledge for portfolio and risk assessment.

- What is the dataset that is being used?
 https://raw.githubusercontent.com/DevalapalleJaswanth/LoanDataSet/master/loan.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- [int_rate, annual_inc,dti,term ] are the variables or driving factors which mainly tells about whether a borrower can go "Default" or "not".
- If "int_rate" is between 10% to 18%, mostly the borrower can go to "Default".
- For 36 months term, "int_rate" should be less than 13%.
- For 60 months term, "int_rate" should be less than 16%.
and "dti" should be between 10 and 15.(ideally lesser the dti the better)
- Good "annual_inc" greater than 50000.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - version 1.3.5
- seaborn - version 0.11.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@DevalapalleJaswanth] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->