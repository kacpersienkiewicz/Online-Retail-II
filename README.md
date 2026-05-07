# Online-Retail-II
[Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) includes a massive amount of orders and invoices by many customers, but by using an [RFM Analysis](https://www.investopedia.com/terms/r/rfm-recency-frequency-monetary-value.asp) the highest value customers can be found and catered to. A Cohort Analysis is similarly used to find high and low value cohorts.

## Exploratory Data Analysis
* Removed entries with missing Customer IDs
* Added a Revenue column based on price times quantity.

## Cohort Analysis
* Created cohorts based on first purchase month, and then used a heat map to showcase retention, which is based only on purchases and not returns.
* The most obvious discrepancy is that January to October 2011 was a downturn for previous customers, which is looked into by looking at the difference in sales (quantity, number of invoices) and later looking at how the prices paid compared to the modal price. It seems to be due to a larger amount of higher than mode prices.

## High Value Customer
A High Value Customer can be can be found by looking at RFM (Recency, Frequency, and Monetary Value), which is explained by an  These three values were calculated and then placed into quintiles for every Customer ID. RFM quintiles were created and used to manual segment customers into tiers of value like high and medium.

![image](https://github.com/kacpersienkiewicz/Online-Retail-II/blob/main/Images/CohortAnalysis.png?raw=true)

## Conclusions
The RFM analysis revealed high and low value customers which provides a list of customers that the business would want to cater to in order to keep.

The Cohort Analysis showcased discrepancies in the data such as the January to October 2011 downtick which was possibly due to an uptick in higher than mode prices leading to an uptick in revenue for the period but a significant decrease in sales. The downside is that without more information, it is difficult to say with certainty what the specific issue is.

