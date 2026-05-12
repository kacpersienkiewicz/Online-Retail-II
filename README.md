# Online-Retail-II
[Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) has over a million orders from a UK e-commerce store who needs help deciding where to allocate some of their marketing budget.

## Key Metrics
* Revenue per month
* Average Order Value
* Invoice Count
* Customer Segmentation (done by RFM Analysis, which measures the recency, frequency and monetary value of a customer's purchases)

## Preparation
While cleaning the data, I made the decision to remove returns and so any records with negative or zero quantity or prices because returns would mess with customer metrics such as frequency of purchases and revenue. The goal is to look at the company's revenue trends, and returns are a concern for the company's profit margin.

## Revenue is concentrated in four months of the year
September, October, November and December accoounts for roughly 44% (46% if December 2011 is assumed to be as successful as the previous year) of total revenue for this two year period, with low points during the spring and summer. On the other hand, the 8 weakest months account for 23% of total revenue, around half of the strongest 8 months, which showcases how dominant those eight months are. 

The minimum value for each year tends to be in February during the post-holliday lull in the cycle. Overall, this makes the business seasonal, and means that it relies on having solid numbers during these four months, which could be dangerous for the business and trying to improve the revenue numbers through marketing should be considered.

![image](https://github.com/kacpersienkiewicz/Online-Retail-II/blob/main/Images/Revenue_by_month.png?raw=true)

## The Off-Season has low order values and volume
In addition to less revenue, the spring and summer months also have low average order values which could imply a lot of discount or small order sizes. In contrast, the peak months have higher average order values and volumes which means that there is still plenty of room to improve between the off-season and holiday season. 

![image](https://github.com/kacpersienkiewicz/Online-Retail-II/blob/main/Images/AOV_and_invoice_count_by_month.png?raw=true)

## 14% of Customers account for half of the revenue
The top customers for the business account for around 50% of revenue for any given month, with a peak of 59.5% in October 2011 and a low of 

![image](https://github.com/kacpersienkiewicz/Online-Retail-II/blob/main/Images/Revenue_by_customer_segment_by_month.png?raw=true)

## Conlcusion and Recommendations
