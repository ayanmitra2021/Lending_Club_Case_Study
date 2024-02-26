# Lending club case study
> A case study on loan data 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A case study on loan data to determine defaulters such that the lending club can minimize the risk of lending loans
- The data is cleaned by taking out the unnecessary columns, and by formatting important numeric and date columns. Various charts and graphs are produced to describe the data. A conclusion is given at the end of each analysis
- To determine how the lending club can minimize the risk while lending loans and increase profitability 
- A dataset of ~40k loan records is used for analysis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### Defaulters 
- The lending club should prefer giving loans to those who have their own house than people renting houses or having a mortgage on their home
- Although, the number of loan-takers are more in lower-middle income category, the lending club should pay caution while disbursing loan to people in this income range
- Although, the number of loan-takers are more with the rate of interest between 11% to 15%, but we can see the count from other categories is still higher
- The lending club can be cautious deciding the rate of interest for loan-takers in the income category 
- The results are a bit contradictory when it comes installment payment amount. It seems people with a smaller installment to pay are tending to default on their loan more than people with bigger installment to pay
- The lending club should recalibrate their installment payment formulas so that it stands >$600 per month
- Loan takers who typically pay a lower monthly installment with an interest rate between 10% to 17% are defaulting on their loan more than the rest of the group
- The loan term doesn’t seem to have an impact on defaulting a loan
- The lending club must be very careful granting loans to unemployed people
- The lending club must pay caution while lending loans to those people who employers are in Defense, Retail, or Postal service
- While the population of defaulters is largest in 10+ years employment length category, it is obvious that people are taking and defaulting on loan if they have <1 year of service
- The lending club need to pay caution while lending loans to people with <1 year of employment
- People with 6 to 9 years of employment length tend to be defaulting less on their loan
- The lending club need to very careful while lending loan to those who are taking it for debit consolidation 
- The lending club need to very careful while determining the loan amount and the installment amount 
- The installment amount is also correlated with annual income of the person
- The lending club must use a scoring mechanism (like credit rating) before granting a loan to its members 
- There is a large number of defaulters with a zero revolving balance has taken the loan for debt consolidation which seems obvious. But it seems a large number of defaulters with zero revolving balance also falls into the category of home improvement, major purchase, and small business. This may indicate the lending club to check purpose of  the loan and the borrowers revolving balance at the time of taking the loan, and accordingly grant or reject the loan application


### Current loans 
- 76% to 99% of all lended loan is already collected which is a good indication
- The outstanding amount to funded amount and late fee to funded amount ratios are within 0%-25% indicating a low risk profile for the lending club
- It seems borrower has paid off all accrued interest charges up to the current date. This suggests that the borrower is making timely and sufficient payments to cover both the principal amount and the interest charges, which is a positive indicator of loan performance
- It seems borrowers who have been delinquent at least once in the past 2 years are a majority paying less than $600 in installment. As a proactive measure, the lending club may communicate the late /delinquency fee policies to borrowers who typically pays less than $600 as monthly installment

### Fully paid loans 
- About 82% of all borrowers in each home ownership category have paid off their loans, which is consistent.
- Greater than 80% of all borrowers in each employment length category have paid off their loans, which also seems to be consistent. 
- A revolving line utilization rate typically denotes the ratio of a person's credit debt to their total credit limit. We can see, the median of the revolving line utilization rate for the fully paid and current loans are almost same, however it is much higher for the charged off loans. As a result the lending club may pay caution while granting loan to those borrowers whose revolving line utilization rate is higher than 50%, because they are most likely become defaulters.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- seaborn
- matplotlib.pyplot

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@ayanmitra2021] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->