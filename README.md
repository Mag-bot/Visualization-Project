# Prosper Loan Data Exploration
## by Magon Bowling


## Dataset

The Prosper Loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, credit score ranges, borrower income, employment status, and many others.  I chose to explore the following features in the dataset:

* Term
* ListingCategory
* BorrowerState
* EmploymentStatus
* EmploymentStatusDuration
* IsBorrowerHomeowner
* CreditScoreReportLower
* CreditScoreReportUpper
* DebtToIncomeRatio
* IncomeRange
* StatedMonthlyIncome
* LoanOriginalAmount
* MonthlyLoanPayment

With a copy of these selected variables, I cleaned the data for quality and tidiness issues before I began working on the exploration of single variables and relationships between two or more variables.  


## Summary of Findings

#### Univariate Exploration
I discovered in the univariate exploration the three year term loans were the most popular of the three options: 12 month, 36 month or 60 month.  The Debt Consolidation category was abundantly more popular than any other 20 loan listing categories.  The employment status duration histogram revealed that the highest count of individuals was during the shortest time in employment and progressively decreased over time.  I did try a log scale for the employment durations.  Both employment status duration charts reflected the same conclusion of a decrease in count over time.  I was not surprised that there were slightly more homeowners who borrowed, but I was surprised that credit ranges were quite normally distributed.  I wanted to visualize stated monthly incomes in both the histogram and box plot and found that the majority of monthly incomes fall within `$3200` and `$6800`.  The distribution for stated monthly incomes was right-skewed, as well as the debt to income ratio histogram.

#### Bivariate Exploration
In the exploration of two features, the shorter term loans have smaller loan amounts and monthly loan payments, as should be expected.  It also should be expected that lower credit score ranges would have smaller loan amounts and monthly loan payments.  I discovered a fairly consistent distribution among the many different states with the exception of a few in regards to loan amounts and payments.  I did discover diversity in the loan amounts and payments given listing categories.  It appeared that homeowners had greater loan amounts and monthly loan payments.  Higher incomes were found more likely with homeowners as well.  I did find less diversity with credit score ranges and stated monthly incomes.  I believe I discovered that long term employment is not the most beneficial.  Working into newer positions with higher pay more frequently seems to be the better way to go because loans are given just as readily to individuals with short employment durations as longer employment durations.  There is a linear relationship between loan amounts and monthly loan payments.  Stated monthly income ranges were most abundantly between 0 and 20K with monthly loan payments between 0 and 1K mostly.  Employment status can range to as long as 60 years or more.

I think that I appreciate the relationships between owning a home and credit scores, income range, and loan amounts.  I used several box and violin plots that allowed me to see how loans compare across states, listing categories and various ranges, like credit score and income.  This was an exploration full of relationships and insight.

#### Multivariate Exploration
In this section I was able to explore more than two features together.  I found that homeowners seem to have less debt to income ratio as compared to non-homeowners.  There was a much greater chance of having a higher debt to income ratio with a low income.  The higher the credit score range, the lower the debt to income ratio.  There is a correlation between credit score range and income range for loan amounts. Those who have higher incomes also have higher credit scores and borrow larger sums of money.  I also found that the income ranges revealed a linear regression between employment status durations and debt to income ratios.  The lowest range had the greater slope, followed by each consecutive income range.  The greater two income ranges are relatively the same.  However, both 'Not-employed' and 'Not displayed' revealed a negative correlation.

I think debt to income ratio strengthened other features, such as employment and income.  I think comparing homeowners and non-homeowners was an interesting comparison.  I could have gone several directions with this exploration and found insightful features of interest.  I was probably most interested in the point plots with regards to the credit score ranges.  I thought it was interesting to see the same curve or increase with regards to the term lengths and loan amounts.  I was also surprised to see such error bars on the plot with homeowners and debt to income ratio for each credit score range.  It makes sense that the majority of individuals would be within the credit range of 640 and 800.  What is interesting to me is the large range or individuals with debt ratios in low or high credit scores.  

## Key Insights for Presentation

My investigation is the relationships between homeowners, their employment status durations and incomes and their impact on debt to income ratios and credit score ranges.  As I strive to make my own well-informed financial decisions, I find that data is honest.  I want to know more about how employment impacts individuals owning their own home and living with debt.  Do individuals who earn more money have less debt to income ratio?  Do individuals who make more money own their own home?  Do individuals with higher incomes have higher credit scores and borrow more money?  My investigation will strive to answer those questions.

My analysis and visualizations will focus on the following key features: 1. Employment Status Duration, 2. Is Borrower a Homeowner, 3. Income Range, 4. Credit Score Range, and 5. Debt to Income Ratio.  I will lead you through my investigation systematically, starting with single variables followed by relationships between two and then three features.
