# PowerBI-Dashboard-Olist-Ecommerce-Sales

### Dataset Link :https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## 📊 Project Overview

This project is an end-to-end data analysis of the Brazilian e-commerce dataset (Olist), aiming to extract meaningful business insights using SQL and Power BI. The dataset contains customer order data including payments, product categories, seller info, customer reviews, and delivery performance.

The final outcome is a multi-page interactive Power BI dashboard that presents deep insights into sales trends, product performance, seller analysis, and customer satisfaction.

## 📌 Problem Statement

The Brazilian e-commerce company is experiencing challenges in understanding customer satisfaction and sales trends across products, sellers, and regions. With large volumes of transaction, review, and delivery data, the company lacks a centralized and actionable view of business performance. There is a need to analyze sales patterns, identify top-performing categories and sellers, evaluate shipping delays, and uncover areas driving negative reviews.

This project aims to develop a Power BI dashboard using SQL for data preparation to help stakeholders make informed decisions, improve customer experience, and boost overall business efficiency.

## Project Workflow

This section outlines the step-by-step process followed to complete the end-to-end data analysis project using SQL and Power BI.

### 🔹 Step 1: Uploading Dataset to MySQL
- Imported all CSV files from the Olist Brazilian E-commerce dataset into MySQL.
- Created individual tables for each dataset, such as:
  - `orders`
  - `order_items`
  - `customers`
  - `products`
  - `sellers`
  - `order_reviews`
  - `product_category_name_translation`
  - `order_payments`
  - `geolocation`

<pre><code>```sql LOAD DATA LOCAL INFILE 'C:/Users/sameer kumar sahu/Desktop/MySQL_Datasets/Brazilian E-Commerce Public Dataset/olist_order_reviews_dataset.csv' INTO TABLE reviews FIELDS TERMINATED BY ',' ENCLOSED BY '"' LINES TERMINATED BY '\n' IGNORE 1 ROWS; ```</code></pre>
