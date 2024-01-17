# Project Name
> Upgrad EPGP AI ML Lending loan case study from Garv Daga and Pushpendra Hirwani


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
- The dataset being used in 'loan.csv' under 'loan' directory provided by Upgrad itself.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The chances of bad loans is the most for small business
- Loan amount value is inversely proportional to amount of folks asking for that particular loan amount
- The higher the Interest rates higher are the chances of an individual to default on the loan which suggests there is a higher likelihood of loan getting defaulted when loan is disbursed with higher interest rates
- As the Annual income increases the tendency of some to default decreases
- Loans taken from States 'TN' , 'NV' and 'AK' have higher probability of Defaults.
- As the publicly recorded bankcruptcies increases the Charge off/Defaulting percentage of an individual also increases which suggests there is a higher likelihood of loan getting defaulted when loan is disbursed to individual with higher publicly recorded bankruptices although we dont have a lot entries for individual with 2 publicly recorded bankruptcies
- As the dti keeps on increasing the Charge off percentage also increases which suggests there is a higher likelihood of loan getting defaulted when loan is disbursed to individual with higher dti
- An individual with home ownership status as "OTHER" and they generally take a higher loan amount and there is a very high tendency of their loan being "Charged off"
- As we move to lower employment grades the Charge off proportions keeps on increasing which suggests there is higher chance of loans being defaulted when disbursed to individual with lower employment grades
- Folks with zipcode ranging from 010xx-12xx, living around 338xx or 754xx, 622xx, 882xx-90xx have higher tendency of defaulting the loans

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Visual studio Code - version 1.0
- numpy, pandas, seaborn, matplotlib, 
- Anaconda 3 
- Python 3.11.4

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by www.kaggle.com

## Contact
Created by: [@garv-daga(Garv Daga)] & [@pozoxoxo(Pushpendra Hirwani)]