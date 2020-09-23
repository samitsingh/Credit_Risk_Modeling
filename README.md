# Credit_Risk_Modeling
### Predicting Probability of Default of a Potential Borrower

# Project Summary
This project will predict whether a borrower will default a loan or not based on his/her income, credit history, age, Loan Amount etc. This project will help the Financial firms, to process the borrower's information before making a decision. This project will apply machine learning and business rules to reduce risk and ensure profitability of financial firms.

Let's take an example of 2 applicants who had applied for a loan of 1000$ each. Financial firm process both application manually.

Applicant A :- Ideally his application should be rejectd based on his financial condistion, But financial firm approves his loan and released 1000 dollars loan to him. Later that applicant did not repaid the loan and got defaulted. In this case the total amount of loss of bank is *1000$*. 

Applicant B :- Ideally his application should be approved based on his good financial condition, But financial firm rejects his loan. In this case financial firm has lost the interest amount ex. 70$, which they had earned.

The financial firm will be in more debt, if they approves a defaulters loan rather then rejecting a non-defaulters loan. In other words giving a loan to a bad customer marked as a good customer results in a greater cost to the financial firm than denying a loan to a good customer marked as a bad customer.

In this project, we are developing a automated process, which will approve/reject Loan applications, based on different factors. It will save a lot of time of the financial firm which was spent on manual process and help them to reduce the human errors and save Banks money by reducing the loan to defaulters.

## 1. Introduction
The training data is in one CSV file, which contains features and the target variable. The test file contains features for which we need to predict the whether borrower will default a loan or not. Following are the features and their descriptions:

* Loan_ID: The loan id of application. It is unique for every applicant.
* Gender: The gender of every applicant.
* Married: Marital status of every applicant.  
* Dependents: The number of dependents every applicant has.
* Education: Education of every applicant 'Graduate' or 'Not Graduate'.
* Self_Employed: Whether a person is 'self employed' or not.
* ApplicantIncome: The annual income of every applicant.
* CoapplicantIncome: The annual income of every co-applicant
* LoanAmount: The amount of loan requested by applicant.
* Loan_Amount_Term: The number of months taken to repay the loan.
* Credit_History: The credit history of every applicant.
* Property_Area: The location where the property of applicant is located like 'urban', 'semiurban', 'rural'.  
* Loan_Status: The target variable, whether loan application is approved or rejected.
 

## Loss Given Default (LGD)
Loss given default (LGD) refers to the amount of loss that a lender will suffer in case a borrower defaults on the loan. For example, assume that two borrowers, A and B, with the same debt-to-income ratio and an identical credit score. Borrower A takes a loan of $10,000 while B takes a loan of $200,000.

The two borrowers present with different credit profiles, and the lender stands to suffer a greater loss when Borrower B defaults since the latter owes a larger amount. Although there is no standard practice of calculating LGD, lenders consider an entire portfolio of loans to determine the total exposure to loss.
