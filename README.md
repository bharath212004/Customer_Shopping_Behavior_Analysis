📌 Project Overview

This project analyzes customer shopping behavior for a retail business to identify revenue drivers, customer segments, and actionable opportunities to improve marketing strategy, subscriptions, and customer loyalty.

The analysis covers the full analytics lifecycle:

Data cleaning and feature engineering (Python)

Business analysis using SQL

Interactive dashboard creation (Power BI)

Business insights and recommendations

🎯 Business Problem

The retail company observed changes in purchasing patterns across:

Customer demographics

Product categories

Discount usage

Subscription behavior

The goal was to answer:

How can customer shopping data be leveraged to improve revenue, engagement, and long-term loyalty?

📊 Dataset Summary

Records: 3,900 transactions

Features: 18 columns

Key data included:

Customer demographics (age, gender, location, subscription status)

Purchase behavior (category, amount, season, discounts)

Engagement signals (review ratings, shipping type, frequency)

Data issues handled:

Missing values in review ratings

Redundant columns

Inconsistent column naming

🛠️ Tech Stack

Python: Pandas, NumPy (data cleaning & feature engineering)

SQL: Business analysis and customer segmentation

Power BI: Dashboard and data visualization

GitHub: Version control and project documentation

🔧 Data Preparation & Feature Engineering (Python)

Key steps performed:

Cleaned and standardized column names

Imputed missing review ratings using median by product category

Engineered new features:

age_group

purchase_frequency_days

Identified and removed redundant fields (e.g., promo code flag)

Loaded the cleaned dataset into a relational database for SQL analysis

🧮 SQL Analysis (Business Questions Answered)

The SQL layer focused on decision-driven analysis, not just queries.

Key insights extracted:

Revenue comparison by gender

Identification of high-spending discount users

Subscriber vs non-subscriber revenue analysis

Discount-dependent products impacting margins

Customer segmentation:

New

Returning

Loyal

Revenue contribution by age group

Repeat buyer behavior and subscription correlation

All SQL queries are available in the /sql directory.

📈 Power BI Dashboard

An interactive dashboard was built to support executive-level decision making.

Dashboard Highlights:

Total customers, average purchase value, average review rating

Revenue and sales breakdown by category and age group

Subscription status distribution

Filters for gender, category, shipping type, and subscription

The dashboard enables stakeholders to quickly identify:

High-value customer segments

Strong and weak product categories

Opportunities to optimize pricing and promotions

💡 Key Business Insights

Subscribers generate similar average order value but stronger long-term value

Certain products rely heavily on discounts, risking margin erosion

Specific age groups contribute disproportionately to total revenue

Loyal customers represent a major share of total transactions

📌 Business Recommendations

Promote subscriptions with exclusive benefits rather than blanket discounts

Focus marketing efforts on high-revenue age segments

Reevaluate discount strategies for margin-sensitive products

Prioritize top-rated and high-performing products in campaigns

Implement loyalty programs to convert repeat buyers into long-term customers
