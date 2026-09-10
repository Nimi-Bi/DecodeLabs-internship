# Online Sales Performance Analysis

## 📌 Project Overview

This project analyzes an online retail sales dataset to understand sales performance, customer behavior, product performance, order outcomes, and marketing-related activity.

The project follows an end-to-end data analytics workflow:

**Data Cleaning → Exploratory Data Analysis → KPI Development → Business Analysis → Visualization → Insights**

The work was completed using **Microsoft Excel**, with data cleaning, Pivot Tables, calculated metrics, and an interactive dashboard used to transform raw transactional data into actionable business insights.

This project serves as **Project 1 (Data Cleaning & Preparation)** and **Project 2 (Exploratory Data Analysis)** of my Data Analytics internship at DecodeLabs.

---

## 🎯 Project Objectives

The main objectives of the project were to:

* Clean and prepare the raw sales dataset for analysis.
* Identify and address data-quality issues.
* Standardize dates, numerical fields, and categorical values.
* Develop key sales and customer performance metrics.
* Analyze sales trends across time.
* Evaluate product and order performance.
* Explore customer purchasing behavior.
* Analyze coupon usage and referral sources.
* Translate the findings into Pivot Tables, charts, and an interactive Excel dashboard.

---

## 📊 Dataset

The dataset contains online retail transaction records covering sales, customers, products, orders, payments, and marketing-related information.

Key fields include:

* `OrderID`
* `Date`
* `CustomerID`
* `Product`
* `Quantity`
* `UnitPrice`
* `ShippingAddress`
* `PaymentMethod`
* `OrderStatus`
* `CouponCode`
* `ReferralSource`
* `Revenue`

The dataset was structured around individual sales transactions, allowing analysis at the order, customer, product, and marketing-channel levels.

---

# 🧹 Project 1 — Data Cleaning & Preparation

Before performing the analysis, the dataset was reviewed and prepared to ensure that the results would be based on consistent and reliable data.

### 1. Dataset Structure Review

The raw dataset was examined to understand:

* Transaction structure
* Available fields
* Customer and product information
* Date coverage
* Sales and revenue fields
* Operational and marketing fields

The fields required for the subsequent sales, product, customer, order-status, coupon, and referral-source analyses were identified.

### 2. Missing Value Checks

The dataset was reviewed for blank and missing entries.

Fields where missing values could affect calculations, categorization, or analysis were identified and reviewed during the cleaning process.

### 3. Duplicate Checks

Transaction and order records were checked for duplicate entries.

This was important to prevent duplicate records from distorting:

* Order counts
* Revenue calculations
* Customer analysis
* Product performance results

### 4. Date Standardization

Date fields were standardized into a consistent format.

Additional **Month** and **Year** classifications were created to support time-based sales analysis.

### 5. Numeric Field Validation

Numerical fields such as:

* `Quantity`
* `UnitPrice`
* Revenue / transaction value

were reviewed to ensure that they were stored and formatted appropriately for calculations and Pivot Table analysis.

### 6. Categorical Data Standardization

Categorical fields were reviewed and standardized to ensure that inconsistent values would not be treated as separate categories during analysis.

The fields reviewed included:

* Product
* Payment Method
* Order Status
* Coupon Code
* Referral Source

### 7. Revenue Validation

The relationship between **Quantity × UnitPrice** and the transaction/revenue values was checked.

This validation was important because revenue was used throughout the KPI and product-performance analysis.

### 8. Dataset Preparation

After cleaning and validation, the dataset was maintained in a consistent tabular structure suitable for Pivot Tables and further analysis.

Derived fields such as Month and Year were also prepared for subsequent analysis.

---

# 🔎 Project 2 — Exploratory Data Analysis

Following the cleaning process, Exploratory Data Analysis (EDA) was performed to identify patterns, trends, and performance differences within the sales data.

## 1. Overall Sales Performance

Core KPIs were developed to establish a baseline view of business performance.

These included:

* Total Revenue
* Total Orders
* Total Customers
* Total Items Sold
* Average Order Value
* Revenue per Customer
* Average Items per Order

These metrics provided the foundation for the subsequent analysis.

---

## 2. Sales Trend Analysis

Month and Year classifications were used to investigate sales performance over time.

The analysis examined:

