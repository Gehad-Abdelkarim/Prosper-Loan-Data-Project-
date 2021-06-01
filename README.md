README FIRST
============

Communicate Data Findings
Prosper Loan Data:

Who's Prosper?
Prosper is a peer to peer lending company that based in San Francisco, spcialized in loans and low interest rates to the borrowers.

What is the structure of your dataset?
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The data contains numeric and categorical.

What is/are the main feature(s) of interest in your dataset?
This dataset contains 81 different variable for different findings

Main figurings to find out

What's income level for the borrowers?
Does Estimated Return varies from the Actual Return?
What's the borrowers Credit Score?
Does Credit Score and Credit Rating influence the borrowers APR?
Does borrower Income has influence?
What are the Credit rating for Homeowner borrowers?
Does Lenders prefer borrowers with better Prosper Score ?
What features in the dataset do you think will help support your investigation into your feature(s) of interest?


This dataset have so much to explore:

1- IncomeRange : The income range of the borrower at the time the listing was created.
2- DebtToIncomeRatio: The debt to income ratio of the borrower at the time the credit profile was pulled. This value is Null if the debt to income ratio is not available. This value is capped at 10.01 (any debt to income ratio larger than 1000% will be returned as 1001%).
3- BorrowerRate: The Borrower's interest rate for this loan.
4- CreditGrade: The Credit rating that was assigned at the time the listing went live. Applicable for listings pre-2009 period and will only be populated for those listings.
5- ProsperRating (Alpha) : The Prosper Rating assigned at the time the listing was created between AA - HR. Applicable for loans originated after July 2009.
6- EstimatedReturn: The estimated return assigned to the listing at the time it was created. Estimated return is the difference between the Estimated Effective Yield and the Estimated Loss Rate. Applicable for loans originated after July 2009. This is on an annual percentage rate (APR).
7- ActualReturn: To see how well our note performed vs the Estimated Returns, we will derive this feature based on how Prosper calculates their Annualized Net Returns.
8- LoanStatus: The current status of the loan: 'Cancelled', 'Chargedoff', 'Completed', 'Current, Defaulted', 'FinalPaymentInProgress', 'PastDue'. The PastDue status will be accompanied by a delinquency bucket.
9- CreditScoreAve: the average between the 'CreditScoreRangeLower', 'CreditScoreRangeUpper'.
10- EstimatedEffectiveYield: Effective yield is equal to the borrower interest rate (i) minus the servicing fee rate, (ii) minus estimated uncollected interest on charge-offs, (iii) plus estimated collected late fees. Applicable for loans originated after July 2009.
11- IsBorrowerHomeowner: A Borrower will be classified as a homowner if they have a mortgage on their credit profile or provide documentation confirming they are a homeowner.


Conclusion :

By using Univariate analysis we were able to get sense of the dataset features. Then we did Bivariate and Mulitvariate analysis to find the relationship between the features.

Also we found that the Actual Rate that Prosper is miscalculated to show higher rate to attracte investors. Moreover, there was negative trend between the Credit Rating and the Estimated Interest Return. Which lead that leander like to get repaid faster so they give better interest rate for borrowers with high Credit score.