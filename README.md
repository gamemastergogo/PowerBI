
# E-Commerce Sales Dashboard
### Dashboard Link : https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

## Problem Statement

This dashboard helps with analyzing and visualizing e-commerce sales data to gain insights into various aspects of sales performance. The goal is to understand sales trends by key metrics such as quantity, profit, and sales by category, customer, payment method, state, and time (monthly basis). This information will support decision-making for improving overall business strategies.


### Steps followed 

1. *Import the Data:*
   - Load the provided data tables (Orders and Details) into Power BI. Ensure that both tables are correctly imported and related based on a common key, typically the Order ID.

2. *Data Cleaning and Preparation:*
   - Inspect the data for missing values or inconsistencies.
   - Ensure that all columns are in the correct data type (e.g., Quantity, Profit as numbers, PaymentMode as text).
   - Create any necessary calculated columns or measures (e.g., Total Sales Amount, Profit, Average Order Value (AOV)).

3. *Data Modeling:*
   - Define relationships between the Orders and Details tables. A common setup is one-to-many (where Orders is the one side and Details is the many side).
   - Define aggregations and measures for key metrics (such as Sum of Amount, Sum of Profit, and Sum of Quantity).

4. *Visualizations:*
   - *Top KPIs:*
     - Create cards showing key performance indicators (KPIs) like total sales amount (438K), total quantity sold (5615), total profit (37K), and average order value (121K).
   
- *Category Analysis:*
     - Create a Donut Chart to show the breakdown of quantities sold by product category (Clothing, Electronics, Furniture).
   
   - *Payment Mode Analysis:*
     - Use a Pie Chart to display the proportion of sales based on different payment modes (COD, UPI, Debit Card, Credit Card, EMI).
   
   - *Customer Insights:*
     - Visualize the Sum of Amount by CustomerName in a Bar Chart, showcasing sales from key customers (Harivansh, Madhav, Shiva, etc.).

   - *State-wise Sales:*
     - A Bar Chart displaying sales by state (Maharashtra, Madhya Pradesh, Uttar Pradesh, Delhi) helps analyze regional performance.

   - *Profit by Month:*
     - A Bar Chart or Line Chart illustrating monthly profit trends to highlight the sales performance and identify any seasonal trends or dips.

   - *Sub-Category Profit Analysis:*
     - A Horizontal Bar Chart representing profit margins by sub-categories (e.g., Printers, Bookcases, Saree, etc.).
5. *Adding Filters and Slicers:*
   - Add slicers to allow filtering by states, categories, or quarters. This allows dynamic interaction with the data, where users can focus on a specific region, time period, or product type.

6. *Formatting:*
   - Apply consistent color schemes, borders, and formatting to ensure the dashboard is visually appealing and easy to understand.
   - Ensure the axes are labeled clearly, and data values are easy to interpret.

### *Snapshot of Dashboard:*

![Screenshot 2024-09-09 160016](https://github.com/user-attachments/assets/f95f8f66-6595-4d7c-b13e-bcbed0ce64d6)


### *Conclusion:*
This dashboard provides a comprehensive overview of the e-commerce sales data, breaking down the key metrics and visualizing the performance across different dimensions such as product categories, payment modes, and geographical regions.
