# Online-Retail-II
[Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) includes a massive amount of orders and invoices by many customers, but not all of them are as valuable. Some customers are recent, and frequent big spenders and others are not. 

The purpose here is to find out who these valuable customers are by using [RFM Analysis](https://www.investopedia.com/terms/r/rfm-recency-frequency-monetary-value.asp) and a Cohort Analysis to find trends to investigate.

## Exploratory Data Analysis
* Removed entries with missing Customer IDs
* Added a Revenue column based on price times quantity.

## Cohort Analysis
* Created cohorts based on first purchase month, and then used a heat map to showcase retention, which is based only on purchases and not returns.
* The most obvious discrepancy is that January to October 2011 was a downturn for previous customers, which is looked into by looking at the difference in sales (quantity, number of invoices) and later looking at how the prices paid compared to the modal price. It seems to be due to a larger amount of higher than mode prices.

## High Value Customer
A High Value Customer can be can be found by looking at RFM (Recency, Frequency, and Monetary Value), which is explained by an  These three values were calculated and then placed into quintiles for every Customer ID. RFM quintiles were created and used to manual segment customers into tiers of value like high and medium.

## Conclusions
The RFM analysis revealed high and low value customers, and the Cohort Analysis showcased discrepancies in the data such as the January to October 2011 downtick which was possibly due to an uptick in higher than mode prices leading to an uptick in revenue for the period but a significant decrease in sales.

It also showcased other periods of below or above average value cohorts which could exist due to similar differences in price distribution.
