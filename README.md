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
This project shows analysis of financial performance for a payment solutions platform. The platform assists businesses worldwide in processing transactions. 
Customers are charged a small fee based on the amount they charge their clients (processed amount), which contributes to the platform's gross revenue. 
After deducting processing fees paid to third parties, the company retains the net revenue. 

The goals for the analysis were to:
1. Trends in net revenue, number of transactions and other KPIs across continent, country and business category
2. Peformance of KPIs month over month. 


#Executive-summary-of-insights
1. US is the highest market, followed by Brazil, Canada, Colombia and France
2. Net Revenue is trending positive MoM (15.3%) with fluctuations MoM, but showing a steep decline in December. 
3. Transations and net revenue were strong May-November
4. Processed amount trend: North America> South America> Europe
5. Transactions trend: South America> North America > Europe
6. Net Revenue trend: South America> North America > Europe
7. Retail, consulting and clothing were highet categories of business driving net revenue

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
1. US is the highest market, followed by Brazil, Canada, Colombia and France
2. Net Revenue is trending positive MoM (15.3%) with fluctuations MoM, but showing a steep decline in December. 
3. Transations and net revenue were strong May-November
4. Processed amount trend: North America> South America> Europe
5. Transactions trend: South America> North America > Europe
6. Net Revenue trend: South America> North America > Europe
7. Retail, consulting and clothing were highet categories of business driving net revenue

## Recommendations 
1. Investigate the December Decline: While net revenue shows a positive trend overall, the steep decline in December is a major concern. This could be due to seasonal factors, a change in marketing spend, or a shift in user behavior.
   Conduct an investigation to understand the cause and prevent a long-term trend.  

2. Leverage Strengths in North America and South America: The trends for processed amount, transactions, and net revenue show that North and South America are the top-performing regions.
   Focus on scaling marketing and business development efforts in these areas to capitalize on their strong performance.

3. Capitalize on Top Business Categories: The insights highlight that retail, consulting, and clothing are the highest-revenue-driving categories.
   Develop targeted campaigns and product offerings specifically for these sectors to maximize their revenue potential.

4. Balance Processed Amount and Transactions: The data shows that South America leads in transactions and revenue, while North America leads in processed amount.
   This suggests that North America has a higher average transaction value. Analyze the factors contributing to this difference and explore strategies to increase the average transaction
   value in the South American market. This could involve upselling, cross-selling, or product bundling.
