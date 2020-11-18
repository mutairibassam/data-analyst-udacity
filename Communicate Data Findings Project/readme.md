# Prosper Loan Data Analysis
## by Bassam A. Mutairi


## Dataset

This data set contains 113,937 loans with 81 variables on each loan. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)

## Summary of Findings

The distribution of Borrowers Annual Percentage Rate looks multimodal. Most of the values are at the range of 0.05 and 0.4. The distributions of stated monthly income is highly right right skewed. Most stated monthly incomes are less than 30K, but some of them are incredibly high, like greater than 100k. Surprisingly, most of borrowers with greater than 100k monthly income only loan less than 5k dollars. So, the very large stated monthly income may be made up.

The Borrower APR is negatively associated with the loan original amount which mean the more the loan amount, the lower the APR. It also shows at different sizes of the loan amount, the APR has a large range, but the range of APR decreases with the increase of loan amount. The Prosper rating also has a strong effect on the borrower APR, which decreases with the better rating.

A surprising interaction is that the borrower APR and loan amount is negatively correlated when the Prosper ratings are from HR to B, but the correlation is turned to be positive when the ratings are A and AA. Another interesting thing is that the borrower APR decrease with the increase of borrow term for people with HR-C raings. But for people with B-AA ratings, the APR increase with the borrow term.


## Key Insights for Presentation

For the presentation, I just focus on features that could affect the borrower APR, which are original loan amount, Prosper rating. I started by showing the distribution of borrower APR and loan amount variable. Then, I showed the relationship between APR vs. loan amount. I also investigated the effect of rating on ralationship between APR and loan amount, as well as the effect of rating on relationship between borrower APR and term.
