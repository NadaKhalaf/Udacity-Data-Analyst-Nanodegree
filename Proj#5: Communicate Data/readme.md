# (Dataset Exploration Title)
## by (Nada Alkhalaf)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1598802388385000&usg=AOvVaw3fxHB8k4ccM0zllrAcgHES), And this data [dictionary](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1598802388386000&usg=AOvVaw1A4JQazJP_rUmAt2yIxAiQ) explains the variables in the data set. 


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

In the exploration, I found that there was a relationship between (term and loanorginamount), (prosperscore and incomeverifiable), (prosperscore and loanorginamount) (isBorrwerHomeOwner and loanorginamount). 
(EmploymentStatus and loanstatuse): There is a number of outliers, and it looks like most of the ('Chargedoff': 1) loans are part time, also most of the retired people have (Chargedoff': 1, 'Completed': 2, 'Current': 3)
(IncomeRange and loanstatuse): Not employed are mostly ('Chargedoff': 1). the borrowers with highe range are more likly to pay there loan
(IsBorrowerHomeowner and loanstatuse)and(IncomeVerifiableand loanstatuse): the two plots are very similar, i think this feature doesn’t really affect the loan statues.
Term vs LoanStatus: This plot is very helpful, in the first plot I can see that most borrowers are in the 36-month term, and that a large number completed their loan. 
IncomeVerifiable vs LoanStatus: In the second plot I see that the data is very imbalance, most of borrowers have a verified income
EmploymentStatus vs LoanStatus: In the third plot I can see that most borrowers are employed and there is a large number of completed loans on it. 
Term effect the relationship between ProsperScore and LoanOriginalAmount And the completd loan statuse got a highe prosperscore, less risky, which is related. 



Outside of the main variables of interest, I verified the a relationship between (term and loanorginamount), (prosperscore and incomeverifiable), (prosperscore and loanorginamount) (isBorrwerHomeOwner and loanorginamount)was observed.
and the strongest one was between term and LoanOrginlAmount but it is not that strong. 

## Key Insights for Presentation

> For the presentation, I focus on just the influence of LoanStatus and the relationships between some variabels. I start by introducing the Distribution of LoanStatus, followed the heatmap of four numerical variables, and two booleans, then plot term effect on the relationship between ProsperScore and LoanOriginalAmount.
