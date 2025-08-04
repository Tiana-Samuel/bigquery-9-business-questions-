# BigQuery Business Analytics Project
This project demonstrates how Google BigQuery can be used to answer key business questions using real-world transactional data. The analysis uncovers customer behavior, product performance, and sales trends through structured queries and data aggregation.

## 🔍 Project Objective
To extract actionable insights from sales, customer, and product data using SQL queries in Google BigQuery. This analysis answers 9 core business questions relevant to decision-making in e-commerce or retail environments.

## 📊 Dataset Overview
The dataset contains three main tables:
- `CUSTOMER`: Contains customer ID, name, gender, location, etc.
- `PRODUCT`: Contains product ID, name, category, and price.
- `TRANSACTION`: Contains transaction details, including date, product purchased, customer ID, payment method, and total price.

## ❓ 9 Business Questions Answered
1. **What are the details of all transactions made by the customer with ID 1000?**
2. **Which products are the most frequently purchased?**
3. **How much has each customer spent in total?**
4. **What are the total sales for each product category?**
5. **What is the average value of transactions for each customer?**
6. **What are the monthly sales trends for each product?**
7. **Which payment methods are most commonly used?**
8. **Who are the top 10 customers by total spending?**
9. **How many transactions occurred each day?**

## Tools & Technologies
- **Google BigQuery** – for SQL querying and cloud data analysis
- **Google Cloud Console** – for managing queries and results
- **SQL** – for data exploration, joins, aggregation, and filtering

## ✅ How to Reproduce
1. Open [Google Cloud Console](https://console.cloud.google.com/).
2. Navigate to BigQuery.
3. Import the dataset tables: `CUSTOMER`, `PRODUCT`, `TRANSACTION`.
4. Run the provided SQL queries in the BigQuery editor.
5. Review results, filter, or export for visualization.
