# Customer Shopping Behavior Analysis

> End to end Customer Shopping Behavior Analysis using **Python, PostgreSQL, and Power BI** to uncover customer spending patterns, product performance, subscription behavior, loyalty trends, and actionable business insights.

---

## Overview

The goal of this project is to transform raw customer shopping data into meaningful business insights.

### Analysis Focus

- Customer spending and revenue
- Product and category performance
- Customer loyalty and repeat purchases
- Subscription behavior
- Discounts and promotions
- Age group spending
- Shipping behavior
- Customer reviews and ratings

---

## Dataset

The project uses a **Customer Shopping Behavior** dataset containing **3,900 purchase records**.

### Dataset Includes

| Column | Description |
|---|---|
| Customer ID | Unique customer identifier |
| Age | Customer age |
| Gender | Customer gender |
| Product Purchased | Product purchased by the customer |
| Category | Product category |
| Purchase Amount | Amount spent on the purchase |
| Location | Customer location |
| Size | Product size |
| Color | Product color |
| Season | Purchase season |
| Review Rating | Customer review rating |
| Subscription Status | Customer subscription status |
| Shipping Type | Shipping method used |
| Discount Applied | Whether a discount was applied |
| Previous Purchases | Number of previous purchases |
| Payment Method | Payment method used |
| Frequency of Purchases | Customer purchase frequency |

### Additional Features

Additional features were created during the analysis:

- `age_group` — Groups customers based on age
- `purchase_frequency_days` — Converts purchase frequency into approximate days

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** | Data loading, cleaning, EDA, and feature engineering |
| **Pandas** | Data manipulation and analysis |
| **PostgreSQL** | Database storage and SQL analysis |
| **SQL** | Business questions and analytical queries |
| **Power BI** | Interactive dashboard and visualization |
| **Microsoft Powerpoint** | Presentation creation |

---

## Project Workflow

### 1. Data Loading

The customer shopping dataset was loaded into Python using Pandas.

### 2. Exploratory Data Analysis

The dataset was explored using:

- `df.info()`
- `df.describe()`
- Null value checks
- Column inspection
- Basic statistical analysis

### 3. Data Cleaning

The cleaning process included:

- Standardizing column names
- Checking missing values
- Handling missing review ratings using category-level median values
- Removing redundant columns
- Checking data consistency

### 4. Feature Engineering

Two additional features were created:

- `age_group` — Groups customers based on age
- `purchase_frequency_days` — Converts purchase frequency into approximate days

### 5. PostgreSQL Integration

The cleaned DataFrame was loaded into PostgreSQL using **SQLAlchemy** and **psycopg2**.

### 6. SQL Business Analysis

SQL queries were used to answer business questions related to:

- Revenue
- Products
- Subscriptions
- Discounts
- Customer loyalty
- Repeat purchases
- Shipping
- Age groups

### 7. Power BI Dashboard

The cleaned data was connected to Power BI to create an interactive dashboard containing:

- Total purchases
- Average purchase amount
- Average review rating
- Subscription breakdown
- Revenue by category
- Revenue by age group
- Customer behavior insights
- Interactive filters

### 8. Report & Presentation

The findings were summarized in an analysis report and presented through a PowerPoint presentation.

---

## Dashboard

The Power BI dashboard provides an interactive view of customer shopping behavior.

### Dashboard Sections

- Revenue Analysis
- Category Performance
- Subscription Behavior
- Customer Loyalty
- Age Group Analysis
- Shipping Analysis
- Product Ratings
- Discount Analysis

> **Power BI Dashboard:** 
<p align="center">
  <img src="SS/DASHBOARD.png" width="900">
</p>


## Key Results

Some of the major findings from the analysis include:

### Revenue

- Clothing and Accessories contribute roughly **77% of total revenue**.

### Subscription Behavior

- Subscribers represent approximately **27% of the dataset**.
- Average spending between subscribers and non-subscribers is relatively similar.

### Customer Loyalty

- The customer base contains a large **Loyal** segment.
- Repeat buyers represent a strong opportunity for subscription adoption.

### Product Ratings

- **Gloves** have the highest average review rating among the top-rated products.

### Discounts

- **Hat** has the highest discount rate among the analyzed products.

### Age Groups

- Revenue is relatively balanced across different age groups.

---

## Business Recommendations

Based on the analysis:

### 1. Increase Subscription Adoption

Increase subscription adoption among regular customers by providing stronger incentives and benefits.

### 2. Target Repeat Buyers

Target repeat buyers with subscription offers because they have already demonstrated ongoing engagement.

### 3. Review Discount Strategies

Review discount strategies to ensure promotions support sales while protecting profit margins.

### 4. Prioritize Key Categories

Continue prioritizing **Clothing and Accessories** because they contribute the majority of revenue.

### 5. Promote Highly Rated Products

Promote highly rated products in marketing campaigns and product recommendations.

### 6. Continue Customer Acquisition

Continue attracting new customers while maintaining strong customer retention.

