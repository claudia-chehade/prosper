# Advices for private investors in small loans using propser.com as example

## About the data
This analysis investigates a data set from prosper.com which is a lending platform for private investors.
The dataset includes data from 2006 until 2014 and was provided by Udacity.

## Targets of Investigation
The main target was to find strategies to help investors in avoiding losses when lending money via prosper.com.
QAs a historian I was also interested to see how the pretext of the financial crisis looked like in the mirror of private investements.

## Methodology
1. Loans Details: 
I assumed that loans which increase productivity (business, student) are more likely to be paid back than loans which only serve consumption (Home Improvements,Vacation, etc.) I explored the distribution of loans in different loan categories. I included the distribution of loans across loan categories over time to see how the overall risk was evolving. This is a useful context information for investors to recognize similiar settingsas in the financial crisis in 2008/2009.
The most useful information is about the default rates of the listing categories. Thats why I chose this as main part of my explanation.
To get better information about the default rates in each category I combined it with the state information. 

2. Borrowers Details: 
When exploring the borrowers the distribution over ratings / scores was not really surprising. I skipped it for the explanation.
Combining the ratings / scores with the DebtToIncomeRatio made it more interesting, especially when comparing distributions before and after 2009. It made clear that even after 2009 it is not a good idea to only rely on the score, since even given a high score the lender can accidently pick a borrower which might be highly indebted. So looking at the DebtToIncomeRatio is a good advice for investors.
For explanation I skipped the employment status and occupation as dead ends of my exploration.

3. Borrowers History:
The borrowers history information might contain more indicators for default risks. This would be worth to be investigated in the next step.

# Sources
https://www.lendacademy.com/prosper-review/
I had a look at the loans listed on https://www.prosper.com
