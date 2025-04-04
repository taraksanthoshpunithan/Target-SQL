
# 🔍**Target-SQL**📈

This repository presents a comprehensive business case study of a leading retail supermarket, leveraging SQL to analyze data and extract actionable insights for strategic decision-making.

---

## 📌 **Introduction** 

![Target Logo](https://github.com/taraksanthoshpunithan/src/blob/main/images/TargetLogo.jpeg?raw=true)

**Target** is a globally recognized retail brand based in the **United States**, known for its outstanding value, innovation, and exceptional customer experience. 

This case study focuses on **Target's operations in Brazil**, analyzing **100,000 orders** placed between **2016 and 2018**.

The dataset covers:

✅ **Order Status & Pricing**  
✅ **Payment & Freight Performance**  
✅ **Customer Locations & Demographics**  
✅ **Product Attributes & Customer Reviews**  

By analyzing this dataset, we aim to explore key business metrics, including **order trends, pricing strategies, shipping efficiency, and customer satisfaction**.

This project was conducted using **Google BigQuery** for data storage, processing, and analysis.

---

## 📌 **Dataset Overview**

### 📥 **Dataset Location** 

The dataset used in this study is available here: **[Dataset](https://drive.google.com/drive/folders/1TGEc66YKbD443nslRi1bWgVd238gJCnb)**  

### 📊 **Files Included** 

The dataset consists of **8 CSV files**, each containing key business information:

| 📜 **File Name** | 📄 **Description** |
|-------------|--------------|
| `customers.csv` | Customer details (ID, location, etc.) |
| `geolocation.csv` | Geographic coordinates of customers |
| `order_items.csv` | Product-level details of each order |
| `payments.csv` | Payment method, installment details, and values |
| `reviews.csv` | Customer reviews and feedback |
| `orders.csv` | Order-level data (status, timestamps, etc.) |
| `products.csv` | Product details (categories, descriptions, etc.) |
| `sellers.csv` | Seller details and locations |

---

## 📊 **Database Schema**  

![Schema](https://github.com/taraksanthoshpunithan/src/blob/main/images/TargetSchema.png?raw=true)

---

## 🔍 **Project Objective** 

The goal of this project is to **analyze the dataset**, uncover **valuable insights**, and provide **data-driven recommendations** for business optimization.

### 🔹 **Exploratory Data Analysis (EDA)** 

✔ Identify data types in the `customers` table  
✔ Determine the time range of order placements  
✔ Count customer distribution by **city** and **state**  

### 🔹 **Order Trends Analysis** 

✔ Identify **annual and monthly order trends**  
✔ Detect **seasonal patterns** in customer orders  
✔ Analyze **order placements based on time of day**  

### 🔹 **E-Commerce Growth in Brazil** 

✔ Track **monthly order volumes per state**  
✔ Visualize **customer distribution across regions**  

### 🔹 **Economic Impact Analysis** 

✔ Calculate **YoY% increase in order costs (2017 vs. 2018)**  
✔ Analyze **total & average order price** per state  
✔ Evaluate **total & average freight cost** per state  

### 🔹 **Shipping & Delivery Performance** 

✔ Compute **average delivery time** for each order  
✔ Compare **estimated vs. actual delivery times**  
✔ Identify states with **fastest & slowest deliveries**  
✔ Rank **top 5 states** by **freight cost & delivery time**  

### 🔹 **Payment Analysis**

✔ Identify **monthly trends** in payment methods  
✔ Categorize orders based on **installments paid**  

---

## 🎯 **Conclusion** 

This **SQL-based business case study** on **Target's Brazil operations** provides key insights into **customer behavior, sales trends, logistics performance, and economic impact**. These findings can help **optimize supply chain processes, improve customer satisfaction, and enhance business strategies** for long-term growth.  

---
