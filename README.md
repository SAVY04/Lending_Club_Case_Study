# Lending Club Case Study
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

![image](https://github.com/user-attachments/assets/2bbe8c5b-0d6f-437e-bc92-a922ee8e8332)

When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

 

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Debt Consolidation is the most common loan purpose, but Small Business Loans have the highest default risk, with Renewable Energy and Educational Loans also showing significant, though lower, risk. Understanding these varying risks can help in better managing defaults.
- Most loans are between 5000 and 10000 dollars. Borrowers with 10+ years of experience apply for larger loans and have higher debt-to-income ratios, while less experienced borrowers typically request smaller amounts. This suggests a correlation between borrower experience and loan size.
- Grade G borrowers have the highest default rates, while interest rates rise with loan grades from Grade A to Grade G. Lower-grade loans are riskier, so adjusting policies based on loan grades can improve risk management.
- Borrowers with 'Other' home ownership status have the highest default rates, followed by renters. Homeowners (Own and Mortgage) generally have lower default rates. Analyzing home ownership status helps assess borrower stability and default risk.
- 60-month loans have higher default rates than 36-month loans, with longer terms linked to increased risk. Shorter-term loans generally perform better, suggesting that re-evaluating loan term policies could help reduce defaults.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Contact
Created by Saurabh Dubey[@SAVY04] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
