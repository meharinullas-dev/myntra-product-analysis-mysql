# myntra-product-analysis-mysql
Myntra product analysis using MySQL and SQL queries to analyze pricing, brands, discounts, ratings, and customer engagement.
# Myntra Product Analysis Using MySQL

## 📌 Project Overview

This project analyzes Myntra product data using MySQL to identify useful insights into product pricing, brand performance, discounts, customer ratings, and product popularity.

The project uses SQL queries to explore product information, compare brands, identify highly rated products, and analyze discount patterns.

## 🎯 Project Objectives

- Analyze product prices and identify the minimum and maximum selling prices.
- Identify brands with the highest average product prices.
- Compare customer ratings across different brands.
- Analyze discounts offered by different brands.
- Identify popular products based on customer ratings and number of ratings.
- Apply SQL concepts to a real-world e-commerce dataset.

## 🛠️ Tools and Technologies

- **Database:** MySQL
- **IDE:** MySQL Workbench
- **Query Language:** SQL
- **Dataset Source:** Originally downloaded from Kaggle

## 📂 Dataset Description

The dataset contains 52,120 Myntra product records and seven columns.

| Column Name | Description |
|---|---|
| `brand_name` | Name of the product brand |
| `pants_description` | Description of the product |
| `price` | Selling price of the product |
| `MRP` | Maximum Retail Price |
| `discount_percent` | Discount percentage |
| `ratings` | Customer rating |
| `number_of_ratings` | Number of customer ratings |

The recovered dataset is saved as `myntra_products.csv`.

## 📊 SQL Analysis Performed

The project contains 15 SQL queries covering:

1. Calculate the total number of products.
2. Count the number of unique brands.
3. Calculate the average selling price.
4. Find the minimum and maximum product prices.
5. Identify the five brands with the highest average selling prices.
6. Find the brand with the highest average rating.
7. Identify brands with an average rating above 4.
8. Find brands offering the highest average discounts.
9. Identify products with discounts greater than 50%.
10. Find the five most expensive products.
11. Identify brands with more than 100 products.
12. Find brands with the highest total number of ratings.
13. Identify highly rated products with at least 100 ratings.
14. Compare discount categories with average ratings.
15. Identify brands with good ratings and high discounts.

## 🧠 SQL Concepts Used

- `SELECT` and `WHERE`
- Aggregate functions: `COUNT()`, `AVG()`, `SUM()`, `MIN()`, `MAX()`
- `DISTINCT`
- `GROUP BY` and `HAVING`
- `ORDER BY` and `LIMIT`
- `ROUND()`
- Conditional expressions using `CASE WHEN`

## 🔍 Key Findings

According to the results recorded in the project report:

- Total products analyzed: 52,120
- Unique brands: 417
- Average selling price: ₹1,594.52
- Minimum selling price: ₹337
- Maximum selling price: ₹54,000
- Roadster had the highest total number of customer ratings in the reported analysis.

These findings help compare product pricing, brand performance, discounts, and customer engagement.

## 🚀 How to Run the Project

1. Install MySQL Server and MySQL Workbench.
2. Download or copy the `myntra_products.csv` dataset into your project folder.
3. Create a database:

   ```sql
   CREATE DATABASE myntra_db;
   USE myntra_db;
   ```

4. Create a table named `myntra_products` with columns matching the dataset.
5. Import the CSV into the table using MySQL Workbench.
6. Execute the SQL queries to perform the analysis.
7. Review the results and identify useful business insights.

## 📁 Project Structure

```text
Myntra-Product-Analysis-MySQL/
│
├── dataset/
│   └── myntra_products.csv
│
├── sql/
│   └── myntra_analysis.sql
│
├── screenshots/
│   └── query_results.png
│
└── README.md
```

*The folder and SQL filenames above are suggested. Replace them with your actual filenames.*

## 📝 Conclusion

This project demonstrates how MySQL can be used to analyze e-commerce product data and extract meaningful business insights. Using SQL queries and aggregate functions, the project explores product pricing, brand performance, discounts, and customer ratings.

The project strengthened practical SQL skills and demonstrated how data analysis can support product comparison and business decision-making.

## 👩‍💻 Author

**Meharin Ullas**



