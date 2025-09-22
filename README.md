

Target Brazil E-commerce Data Analysis
Project Overview
This project is a business case study that analyzes Target's e-commerce operations in Brazil using a dataset from 2016 to 2018. The goal is to explore key trends in customer behavior, order patterns, payments, freight costs, and delivery performance. The analysis provides actionable insights and recommendations to help Target improve its operations and enhance customer satisfaction.


Business Questions Answered
The analysis addresses several key business questions to provide a comprehensive view of the e-commerce operations:


Order Trends: Is there a growing trend in the number of orders over the years, and can any monthly seasonality be identified? 



Customer Behavior: During what time of day do Brazilian customers typically place their orders? How are customers distributed across different states? 



Logistics & Delivery: How long does it take to deliver each order, and how does the actual delivery time compare to the estimated delivery time? Which states have the highest and lowest average freight costs and delivery times? 




Payments & Sales: What is the percentage increase in order cost from 2017 to 2018? What are the total and average order values and freight costs for each state? What are the most common payment types and how are payments distributed across different installments? 




Methodology & Tools
The analysis was performed using SQL, with all queries documented and executed to extract insights from the dataset.


Data Exploration: Initial steps involved checking the data types and characteristics of each table to understand the structure of the dataset.

Data Analysis: Complex SQL queries were used to:

Calculate time differences for delivery performance.

Join multiple tables (e.g., 

customers, orders, payments) to link customer information with order and payment data.


Aggregate data to find trends by year, month, state, and time of day.




Use Common Table Expressions (CTEs) to calculate complex metrics like percentage increase in costs.


Visualization: While not included in the provided PDF, key insights were derived from the query results, such as the total orders per year, which showed growth from 2016 to 2018. The analysis also identified that the highest number of orders were placed in the afternoon and night.




Key Insights & Recommendations
The analysis revealed several key findings that led to actionable recommendations for the business:

Customer Ordering Trends: Orders are growing steadily, with clear seasonal peaks. 

Recommendation: Invest in seasonal campaigns and improve demand forecasting to ensure inventory readiness before peak periods.

Time of Day for Orders: Most orders are placed in the afternoon and night. 

Recommendation: Optimize advertising spend and offer limited-time flash sales during these peak hours to drive conversions.

Regional Distribution: Customers are highly concentrated in Southeast states, with lower penetration in Northern and Northeastern states. 

Recommendation: Strengthen logistics in the Southeast and run localized marketing campaigns in underpenetrated regions.


Freight & Delivery: Some states have high freight costs, and many orders are delivered faster than estimated. 

Recommendation: Negotiate better rates with logistics providers and highlight early deliveries as a competitive advantage.



Payments & Installments: The majority of payments are via credit card, with a noticeable share using multi-installments. 

Recommendation: Promote installment flexibility (e.g., 0% EMI options) to encourage higher-value purchases.
