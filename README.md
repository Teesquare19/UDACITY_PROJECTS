# Udacity-Data-Visualization: Prosper Loan

## by Titilope Onabajo


## Dataset Overview

> Prosper is a P2P lending platform that allows investors to choose among personal loans to invest in. They do that by considering a number of factors, which include a custom calculated Prosper Score that represents the risk for each loan. The higher the score, the lower the risk, and the lower the interest rates paid by the borrower to the investors. 


The data process can be split into 3 phases, which are:
* Using Data Wrangling process [Gathering, Assessing, Cleaning]
* Using Exploratory and Explanatory Data analysis
* Visualize data using [ Univariate plots, Bivariate Plots, Multivariate Plots]


## Summary of Findings

> The most frequent APR for borrowing is 30%, followed by 15%,16% and 20% respectively. 
> A very high percentage of borrowers are employed. 82.2%. This is a good metrics for the loan company, as employment status is a very important metrics of determining borrowers credibility in obtaining loans and the amount that can be lent to each borrower. 
> 62% of people who borrow from Prosper Loans earn between 0 - 75,000, and 30% earn above 75,000; whilst the 8% remaining fall within 0, not employed and Not displayed.
> Largely the debt to Income ratio of borrowers concentrates around the 13% - 23%, after which there is a decline in the distribution except at 34%, 41% and 47%.
> The distribution above depicts that the most common rating is C, while on an overall level credit ratings A,B,C and D account for 74%. It can also be inferred that while the ratings increase sporadically between AA and A is because AA is the highest ratings and hence the scutiny and criteria to be fulfilled to attain that credit rating. Also, from Credit rating C, the numbers begin to decline.
> The lower the credit rating of a borrower, the higher the APR on loan to be incurred. Borrowers with lower credit ratings of E, HR tend to pay more interests over 20% on each loan obtained.
>  The loan status history reveals less than 5% default status; this depicts that the that the company has a good loan recovery structure in place. Almost 50% of total loan disbursed are current loans still being serviced, while 33% has been completed. 
> The distribution seen above provides a broad insight into the distribution of the loan term disbursed. 77% of the laon period is usually for 36 months whiile 21.5% is 60 months and 1.4% is within a year.
>  The distribution of the loan amount frequently borrowed and disbursed as revealed through histograph showed a rightly skewed data, with a large part of the data lying between 0 - 15,000. It can be deduced that 5,000 is the most disbursed loan amount, followed by 15,000 and 10,000 respectively.
> Most of the applicants are from the CA state, followed closely by TX,NY,FL and IL being the Top 5 states where there loan applicants resides.
> The relationship between the borrower's rate and employment status was explored, People who are employed don't necessarily have lower rate. But unemployment does have the highest median rate at almost 30% and higher distribution count of loan application at rates above the median.
> Considering the income range and borrower's rate as well, we can identify almost similar pattern especially for the not employed category. Most likely than not, Prosper Loan determines the rate based on employment status and income range.
> Considered Borrower APR against Loan term reveals that there is higher data points 60 months than an other category. However, the median rates for 36 months and 60 months are not so far apart, with 12 months slightly higher than the other 2 terms. It is interesting to see that 12 month period seems to have a wide and almost even range of APR rate distribution. 
> The scatterplot between Loan Original Amount and Borrower Rate depicts a weak negative relationship between the 2 variables.It seems Prosper Loan reduces the rates as the loan amount increases.
> Borrower rate has a strong negative correlation with Proper ratings, weak negative correlation with Monthly Income and weak positive correlation with Debt to Income ratio.
> High rating A(A), the borrowers has the lowers APR, while the patterns also shows the lowerest rating(HR) of borrowers have the highest APR.
> It is very interesting in each income range what the loan amount looks like when compared to the income range of the borrowers and time period of the loan. 36 month tenure period stands to be the most dominant period across all income range. However, we begin to notice a break from the norm as the loan amount begins to increase across ranges, especially between $25,000 to above 100,000, at this point and above loan amount of $10,000, loan tenure of 60 mon seems to be almost at par with 30 months.


## Key Insights

> People prefer to take loans with 36 months term, as it has the highest frequency and wider Borrower APR range
> After exploring different variables related to BorrowerAPR using Heatmap; ProsperScore has the strongest relationship with Borrower's APR (negatively correlated). 
> The plot created multiple histogram plots (BorrowerAPR vs ProsperScore) on different letter ratings. The plots showed the lowerest rating(HR) of borrowers received the highest APR percentage, and borrowers with highest rating (AA) received the lowerst APR percentage.


## Resources
- Prosper data dictionary[https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0]
- matplitlib documentation
- seaborn documentation
- Example Project from Udacity