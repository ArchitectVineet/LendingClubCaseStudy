# Lending Club Case Study
> Purpose of this project to analsye loan dataset to provide driving factors/variables which has significant imapct on customer defaulting on their loans and taking actions like denying such loan application, increasing interest rate, reducing loan amount etc. for such loans and saving bank from financial loss. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#Tech stack)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Lending Club lends various types of loan to urban customers. On receiving loan application , company has to make a decision to either approve the loan or reject the loan application. If a loan application is rejected and if that applicant would have repaid the loan then it is loss of business. If a loan application is approved and applicant default then it is a financial lost to company.
Lending club wants to analyse and find out the variables/data patterns which impact loan repay capability and want to use those insights to take actions on the loan application like rejecting a high probable default loan application, reducing amount for loan, changing tenure of lloan, charging higher interest rate etc.
As an analyst in the company , we have to do Exploratory data analysis and determine those variables which has clear impact on loan status.

Note: Loan rejected has not been considered in Loan Dataset.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-Loans with grade B and C has higher chances of default compared to loans with status A ,F and G
-Lending club should give more loans to people whose are source verified as they have lesser chance of defaulting on their loan.
-Loans with interest rates between 10% to 18% has highest chance of getting charged off. Interest rate should be managed to be out of this range.
-Loans grant with loan amount in range of 2000 -10000 has highest chance of getting charged off
-Lending club should give more loans to people who own a house as they have  lowest number of charged off loan.
-Loan applicants from CA ,CO and CT has higher chance of default may be due to state economy or some other state specific reason to be investigated. Lending club should come up with different loan policy for residents of these states.
-For customer with other variables indicating a possibility of charge off in future, Loan can be granted to applicant for longer duration of 60 month to reduce chances of defaulting on loan.
-Customers having dti in range of 10 to 20 has higher chance of defaulting their loan. Lending club can use this variable to reject loans or tighten loan conditions. 
-Higher number of loans which get defaulted are being given in last 4 months of an year. This could be due to pressure on bankers to meet yearly targets and lesser scrutiny of loan applications. Lending club must plan for more audits and checks in last 4 month of approved loan applications
 

  

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used

-Python library - version 3.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project has been given by Upgrad as part of our Machine Learning and AI executive PG course. Thanks Upgrad for providing this loan dataset from Lending club to analyze this data using Exploratory data analysis.


## Contact
Created by [@ArchitectVineet] - feel free to contact reach to Vineet Kumar and Raghavender B for this analysis. Currently we are using Vineet Kumar's github id to maintain project code base.


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->