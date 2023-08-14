# Supply-chain-sql-project


Business Analytics Queries for Customer Insights

These SQL queries are designed to provide valuable insights into customer behavior, sales performance, and operational efficiency. By analyzing the data from the sc_customertable and related tables, businesses can make informed decisions to optimize operations, enhance customer experiences, and drive revenue growth.

Table of Contents

Overview
Queries and Insights
Updating Sales Currency Values
Identifying Duplicate Data
Enhancing Late Delivery Risk Analysis
Analyzing Customer Segments
Top Revenue-Generating Markets
Late Delivery Risk in Specific Cities
Comparing Late Deliveries and Late Delivery Risks
Department Sales Performance
City-Level Revenue Analysis
Revenue Analysis in Puerto Rico
Top Revenue-Generating Customer Segments
Top Revenue-Generating Customers
Top Selling Products in the USA
Overview

These queries utilize the sc_customertable and related tables to extract meaningful insights. The results help businesses answer critical questions related to sales, delivery performance, customer segments, and revenue generation. By leveraging these insights, businesses can improve decision-making processes and enhance overall performance.

Queries and Insights

Updating Sales Currency Values
Query: UPDATE sc_customertable SET Sales_per_customer = ROUND(Sales_per_customer, 2);
Insight: Updates sales values to two decimal places for improved currency representation.


Identifying Duplicate Data
Query: Checks for duplicate rows based on specific columns.
Insight: Ensures data integrity and accuracy by identifying and addressing duplicate records.


Enhancing Late Delivery Risk Analysis
Query: Modifies Late_delivery_risk column to display "YES" or "NO".
Insight: Makes the data more user-friendly and easier to understand.


Analyzing Customer Segments
Query: Calculates average sales per customer for different segments.
Insight: Identifies high-value customer segments based on average sales.



Top Revenue-Generating Markets
Query: Determines the top five revenue-generating markets (regions).
Insight: Helps prioritize regions with the highest sales potential.


Late Delivery Risk in Specific Cities
Query: Analyzes late delivery risk in specific cities within the USA.
Insight: Assesses delivery efficiency and identifies areas for improvement.


Comparing Late Deliveries and Late Delivery Risks
Query: Compares actual late deliveries to late delivery risks in specific cities.
Insight: Highlights the correlation between perceived risks and actual delivery delays.


Department Sales Performance
Query: Orders departments by highest average sales per customer.
Insight: Identifies departments contributing significantly to revenue.


City-Level Revenue Analysis
Query: Analyzes top cities generating revenue in the USA.
Insight: Reveals revenue distribution across different cities.


Revenue Analysis in Puerto Rico
Query: Analyzes top cities generating revenue in Puerto Rico.
Insight: Provides insights into revenue distribution by region.


Top Revenue-Generating Customer Segments
Query: Calculates total revenue for each customer segment.
Insight: Helps focus marketing efforts on high-revenue segments.


Top Revenue-Generating Customers
Query: Identifies top customers generating the highest revenue.
Insight: Prioritizes engagement and personalized services for high-value customers.


Top Selling Products in the USA
Query: Identifies the top 10 most selling products in the USA.
Insight: Informs inventory management and marketing strategies for popular products.



By using these SQL queries to extract insights from the data, businesses can gain a deeper understanding of their operations, customer preferences, and revenue drivers. This information empowers decision-makers to implement targeted strategies, optimize resources, and ultimately thrive in a competitive market environment.
