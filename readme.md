# Advices for private investors in small loans based on propser.com

## About the data

This analysis investigates a data set from prosper.com which is a lending platform for private investors.

The dataset includes data from 2006 until 2014 and was provided by Udacity.

## Targets of Investigation

Prosper likes to promote the fact that every investor since 2009 (Prosper 2.0) that has invested in at least 100 loans has made a positive return. (Source: https://www.lendacademy.com/prosper-review/)

The interpretation of the sentence is a bit tricky: Does it mean at least one loan got a positive return while the rest got lost or returned less than invested? Or is the total return adressed? What if we take the 100 worst loans, is there still a positive return?

To get out of this ambiguity we take a simpler question. Instead of asking: What to do to maximize returns - we take a more defensive approach. What shall an investor do to avoid losses? In time of zero interest rates provided by banks we consider an positive return already as achievement.

As a historian I was also interested to see how the pretext of the financial crisis looked like in the mirror of private investements.

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

## Results
We assume we invest 100 Dollar into 100 different loans on prosper platform - what can we do to achieve a positive return in total?

Since we now know that default rates for certain states and categories can go up to 67% we create a blacklist of the worst combinations starting with the Los Angeles Car loans.

We combine this with a whitelist of very low defaulting loans like the business credits in Idaho. Since this whitelist combinations tend to count only a few loans they likelyhood that we get one of them is very low.

A good average combination of state and category has a default rate between 20% and 25%.


But what does this mean? From our 100 invested Dollars 20 Dollar will probably be lost. Can the other 80% loans compensate that loss with their returns? For doing so, the successful loans should have a return rate of at least 25%. The maximum return rate for the worst prosper rates is 49%. As per what we saw on prosper.com medium prosper rates hat return rates around 20%. So we really doubt wether will be possible to compensate all losses with acting on medium risk levels.

For investing successfully on prosper.com we not only combine black and white lists. We need a better strategy considering combinations of prosper ratings, state, category and tendencies over time. We could also investigate the impact of other attributes of the borrower like his occupation.

# Sources

https://www.lendacademy.com/prosper-review/
I had a look at the loans listed on https://www.prosper.com