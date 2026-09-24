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
🎯 Project Objectives
The major objectives of this project are:
Understand the structure and quality of the raw data.
Clean and preprocess all datasets.
Identify and handle missing and duplicate values.
Detect and handle outliers and invalid records.
Perform different types of joins using Pandas.
Create meaningful features for analysis.
Analyze sales, customers, products, payments, and reviews.
Create meaningful visualizations.
Extract important business insights.
Build a complete end-to-end E-Commerce analytics project.

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
### 🧹 Data Quality Challenges


The raw datasets contain several real-world-style data quality problems.
The project identifies and handles issues such as:
Missing values
Duplicate records
Invalid foreign keys
Incorrect data types
Invalid dates
Negative quantities
Negative amounts
Extreme outliers
Inconsistent category names
Inconsistent payment methods
Invalid ratings
Incorrect or unusual values
The objective is not simply to remove problematic records, but to understand the issue and apply an appropriate data-cleaning approach.

---

### 🛠️ Data Cleaning & Preprocessing
The following data-cleaning operations are performed throughout the project.
Missing Value Handling
Missing values are identified and handled using appropriate techniques depending on the column and business context.
Duplicate Detection
Duplicate records are identified and removed where appropriate.
Data Type Correction
Columns are converted into suitable data types for further analysis.
Examples include:
Date columns
Numerical columns
Categorical columns
Data Standardization
Inconsistent categorical values are standardized.

---

###  📊 Outlier Analysis
Outliers are investigated using statistical techniques such as the Interquartile Range (IQR) method.
The project uses:
Q1
Q3
IQR
Lower Bound
Upper Bound
to identify extreme observations.
However, statistical outliers are not automatically assumed to be incorrect.
Business rules are also considered when validating values.

---

### 🔗 Data Integration
After cleaning the individual datasets, the project combines the relational tables using Pandas joins and merges.
This creates a consolidated dataset that can be used for:
Sales analysis
Customer analysis
Product analysis
Payment analysis
Review analysis
Profitability analysis

---

### ⚙️ Feature Engineering
Several business-oriented features are created from the cleaned transactional data.

---

### 🔍 Exploratory Data Analysis
The project performs Exploratory Data Analysis across multiple business dimensions.
📈 Sales Analysis
Sales analysis includes:
Category-wise sales
Monthly sales trends
Revenue analysis
Order analysis
Average Order Value (AOV)
City-wise sales performance
Sales distribution across categories

🛍️ Product Analysis
Product-level analysis includes:
Product prices
Average product price
Category-wise pricing
Product performance
Stock-related analysis
Cost and selling price analysis

👥 Customer Analysis
Customer analysis includes:
Customer distribution
Customer demographics
City-wise customer analysis
Customer order behavior
Average Order Value by city

💳 Payment Analysis
Payment analysis includes:
Payment method distribution
Payment status
Transaction amounts
Payment-related patterns

⭐ Review Analysis
Customer review analysis includes:
Customer ratings
Rating distribution
Review-related patterns
Customer satisfaction indicators

---

### 📊 Data Visualization
Visualizations are used throughout the project to communicate patterns and business insights.
The project includes:
Bar Charts
Pie Charts
Histograms
Box Plots
Scatter Plots
Line Charts
Pair Plots

These visualizations are used to understand:-
Distributions
Trends
Category comparisons
Relationships between numerical variables
Sales composition
Product and customer patterns

---

### 📌 Key Business Metrics
Important metrics created or analyzed in the project include:
Total Orders
Sales
Gross Amount
Discount Amount
Net Amount
Profit
Profit Margin
Average Order Value (AOV)
Average Product Price
Customer Ratings

---

### 💼 Business Questions
The project uses the cleaned and integrated dataset to answer several business-oriented questions.
Examples include:
Which categories generate the highest sales?
Which categories generate the highest profit?
What is the average product price by category?
How do sales change over time?
Which cities have higher Average Order Value?
Which payment methods are most commonly used?
How do discounts affect sales and profitability?
Which products or categories perform better?
What patterns can be observed in customer ratings?
What are the major sales and profitability patterns in the business?

---

### 🧰 Tools & Technologies
The project was developed using:
Tool - 
Python ,
Pandas ,
NumPy ,
Matplotlib ,
Seaborn	 ,
Jupyter Notebook 

---

### 👨‍💻 Author
Ajeet Kumar
Data Science Aspirant
This project was created as part of my Data Science and Analytics learning journey to practice real-world data cleaning, exploratory analysis, visualization, and business problem-solving using Python.


### ⭐ Conclusion
This project demonstrates a complete E-Commerce Data Analytics workflow, starting from raw and imperfect datasets and progressing through data cleaning, integration, feature engineering, exploratory analysis, visualization, and business insight generation.
The project provides practical experience in converting raw transactional data into meaningful information that can support business analysis and decision-making.







