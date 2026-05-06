# Online-Retail-II
The purpose of this repository is to analyze the [Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) dataset found on UC Irvine's Machine Learning Repository, to do two things:
* Cohort Analysis on first purchsae month, repeat purchase behavior, and long-term revenue contribution.
* Find/Predict high value customers via clustering.

Both of these help determine who the high value customers a business wants to keep and cater to are, and see if they can be found ahead of time to cater to them earlier. Additionally, the cohort analysis can help figure out if there were any better periods for retention, or revenue.

## Exploratory Data Analysis
* Removed entries with missing Customer IDs
* Added a Revenue column based on price times quantity.
* Later on created 

## Cohort Analysis
* Created cohorts based on first purchase month, and then used a heat map to showcase retention.

## High Value Customer
A High Value Customer can be can be found by looking at RFM (Recency, Frequency, and Monetary Value), which is explained by an [Investopedia Article](https://www.investopedia.com/terms/r/rfm-recency-frequency-monetary-value.asp). These three values were calculated and then placed into quintiles for every Customer ID.

### Clustering


## Conclusions

## TODO
*I want to add two aspects to the cohort analysis: repeat purchase behavior, and long-term revenue contribution.
* Figure out some way to analyze the Parallelogram.