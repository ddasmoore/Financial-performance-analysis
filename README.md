# Financial-performance-analysis

  ## Table of Contents
* [About the project](#About-the-project)
* [Executive summary of insights](#Executive-summary-of-insights)
* [Technical Details and detailed insights](#Technical-Details-and-detailed-insights)
  *   [About the dataset](#About-the-dataset)
  *   [Tools and libraries](#Tools-and-libraries)
  *   [Data analysis](#Data-analysis)
  *   [Results](#Results)
  *   [Recommendations](#Recommendations )

## About-the-project
This project was conducted for an international fintech company that facilitates online payment processing for businesses worldwide. The platform enables merchants to accept payments from their customers by handling the technical and financial aspects of transactions. The core business model is based on a fee structure: the platform earns gross revenue from a small, percentage-based fee on each transaction, and net revenue is the amount retained after paying third-party processing costs.

As a data analyst, I was tasked with a series of analyses aimed at optimizing revenue streams and providing actionable insights into market dynamics. My work involved dissecting the transactional data to understand key drivers of profitability and identify opportunities for strategic growth.

The goals for the analysis were to:
1. Trends in net revenue, number of transactions and other KPIs across continent, country and business category
2. Peformance of KPIs month over month. 

#Executive-summary-of-insights
1. The largest business share in terms of revenue came from South America, followed by North America and Europe. 
2. Net revenue had a positive month-over-month growth trend (15.3%). 
3. The period from May to November was a peak performance period for both transaction volume and net revenue.
4. While South America accounted for the highest volume of transactions and net revenue, North America generated the largest processed amount, indicating higher-value transactions in that region.
5. The Retail, Consulting, and Clothing sectors were the primary drivers of net revenue in 2024. 

<img width="1594" height="1112" alt="image" src="https://github.com/user-attachments/assets/e3c4ed14-4037-4ce8-b495-9a10f78acff0" />

## Technical-Details-and-detailed-insights

## About-the-dataset
The dataset contained the following columns:
`tx_date (date)`
`country`
`continent`
`business_category`
`pv_amount (processed amount in local currency)`
`pv_amount_dollars (processed amount in dollars)`
`gross_revenue (gross revenue in local currency)`
`gross_revenue_dollars (gross revenue in dollars)`
`net_revenue (net revenue in local currency)`
`net_revenue_dollars (net revenue in dollars)`
`tx_count (number of processed payment transactions)`

## Tools-and-libraries
The data was analyzed and visualized using Tableau


## Results
The analysis was conducted on data from Jan 1, 2024 to December 21, 2024 (Report Date). 

1. In the last month, between November 21 and December 21, the company processed a total of $314.5 billion across 237.1 million transactions, generating $77.1 million in net revenue.

2. Net revenue showed a positive month-over-month (MoM) trend of 15.3%. The period from May (net revenue: $91,189K, +16% increase MoM)  to November (Net revnue: $94,633K, -.04% change MoM) was particularly strong, with net revenue consistently exceeding $85K each month.

4. South America contributed the largest share of net revenue, followed by North America and Europe. Notably, Brazil was the top-performing country in net revenue month-over-month, exceeding $41K every month in net revenue between January and November.

5. South America consistently led in transaction volume and net revenue. By contrast, North America generated a larger processed amount, indicating a higher average transaction value in that region. The only exception was January when Brazil also led in processed amount. 

6. The Retail, Consulting, and Clothing sectors were the main drivers of net revenue. While Retail, Restaurants, and Transportation consistently led in transaction volume throughout the year, processed amount from the Restaurant category surpassed that of Consulting in the second half of the year (starting in June).

## Recommendations 
1. The data shows South America's potential as the primary driver of net revenue and transaction volume. To maintain and expand this leadership, a more nuanced, "in-market" approach is necessary. Research and integrate payment methods popular in Brazil and other key South American countries (e.g., real-time payment systems like PIX in Brazil). This can significantly reduce payment friction and increase conversion rates.
   
2. The data indicates that North America accounts for the largest processed amount, signaling a high average transaction value. This presents a prime opportunity to build a more profitable client base without necessarily chasing high transaction volume. Shift focus in North America from broad-based acquisition to a targeted strategy for high-value business clients.
   
3. Create tailored product solutions and marketing campaigns for highest-performing sectors: Retail, Consulting, and Clothing, and for the high-growth Restaurants category.
   
4. The consistent performance from May to November suggests that a proactive strategy can maximize this period, while an understanding of the slower months allows for resource optimization. For example, launching targeted marketing and sales campaigns in late Q1 and early Q2 may capture new clients ahead of the busy season.
