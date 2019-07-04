# Problem-Statement-Exploratory-Data-Analysis

### __Introduction to Problem Statement__ 

You work for a __consumer finance company__ which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. __Two types__ of risks are associated with the bank’s decision:

* If the applicant is likely __to repay the loan__, then not approving the loan results in a __loss of business to the company__

* If the applicant is __not likely to repay the loan__, i.e. he/she is likely to default, then approving the loan may lead to a __financial loss__ for the company

The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, you will use EDA to understand how __consumer attributes__ and __loan attributes__ influence the tendency of default.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

1. __Loan accepted__: If the company approves the loan, there are 3 possible scenarios described below:
* __Fully paid__: Applicant has fully paid the loan (the principal and the interest rate)

* __Current__: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

* __Charged-off__: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has __defaulted__ on the loan

2. __Loan rejected__: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

### __Business Objectives__

This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast-online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who __default__ cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the __driving factors (or driver variables)__ behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.