* Revenue by month
* Revenue by year
* Monthly sales patterns
* Changes in performance across years
* Potential seasonal fluctuations

This helped identify **when sales were being generated** rather than relying solely on overall revenue totals.

---

## 3. Order Status Analysis

Orders were analyzed according to their status, including categories such as:

* Completed / Delivered
* Shipped
* Pending
* Cancelled
* Returned

The analysis was used to evaluate operational performance through metrics such as:

* Completed order rate
* Cancellation rate

---

## 4. Product Performance Analysis

Products were compared using:

* Quantity sold
* Sales volume
* Revenue generated

This analysis helped distinguish between products that generated high sales volume and products that generated high revenue.

A key analytical consideration was that the product selling the most units is not necessarily the product generating the most revenue.

---

## 5. Customer Analysis

Customer purchasing behavior was explored through:

* Unique customer counts
* Customer spending
* Revenue per customer
* One-time versus repeat purchasing
* Highest-spending customers

The objective was to better understand customer contribution to overall sales performance and whether revenue was primarily driven by customer acquisition or retention.

---

## 6. Coupon Performance Analysis

The coupon-code field was analyzed to understand the role of promotional activity in sales performance.

The analysis considered:

* Coupon usage frequency
* Revenue associated with coupon usage
* Contribution of coupon-driven sales
* Coupon dependency

---

## 7. Referral Source Analysis

Referral sources were compared to understand how different acquisition channels contributed to sales.

Sources included channels such as:

* Instagram
* Facebook
* Google
* Email
* Referral

The analysis considered:

* Order volume
* Revenue
* Average revenue per order

This provided a way to compare both the volume and potential value of different acquisition channels.

---

# 📈 Dashboard & Reporting

The results of the analysis were transformed into an interactive Excel reporting layer using:

* KPI cards
* Pivot Tables
* Pivot Charts
* Sales trend visualizations
* Product performance analysis
* Customer analysis
* Coupon analysis
* Referral-source analysis
* Order-status reporting

The dashboard brought the different analytical areas together into a single reporting view.

---

# 🛠️ Tools & Skills

### Tools

* **Microsoft Excel**
* Pivot Tables
* Pivot Charts
* Excel formulas
* Data cleaning and preparation
* Data visualization

### Analytical Skills

* Data cleaning
* Data validation
* Exploratory Data Analysis
* KPI development
* Trend analysis
* Product analysis
* Customer analysis
* Operational analysis
* Marketing/channel analysis
* Business insight generation
* Data storytelling

---

# 🔄 Analytical Workflow

Raw Transaction Data 

        ↓ 
Dataset Structure Review

        ↓
Data Quality Assessment

        ↓
Missing Value & Duplicate Checks

        ↓
Date & Numeric Validation

        ↓
Categorical Standardization

        ↓
Revenue Validation

        ↓
Derived Fields (Month & Year)

        ↓
KPI Development

        ↓
Exploratory Data Analysis

        ↓
Sales & Product Analysis

        ↓
Customer & Order Analysis

        ↓
Coupon & Referral Analysis

        ↓
Business Insights

        ↓
Pivot Tables & Charts

        ↓
Interactive Excel Dashboard

```

---

# 📁 Project Structure

`
online-sales-performance-analysis/
│
├── README.md
│
├── data/
│   └── cleaned_sales_data.xlsx
│
├── analysis/
│   └── online_sales_analysis.xlsx
│
└── images/
    ├── dashboard.png
    ├── sales-trend-analysis.png
    └── product-performance.png
```

# 💡 Key Learning Outcomes

This project strengthened my ability to move from raw transactional data to a structured analytical output.

Key areas of learning included:

* Preparing messy transactional data for analysis
* Validating data before drawing conclusions
* Using Pivot Tables to explore large datasets
* Developing meaningful business KPIs
* Analyzing sales performance from multiple perspectives
* Connecting data patterns to business questions
* Presenting analytical findings through an interactive dashboard

Most importantly, the project reinforced the principle that **good analysis starts with reliable data**.

## 📌 Project Context

This project was completed as part of the **DecodeLabs Data Analytics Internship — Batch 2026**.

**Project 1:** Data Cleaning & Preparation

**Project 2:** Exploratory Data Analysis
