# Customer Shopping Trends Analysis 🛍️

## 📌 Project Overview
An end-to-end data analytics pipeline tracking customer shopping behavior from raw data to business intelligence. This project utilizes **Python** for engineering, **PostgreSQL** for analysis, and **Power BI** for visualization.

## 📖 Data Dictionary
To ensure clarity during analysis, here is a breakdown of the key attributes in the dataset:

| Column Name | Description |
| :--- | :--- |
| **Customer_ID** | Unique identifier for each customer. |
| **Age / Gender** | Demographic information of the shopper. |
| **Item_Purchased** | The specific product bought during the transaction. |
| **Category** | The broad classification of the product (Clothing, Footwear, etc.). |
| **Purchase_Amount_USD** | The total value of the transaction in US Dollars. |
| **Location** | The geographic location of the purchase. |
| **Review_Rating** | The customer's satisfaction score (1.0 - 5.0). |
| **Subscription_Status** | Indicates if the customer is a premium member ('Yes'/'No'). |
| **Previous_Purchases** | Total number of prior transactions by the customer. |
| **Payment_Method** | The method used (Credit Card, Cash, PayPal, etc.). |

## 🛠 Tech Stack
- **Data Engineering:** Python (Pandas, NumPy)
- **Database:** PostgreSQL
- **Visualization:** Power BI

## 🚀 Project Roadmap & Progress
- [x] **Day 1: Data Preprocessing (Python)**
  - Handled missing values and optimized data types.
- [x] **Day 2: SQL Analytical Layer - Phase 1**
  - Migrated data to PostgreSQL and ran initial descriptive queries.
- [x] **Day 3: Advanced SQL & Customer Segmentation**
  - Categorized customers into 'New', 'Returning', and 'Loyal' based on purchase history.
  - Analyzed spending behavior across different demographics.
- [ ] **Day 4: Business Intelligence Dashboard (Power BI)**
  - Creating interactive visual reports for stakeholders.

## 📂 Repository Structure
- `Customer_Shopping_Behaviour_Analysis.ipynb`: Python preprocessing.
- `customer_shopping_analysis.sql`: Full 10-question SQL analysis.
- `customer_shopping_behavior.csv`: Cleaned dataset.
- `requirements.txt`: Environment dependencies.
