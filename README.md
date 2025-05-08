# PowerBI-Dashboard-Olist-Ecommerce-Sales

### Dataset Link :https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## 📊 Project Overview

This project is an end-to-end data analysis of the Brazilian e-commerce dataset (Olist), aiming to extract meaningful business insights using SQL and Power BI. The dataset contains customer order data including payments, product categories, seller info, customer reviews, and delivery performance.

The final outcome is a multi-page interactive Power BI dashboard that presents deep insights into sales trends, product performance, seller analysis, and customer satisfaction.

## 📌 Problem Statement

The Brazilian e-commerce company is experiencing challenges in understanding customer satisfaction and sales trends across products, sellers, and regions. With large volumes of transaction, review, and delivery data, the company lacks a centralized and actionable view of business performance. There is a need to analyze sales patterns, identify top-performing categories and sellers, evaluate shipping delays, and uncover areas driving negative reviews.

This project aims to develop a Power BI dashboard using SQL for data preparation to help stakeholders make informed decisions, improve customer experience, and boost overall business efficiency.

## 📁 Tools Used

-SQL(MySQL Workbench): Data upload and query execution.
-Power BI Desktop: Data modeling and dashboard creation.
-GitHub: Project documentation and version control.

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

### 🔹 Step 2: Data Integration Using SQL JOINs
- Select important cloumns for my Dashboard.
- Used `JOIN` operations in SQL to merge relevant tables for analysis.
- Created views or final tables that consolidate customer, order, product, payment, and review information.
  Snap of the query,
 ![Image](https://github.com/user-attachments/assets/55056fe5-0979-4b6b-af3a-6b19c84ac8d3)

### 🔹 Step 3: Connecting MySQL to Power BI
- Connected Power BI to the MySQL database.
- After Load the data, open Power Query Editor and clean the merged data. Like verify all columns data types, fill the null values & created some new columns etc. Based on my problem statement and dashboard.
![Image](https://github.com/user-attachments/assets/e798cf34-2c13-4275-b062-e8610cd6b269)
- Imported the cleaned and joined data directly into Power BI for visualization.

### 🔹 Step 4: Building the Power BI Dashboard
- Created multiple pages in Power BI covering different analysis areas:
  - **Sales Overview**
  - **Product & Category Analysis**
  - **Custome & Profitability Performance**
  - **Customer Review & Satisfaction**
- Used slicers and filters to make the dashboard interactive and dynamic.
- Implemented KPIs, bar charts, pie charts, line charts, and tables for deep insights.

### 🔹 DashBoard Creation On Power BI
- Page 1: Sales & Order Trends – Monthly trends, total orders, revenue, customer state-wise breakdown.

![Image](https://github.com/user-attachments/assets/f064bd36-89f1-4cb0-881c-4f21da7b26d8)

- Page 2: Product & Category Analysis – Top categories/products by revenue and units sold, seller performance.

![Image](https://github.com/user-attachments/assets/0d670d75-a838-40f3-a4a2-e8a4a8143b3a)

- Page 3: Customer & Profitability – Total Customers, Repet Customer, Net revenue.

![Image](https://github.com/user-attachments/assets/749a31c2-8b70-42be-bd2d-efcf55bef3bd)

- Page 4: Reviews & Customer Satisfaction – Review score distribution, satisfaction trends, categories with low/high ratings.

![Image](https://github.com/user-attachments/assets/4ca7bddb-4a9a-481c-a6b5-2602ec19c6cc)

![Image](https://github.com/user-attachments/assets/70da8c7f-0736-4fde-be5d-261331d9f119)

![Image](https://github.com/user-attachments/assets/cba60ea4-1341-4ac2-a573-62ae9efdfe2a)

### DashBoard Live





