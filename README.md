# Online Sales Data Cleaning & Preparation

## 📌 Project Overview

This project focuses on **Data Cleaning and Preparation** of an online retail sales dataset.

The objective was to review the raw transactional data, identify potential data-quality issues, standardize inconsistent fields, validate numerical information, and prepare the dataset for subsequent analysis.

This project was completed as **Project 1 of the DecodeLabs Data Analytics Internship — Batch 2026**.

The workflow followed the principle:

**Raw Data → Data Quality Assessment → Cleaning & Standardization → Validation → Analysis-Ready Dataset**

---

## 🎯 Project Objectives

The main objectives of this project were to:

* Review and understand the structure of the raw dataset.
* Identify missing or blank values.
* Check for duplicate transaction records.
* Standardize date fields.
* Validate numerical fields.
* Standardize categorical values.
* Validate revenue calculations.
* Create analytical date fields.
* Prepare a consistent dataset for further analysis.

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

The transactional structure of the dataset makes it suitable for subsequent analysis of sales performance, products, customers, order outcomes, and marketing activity.

---

# 🧹 Data Cleaning Process

## 1. Reviewed the Raw Dataset Structure

The raw dataset was first examined to understand:

* The transaction structure
* Available fields
* Customer and product information
* Date fields
* Sales and revenue fields
* Operational and marketing fields

This helped determine which fields required validation and preparation before analysis.

---

## 2. Checked for Missing Values

The dataset was reviewed for blank and missing entries.

Fields where missing values could affect calculations, categorization, or subsequent analysis were identified and reviewed.

This step helped ensure that incomplete records would not unintentionally affect analytical results.

---

## 3. Checked for Duplicate Records

Transaction and order records were reviewed for duplicate entries.

The purpose was to prevent duplicated transactions from affecting:

* Order counts
* Revenue calculations
* Customer analysis
* Product analysis

Duplicate checks were therefore treated as an important part of validating the integrity of the dataset.

---

## 4. Standardized Date Fields

The date field was reviewed and standardized into a consistent date format.

Additional analytical fields were created for:

* **Month**
* **Year**

These fields were prepared to support the sales-trend analysis that would follow during the exploratory analysis stage.

---

## 5. Validated Numeric Fields

Numerical fields were reviewed for consistency and appropriate formatting.

The main fields included:

* `Quantity`
* `UnitPrice`
* Revenue / transaction value

The objective was to ensure that numerical values could be reliably used in calculations and Pivot Tables.

---

## 6. Standardized Categorical Fields

Categorical fields were reviewed for inconsistent values that could cause the same category to appear as multiple groups during analysis.

The fields reviewed included:

* `Product`
* `PaymentMethod`
* `OrderStatus`
* `CouponCode`
* `ReferralSource`

Standardizing these fields helped ensure that future Pivot Table analysis would group categories correctly.

---

## 7. Validated Revenue Calculations

The relationship between **Quantity × UnitPrice** and the transaction/revenue values was reviewed.

This validation was important because revenue would later be used for:

* KPI calculations
* Product performance analysis
* Sales trend analysis
* Customer analysis

Ensuring that the underlying revenue values were reliable was therefore an important part of the preparation process.

---

## 8. Prepared the Dataset for Analysis

After completing the cleaning and validation checks, the dataset was maintained in a consistent tabular structure suitable for further analysis.

Derived fields such as **Month** and **Year** were also prepared for the next stage of the project.

The resulting dataset was ready to be used for **Exploratory Data Analysis (Project 2)**.

---

# 📋 Cleaning Summary

| Cleaning Area     | Action Taken                                     | Purpose                                         |
| ----------------- | ------------------------------------------------ | ----------------------------------------------- |
| Missing Values    | Reviewed blank and missing fields                | Prevent incomplete data from affecting analysis |
| Duplicates        | Checked transaction records for duplicates       | Prevent double-counting                         |
| Dates             | Standardized date formatting                     | Ensure consistent date analysis                 |
| Month / Year      | Created derived date fields                      | Support time-based analysis                     |
| Numeric Fields    | Validated Quantity, UnitPrice and revenue fields | Ensure reliable calculations                    |
| Product           | Reviewed and standardized categories             | Ensure accurate grouping                        |
| Payment Method    | Reviewed and standardized categories             | Ensure accurate grouping                        |
| Order Status      | Reviewed and standardized categories             | Ensure accurate order reporting                 |
| Coupon Code       | Reviewed and standardized entries                | Support coupon analysis                         |
| Referral Source   | Reviewed and standardized entries                | Support channel analysis                        |
| Revenue           | Validated transaction-value calculations         | Ensure reliable revenue analysis                |
| Dataset Structure | Maintained a consistent tabular format           | Prepare data for further analysis               |

---

# 🛠️ Tools Used

* **Microsoft Excel**
* Excel formulas
* Data cleaning and validation
* Data formatting
* Pivot Table preparation

---

# 🔄 Data Preparation Workflow

```text
Raw Online Sales Dataset
        ↓
Review Dataset Structure
        ↓
Check Missing Values
        ↓
Check Duplicate Records
        ↓
Standardize Dates
        ↓
Validate Numeric Fields
        ↓
Standardize Categorical Fields
        ↓
Validate Revenue
        ↓
Create Month & Year Fields
        ↓
Final Data Validation
        ↓
Analysis-Ready Dataset
```

---

# 💡 Key Learning Outcomes

This project strengthened my understanding of the importance of data quality before analysis.

Through the cleaning process, I practiced:

* Reviewing transactional datasets systematically
* Identifying potential data-quality issues
* Checking for missing and duplicate records
* Standardizing dates and categorical fields
* Validating numerical data
* Checking the reliability of calculated values
* Preparing structured data for Pivot Table analysis

A key takeaway from the project was that **reliable analysis depends on reliable data**. Cleaning and validation are therefore essential steps before calculating KPIs or drawing business conclusions.

---

# 📁 Project Files

```text
online-sales-data-cleaning/
│
├── README.md
│
├── data/
│   └── cleaned_sales_data.xlsx
│
└── images/
    └── cleaning-process.png
```

---

# 📌 Internship Context

**Program:** DecodeLabs Data Analytics Internship
**Batch:** 2026
**Project:** Project 1 — Data Cleaning & Preparation
**Domain:** Data Analytics
**Primary Tool:** Microsoft Excel

---


