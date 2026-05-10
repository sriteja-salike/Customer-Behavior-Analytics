# Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes the shopping behavior of 3,900 customers across multiple product categories. The objective is to identify spending patterns, product preferences, and customer loyalty trends to support data-driven business decisions and targeted marketing strategies.

The project follows an end-to-end analytics lifecycle:

- Data cleaning and preparation in Python  
- Structured querying and analysis in SQL  
- Interactive visualization using Power BI  

---

## 🛠️ Tools & Technologies Used

- **Python (Pandas):** Data cleaning, preprocessing, missing value handling, and feature engineering  
- **PostgreSQL:** Advanced querying and business analysis  
- **SQLAlchemy:** Database connectivity between Python and PostgreSQL  
- **Power BI:** Interactive dashboards and KPI visualization  

---

## 📊 Key Insights & Findings

### Revenue Drivers
- Male customers generated higher total revenue **($157,890)** compared to female customers **($75,191)**.

### Customer Loyalty Segmentation
- **Loyal:** 3,116 customers  
- **Returning:** 701 customers  
- **New:** 83 customers  

The dataset is heavily skewed toward repeat and loyal buyers.

### Subscription Impact
- **27%** of customers are subscribers.  
- Non-subscribers have a slightly higher average spend than subscribers.

### Product Performance
- **Clothing** is the top revenue-generating category.  
- **Blouses** and **Jewelry** are among the most frequently purchased products.

### Age Group Contribution
- **Young Adults** contribute the highest revenue at **$62,143**.

### Revenue Concentration Across Top Spender Tiers
- The top **10%** of customers generate **16.1%** of revenue.
- The top **20%** generate **31.0%**, the top **30%** generate **44.5%**, and the top **50%** generate **67.2%**.
- Distribution is relatively flat — no strong 80/20 effect — suggesting revenue is broadly spread rather than concentrated in a small high-value segment.

### Product-Level Sales Dependency on Discounts
- **19 of 25 products (76%)** have over **40%** of their sales tied to discounts.
- Most discount-reliant items: **Hat (50.0%)**, **Sneakers (49.7%)**, **Coat (49.1%)**, **Sweater (48.2%)**, **Pants (47.4%)**.
- Least discount-reliant: **Socks (32.7%)**, **Blouse (33.9%)**, **Sandals (36.9%)** — flagging pricing-strategy risk across most of the catalog.

### Subscriber vs. Non-Subscriber Discount Reliance
- **100%** of subscriber purchases use a discount, vs. only **21.9%** for non-subscribers.
- Despite full discount usage, subscribers spend **slightly less on average ($59.49 vs. $59.87)**.
- The loyalty program drives no observable spend lift — its value is almost entirely discount-based.

---

## 📈 Work Performed

### 1️⃣ Data Preparation
- Identified and handled missing values.  
- Imputed missing **review ratings** using the median rating of each product category.

### 2️⃣ Feature Engineering
- Created an `age_group` column for demographic segmentation.  
- Converted text-based purchase frequency into numerical values for quantitative analysis.

### 3️⃣ SQL Business Analysis
Performed advanced SQL analysis to answer key business questions:

- Identified high-spending discount users  
- Compared performance across shipping types  
- Determined discount-dependent products  
- Quantified revenue concentration across top spender tiers  
- Measured product-level sales dependency on discounts  
- Compared discount reliance between subscribers and non-subscribers  

### 4️⃣ Dashboard Development
Developed an interactive Power BI dashboard showcasing:

- **Average Purchase Amount:** $59.76  
- **Average Review Rating:** 3.75  
- Revenue by gender  
- Revenue by category  
- Loyalty segmentation  
- Subscription insights  
