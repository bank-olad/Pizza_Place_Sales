## Project Overview

This project explores one year of sales data from a fictional pizza restaurant using **Python**, **Pandas**, and **Matplotlib**. The objective is to perform Exploratory Data Analysis (EDA) to uncover valuable business insights, identify customer purchasing patterns, evaluate product performance, and support data-driven decision-making.

---

## Dataset Description

The dataset contains transactional records for every pizza order made during one year.

It includes information such as:

- Order ID
- Order Date
- Order Time
- Pizza ID
- Pizza Name
- Pizza Category
- Pizza Size
- Quantity Ordered
- Unit Price
- Sales Amount
- Ingredients

The project combines the following CSV files:

- `orders.csv`
- `order_details.csv`
- `pizzas.csv`
- `pizza_types.csv`

---

## Business Questions Answered

This analysis addresses the following questions:

1. What is the total revenue generated?
2. What is the total quantity of pizzas sold?
3. How many customer orders were placed?
4. How many pizza types are sold?
5. What is the average pizza price?
6. What are the peak sales hours?
7. Which day of the week generates the highest sales?
8. What are the Top 5 bestselling pizzas?
9. How do sales vary across different months?
10. Which pizza types are underperforming?

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Analysis Workflow

The project follows a structured data analysis workflow:

- Import datasets
- Merge datasets
- Inspect data
- Handle encoding issues
- Create calculated fields
- Perform exploratory data analysis (EDA)
- Aggregate data using `groupby()`
- Visualize trends with charts
- Generate business insights

---

## Analysis Performed

The notebook includes analyses such as:

### Revenue Analysis
- Total sales generated
- Average pizza price

### Sales Performance
- Total quantity sold
- Total customer orders

### Product Analysis
- Number of pizza types
- Top 5 bestselling pizzas
- Lowest-selling pizzas

### Time-Based Analysis
- Peak sales hours
- Sales by day of the week
- Monthly sales trends

### Visualizations
- Bar chart of hourly orders
- Daily sales analysis
- Monthly sales trends
- Product performance comparisons
---

## Skills Demonstrated

This project demonstrates practical data analytics skills, including:

- Exploratory Data Analysis (EDA)
- Data Aggregation with Pandas
- Business Intelligence
- Data Visualization
- Trend Analysis
- Python Programming

---

## Key Python Concepts Used

- `read_csv()`
- `merge()`
- `groupby()`
- `sum()`
- `mean()`
- `count()`
- `nunique()`
- `sort_values()`
- `reset_index()`
- `reindex()`
- Date and Time manipulation
- Matplotlib visualizations

---

## Sample Output

The notebook generates insights including:

-  Total Revenue
-  Total Pizzas Sold
-  Total Orders
-  Top 5 Bestselling Pizzas
-  Lowest Performing Pizzas
-  Best Sales Day
-  Peak Ordering Hours
-  Monthly Sales Trends
