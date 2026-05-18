# Customer_Sales_behavior_analysis
Data analytics Project showcasing customer behavior analysis using python, sql and power BI
Customer Shopping Behavior Analysis
Project Overview

This project analyzes customer shopping behavior using transactional purchase data to uncover valuable business insights. The analysis focuses on customer demographics, purchasing patterns, product preferences, subscription behavior, and discount usage.

The project demonstrates a complete end-to-end data analytics workflow including:

Data loading and cleaning using Python
Exploratory Data Analysis (EDA)
SQL-based business analysis using PostgreSQL
Interactive Power BI dashboard creation
Business reporting and presentation using Gamma

The goal of this project is to help businesses make data-driven decisions related to customer retention, product strategy, and marketing optimization.

Dataset Summary

The dataset contains customer transaction records collected from shopping activities.

Dataset Details
Total Rows: 3,900
Total Columns: 18

Key Features
Customer demographics:
Age
Gender
Location
Subscription Status
Purchase information:
Item Purchased
Category
Purchase Amount
Season
Size
Color
Shopping behavior:
Discount Applied
Previous Purchases
Frequency of Purchases
Review Rating
Shipping Type

Data Quality
Missing values identified in the Review Rating column
Duplicate and inconsistent records checked during preprocessing

Tools & Technologies
Tool	Purpose
Python	Data analysis and preprocessing
Pandas & NumPy	Data manipulation
Matplotlib & Seaborn	Data visualization
PostgreSQL / MySQL	SQL querying and business analysis
Power BI	Dashboard development
Gamma	Presentation creation
Jupyter Notebook	Python coding environment

Project Workflow
1. Data Loading
Imported the dataset into Python using Pandas
Explored dataset structure using:
df.info()
df.describe()
2. Data Cleaning & Preparation
Handled missing values in the Review Rating column using median imputation
Renamed columns into snake_case format
Removed redundant columns
Verified data consistency and quality
3. Feature Engineering
Created additional columns for deeper analysis:
age_group
purchase_frequency_days
4. Exploratory Data Analysis (EDA)
Performed EDA to identify:
Customer spending trends
Product popularity
Seasonal purchasing behavior
Subscription patterns
Discount usage behavior

Created multiple visualizations to support analysis and insight generation.

5. SQL Analysis (PostgreSQL/MySQL)

Loaded the cleaned dataset into PostgreSQL for advanced querying and business analysis.

Key SQL Analyses
Revenue by gender
High-spending discount users
Top-rated products
Shipping type comparison
Subscribers vs non-subscribers analysis
Discount-dependent products
Customer segmentation
Top products by category
Repeat buyers and subscriptions
Revenue contribution by age group

Power BI Dashboard

An interactive Power BI dashboard was created to visualize business insights.

Dashboard Features
KPI cards
Revenue analysis
Customer segmentation visuals
Product performance tracking
Subscription analysis
Interactive slicers and filters
Trend analysis charts

Key Insights & Results
Loyal and repeat customers contribute significantly to revenue
Subscribers tend to spend more on average
Certain products are highly dependent on discounts
Express shipping customers show higher purchase values
Specific age groups generate the highest revenue

Business Recommendations
Introduce stronger loyalty programs for repeat customers
Promote subscription benefits to increase retention
Optimize discount strategies to protect profit margins
Focus marketing efforts on high-performing customer segments
Highlight top-rated products in campaigns

Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── dataset/
├── notebooks/
├── sql_queries/
├── powerbi_dashboard/
├── reports/
├── presentation/
├── README.md

How to Run the Project
Python Analysis
Install required libraries:
pip install pandas numpy matplotlib seaborn
Open Jupyter Notebook:
jupyter notebook
Run the notebook files inside the notebooks/ folder.

SQL Analysis
Import the cleaned dataset into PostgreSQL/MySQL
Run SQL scripts from the sql_queries/ folder

Power BI Dashboard
Open the .pbix dashboard file in Power BI Desktop
Refresh the dataset connection if needed
Conclusion

This project showcases practical data analytics skills across the full analytics lifecycle:

Data cleaning
Exploratory Data Analysis
SQL querying
Data visualization
Dashboard creation
Business reporting

The project demonstrates the ability to transform raw transactional data into meaningful business insights using industry-standard analytics tools.









