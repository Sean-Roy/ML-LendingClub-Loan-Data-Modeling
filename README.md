# ML-LendingClub-Loan-Data-Modeling
Decision Tree and Random Forest machine learning and data analysis/exploration of 2007-2010 LendingClub dataset.

Decision Tree and Random Forest modeling is utilized to predict the probability that a given borrower would pay off the loan in time.

Values in the dataset represent the below:
* credit.policy: 1 for meeting credit underwriting criteria of LendingClub.com, else 0.
* purpose: The purpose of the loan (6 unique values).
* int.rate: Interest rate of the loan, as a proportion (eg: 15% = 0.15). Riskier borrowers are assigned higher interest rates.
* installment: Monthly installments owed if load is approved.
* log.annual.inc: Natural log of the self-reported annual income of the borrower.
* dti: Debt-to-income ratio of the borrower (debt amount / annual income).
* fico: The FICO credit score of the borrower.
* days.with.cr.line: The number of days the borrower has had a credit line.
* revol.bal: Revolving balance - ie: amount unpaid at the end of the credit card billing cycle.
* revol.util: Revolving line utilization rate - ie: amount of the credit line used, relative to total credit available.
* inq.last.6mths: Number of inquiries by creditors in the last 6 months.
* delinq.2yrs: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.
* pub.rec: Number of derogatory public records (eg: bankruptcy filings, tax liens, or judgments).
