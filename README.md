# SQL-Data-analytics-project-E-commerce
The goal is to analyze structured business data, understand its behavior, and transform raw data into actionable insights through systematic exploration, aggregation, and reporting.

# 📊 Data Analytics Project – Sales Analysis

## 📌 Project Overview

This project demonstrates an **end-to-end data analytics workflow** using a **star schema sales dataset**.  
It follows a structured approach starting with **Exploratory Data Analysis (EDA)** and extending to **Advanced Analytics**, transforming raw transactional data into **business-ready insights**.

The project reflects how Data Analysts work in real-world environments using SQL-based analysis and reporting logic.

---

## 🗂 Dataset Description

The data model follows a **star schema** consisting of one fact table and two dimension tables.

### 1️⃣ fact_sales
**Grain:** one row per sales transaction  

**Key columns:**
- `order_id`
- `order_date`
- `customer_key`
- `product_key`
- `sales_amount`
- `quantity`
- `discount_amount`

This table contains all measurable business metrics and transactional data.

---

### 2️⃣ dim_customers
**Purpose:** customer-level attributes  

**Example columns:**
- `customer_key`
- `customer_id`
- `gender`
- `country`
- `segment`

Used for customer segmentation and demographic analysis.

---

### 3️⃣ dim_products
**Purpose:** product-level attributes  

**Example columns:**
- `product_key`
- `product_name`
- `category`
- `subcategory`

Used for product, category, and part-to-whole analysis.

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA phase focuses on understanding the structure, quality, and behavior of the data.

### ✔ Database Exploration
- Understanding table structure and relationships
- Identifying primary and foreign keys
- Verifying fact–dimension joins

### ✔ Dimensions Exploration
- Analyzing categorical variables (customers, products, categories)
- Checking cardinality and uniqueness

### ✔ Date Exploration
- Analyzing order dates
- Identifying time range and granularity (daily, monthly, yearly)

### ✔ Measures Exploration
- Reviewing numerical metrics such as sales, quantity, and discounts
- Detecting missing values and extreme values

### ✔ Magnitude Analysis
- Comparing sales volumes across categories and customers
- Understanding distribution and scale of metrics

### ✔ Ranking Analysis
- Top-N and Bottom-N customers and products
- Identifying best and worst performers

---

## 📈 Advanced Analytics

After EDA, deeper analytical techniques are applied to generate actionable insights.

### 🔹 Change-over-Time Analysis
- Sales trends over time
- Growth and decline patterns

### 🔹 Cumulative Analysis
- Running totals of sales
- Year-to-date (YTD) performance tracking

### 🔹 Part-to-Whole Analysis
- Contribution of products and categories to total sales
- Percentage-based insights

### 🔹 Performance Analysis
- KPI evaluation (sales, quantity, discounts)
- Performance comparison across segments

### 🔹 Data Segmentation
- Customer and product segmentation
- Segment-level performance insights

### 🔹 Reporting
- Aggregated, reporting-ready datasets
- Designed for visualization in Power BI or similar BI tools

---

## 🛠 Tools & Skills Used

- **SQL**
  - Joins, aggregations
  - CTEs and window functions
- **Data Modeling**
  - Star schema understanding
- **Analytical Thinking**
  - Business KPIs and metrics
- **Reporting & BI Readiness**

---

## 🎯 Key Outcomes

- Clear understanding of sales performance drivers
- Structured analytical workflow from raw data to insights
- Reusable SQL logic for reporting and dashboards
- Strong portfolio project aligned with **Data Analyst roles**

---



## 👤 Author

**Ismail Drissi-Bahi**  
Bachelor in Business Mathematics  
Aspiring Data Analyst
