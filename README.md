# Bachelor-Thesis
This repository contains the Bachelor thesis in statistics and data analysis by Johannes Hedström and [Mikael Montén](https://github.com/orednilserik).


# Mixed media model for marketing
## The relationship between conversion in number of new accounts and spending on marketing channels


##  Abstract 
This academic thesis, conducted for CTRL Digital, a digital marketing agency, explores the spending on
various marketing channels and their impact on the number of new accounts for an unnamed company in the
finance and loan services industry. The objective is to statistically model the relationship between spending
and outcomes to assist the company in evaluating the effectiveness of their marketing budget and investigate
whether a budget change would result in increased response and more new accounts. Additionally, this research
is of interest to CTRL Digital, as a generalizable model applicable to different companies would expand their
product offerings.
Data was collected from various data sources using BigQuery and aggregated at a daily level. Common variables
such as spending and the number of new accounts were combined into a dataset. Three types of transformations
were applied to the spending variables to capture any carryover effects of marketing on the number of new
accounts. External variables considered to affect the frequency of new accounts were also included. Subsequently,
11 different XGBoost models were fitted with the applied transformations, and the top three models were
selected. The chosen models included one without any transformation, one with a decay rate transformation,
and one with a proportion transformation of the variables.
The results revealed non-linear relationships between marketing spending and the number of new accounts for
the company. However, the models either exhibited overfitting to the training data and insufficient observations
which hindered the ability to draw reliable conclusions for all marketing channels.
For the company’s three largest channels, the results showed that Google provides the most effect when it
accounts for approximately 10 percent of the budget, while Meta and Affiliate yield optimal results at around
25 percent each, assuming the overall marketing budget is relatively high. At a share of approximately 60
percent of the current budget, Affiliate also demonstrated a significant increase in the number of new accounts,
even though the total expenditure was low.




