# ZenPulse-Ecommerce-Analysis

ZenPulse, established in 1983, is an e-Commerce platform known for selling top quality consumer electronics at exceptionally low prices.  

## Dataset Structure & Initial Checks

The dataset of Electronic Express consists of 108,000 records over a 4 year period between 2019-2022 extracted from the company's Enterprise Resource Planning (ERP) system and systematically arranged into a spreadsheet comprising of four tables as displayed below: orders, customers, geo_lookup, and order_status. In preparation for analysis, a rigorous assessment of data quality was undertaken to ascertain and address potential issues.

![image](https://github.com/mlatona17/Electronic-Express-eCommerce-Analysis/assets/67985288/db27f1eb-4e48-4e04-bb76-28519240f1f4)


Employing Excel, the data cleaning process meticulously scrutinized all records. This examination ensured the identification and documentation of minimal quality issues, encompassing discrepancies in product naming, absence of country data, prerequisite columns for analysis, instances of null values. Once this process was complete and confidence in the integrity of the data was up to standard, a thorough exploratory analysis was performed to extract insights and trends to see if any key metrics could be improved.

## Summary of Key Insights and Findings

### Sales Performance Overview

**By Time Period**

- Between 2019 and 2022 total sales were $28M which consister of 108k orders and an average order value of $260 per order.
- 2020 saw a 163% jump in sales and doubling in total orders compared to prior year. In particular Q2 of that year saw a 53% spike in sales and 50% increase in total orders from Q1 which can likely be attributed to increased spending during lockdowns from the pandemic.
- The largest dropoff in sales YoY came in 2022 where the company saw a $4.2M decrease (-46%) in total sales.
- Across all 4 years the average order value increased in Q3 and Q4 which can be explained by customers purchasing in bulk during the holiday season.

**By Product Mix**

- The 4k gaming monitor, Apple Airpods, Macbook Laptop, and Thinkpad Laptop account for 96% of total sales.
- The Apple Airpods were consistently the most popular product every year with total orders of 48k (45% of total orders). Due to pricing differences however the 4k Gaming Monitor brought in the most revenue with nearly $10M in sales.
- In contrast the Bose Soundport Headphones was the least popular product by a large margin with only 27 orders and $3.3k in sales.
- 
**By Region**
  
- Overall North America dominated in both total sales and orders with over a 50% share in each. On the contrary LATAM accounted for only 6% and 7% share of total sales and orders respectively.

**Product Performance by Region**

- Apple Airpods were the most popular product sold within each region with an average of 12k units sold per year. Amongst all regions North America bought the most Airpods with 25k units sold followed by EMEA (15k), APAC (5.6k) and LATAM (2.6k).


### Refund Rates

- Overall $2.2M or 8% of total sales was refunded. The Thinkpad Laptop and Macbook Air Laptop had the highest refund rates at 12% and 11% respectively. The Apple Airpods and 27in 4k Gaming Monitor had the largest number of refunds however with 2,636 and 1,444 returns respectively.


### Loyalty Program

- The loyalty program has seen an increase in partcipation over the years. The proportion of loyalty to non-loyalty members went from 12%/88% to 53%/47% from 2019 to 2022.
- In 2022 loyalty members spent an average $30 more per order than non-loyalty where in 2019 non-loyalty spent $26 more per order than loyalty.

### Marketing Channel Performance

- The direct marketing channel brought in the most business with $23M in sales and and 84k orders while social media attracted lowest with $300k in sales and 1.3k in orders.
- Amongst each marketing channel loyalty members favored email marketing the most over non-loyalty with 58% of purchases driven from that channel coming from loyalty members. 


### Operational Efficiencies

**Time to Deliver:** The average overall time to deliver, as defined as the amount of time an order took from purchase to delivery, was 7.5 days. This was uniform across all regions.
**Time to Ship:** The average time to ship, as defined as the amount of time an order took to ship from purchase, was relatively similiar across the product line with the Bose Headphones shipping out the fastest at 1.78 days and the Samsung Cable Pack the slowest at 2.07 days.


## Recommendations

- Maybe consider dropping product line if inventory costs provide a low or negative profit margin
- The average time to deliver was the same for both loyalty and non-loyalty members possibly indicating potential for improvement for the company.


