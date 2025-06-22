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

| Column Name        | Description                            |
|--------------------|----------------------------------------|
| `TransactionID`    | Unique identifier for each transaction |
| `TransactionDate`  | Date of transaction                    |
| `TransactionTime`  | Time of transaction                    |
| `Product`          | Name of the product sold               |
| `Category`         | Category of product (e.g., Beverage)   |
| `Quantity`         | Quantity sold                          |
| `UnitPrice`        | Price per unit                         |
| `CustomerID`       | Unique ID of customer (if available)   |
| `Location`         | Store location (if multiple branches)  |



## ❓ Business Questions & Findings

### 1. 💰 What is the total revenue generated over time?
**Finding**:  
Revenue shows an overall upward trend with noticeable peaks during weekends. The highest sales occurred in **December**, indicating a seasonal holiday surge.

---

### 2. 📅 What are the busiest days and hours?
**Finding**:  
- **Saturday** and **Sunday** have the highest footfall.
- Most purchases occur between **8 AM – 10 AM**, aligning with coffee rush hours.

---

### 3. 📦 Which products contribute the most to sales?
**Finding**:  
- **Espresso** and **Cappuccino** are the top-selling beverages by volume.
- **Whole Bean Coffee Bags** contribute significantly to revenue due to higher prices.

---

### 4. 🏆 Who are our top customers?
**Finding**:  
A small segment of **repeat customers** contributes a large portion of total revenue. Introducing a **loyalty program** could increase retention and frequency.

---

### 5. 📊 What is the average monthly revenue and how does it trend?
**Finding**:  
- Average monthly revenue is **$12,000**.
- There’s steady growth with a slight dip during the rainy season (April).

---

### 6. 📉 Are there seasonal or daily patterns in purchases?
**Finding**:  
- Sales increase during holidays (e.g., Christmas, Easter).
- **Weekdays** show consistent sales, while **weekends** see spikes.

---

### 7. 🎯 How well are we meeting monthly sales targets?
**Finding**:  
- Sales exceeded targets in **4 out of 6 months**.
- Conditional formatting (green/red arrows) shows positive MoM changes for January–March and drops in April–May.

---

### 8. 📈 What’s the average order size and cart value?
**Finding**:  
- **Average Cart Size**: 1.8 items  
- **Average Order Value**: $6.50  
Upselling pastries or snacks could improve cart size.

---

## 📊 Tools & Technologies  
- **Power BI** – Dashboarding and Visual Analytics  
- **DAX (Data Analysis Expressions)** – For calculated columns, KPIs, MoM metrics  
- **Excel/CSV** – For data cleaning and initial prep

---

## 🧠 Insights & Recommendations  

- Promote high-margin products like whole beans or merchandise.
- Run targeted marketing campaigns during slow sales days.
- Introduce combo offers to increase average cart size.
- Launch loyalty or rewards programs to retain top customers.

---

## 📎 Dashboard Preview  
(Embed dashboard screenshot or link here)

> *For full interaction, access the live Power BI report in the project folder or shared workspace.*
