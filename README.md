# Credit_risk_analysis_data_analysis
Credit risk analysis data analysis - EDA


**CREDIT RISK ANALYSIS IN BANKING AND FINANCIAL SECTOR**

**Aim of the analysis:**

The aim of the analysis is to search for statistical relationships that could give us some insights about the risk of credit for both lenders and borrowers. 
Whenever a financial institution receives an application, they must decide whether to approve or disapprove the loan application based on consumer’s profile. Basically, there are two types of risks which are related to the decision. Firstly, if the loan applicant is presumed to repay the loan, then not approving the loan application will be a loss to the company. Secondly, if the applicant is not presumed to pay the loan or the applicant is most likely to default, then approving the loan application results in the financial loss to the company.
Financial institutions use credit risk analysis models to determine the probability of default of a potential borrower.
This provides information on the level of a borrower’s credit risk at any particular time. If the lender fails to detect the credit risk in advance, it exposes them to the risk of default and loss of funds. 
Lenders can rely on the validation provided by credit risk analysis to make key lending decisions on whether to extend credit to the borrower. 
Exploratory Data Analysis is done to analyse the pattern in the data. This will help the loan providing company by segregating the consumer on the basis of likely to be a defaulter or non-defaulter, and only providing loan to the one who is capable of repaying it.

**Data Source:**
https://www.kaggle.com/datasets/laotse/credit-risk-dataset

**Feature Descriptions:**

person_age: Age of the individual applying for the loan.

person_income: Annual income of the individual.

person_home_ownership: Type of home ownership of the individual.

person_emp_length: Employment length of the individual in years.

loan_intent: The intent behind the loan application.

loan_grade: The grade assigned to the loan based on the creditworthiness of the borrower.

loan_amnt: The loan amount requested by the individual.

loan_int_rate: The interest rate associated with the loan.

loan_status: Loan status, where 0 indicates non-default and 1 indicates default.

  0: Non-default - The borrower successfully repaid the loan as agreed, and there was no default.
  
  1: Default - The borrower failed to repay the loan according to the agreed-upon terms and defaulted on the loan.

loan_percent_income: The percentage of income represented by the loan amount.

cb_person_default_on_file: Historical default of the individual as per credit bureau records.

  Y: The individual has a history of defaults on their credit file.
  
  N: The individual does not have any history of defaults.
  
cb_preson_cred_hist_length: The length of credit history for the individual.

**Observations:**
1. The customer who lives in a rented house is more likely to default than the one who owns a house. 
2. Loans with debt consolidation reasons defaulted the most. Loans with education, home improvement and venture purposes defaulted the least. Overall, there is not much variations of default rate among loan intent categories.
3. Borrowers with previous default record defaulted more than those with no previous default record.

4. Customer’s age, their income and employment length (years of service) etc. has a negative effect on the loan status being default, which means the larger these variables, the less likely the person is risky. 

5. Loan interest rate and loan amount has a positive effect on loan status being default, which means the larger these variables, the more likely the person is risky.

