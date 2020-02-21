# Loan Approval Prediction on Czech Republic Bank data

## Problem Statement:
A bank wants to automate their loan approval process.  They have provided a semi anonymized dataset containing 606 successful and 76 not successful loans along with their information and transactions.

These loans are for existing clients 
This could be used to pre approve existing customers and market to them accordingly

## Outcomes Predictions:
33% of rejected loans were incorrectly predicted so they should’ve been approved  
and there were 2.4% of approved loans which were incorrectly predicted so loans that should’ve been rejected.

## Data Acquisition:
Pulled finance data from SQL database 

## Data Preparation: 
- For our prediction model we used different Account details: such as statement frequency. 
- Client information: such as their demographics. 
- Transaction details: the amount of money going in and out of an account. 
	- We also created other characteristics by grouping them so our model could extract better meanings with more helpful data such as number of transactions by different types: cash withdrawal, bank transfers, credited interest, etc. Also grouped balances by certain months before the initial loan date – just to see if prior history would have an effect.
  
## Modeling:
Random Forest

## Model Evaluation:
F1 score.

## Deliverable:
Presentation for marketing and loan manager 


