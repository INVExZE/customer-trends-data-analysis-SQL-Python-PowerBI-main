# 📊 Customer Shopping Behavior Analysis: End-to-End Portfolio Project

This repository showcases a comprehensive, industry-standard data analytics workflow. The project simulates the real-world responsibilities of a professional analyst—translating raw transactional data into strategic business intelligence through data engineering, statistical analysis, and interactive storytelling.

## 📌 Project Overview
The objective of this project is to analyze customer shopping behavior using a dataset of **3,900 purchases** [cite: 3, 6]. By leveraging a tech stack of **Python, SQL, and Power BI**, the project uncovers deep insights into spending patterns, customer segmentation, and product performance to drive data-driven decision-making [cite: 4, 13, 26, 76].

### 🛠️ Tech Stack & Workflow
* **Data Preparation (Python):** Cleaning, handling missing values, and feature engineering [cite: 14, 19, 21].
* **Database Management (PostgreSQL):** Loading cleaned data into a relational database for structured querying [cite: 25].
* **Advanced Analytics (SQL):** Running complex queries to extract revenue drivers and behavioral trends [cite: 27].
* **Data Visualization (Power BI):** Building a dynamic dashboard for stakeholder reporting [cite: 77].

---

## 📂 Dataset Summary
The analysis is based on a retail dataset with the following characteristics:
* **Rows:** 3,900 [cite: 6].
* **Columns:** 18 [cite: 7].
* **Key Features:**
    * **Demographics:** Age, Gender, Location, and Subscription Status [cite: 9].
    * **Transactional:** Item Purchased, Category, Purchase Amount ($), Season, and Size [cite: 10].
    * **Behavioral:** Review Ratings, Shipping Type, Discount Usage, and Frequency of Purchases [cite: 11].

---

## ⚙️ Implementation Stages

### 1. Exploratory Data Analysis (Python)
The initial phase focused on transforming raw data into an analysis-ready format:
* **Missing Data Imputation:** Filled 37 missing values in the `Review Rating` column using the median rating per category [cite: 12, 19].
* **Feature Engineering:**
    * Created `age_group` bins for demographic segmentation [cite: 22].
    * Developed `purchase_frequency_days` to track customer cadence [cite: 23].
* **Data Standardization:** Converted column names to `snake_case` and dropped redundant features like `promo_code_used` [cite: 20, 24].
* **SQL Integration:** Established a connection to PostgreSQL to export the cleaned DataFrame [cite: 25].

### 2. Strategic Analysis (SQL)
Using PostgreSQL, critical business questions were answered to identify growth opportunities:

| Metric | Insight |
| :--- | :--- |
| **Revenue by Gender** | Male customers generated significantly higher revenue ($157,890) compared to Female customers ($75,191) [cite: 34, 37]. |
| **Subscription Impact** | Non-subscribers account for 73% of the customer base, with an average spend of $59.87 [cite: 49]. |
| **Customer Segments** | Identified 3,116 **Loyal** customers, 701 **Returning** customers, and 83 **New** customers [cite: 54]. |
| **Top Products** | **Gloves** (3.86) and **Sandals** (3.84) lead in average review ratings [cite: 43]. |
| **Category Leaders** | **Jewelry** (Accessories), **Blouse** (Clothing), and **Sandals** (Footwear) are the top purchased items [cite: 56]. |

### 3. Data Visualization (Power BI)
A high-impact dashboard was developed to provide at-a-glance insights for executives [cite: 81].

![Project Workflow](https://github.com/user-attachments/assets/8bbd5dc9-eb6c-40c1-8f19-c08b4107f654)

**Key Dashboard Components:**
* **KPI Cards:** Total Customers (3.9K), Avg Purchase Amount ($59.76), and Avg Rating (3.75) [cite: 82, 84, 86].
* **Revenue Analysis:** Breakdown by Age Group (Young Adults lead with $62,143) and Product Category [cite: 66, 92].
* **Behavioral Filters:** Slicers for Gender, Subscription Status, and Shipping Type to allow for deep-dive exploration [cite: 78, 88, 100].

---

## 📈 Strategic Business Recommendations
Based on the data, the following actions are recommended:
* **Optimize Subscriptions:** Promote exclusive benefits for subscribers to convert the high volume of non-subscribers [cite: 115].
* **Loyalty Integration:** Reward repeat buyers to move them into the "Loyal" segment [cite: 118].
* **Review Discount Policy:** Balance sales boosts with margin control to ensure profitability [cite: 119].
* **Targeted Marketing:** Focus digital ad efforts on high-revenue age groups and express-shipping users [cite: 121].
* **Product Positioning:** Highlight top-rated and best-selling products like Gloves and Jewelry in marketing campaigns [cite: 120].

---

## 🚀 How to Use This Project
1.  **Clone the Repo:**
    ```bash
    git clone https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI.git
    ```
2.  **Clean the Data:** Run the `Customer_Shopping_Behavior_Analysis.ipynb` notebook to process the raw data [cite: 13].
3.  **Load SQL:** Execute the Python script to push data to your PostgreSQL database [cite: 25].
4.  **Analyze:** Run structured SQL queries to answer business questions [cite: 27].
5.  **Visualize:** Connect the SQL database to Power BI to explore the interactive dashboard [cite: 77].

---
*This project is licensed under the MIT License.*
