# Lending Club Case Study
> Upon receiving a loan application, the business must decide whether to approve the loan based on the applicant's profile. Granting the loan could result in a loss of money for the company if the borrower is not likely to repay the debt, or if default is probable. The purpose of the analysis is to identify the crucial variables that are solid indicators of loan defaults so that those making decisions can minimize the likelihood of default risk by utilizing them to accept or reject loan applications..


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Background

> Consumer financing company that specializes in providing urban clients with a range of loans. Upon receiving a loan application, the business must decide whether to approve the loan based on the applicant's profile. Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. If the lender is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss.

### Business Problem
> Assess the data and identify the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

## About Dataset
It contains the complete loan data for all loans issued through the time period 2007 to 2011. If the loan requests from applicants were turned down by the company, then there will be no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- These are the key variable which influences default status -int_rate, term, grade, subgrade, annual_inc, purpose and addr_state
- These are the correlated variables in the dataset –int_rate & grade,  installment & funded_amnt_inv




## Technologies Used
- Python - version 3.11.3
- pandas  - version 2.1.3
- numpy   - version 1.26.2
- matplotlib - version 3.8.2
- seaborn - version 0.13.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
-  This research was motivated by IIIT-B, for the Machine Learning and Artificial Intelligence course

## Contact
Created by [@kiranupgrad] - feel free to contact me!


