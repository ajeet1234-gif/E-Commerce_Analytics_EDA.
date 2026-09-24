# 🛒 E-Commerce Analytics EDA

## 📌 Project Overview

This project is an end-to-end **E-Commerce Sales Analytics and Exploratory Data Analysis (EDA)** project built using Python.

The project works with multiple interconnected E-Commerce datasets and focuses on transforming raw and messy data into a clean, analysis-ready dataset.

The analysis covers:

- Data Cleaning & Preprocessing
- Missing Value Handling
- Duplicate Detection
- Data Type Correction
- Invalid Value Detection
- Outlier Analysis
- Data Standardization
- Data Transformation
- Table Joins
- Feature Engineering
- Exploratory Data Analysis
- Business Question Analysis
- Data Visualization
- Business Insights

---

## 📊 Dataset Structure

The project contains six relational tables:

### 1. Customers
Contains customer demographic and registration information.

### 2. Products
Contains product details such as:

- Product
- Category
- Brand
- Price
- Stock
- Supplier

### 3. Orders
Contains order-level information including:

- Customer
- Order Date
- Order Status
- Coupons
- Discounts
- Delivery information

### 4. Order Items
Contains individual products and quantities associated with each order.

### 5. Payments
Contains:

- Payment Method
- Payment Status
- Payment Date
- Transaction Amount

### 6. Reviews
Contains:

- Customer Ratings
- Review Dates
- Review Text

---

## 🔗 Table Relationships

The datasets are connected through primary and foreign keys.

```text
Customers
    │
    │ customer_id
    ↓
Orders
    │
    ├──────────────→ Payments
    │
    ├──────────────→ Reviews
    │
    ↓
Order_Items
    │
    │ product_id
    ↓
Products
