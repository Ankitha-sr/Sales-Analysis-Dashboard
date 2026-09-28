# Vrinda Store – E-commerce Sales Analysis Dashboard

An interactive Excel dashboard analyzing 2022 sales data for Vrinda Store, an Indian clothing retailer that sells through multiple online marketplaces.

**Objective**

Help the store understand its 2022 sales performance and plan for growth by answering questions like:

How do sales and order volume change month to month?

Who buys more, men or women, and in which age groups?

Which states and marketplace channels drive the most revenue?

What share of orders are delivered, returned, cancelled, or refunded?

**Dataset**

Records: 31,047 orders (January – December 2022)

Fields: Order ID, Customer ID, Gender, Age, Date, Status, Channel, SKU, Category, Size, Quantity, Amount, Shipping City/State/Postal Code, B2B flag

Source: Vrinda Store sample dataset used for Excel practice

**Tools & Techniques**
Microsoft Excel


Data cleaning: standardized inconsistent values (Gender M/W → Men/Women; Quantity One/Two → 1/2)

Formulas: nested IF to create an Age Group column (Teenager / Adult / Senior); TEXT to extract the month name from the order date

PivotTables & PivotCharts: six pivots covering monthly sales vs. orders, sales by gender, order status, top 5 states, age group by gender, and channel share

Slicers: interactive filters for Month, Channel, and Category

**Key Insights**

Women account for about 64% of total sales.

Maharashtra, Karnataka, and Uttar Pradesh are the top 3 states by sales.

Amazon is the leading channel with 35.5% of sales, followed by Myntra (23.3%) and Flipkart (21.6%).

92.3% of orders were delivered successfully; the rest were returned, cancelled, or refunded.

Sales peaked in March and gradually declined toward the end of the year.

**Recommendation**


Target women customers in the top states (Maharashtra, Karnataka, Uttar Pradesh) with offers and ads on Amazon, Myntra, and Flipkart to grow sales.
