# Prosper loans dataset Investigation

## by Artyom Chernyaev


## Dataset

This data set contains information on peer to peer loans facilitated by credit company Prosper. There are 113,937 loans with 81 variables. For the purpose of this investigation I've taken the following variables: Term, LoanStatus, BorrowerRate, ProsperRating (Alpha), ListingCategory (numeric), EmploymentStatus, DelinquenciesLast7Years, StatedMonthlyIncome, TotalProsperLoans, LoanOriginalAmount, LoanOriginationDate, Recommendations and Investors.


## Summary of Findings

<ul>
    <li>Prosper ratings are almost normally distributed. Distribution of monthly stated income is very awkward: with a lot of outliers and very large range of values. Most loans are below 15 thousand, seems like most loans are increments of 5 thousand. Prosper rating D is the most frequent rating among defaulted credits.</li>
    <li>Default credits tend to be given to individuals with lower rating. Business and home improvement seems to be riskier categories. The borrower rate tends to be higher for defaulted credits. Long term (60 months) credits are riskier than short term (12 months). Borrower rate for individuals with low rating is higher. High monthly income corresponds to higher rating. Employment status of individuals with lower ratings tends to be 'Not employed', 'Self-employed', 'Retired' or 'Part-time'.</li>
    <li>Defaulted credits tend to be larger than completed for all Prosper ratings except the lowest ones.</li>
</ul>


## Key Insights for Presentation

I've chosen key plots with high data-to-ink ratio for the presentation. The plots I've chosen shows distribution of main variables, Loan status, monthly income, Prosper rating and I've tried to tell a story what are major predictors for loan status and Prosper rating variables.