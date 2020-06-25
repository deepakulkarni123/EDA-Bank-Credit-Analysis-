# EDA-Bank-Credit-Analysis-

When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision: 1)If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company 2)If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

The data given below contains the information about the loan application at the time of applying for the loan. It contains two types of scenarios: 1)The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y instalments of the loan in our sample, 2)All other cases: All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company): 1)Approved: The Company has approved loan Application 2)Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want. 3)Refused: The company had rejected the loan (because the client does not meet their requirements etc.). 4)Unused offer: Loan has been cancelled by the client but on different stages of the process.

This dataset has 3 files as explained below:

'application_data.csv' contains all the information of the client at the time of application. The data is about whether a client has payment difficulties.
'previous_application.csv' contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.
'columns_description.csv' is data dictionary which describes the meaning of the variables.
