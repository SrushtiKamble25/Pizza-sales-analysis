
 # Pizza Sales Analysis Dashboard


## Problem Statement

Managing a pizza business involves tracking sales performance, identifying best-selling and least-selling pizzas, and analyzing peak order times. Understanding these sales trends helps optimize revenue, inventory, and marketing strategies. This dashboard provides an in-depth analysis of sales trends, allowing stakeholders to make data-driven decisions to improve operational efficiency and profitability.

## Steps followed 

### Data Processing in Power BI
1. Data Loading: Imported the pizza sales dataset into Power BI Desktop.
2. Data Cleaning: Used Power Query Editor to remove errors and missing values.
3. Feature Engineering: Created calculated columns for Total Sales, Total Orders, and Total Pizzas Sold.
4. Data Filtering: Removed inconsistencies and null values (less than 1% of the dataset).
5. Dashboard Customization: Applied an intuitive color scheme and layout for enhanced readability.

### Visualizations Added:
- Line Chart: Sales Trend by Month
- Pie Chart: Percentage of Sales by Pizza Category.
- Donut Chart: Percentage of Sales by Pizza Size.
- Bar Charts:
  - Total Orders by Day of the Week
  - Total Orders by Month
  - Total Pizza Sold by Category
- KPI Cards: 
  - Total Orders
  - Total Pizza Sold
  - Total Revenue
  - Average Pizzas per Order


## SQL Query for Pizza Sales

- To analyze the pizza sales data, we used SQL queries to extract key insights. The SQL queries include:

- Aggregating total sales, revenue, and order volume.

- Identifying best-selling and least-selling pizzas based on revenue and quantity.

- Extracting peak order times and busiest sales periods.

- Analyzing customer order behavior to determine average pizzas per order.

### The relational data model includes the following tables:

- orders (date, order_id, time)

- order_details (order_details_id, order_id, pizza_id, quantity)

- pizzas (pizza_id, pizza_type_id, price, size)

- pizza_types (pizza_type_id, name, category, ingredients)

### Image for table relationships:

![Image](https://github.com/user-attachments/assets/b4cd2a94-d498-4f46-974b-67fa2ac67eb7)

These tables are interconnected using primary and foreign key relationships to facilitate efficient querying and analysis.

## Key Insights from the Dashboard
### 1. Overall Sales Performance
- 📌 Total Orders: 21K
- 📌 Total Pizza Sold: 50K
- 📌 Total Revenue: $1.58K
- 📌 Average Pizzas per Order: 2.32

### 2. Sales Trends
- Orders are highest on Fridays and Saturdays, especially during the evenings.
- The busiest months for sales are January and July.
- Sales are evenly distributed throughout the week, but weekends contribute to a significant percentage of total revenue.
### 3. Product Performance
- Best-Selling Products:
  - Revenue: Thai Chicken Pizza generates the maximum revenue.
  - Quantity: Barbecue Chicken Pizza sells the highest quantity.

- Least Selling Products:
  - Revenue & Quantity: Brie Carry Pizza contributes to the lowest revenue and sales volume.

### DASHBOARD
Page 1:

![Image](https://github.com/user-attachments/assets/985de626-404e-46d7-9c0f-4285fd5f0ed6)

Page 2:

![Image](https://github.com/user-attachments/assets/d834a9ea-6904-47b9-99f9-362adc6b585a)



## Conclusion
This Pizza Sales Dashboard in Power BI provides insights into sales trends, product performance, and revenue optimization strategies. Peak sales occur on weekends and during the months of January and July. Classic and large-sized pizzas dominate sales, while some varieties need better marketing efforts. With data-driven insights, businesses can optimize pricing, promotional campaigns, and inventory management to enhance overall profitability.
