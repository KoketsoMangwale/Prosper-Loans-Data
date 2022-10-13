# Proper Loans Data Exploration
## by Koketso Mangwale


## Dataset


In this project I will explore and analyse the loans data from Prosper from
Quarter 4 of 2005 to Quarter 1 of 2014 in the USA.  
The dataset is made up of 113 937 loan observations and 81 variables stored in a CSV file.

The Prosper Loan Data is made up of the borrower credit profile, location, employment, 
income, payment history, loan information, borrower's credit score change over time 
as well as loan investment information. 

This project will demonstrate the exploration through visuals of univariate and multivariate variables. 

The detailed description of each column can be found [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

Through the loan analysis, I observed that there is a strong positive correlation between 
Annual Percentage Rate (APR) and interest rates.There is a high concentration of loans extended to 
full-time employed borrowers. Majority of the borrowers take out short and long term loans and have a low DTI ratio.

Also, APR and Prosper score have a negative correlation. The APR lowers when Prosper score gets higher. 
Interestingly there is standout loans having a low score with a low APR or a high score with a high APR. 
It also seems homeownership does not influence the loan's APR.


## Key Insights for Presentation

- Focus first on the distribution of APR, interest rates, and Debt to Income (DTI) ratio.
- Thereafter, I plot the frequency or proportions of categorical features: 
IncomeVerifiable and LoanStatus.
- Lastly, I look at the influence of Prosper Ratings on APR by homeownership and by loan term. Using a scatter plot of the two quantitative features and thereafter using stacked bar plots to add homeownership and loan term.  

`Files found in this directory`
- Part_I_exploration.ipynb
- Part_II_slide_deck.ipynb
- Part_I_exploration.html
- Part_II_slide_deck.html
- prosperLoanData.csv: Loans dataset
- README.md