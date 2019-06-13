Prosper Loan (exploration)
- Data-frame Explanation
Prosper loan data is gathered from 2007 to 2014. The original dataset had 81 columns and 11397
rows. During the data cleaning process, four data-frame were created:
df_clean(¡®prosper_data_ready.csv¡¯) data-frame contains cleaned the whole dataset,
loan_unclosed(¡®unclosesd_loan.csv¡¯) data-frame contains unclosed loan status data which is no fully paid
on the loan, loan_closed(¡®closed_loan.csv¡¯) data-frame contains closed loan status data which is paid off
for the loan, and prosper_date(¡®date_data.csv¡¯) contains data with timestamp index for time series
analysis.
Prosper Loan dataset was explored in univariate, bivariate, and multivariate exploration. To explore
the dataset, a lot of different graph method was used, such as count plot, heat map, scatter plot, etc.

- Univariate Exploration
Univariate exploration analyzes one variable at a time, count plot, and histogram was used for the exploration
Upper credit score was used to analyze data

credit grade C:700 was the highest count of data
There were around 2000 past due loan satus in the data
Borrower state CA had highest proportion of data adding top 10 state proportion it was roughly 55%
Most of the borrower was employed

- Bivariate Exlploration
Bivariate Exploration analyzes two variables at a time. Scatter plots, heat map, box plot, and time series were used to see the relationship between two variables.

APR and credit score had negative relationship as credit score go up APR went decrease
Estimated Loss and return had positive relationship but at some point as loss went up return decreased
APR and Credit grade had positive relation ship on the box plot as credit grade decreased APR went up
There has been data input gap between 2009-5 to 2009-07

- Multivariate Exploration
Multivariate exploration analyzes three or more variables at a time. Scatter plots were mainly used with Facet-grid to analyze data.
Borrower

APR and credit score had different pattern in each year they were all in negative relationship
however, as time flows the graph formed more organized and clear relationship
Estimated Loss and Estimated return clearly shows that credit score seperates them in order
as credit decreased loss increased

Further analyses will be processed in the future... 