# customer_shopping_behavior_analysis
End to end Customer Shopping Behavior Analysis project using Python, PostgreSQL and Power BI to uncover customer spending patterns, product performance, subscription behavior, loyalty trends, and actionable business insights.

# Overview
The goal of this project is to transform raw customer shopping data into meaningful business insights.

The analysis focuses on:
• Customer spending and revenue
• Product and category performance
• Customer loyalty and repeat purchases
• Subscription behavior
• Discounts and promotions
• Age group spending
• Shipping behavior
• Customer reviews and ratings

# Dataset
The project uses a Customer Shopping Behavior dataset containing 3,900 purchase records.
The dataset includes:
• Customer ID
• Age and Gender
• Product Purchased
• Category
• Purchase Amount
• Location
• Size and Color
• Season
• Review Rating
• Subscription Status
• Shipping Type
• Discount Applied
• Previous Purchases
• Payment Method
• Frequency of Purchases

Additional features such as age_group and purchase_frequency_days were created during the analysis.

Tools & Technologies
Tool	Purpose
Python	Data loading, cleaning, EDA and feature engineering
Pandas	Data manipulation and analysis
PostgreSQL	Database storage and SQL analysis alon with business questions and analytical queries
Power BI	Interactive dashboard and visualization

# Project Workflow
1. Load the Data

2. Exploratory Data Analysis
The dataset was explored using:
• df.info()
• df.describe()
• Null value checks
• Column inspection
• Basic statistical analysis

3. Data Cleaning
The cleaning process included:
• Standardizing column names
• Checking missing values
• Handling missing review ratings using category level median values
• Removing redundant columns
• Checking data consistency

4. Feature Engineering
Two additional features were created:
• age_group: Groups customers based on age
• purchase_frequency_days: Converts purchase frequency into approximate days

5. PostgreSQL Integration
The cleaned DataFrame was loaded into PostgreSQL using SQLAlchemy and psycopg2.

6. SQL Business Analysis
SQL queries were used to answer business questions related to revenue, products, subscriptions, discounts, loyalty, repeat purchases, shipping, and age groups.

7. Power BI Dashboard
The cleaned data was connected to Power BI to create an interactive dashboard containing:
• Total purchases
• Average purchase amount
• Average review rating
• Subscription breakdown
• Revenue by category
• Revenue by age group
• Customer behavior insights
• Interactive filters

8. Report & Presentation
The findings were summarized in an analysis report and presented through a PowerPoint presentation.

# Dashboard
The Power BI dashboard provides an interactive view of customer shopping behavior.
Key areas include:
• Revenue Analysis
• Category Performance
• Subscription Behavior
• Customer Loyalty
• Age Group Analysis
• Shipping Analysis
• Product Ratings
• Discount Analysis

# Key Results
Some of the major findings include:
• Clothing and Accessories contribute roughly 77% of total revenue.
• Subscribers represent approximately 27% of the dataset.
• Average spending between subscribers and non subscribers is relatively similar.
• The customer base contains a large Loyal segment.
• Gloves have the highest average review rating among the top rated products.
• Hat has the highest discount rate among the analyzed products.
• Revenue is relatively balanced across different age groups.
• Repeat buyers represent a strong opportunity for subscription adoption.

# Business Recommendations
Based on the analysis:
• Increase subscription adoption among regular customers.
• Target repeat buyers with subscription offers.
• Review discount strategies to protect margins.
• Continue prioritizing Clothing and Accessories.
• Promote highly rated products.
• Continue attracting new customers while maintaining customer retention.
