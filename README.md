# Online-Retail-II
[Online Retail II](https://archive.ics.uci.edu/dataset/502/online+retail+ii) has over a million orders from a UK e-commerce store who needs help deciding where to allocate some of their marketing budget.

## Key Metrics
* Revenue per month
* Average Order Value
* Invoice Count
* Customer Segmentation (done by RFM Analysis, which measures the recency, frequency and monetary value of a customer's purchases)
* Cohorts (Used to compare groups across time)

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
The top customers for the business account for around 50% of revenue for any given month, with a peak of 59.5% in October 2011 and a low of ~44% in March 2010. The high value customers in the next highest segment also contribute around 15% per year and then the other segments contribute the remaning amount. The compnany relies on both a small portion of the customer base and on a small section of the year, which is something that needs to be taken into account at a high level because it can be risky.

![image](https://github.com/kacpersienkiewicz/Online-Retail-II/blob/main/Images/Revenue_by_customer_segment_by_month.png?raw=true)

## Dominance of the first cohort
In addition to the top 14% of customers accounting for around half of revenue, the first cohort of customers, who made their first purchase in December 2009, dominate metrics. They have placed the most orders and contributed the most revenue by a massive margin, but an important thing to note is that their Average Order Value is not much higher than the average cohort, which means that future cohorts can be as lucrative as the first cohort. Relying on this cohort is risky, but other cohorts can also be as productive as the first one if they were given the right incentives like promotions or rewards.

![image](https://github.com/kacpersienkiewicz/Online-Retail-II/blob/main/Images/Customer%20Segment%20Dashboard.png?raw=true)
## Conclusion and Recommendations
The company relies on a small subset of the population for 50% of its revenue and it relies a third of the year for a similar amount of revenue. This is a risky thing to rely on so the company should think about trying to improve revenue in the off-season during Spring and Summer, especially since the average order value and volume is much lower than the peak season which implies that there is a decent amount of untapped potential there. A marketing campaign focused on bundles or limited-time offers could help bring up that portion of the year to provide some sort of safety net if the peak season does not play out as well as it normally does.

Another idea could be to create a VIP program to help retain the top 14% of customers as well as try to retain other high spenders by providing exclusive offers or early access to new products. This is vital to show especiall loyal customers, such as the productive first cohort from December 2009, that the company does not take them for granted.

A third recommendation is to create categories for items to be able to talk about them broadly. Natural Language Processing (NLP) can be used, but the categories need to be agreed on by all relevant stakeholders, like the Marketing and Product Teams, so they can align marketing and product pushes.

Both of these are intended to mitigate the possibility and risks if the peak season doesn't pan out well. Retaining top customers should help prevent it, and marketing during off-peak months should help provide revenue outside of that period.

## Links
* [Tableau Dashboard](https://public.tableau.com/app/profile/kacper.sienkiewicz/viz/Online_Retail_II_17788993017010/Customers)
* [Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii)
