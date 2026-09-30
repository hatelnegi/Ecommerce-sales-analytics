# 🛍️ E-Commerce Sales Analytics

## 📌 Project Overview

This project analyzes e-commerce sales, customer activity, website sessions, pageviews, marketing sources, products, and refunds using Python.

The analysis focuses on understanding sales performance, customer behavior, website activity, marketing performance, and refund patterns.

---

## 🎯 Project Objectives

The key objectives of this project are to:

- Analyze monthly revenue and order trends
- Understand revenue and order performance by product
- Analyze website sessions across different devices
- Identify major website traffic sources
- Compare new and repeat website sessions
- Analyze conversion rates by marketing source
- Examine refund amounts by product
- Understand website pageview behavior
- Calculate key business KPIs such as Average Order Value and Refund Rate
- Identify customers with the highest revenue contribution

---

## 📂 Datasets

The project uses six datasets:

| Dataset | Records | Columns |
|---|---:|---:|
| Orders | 32,313 | 8 |
| Order Items | 40,025 | 7 |
| Refunds | 1,731 | 5 |
| Products | 4 | 3 |
| Website Sessions | 472,871 | 9 |
| Website Pageviews | 1,188,124 | 4 |

### Main Data Areas

- **Orders** — order-level sales information
- **Order Items** — individual items associated with orders
- **Refunds** — refund transactions
- **Products** — product information
- **Website Sessions** — website visit and marketing-source information
- **Website Pageviews** — website pageview activity

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🧹 Data Preparation

The notebook includes several data preparation and validation steps:

- Loading multiple CSV datasets
- Reviewing dataset dimensions and columns
- Checking data types
- Checking missing values
- Checking duplicate records
- Checking invalid or negative values
- Converting date columns to datetime format
- Checking date ranges
- Validating ID fields
- Reviewing categorical variables
- Creating date-based features for analysis

---

## 📊 Analysis Performed

### 1. Monthly Revenue Analysis

Monthly revenue was calculated to understand revenue patterns over time and visualize monthly performance.

### 2. Revenue by Product

Revenue was grouped by product to compare the contribution of different products.

### 3. Orders by Product

The number of unique orders was analyzed by product to understand product-level order volume.

### 4. Website Sessions by Device

Website sessions were analyzed across device types to understand how customers accessed the website.

### 5. Website Sessions by Traffic Source

Sessions were grouped by marketing/traffic source to understand where website traffic originated.

### 6. New vs Repeat Sessions

Website sessions were categorized to compare new and repeat session activity.

### 7. Marketing Source Conversion Rate

Orders were connected with website sessions using the website session ID to calculate conversion rates by marketing source.

### 8. Refund Analysis

Refund amounts were analyzed by product to identify products associated with higher refund values.

### 9. Website Pageviews

Pageviews per session were calculated to understand website engagement.

### 10. Orders by Device

Orders were analyzed by device type to compare order activity across devices.

### 11. Customer Revenue

Customer-level revenue was calculated to identify customers with the highest revenue contribution.

---

## 📈 Key KPIs

### Average Order Value

The calculated Average Order Value (AOV) in the analysis is:

**$59.99**

### Refund Rate

The calculated refund rate is:

**4.40%**

These KPIs provide a high-level view of average transaction value and the proportion of revenue represented by refunds.

---

## 🔍 Key Areas of Insight

The analysis explores several important business questions:

- Which products generate the most revenue?
- Which products receive the highest number of orders?
- Which devices generate the most website sessions and orders?
- Which marketing sources generate the most website traffic?
- Which marketing sources have higher conversion rates?
- How do new and repeat sessions compare?
- Which products have higher refund amounts?
- How engaged are website visitors based on pageviews per session?
- Which customers contribute the highest revenue?

---

## 💡 Business Applications

The analysis can support business decisions related to:

- Product performance
- Marketing channel performance
- Website optimization
- Customer engagement
- Refund monitoring
- Sales performance
- Customer value analysis

---

## 📁 Repository Contents

```text
ecommerce-sales-analytics/
│
├── ECommerce_Python_Analysis.ipynb
└── README.md
