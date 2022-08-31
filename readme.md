# Prosper Loan Data Exploration

## Dataset

The data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. The dataset from prosper can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), with the data dictionary available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Summary of Findings

In the exploration, I found that there was a strong negative relationship between borrower rate and prosper rating. This inverse relationship showed that the higher the prosper rating, the lower the borrower rate.  This negative relationship was also observed with prosper score and income range. However, when I introduced Income as a third variable with borrower rate and prosper rating, an interesting relationship was observed as there seemed to be minimal difference in borrowers rate for lower interest ratings like HR, E & D. But when observed from the mid prosper rating (C) to the highest prosper rating (AA), there is a significant difference in borrowers rate for unemployed people when compared to employed people.  
On the other hand, a positive relationship was observed between borrower rate and loan term, as the higher the loan term, the higher the borrower rate. From the exploration, it was observed that loan term is a major determinant of borrower rate, as there is a significant decrease in borrower rate with shorter loan terms.


Outisde the main variables of interest, I verified the relationship between loan status and prosper score. Not surprisingly, borrowers in good loan standing tend to have higher prosper scores than borrowers that are delinquent on loan payments. With borrower rate introduced, it can be seen that with the mid-range prosper scores, borrowers that are delinquent (chargedoff, defaulted, Past Due) on loan payments usually have significantly higher borrowers rates whereas there seem to be a very small difference in borrowers rate with the highest prosper scores or the lowest propser score.

## Key Insights of Presentation
For the presentation, I focus mainly on just the effect of prosper score, prosper rating, loan term, and income range on borrower rate. I start by introducing the borrower rate variable, followed by the distribution of the prosper rating.

Subsequently, I use a combined box plot and violin plot of borrower rate and prosper rating. The violin plot is used as a more informative plot to show how much of a probability each propser ratings is represented on borrower rate. Afterwards, I used other visuals to show the relationsip between borrower rate and other variables.
