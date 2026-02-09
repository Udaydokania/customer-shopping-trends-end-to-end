# Customer Shopping Trends Analysis 🛍️

## 📌 Project Overview
An end-to-end data analytics pipeline tracking customer shopping behavior from raw data to business intelligence. This project utilizes **Python** for engineering, **PostgreSQL** for deep-dive analysis, and **Power BI** for final visualization and insight generation.

## 🛠 Tech Stack
- **Data Engineering:** Python (Pandas, NumPy)
- **Database Management:** PostgreSQL
- **Business Intelligence:** Power BI (DAX, Interactive Dashboards)
- **Environment:** Jupyter Notebook, SQL Shell

## 📖 Data Dictionary
| Column Name | Description |
| :--- | :--- |
| **Customer_ID** | Unique identifier for each customer. |
| **Age / Gender** | Demographic information of the shopper. |
| **Item_Purchased** | The specific product bought during the transaction. |
| **Category** | Broad classification of the product (Clothing, Footwear, etc.). |
| **Purchase_Amount_USD** | The total value of the transaction in US Dollars. |
| **Location** | The geographic location of the purchase. |
| **Review_Rating** | Customer satisfaction score (1.0 - 5.0). |
| **Subscription_Status** | Indicates if the customer is a premium member ('Yes'/'No'). |
| **Previous_Purchases** | Total number of prior transactions by the customer. |

## 🚀 Project Roadmap & Progress
- [x] **Day 1: Data Preprocessing (Python)**
  - Cleaned raw shopping data and handled missing values.
  - Optimized data types for database ingestion.
- [x] **Day 2: SQL Analytical Layer (PostgreSQL) - Phase 1**
  - Migrated data to PostgreSQL and ran initial descriptive queries.
  - Uploaded cleaned dataset for transparency.
- [x] **Day 3: Advanced SQL & Customer Segmentation**
  - Implemented logic to categorize customers into 'New', 'Returning', and 'Loyal' segments.
- [x] **Day 4: Business Intelligence Dashboard (Power BI)**
  - Built interactive visuals to track KPIs, revenue trends, and customer demographics.

## 📊 Final Insights
- **Segmentation:** Successfully identified the ratio of Loyal vs. New customers to help target retention strategies.
- **Revenue Drivers:** Identified top-performing categories and the impact of discounts on high-value transactions.
- **Demographics:** Analyzed spending patterns across different age groups and locations.

## 📂 Repository Structure
- `Customer_Shopping_Behaviour_Analysis.ipynb`: Python cleaning logic.
- `customer_analysis.sql`: Full 10-question SQL analysis.
- `customer_shopping_behavior.csv`: The processed dataset.
- `Shopping_Trends_Dashboard.pbix`: Power BI dashboard file.
- `requirements.txt`: Environment dependencies.
