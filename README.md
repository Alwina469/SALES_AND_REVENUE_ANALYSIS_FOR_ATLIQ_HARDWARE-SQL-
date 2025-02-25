# SALES AND REVENUE ANALYSIS FOR ATLIQ HARDWARE (SQL)

##  Domain:  Consumer Goods         |            Function: Executive Management

---

**Atliq Hardwares** (imaginary company) is one of the leading computer hardware producers in India and well expanded in other countries too.

However, the management noticed that they do not get enough insights to make quick and smart data-informed decisions. 

They want to expand their data analytics team by adding several junior data analysts. 

Tony Sharma, their data analytics director wanted to hire someone who is good at both tech and soft skills. 

Hence, he decided to conduct a SQL challenge which will help him understand both the skills.

---
## Task:  

Imagine yourself as the applicant for this role and perform the following task

1.    Check ‘ad-hoc-requests.pdf’ - there are 10 ad hoc requests for which the business needs insights.
2.    You need to run a SQL query to answer these requests.

---
## QUESTIONS:

- List of Markets for "Atliq Exclusive" in the APAC Region This query fetches all the markets where the customer "Atliq Exclusive" operates within the APAC region.

- Unique Product Increase (2021 vs. 2020) This query calculates the percentage increase in unique products between the years 2020 and 2021. The output contains: unique_products_2020: Number of unique products in 2020. unique_products_2021: Number of unique products in 2021. percentage_chg: The percentage increase.

- Unique Product Count by Segment This query provides the count of unique products for each segment, sorted in descending order of product count. The output fields are: segment: Product segment. product_count: Number of unique products in that segment.

- Segment with the Most Increase in Unique Products (2021 vs. 2020) This query identifies the segment that had the highest increase in unique products between 2020 and 2021. The output includes: segment: The segment name. product_count_2020: Unique products in 2020. product_count_2021: Unique products in 2021. difference: The difference between 2021 and 2020.

- Highest and Lowest Manufacturing Costs This query fetches the products with the highest and lowest manufacturing costs. The output contains: product_code: Product code. product: Product name. manufacturing_cost: Manufacturing cost of the product.

- Top 5 Customers with Highest Average Discount (Indian Market, 2021) This query provides a list of the top 5 customers who received the highest average pre-invoice discount percentage in the Indian market for the fiscal year 2021. The output contains: customer_code: Customer code. customer: Customer name. average_discount_percentage: The average discount percentage.

- Monthly Gross Sales for "Atliq Exclusive" This query generates a report showing the monthly gross sales amount for the customer "Atliq Exclusive", helping to analyze high and low-performing months. The output includes: Month: Month of the sales. Year: Year of the sales. Gross sales Amount: The gross sales amount for each month.

- Quarter with Maximum Sold Quantity in 2020 This query identifies the quarter in 2020 with the highest total sold quantity. The output contains: Quarter: The quarter (e.g., Q1, Q2). total_sold_quantity: Total sold quantity in that quarter.

- Channel with the Most Gross Sales (2021) This query calculates which sales channel contributed the most gross sales in the fiscal year 2021, along with its percentage contribution. The output includes: channel: Sales channel. gross_sales_mln: Gross sales in million. percentage: Percentage contribution.

- Top 3 Products by Sold Quantity in Each Division (2021) This query lists the top 3 products by total sold quantity for each division in the fiscal year 2021. The output includes: division: The division name. product_code: Product code. product: Product name. total_sold_quantity: The total quantity sold. rank_order: Rank of the product based on sold quantity.
