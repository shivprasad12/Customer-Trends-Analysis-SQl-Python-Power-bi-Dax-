# Customer-Trends-Analysis-SQl-Python-Power-bi-Dax-
 Complete Data Analytics  Project with end-to-end industry standard Data Analysis of Customer Shopping Trends from Retail Data using SQL, Python, Power BI and DAX.

 🛍️ Customer Shopping Behavior Analysis
📘 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The goal is to uncover insights into spending patterns, customer segmentation, product preferences, and subscription behavior to guide data-driven business decisions.

📊 Dataset Summary

Rows: 3,900
Columns: 18
Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency, Review Rating, Shipping Type
Missing Data: 37 values in Review Rating column

🧹 Exploratory Data Analysis (Python)
Performed initial data preparation and cleaning using Python (pandas, NumPy).
Key Steps:
1.Data Loading: Imported dataset using pandas
2.Initial Exploration: Checked structure with .info() and summary stats with .describe()
3.Missing Data Handling: Imputed missing Review Rating values with median ratings per product category

Feature Engineering:
Created age_group feature by binning customer ages
Derived purchase_frequency_days from purchase history
Data Consistency: Verified redundancy between discount_applied and promo_code_used; dropped duplicate column
Database Integration: Connected Python to PostgreSQL and loaded cleaned data for SQL analysis

🧠 Data Analysis using SQL
Executed structured queries in PostgreSQL to answer key business questions:
Revenue by Gender – Compared total revenue by male vs. female customers
High-Spending Discount Users – Identified discount users spending above average
Top 5 Products by Rating – Determined products with highest average review scores
Shipping Type Comparison – Analyzed average purchase amount by shipping method
Subscribers vs. Non-Subscribers – Compared spending and total revenue
Discount-Dependent Products – Listed products with highest discounted purchase ratio
Customer Segmentation – Classified customers as New, Returning, or Loyal
Top 3 Products per Category – Found most purchased items in each category
Repeat Buyers & Subscriptions – Analyzed correlation between repeat buyers and subscription likelihood
Revenue by Age Group – Measured revenue contribution by age segment

📈 Dashboard (Power BI)
Developed an interactive Power BI dashboard for visualization and storytelling:
Revenue trends by gender, category, and age group
Subscription and loyalty segmentation
Top products and discount dependency analysis

💡 Business Recommendations
Boost Subscriptions: Promote exclusive subscriber benefits
Loyalty Programs: Reward repeat buyers to increase retention
Optimize Discount Strategy: Balance sales boosts with profit margins
Product Positioning: Highlight top-rated and best-selling products
Targeted Marketing: Focus on high-value customer segments and express-shipping users

🧰 Tech Stack
Programming: Python (pandas, NumPy, matplotlib, seaborn)
Database: PostgreSQL/Mysql (SQL queries for business analysis)
Visualization: Power BI
Version Control: Git & GitHub

📄 Project Type
Personal Project | End-to-End Data Analysis (Python, SQL, Power BI, DAX)


Gmail:jadhavshivprasad274@gmail.com
Mobile No: 9699725472
