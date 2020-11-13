# Capstone_2
Predicting SBA Guaranteed Loans Defaults

The Small Business Administration works to aid small businesses by reducing the lender risk associated with small business loans. By guaranteeing portions of small business loans, small businesses are more readily able to access crucial start-up capital from risk-averse lenders.

The dataset below presents with a target label 'MIS_Status' meant to classify whether an SBA guaranteed loan is paid in full at maturity or if the loan was charged off, thereby leaving the SBA to pick up the bill for the remaining of the loan balance, or leaving the original bank to eat the losses not covered by the SBA guarantee.

Therefore the task we have before us, is primarily one of Classification(but regression models can also be applied). We will attempt to use the provided dataset and apply a machine learning algorithm, so that we might predict a discrete label output for future SBA guaranteed loans.

Can we predict, based on observed character traits of past accounts, with statistically significant probability that an account will default on its SBA guaranteed loan? Our Target Variable will be 'MIS_Status'

Data sourced from: https://www.tandfonline.com/doi/full/10.1080/10691898.2018.1434342?scroll=top&needAccess=true

Min Li, Amy Mickel & Stanley Taylor (2018) “Should This Loan be Approved or Denied?”: A Large Dataset with Class Assignment Guidelines, Journal of Statistics Education, 26:1, 55-66, DOI: 10.1080/10691898.2018.1434342
