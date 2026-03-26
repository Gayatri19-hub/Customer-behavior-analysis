Overview

This project demonstrates an end-to-end data analytics workflow, starting from raw data processing to generating business insights and visual dashboards. The goal is to analyze customer behavior and uncover meaningful patterns that support data-driven decision-making.

Dataset
Source: (Add your dataset source, e.g., Kaggle / CSV file)
Description: The dataset contains customer-related information such as purchase details, categories, and behavioral attributes.
Key Columns:
Customer ID
Category
Purchase Amount
Subscription Status
Item Purchased

Tools & Technologies
Python (Data Cleaning & EDA)
Pandas
NumPy
Matplotlib / Seaborn
SQL (Data Analysis Queries)
PostgreSQL / MySQL / Microsoft SQL Server
Power BI (Dashboard Creation)
Gamma (Presentation Creation)

Project Steps
1. Data Loading
Imported dataset into Python using Pandas
Verified structure, data types, and initial observations
2. Data Cleaning
Handled missing values (using median/group-based imputation)
Removed duplicates
Standardized column names and formats
3. Exploratory Data Analysis (EDA)
Analyzed trends and distributions
Identified key patterns in customer behavior
Used visualizations for better understanding
4. Database Integration
Connected Python to SQL database using SQLAlchemy
Loaded cleaned dataset into database tables
5. SQL Analysis
Performed queries such as:
Aggregations (SUM, AVG, COUNT)
Grouping (customer segments, categories)
Ranking (top products per category using window functions)
6. Dashboard Creation
Built an interactive dashboard in Power BI
Included KPIs like:
Total Revenue
Average Spend
Customer Count
Added filters and category-wise analysis
