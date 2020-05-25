# Dataset
I have chosen the prosper.cpom data set.

# Exploration
Target was to find strategies to help investors in avoiding losses when lending money via prosper.com.
1. Loans Details: 
I assumed that loans which increase productivity (business, student) are more likely to be paid back than loans which only serve consumption (Home Improvements,Vacation, etc.) I explored the distribution of loans in different loan categories. I included the distribution of loans across loan categories over time to see how the overall risk is evolving. This is a useful context information for investors if we remmber that situation in the financial crisis 2009.
The most useful information is about the default rates of the listing categories. Thats why I chose this as part of the explaination part.
To get better information about the default rates in each category I combined it with the state information. 
2. Borrowers Details: 
When exploring the borrowers the distribution over ratings / scores was not really surprsing. I skipped it for the explaination.
Combining the ratings / scores with the DebtToIncomeRatio made it more interesting, especially when comparing distributions before and after 2009. It made clear that even after 2009 it is not a good idea to only rely on the score, since even given a high score the lender can accidently pick a borrower which might be highly indebted. So looking at the DebtToIncomeRatio is a good advice for investors.
For explaination I skipped the employment status and occupation as dead ends of my exploration.
3. Borrowers History:
Due to the lack of time I did not explore the borrowers history information further to find more indicators for default risks.

# Feedback
Due to the lack of time I was not able to get proper feedback unfortunately.

# Sources
https://www.lendacademy.com/prosper-review/
I had a look at the loans listed on https://www.prosper.com