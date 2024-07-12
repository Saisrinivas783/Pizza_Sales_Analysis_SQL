# Pizza Sales Analysis Using SQL

## Project Overview

This project involves analyzing pizza sales data sourced from Kaggle using SQL. The analysis aims to answer key business questions regarding order trends, revenue, and pizza preferences. The project demonstrates skills in data extraction, transformation, loading (ETL), and SQL querying.

## Data Source

The data for this project is sourced from Kaggle. It includes four CSV files, each representing different aspects of pizza sales.

## Database Setup

1. **Connecting to MySQL Database:** 
   - Used Python to establish a connection with the MySQL database.
   
2. **Table Creation:**
   - Created four tables corresponding to the four CSV files.
   - Defined primary keys and foreign keys to ensure data integrity.

3. **Data Import:**
   - Imported the data from the CSV files into the respective tables.

## Questions Answered

1. **Total Number of Orders:**
   - Determined the overall number of orders placed.

2. **Hour-wise Trend Analysis:**
   - Analyzed the distribution of orders across different hours of the day.

3. **Month-wise Trend Determination:**
   - Examined the trends in order quantities across different months.

4. **Average Number of Orders per Day:**
   - Calculated the average number of orders placed each day.

5. **Total Revenue Calculation:**
   - Computed the total revenue earned from pizza sales.

6. **Top Pizzas by Revenue:**
   - Identified the pizzas generating the highest revenue.

7. **Contribution of Pizza Categories Towards Total Revenue:**
   - Analyzed how different categories of pizzas contribute to the overall revenue.

8. **Most Common Pizza Size Ordered:**
   - Determined the most frequently ordered pizza size.

9. **Most Ordered Pizza and Quantities:**
   - Identified the most ordered pizza and the quantities sold.

10. **Most Ordered Pizza Category:**
    - Determined which category of pizza is ordered the most.

## SQL Techniques Used

- **SELECT Statements:** To fetch data from the tables.
- **GROUP BY Clauses:** To group data for aggregation.
- **Aggregate Functions:** Such as SUM(), AVG(), COUNT(), etc., to perform calculations.
- **JOINS:** To combine data from multiple tables based on relationships.

## How to Run the Project

1. **Set Up Database:**
   - Ensure MySQL is installed and running.
   - Create a new database and import the provided SQL script to set up tables and relationships.

2. **Data Import:**
   - Use the Python script to import data from the CSV files into the MySQL database.

3. **Run SQL Queries:**
   - Execute the provided SQL queries to answer the business questions.

## Conclusion

This project showcases the ability to perform comprehensive data analysis using SQL. It provides insights into order trends, revenue generation, and customer preferences in the pizza sales domain.


