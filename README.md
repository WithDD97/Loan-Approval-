# Loan Approval

Banks play a crucial role in market economies. They decide who can get finance and on what terms and can make or break investment decisions. For markets and society to function, individuals and companies need access to credit.
Credit scoring algorithms, which guess the probability of default, are the methods banks use to determine whether or not a loan should be granted. This project aims to improve state of the art in credit scoring by predicting the probability that somebody will experience financial distress in the next two years.
This project aims to build a model that borrowers can use to help make the best financial decision

## Libraries used:
 - Pandas
 - Sklearn: 
 - Ploty
 - Matplotlib and Seaborn

## Machine learning Algorithms:
- Neural Network
- Xgboost
- Random forest
- SVC
- Kneighbors 

## Data Dictionary
- SeriousDlqin2yrs:	
    Person experienced 90 days past due delinquency or worse 	Y/N

- RevolvingUtilizationOfUnsecuredLines:
    Total balance on credit cards and personal lines of credit except real estate and no installment debt like car loans divided by the sum of credit limits	(percentage)

- age :	
    Age of borrower in years	(integer)

- NumberOfTime30-59DaysPastDueNotWorse:
    Number of times borrower has been 30-59 days past due but no worse in the last 2 years.	(integer)

- DebtRatio: 
    Monthly debt payments, alimony,living costs divided by monthy gross income	(percentage)

- MonthlyIncome:	
    Monthly income	(real)

- NumberOfOpenCreditLinesAndLoans:	
    Number of Open loans (installment like car loan or mortgage) and Lines of credit (e.g. credit cards)	(integer)

- NumberOfTimes90DaysLate:	
    Number of times borrower has been 90 days or more past due.	(integer)

- NumberRealEstateLoansOrLines:	
    Number of mortgage and real estate loans including home equity lines of credit	(integer)

- NumberOfTime60-89DaysPastDueNotWors:	
    Number of times borrower has been 60-89 days past due but no worse in the last 2 years.	(integer)

- NumberOfDependents:	
    Number of dependents in family excluding themselves (spouse, children etc.)	(integer)
    
## Classification problem with Imbalanced Dataset
