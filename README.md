# ☕ Coffee Sales Analysis

## 📌 Background  
In today’s competitive retail environment, understanding customer purchasing behavior and sales trends is critical.
This project analyzes a coffee shop’s transaction data to uncover actionable insights that help drive better business decisions
related to revenue, customer behavior, and sales performance.

---

## 📈 Project Overview  
This analysis explores transactional sales data from a coffee shop with the goal of identifying patterns, 
tracking performance over time, and answering key business questions. Using Power BI and DAX,
interactive dashboards that visualize monthly sales, highlight key performance indicators (KPIs), and uncover areas for growth.

---

## 🧾 Executive Summary — Data Source  
The dataset used for this project is derived from **Coffee Shop sales records**, containing details of each purchase made. It includes:

- Transaction timestamps
- Items purchased
- Pricing and quantities
- Customer identifiers (when available)

The data was cleaned, enriched with time-based attributes, and analyzed using Power BI for real-time insights.

---

## 🗂️ Data Structure Overview  

transaction_id : Unique sequential ID representing an individual transaction
transaction_date : Date of the transaction (MM/DD/YY)
transaction_time : Timestamp of the transaction (HH:MM:SS)
transaction_qty : Quantity of items sold
store_id : Unique ID of the coffee shop where the transaction took place
store_location : Location of the coffee shop where the transaction took place
product_id : Unique ID of the product sold
unit_price : Retail price of the product sold
product_category : Description of the product category
product_type : Description of the product type
product_detail : Description of the product detail



## ❓ Business Questions & Findings

### 1. 💰 What is the total revenue generated over time?
**Finding**:  
Revenue shows an overall upward trend with noticeable peaks during weekends. The highest sales occurred in **December**, indicating a seasonal holiday surge.

---

### 2. 📅 What are the busiest days and hours?
**Finding**:  
- **Friday**,**Monday** and **Thursday** have the highest footfall.
- Most purchases occur between **8 AM – 10 AM**, aligning with coffee rush hours.

---

### 3. 📦 Which products contribute the most to sales?
**Finding**:  
- **Espresso** and **Cappuccino** are the top-selling beverages by volume.
- **Whole Bean Coffee Bags** contribute significantly to revenue due to higher prices.

---

### 4. 📊 What is the average monthly revenue and how does it trend?
**Finding**:  
- Average monthly revenue is **$12,000**.
- There’s steady growth with a slight dip during the rainy season (April).

---

### 5. 📉 Are there seasonal or daily patterns in purchases?
**Finding**:  
- Sales increase during holidays (e.g., Christmas, Easter).
- **Weekdays** show consistent sales, while **weekends** see spikes.

---

### 6. 🎯 How well are we meeting monthly sales targets?
**Finding**:  
- Sales exceeded targets in **4 out of 6 months**.
- Conditional formatting (green/red arrows) shows positive MoM changes for January–March and drops in April–May.

---

### 7. 📈 What’s the average transaction value?

- **Average   Transaction Value**: $5  
.

---

## 📊 Tools & Technologies  
- **Power BI** – Dashboarding and Visual Analytics  
- **DAX (Data Analysis Expressions)** – For calculated columns, KPIs, MoM metrics  


---


---

## 📎 Dashboard Preview  
(Embed dashboard screenshot or link here)

> *For full interaction, access the live Power BI report in the project folder or shared workspace.*
