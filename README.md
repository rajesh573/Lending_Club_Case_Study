# Project Name
> Lending Club Default Analysis


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
	A consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- What is the background of your project?
	When a person applies for a loan, there are two types of decisions that could be taken by the company:

### 1. Loan accepted: 
	If the company approves the loan, there are 3 possible scenarios described below:

#### a) Fully paid: 
		Applicant has fully paid the loan (the principal and the interest rate)

#### b) Current: 
		Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

#### c) Charged-off: 
		Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

### 2. Loan rejected: 
	The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
- What is the business problem that your project is trying to solve?
	The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- What is the dataset that is being used?
	Details of customers with loan is used. The Shape of the loan data is: 39,717 rows × 111 columns

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Grades D to G are high risk — apply stricter filters.
- High interest and long-term loans often lead to default.
- Lower income applicants show higher risk.
- Implement risk-based pricing and improve screening for risky segments.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
### Libraries used in python 3 (ipykernal)
- pandas
- numpy
- matplotlib.pyplot
- seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was based on Course on Statistics Essentials.


## Contact
Created by [@rajesh573] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->