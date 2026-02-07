# Customer Shopping Trends Analysis 

##  Project Overview
This project is an end-to-end data analytics pipeline designed to extract, clean, and visualize customer shopping behavior. By leveraging **Python** for data engineering, **PostgreSQL** for deep-dive analysis, and **Power BI** for business intelligence, this project provides actionable insights into customer retention and revenue growth.

##  Tech Stack
- **Data Preprocessing:** Python (Pandas, NumPy)
- **Database Management:** PostgreSQL
- **Business Intelligence:** Power BI
- **Environment:** Jupyter Notebook, SQL Shell

##  Project Roadmap & Progress
- [x] **Day 1: Data Preprocessing (Python)**
  - Cleaned raw shopping data and handled missing values.
  - Optimized data types for efficient database ingestion.
- [x] **Day 2: SQL Analytical Layer (PostgreSQL) - Phase 1**
  - Successfully migrated cleaned data to PostgreSQL.
  - Developed initial descriptive queries for revenue and shipping analysis.
  - Uploaded the cleaned CSV dataset for transparency.
- [ ] **Day 3: Advanced SQL & Customer Segmentation**
  - Implementing complex logic to categorize customers into 'New', 'Returning', and 'Loyal' segments.
- [ ] **Day 4: Business Intelligence Dashboard (Power BI)**
  - Building interactive visuals to track KPIs and seasonal shopping trends.

##  SQL Analysis Progress (Day 2)
The first 5 business questions have been implemented in `customer_analysis.sql`:
1. **Revenue by Gender:** Identifying spending patterns across demographics.
2. **High-Value Discount Users:** Finding customers who spend above average using promo codes.
3. **Top Rated Products:** Ranking items based on average customer reviews.
4. **Shipping Tier Comparison:** Analyzing average spend between Standard and Express shipping.
5. **Subscription Value:** Comparing total revenue from subscribed vs. non-subscribed users.


- `customer_analysis.sql`: SQL queries (Partially completed).
- `requirements.txt`: Project dependencies (Corrected).
- `cleaned_shopping_data.csv`: The processed dataset ready for analysis.
