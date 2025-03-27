# Customer Targeting marketing with Credit Card Data Case Study 
![credit card piecewise](/cluster_piecewise.png)

## About
The exploration is about using credit card user information with statistics and machine learning to create a draft for a target marketing model to help operators gain more conversion of sales for separate products they may have.
 
## Motivation
The motivation for this came from my interest in how marketing works so well to target user with correct ads and products. Using the credit card data from Kaggle, I wanted to find what quantitative factors could cause companies to reach them. The goal was to create a clustering system that could create groups and find how each demographic got split.

## Methodology

### Preprocessing data
- Uses a Kaggle dataset that includes credit card information such as purchases, balances, and credit limits.
- Preprocessing involved removing unnecessary columns and null values to prepare data for analysis.
### Data exploration 
- Used correlation map and piecewise plots to identify patterns and relationships between features.
- limited features to only one that show high linear correlation with spending and retention of buying.
![credit card piecewise](/cluster_heatmap.png)

### Model valuation and findings
- Used k means clustering to group potential features and group outlier
- Three graphs were created to visualize clusters: credit limit vs balance, credit limit vs purchases, and one-off purchases vs purchases.
- Observations were made about customer behaviors, such as spending patterns based on credit limits.

### Results
- using k mean clustering with our data I found a bit about our marketing strategy that can be used:
  - The people who purchase the most are people who conduct one off purchases.
  - Targeting people whose credit limit on their cards is between 10k-20k will have the biggest amount to spend on things.
  - Most purchases are from people who credit limit is around 7.5k -10k plus.
![credit card piecewise](/creditLimitvsBalance.png)
![credit card piecewise](/creditLimitVsPurchases.png)

