# 🍕 PizzaHut Sales Analysis Project

A data-driven project focused on analyzing PizzaHut’s sales performance using SQL. This analysis explores customer behavior, revenue patterns, and product popularity using real transactional data.

---

## 🎯 Project Objective

The main objective of this project is to extract actionable insights from PizzaHut’s order data by performing structured SQL-based analysis. The project is divided into three levels of complexity:

- **Basic:** Track order volume, revenue, and best-selling pizzas.
- **Intermediate:** Understand ordering trends by time, category, and average daily sales.
- **Advanced:** Perform revenue breakdowns and cumulative sales tracking.

---

## 📁 Dataset Overview

The analysis is based on four structured CSV files that represent different aspects of the PizzaHut ordering and product system:

1. **`order_details.csv`**  
   Contains information about each pizza ordered in every order.  
   - `order_details_id`: Unique identifier for each row  
   - `order_id`: ID linking to the overall order  
   - `pizza_id`: ID of the specific pizza  
   - `quantity`: Number of units ordered  

2. **`orders.csv`**  
   Captures the order-level information with timestamps.  
   - `order_id`: Unique identifier for each order  
   - `date`: Date the order was placed  
   - `time`: Time the order was placed  

3. **`pizza_types.csv`**  
   Contains descriptive information about pizza types.  
   - `pizza_type_id`: Identifier for the pizza type  
   - `name`: Name of the pizza  
   - `category`: Category of the pizza (e.g., Classic, Veggie, Chicken)  
   - `ingredients`: List of ingredients used  

4. **`pizzas.csv`**  
   Provides pricing and size details for each pizza variation.  
   - `pizza_id`: Unique identifier for a specific pizza (type + size)  
   - `pizza_type_id`: Link to the type of pizza  
   - `size`: Size of the pizza (e.g., S, M, L, XL)  
   - `price`: Price of the pizza  

---

## 🧰 Tools & Technologies Used

### 🔹 SQL (Structured Query Language)
- Core tool used for all data analysis tasks in the project.
- Performed complex data manipulations such as filtering, grouping, and sorting.
- Used various SQL operations including:
  - **JOINs** to combine data across multiple tables.
  - **GROUP BY** and **ORDER BY** to summarize and rank results.
  - **Aggregate functions** like `SUM()`, `COUNT()`, `AVG()` to compute totals and averages.
  - **Window functions** for advanced analytics like cumulative revenue.
  - **Date and time functions** to analyze hourly and daily trends.
- Enabled effective transformation of raw sales data into meaningful business insights.

---

## 📊 Key Analyses Performed

### 🔹 Basic Analysis
- Total number of orders
- Total revenue from pizza sales
- Highest-priced pizza
- Most common pizza size
- Top 5 most ordered pizza types

### 🔹 Intermediate Analysis
- Total quantity ordered per pizza category
- Hourly distribution of orders
- Category-wise pizza distribution
- Average number of pizzas ordered per day
- Top 3 pizzas by revenue

### 🔹 Advanced Analysis
- Revenue percentage by pizza type
- Cumulative revenue over time
- Top 3 revenue-generating pizzas per category

---

## 💡 Insights & Recommendations

- **Classic** and **Veggie** pizzas are the most popular categories.
- Medium size is the most commonly ordered size, indicating portion preference.
- Sales peak during **evening hours**, suggesting targeted promotions during those hours may boost sales.
- A few high-priced pizzas contribute a significant share of revenue — upselling these could improve profitability.
- Monitoring top performers in each category helps optimize inventory and marketing.

---

## 🧠 Skills Demonstrated

- Data cleaning and normalization
- SQL joins, group by, aggregate functions, window functions
- Analytical thinking & business insight generation
- Data storytelling through visualizations
- Report documentation and structured analysis


