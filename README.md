# Optimizing-Supply-Chain-Efficiency
# Overview
A Power BI dashboard optimizing supply chain efficiency by analyzing supplier performance, production efficiency, inventory evaluation, order fulfillment, shipping & logistics, and sales overview. Visuals highlight key interdependencies, track performance metrics, and provide actionable insights to enhance decision-making, reduce inefficiencies, and improve supply chain resilience. Ideal for supply chain managers to monitor operations and drive strategic improvements.
# Visuals Included

![image](https://github.com/user-attachments/assets/61b07b78-2bd2-4edc-8c5b-2a5cbc89942e)



**1. Supplier Evaluation**
- No.of Supplier, Avrg.Lead Time, Avrg.Lead Time Variance, Total Qty Supplied, Supplier on Time Delivery Qty Rate, Supplier Efficiency 
-  Total Quantity Supplied With Supplier on Time Delivery Qty Rate
-  No. Of order delivered on time, No. orders delivered late and Supplier Efficiency Per Supplier
-  Order Qty received on time, Total Qty supplied and supplier On-Time Delivery Quantity Rate by Product type
-  Production volumes and Avg. Manufacturing lead time by Product type
 
![image](https://github.com/user-attachments/assets/681b4c7e-30f6-4d7e-916a-05d1ed3d9e0e)


**2. Production Evaluation**
- Defect Rate % , Production Volume , Manufacturing Cost , Avrg. Manufacturing Lead Time, Order Quantity from supplier
- Total NO. of products by Inspection results
- Production volumes and Defect Rate % by Product type
- Qty Sold, Production Volume and Order quantities from supplier by Product type
- Manufacturing cost by Product type and Inspection results
- Order quantities from supplier and supplier On-Time Delivery Quantity Rate by Inspection results

![image](https://github.com/user-attachments/assets/cdef2c7a-2675-4aa7-aaa0-59fd997e517b)



**3. Inventory Evaluation**
- Stock Availability, Stock Levels, Inventory Turnover Ratio, Days Sales of Inventory, Stock Out Rate
- Stock Levels per warehouse
- Stock levels, Qty Sold and Inventory Turnover Ratio by Product type
- Stock Cost and Stock levels by Product type
- Stock levels, Production volumes, and Avg. Manufacturing lead time by Product type

![image](https://github.com/user-attachments/assets/dc2ff2cd-e64f-438a-ba9d-77bd8eb2d523)


**4. Order Fulfilment**
- Lowest Order Cycle, Highest Order Cycle, Avrg. Order Cycle , Order on Time Delivery Rate, Order Volume Per Month, Order Fullfilment Time
- Total NO.order delivered on time Vs.Total Order
- Order volume per month, Average of Order Processing Time(Days) and Order On-Time Delivery Rate by Product type
- Order volume per month
- Factors Affecting Order Fulfillment per Product Type
- Order volume Vs. Production volume per warehouse

![image](https://github.com/user-attachments/assets/e6968b18-15d3-4037-81e8-fc50c4106009)


**5. Shipping And Logistics**
- Average of Shipping times (day), Shipping Cost
- Average of Shipping times (day) by Transportation modes
-  Shipping  Costs by Shipping carriers
-  Average of Shipping times (day) by Shipping carriers

![image](https://github.com/user-attachments/assets/022525a8-01d6-4c68-b4a1-6ed21ffa1379)


**6. Summary**
Each component is interconnected, forming a continuous feedback loop. A weak supplier disrupts production, leading to inventory shortages, order delays, and logistical inefficiencies. Conversely, an optimized evaluation process ensures a smooth, cost-effective, and reliable supply chain, improving customer satisfaction and business profitability.

![image](https://github.com/user-attachments/assets/1fab948b-55c8-4d07-8302-4f5c8f551a05)


**7. Sales Overview**
- Avrg.Price, Total Sales, Total Cost, Total Profit, Profit Margin %, Qty Sold, Total No. order
- Total cost, Total Sales, Total profit and Profit Margin% by Product type
- No. of products per category
- Total Sales & Profit by Product Type with inventory turnover
- Qty Sold and Total Sales by Product type

# Data Processing, Model View, and Calculations 
 ![image](https://github.com/user-attachments/assets/0a2a2649-238b-4d9b-98f8-895e4aa8313a)

This Power BI dashboard leverages several key tools and technologies to perform data transformations and calculations:

- **Power Query:** Used for data importation and transformation, Power Query enables the cleaning, shaping, and loading of data from various sources into the Power BI environment. This process ensures that the data is in the correct format for analysis.

- **DAX (Data Analysis Expressions):** DAX is utilized for creating custom calculations and measures within the dashboard. It allows for advanced data modeling and enables the creation of dynamic calculations that respond to user interactions and filter selections.

- **Data Modeling:** The relationships between different data tables are established to create a comprehensive data model. This ensures accurate insights and visualizations throughout the dashboard.
