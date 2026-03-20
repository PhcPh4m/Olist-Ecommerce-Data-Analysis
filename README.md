# Olist Brazilian E-Commerce Data Analysis

## Project Overview
This project performs an end-to-end data analysis on the **Olist E-Commerce dataset**, the largest department store in Brazilian marketplaces. By leveraging **PySpark** and **SQL**, the project aims to transform raw transactional data into actionable business insights, focusing on customer behavior, operational efficiency, and sales performance.

## Tech Stack & Tools
- **Language:** Python
- **Big Data Framework:** Apache Spark (PySpark SQL & DataFrames)
- **Environment:** Google Colab & HDFS Simulation
- **Visualization:** Matplotlib, Seaborn
- **Key Techniques:** - ETL Pipeline & Data Cleaning
  - RFM Segmentation (Recency, Frequency, Monetary)
  - Market Basket Analysis
  - Geospatial Analytics

## Dataset Architecture
The project utilizes 9 interrelated datasets provided by Olist:
- `olist_orders_dataset`: Core order information and status.
- `olist_order_items_dataset`: Detailed items within each order.
- `olist_order_payments_dataset`: Payment methods and installment details.
- `olist_customers_dataset`: Customer location and identification.
- `olist_products_dataset`: Product attributes (category, dimensions, weight).
- `olist_order_reviews_dataset`: Customer feedback and ratings.
- `olist_sellers_dataset` & `product_category_name_translation`: Supporting metadata.

## Analytical Goals (Business Questions)
1. **Customer Segmentation (RFM):** Identifying "Champions" and "At Risk" customers to optimize marketing strategies.
2. **Operational Excellence:** Analyzing shipping performance and delivery delays across different Brazilian states.
3. **Product Strategy:** Identifying top-performing categories using the Pareto Principle (80/20 rule).
4. **Consumer Behavior:** Discovering product associations to suggest effective "frequently bought together" bundles.

## Key Highlights & Optimizations
- **Scalable Processing:** Utilizing PySpark DataFrames instead of Pandas to handle large-scale joins across 9 tables efficiently.
- **Advanced SQL:** Implementing Window Functions for ranking and complex business logic aggregations.
- **Data Integrity:** Professional handling of null values and translation of Portuguese categories to English for better accessibility.

---
*Note: This project is currently in progress. Detailed insights and visualizations will be updated following the next sprint.*

---
*Dự án đang trong quá trình thực hiện và cập nhật định kỳ.*
