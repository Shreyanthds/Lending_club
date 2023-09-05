# Loan Default Prediction Case Study
![LC_logo](https://github.com/Shreyanthds/Lending_club/assets/115062429/854691d3-0e60-4ab9-b687-1086aa87acea)

## Problem Statement

### Introduction
In this case study, we apply exploratory data analysis (EDA) techniques to develop a basic understanding of risk analytics in banking and financial services. We aim to understand how data is used to minimize the risk of losing money while lending to customers.

### Business Understanding
We work for a consumer finance company specializing in lending various types of loans to urban customers. When the company receives a loan application, it must make a decision for loan approval based on the applicant's profile.

Two types of risks are associated with the bank's decision:

1. If the applicant is likely to repay the loan, not approving the loan results in a loss of business to the company.

2. If the applicant is not likely to repay the loan, i.e., likely to default, approving the loan may lead to a financial loss for the company.

The provided data contains information about past loan applicants and whether they 'defaulted' or not. The goal is to identify patterns indicating if a person is likely to default, which can be used for taking actions such as denying the loan, reducing the loan amount, or lending to risky applicants at a higher interest rate.

## Valuable Features for Portfolio and Risk Assessment

This information is valuable for portfolio and risk assessment, helping the company make informed decisions regarding lending practices. Key features to consider include:

1. `funded_amnt`: The initial loan amount funded by investors is a key factor. Higher loan amounts may pose higher default risk.
2. `installment`: Monthly loan payments are crucial. Higher installments relative to income can strain borrowers, increasing default risk.
3. `total_pymnt`: The total payment received indicates whether borrowers have met their obligations, impacting default assessment.
4. `total_pymnt_inv`: Similar to total payment, this metric considers investor contributions, revealing the overall repayment performance.
5. `total_rec_prncp`: The total principal received signifies how much of the loan amount has been repaid, influencing default predictions.
6. `total_rec_int`: Total interest received reflects a borrower's commitment to loan repayment, affecting default assessments.
7. `last_pymnt_amnt`: The latest payment amount indicates the borrower's current financial stability and potential for default.
8. `revol_bal`: A high revolving balance may indicate financial stress, affecting the ability to repay loans and increasing default risk.
9. `int_rate`: Interest rates impact affordability. Higher rates can strain borrowers, elevating the likelihood of default.
10. `annual_inc`: Borrower income plays a critical role. Lower income levels relative to loan amount can raise default risk.

## Contributors
- Shreyanth HG
- Vignesh V
