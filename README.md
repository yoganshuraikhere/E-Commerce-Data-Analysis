# E-Commerce Data Analysis using PySpark

📌 Project Overview
This project involves analyzing an e-commerce dataset using PySpark to extract valuable business insights. The dataset includes information on customers, orders, products, sellers, payments, reviews, and geolocations.

**Key Objectives**:
* Identify top-selling products.
* Compute revenues within specific date ranges.
* Count total orders by product category.
* Analyze customer distribution by region.
* Implement error handling and logging.
* Visualize key insights using Matplotlib / Seaborn.

**🛠 Technologies Used**
Databricks / PySpark – For big data processing.
Azure / DBFS – Cloud storage for datasets.
Matplotlib / Seaborn – For data visualization.
Python Logging & Exception Handling – To ensure robustness.
📂 Dataset Description
The dataset consists of multiple related tables:

**Table Name	Description**
customers	Customer details (ID, region, etc.)
geolocation	Geographical information (city, state, latitude, longitude)
order_items	Details of items in each order
order_payments	Payment details for each order
order_reviews	Customer reviews and ratings
orders	Order records with timestamps
products	Product details (name, category, price, etc.)
sellers	Seller details (ID, region, etc.)
product_translation	Product descriptions in different languages

**🚀 Implementation Steps**
  * Data Loading & Cleaning
      Load CSV/Parquet files into PySpark DataFrames.
      Handle missing values and duplicates.
  * Transformations & Business Insights
      Identify top-selling products based on total orders.
      Calculate revenues within date ranges.
      Count total orders by product category.
      Analyze customer distribution by regions.
      Find revenue generated annually.
      Find Most valued Customers and Salesman.
      Product_Category sales over Time for Product Category informatica_acessorios over 2 months from 2017-05-01 to 2017-07-01.
      Total Orders by city.
      Most Reviewed product.
      Find min and max priced products.
      Returning Customers to understand Customer loyalty.
      Show how many orders have been placed by how many customers.
      etc.  
  * Error Handling & Logging
      Implemented structured logging for debugging.
      Used exception handling to catch and log errors.
  
  * Visualization & Reporting
    Used Matplotlib & Seaborn for trend analysis.

📜 Key Takeaways
* PySpark for large-scale data processing.
* Logging & error handling for debugging.
* Data visualization for actionable insights.

👨‍💻 Author
* Yoganshu Raikhere – Data Engineering Enthusiast
