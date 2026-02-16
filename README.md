# 🛒 Zepto Inventory & Pricing Analysis (SQL Project)

## 📌 Project Overview

This project analyzes a real-world styled e-commerce inventory dataset
scraped from Zepto's product listings (sourced from Kaggle). The dataset
simulates an online grocery inventory system where each row represents a
unique SKU (Stock Keeping Unit).

The objective of this project is to:

-   Perform structured data cleaning and validation
-   Analyze pricing and discount strategies
-   Evaluate inventory health
-   Estimate potential revenue
-   Identify value-for-money products
-   Generate actionable business insights using SQL

This project demonstrates strong SQL fundamentals, structured analytical
thinking, and business-oriented problem solving.

------------------------------------------------------------------------

# 🗂 Dataset Description

Each row represents a unique SKU.

## 📊 Columns

**sku_id:** Synthetic primary key
  
**category:** Product category (Fruits, Snacks, Beverages, etc.)
  
**name:** Product name
  
**mrp:** Maximum Retail Price (converted from paise to ₹)
  
**discountPercent:** Discount percentage applied
  
**discountedSellingPrice:** Final selling price (₹)
  
**availableQuantity:** Units available in inventory
  
**weightInGms:** Product weight in grams
  
**outOfStock:** Boolean stock availability flag
  
**quantity:** Units per package

------------------------------------------------------------------------

# 🛠 Project Workflow

## 1️⃣ Database & Table Creation

Created a structured SQL table with appropriate data types and
constraints.

## 2️⃣ Data Import

-   Imported CSV using pgAdmin\
-   Resolved UTF-8 encoding issue\
-   Verified successful row ingestion

## 3️⃣ Data Exploration

-   Verified total SKU count\
-   Observed sample records\
-   Checked null values\
-   Identified distinct categories\
-   Compared in-stock vs out-of-stock SKUs\
-   Detected duplicate product names

## 4️⃣ Data Cleaning & Transformation

-   Removed invalid price records\
-   Converted prices from paise to rupees

------------------------------------------------------------------------

# 📊 Business Insights

-   Top 10 best-value products based on discount percentage\
-   High MRP products are currently out of stock\
-   Estimated revenue per category\
-   Premium products with minimal discount\
-   Top 5 categories by average discount\
-   Price per gram analysis\
-   Weight-based segmentation\
-   Total inventory weight per category

------------------------------------------------------------------------

# 📈 Key Findings

-   Revenue concentration varies significantly across categories.\
-   Some categories rely heavily on a discount-driven sales strategy.\
-   Premium stock-outs indicate potential revenue leakage.\
-   Bulk packaging often delivers better price-per-gram value.

------------------------------------------------------------------------

# 🧠 Skills Demonstrated

-   SQL Data Modeling\
-   Data Cleaning & Transformation\
-   Aggregations & Grouping\
-   Conditional Logic (CASE)\
-   Revenue Estimation\
-   Inventory Risk Analysis\
-   Pricing Strategy Evaluation

------------------------------------------------------------------------

# 🛠 Tools Used

-   PostgreSQL
-   Kaggle Dataset

------------------------------------------------------------------------

# 👤 Author

Kalash Dwivedi

💼 LinkedIn: https://www.linkedin.com/in/kalash-dwivedi/

Let’s connect professionally and grow your data career
