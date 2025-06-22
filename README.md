# ☕ Coffee Sales Analysis

---
## 📌 Background  
In today’s competitive retail environment, understanding customer purchasing behavior and sales trends is critical.
This project analyzes a coffee shop’s transaction data to uncover actionable insights that help drive better business decisions
related to revenue, customer behavior, and sales performance.

---

## 📎 Dashboard Preview  
![image](https://github.com/user-attachments/assets/9d41169e-a6b9-4eed-9290-a0eb740d4f8d)


![image](https://github.com/user-attachments/assets/04ce39c4-5b93-45f0-91f5-50225b43175b)
 

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

| Column Name         | Description                                     |
|---------------------|-------------------------------------------------|
| `transaction_id`     | Unique identifier for each transaction         |
| `transaction_date`   | Date of transaction                            |
| `transaction_time`   | Time of transaction                            |
| `transaction_qty`    | Quantity sold                                  |
| `store_id`           | Unique ID of the coffee shop where the transaction took place |
| `store_location`     | Store location (if multiple branches)          |
| `product_id`         | Unique ID of the product sold                  |
| `unit_price`         | Price per unit                                 |
| `product_category`   | Category of product (e.g., Beverage)           |
| `product_type`       | Description of the product type                |
| `product_detail`     | Name of the product sold                       |

## 🔗 Data Source
(https://www.kaggle.com/datasets/ahmedabbas757/coffee-sales)

## ❓ Business Questions & Findings

### 1. 💰 What is the total revenue generated over time?
**Finding**:  
The total venue was $698812 from January to June. There was a general increase in revenue during this period. 


---

### 2. 📅 What are the busiest days and hours?
**Finding**:  
- **Friday** and **Monday** have the highest revenue.
- Most purchases occur between **8 AM – 10 AM**, aligning with coffee rush hours.

---

### 3. 📦 Which products contribute the most to sales?
**Finding**:  
- **Espresso** and **Cappuccino** are the top-selling beverages by volume.
- **Whole Bean Coffee Bags** contribute significantly to revenue due to higher prices.

---

### 4. 📊 What is the average monthly revenue and how does it trend?
**Finding**:  
- Average monthly revenue is **$116467**.
- There’s steady growth with a slight dip in February.

---

### 5. 📈 What are the top 10 best selling products with their associated categories?
**Finding**:  

| Product Detail                    | Product Category      | Total Quantity Sold |
|----------------------------------|------------------------|----------------------|
| Serenity Green Tea Rg            | Tea                    | 4,477                |
| Our Old Time Diner Blend Sm      | Coffee                 | 4,484                |
| Latte Rg                         | Coffee                 | 4,497                |
| Traditional Blend Chai Rg        | Tea                    | 4,512                |
| Peppermint Rg                    | Tea                    | 4,564                |
| Dark chocolate Lg                | Drinking Chocolate     | 4,668                |
| Morning Sunrise Chai Rg          | Tea                    | 4,643                |
| Columbian Medium Roast Rg        | Coffee                 | 4,547                |
| Latte                            | Coffee                 | 4,602                |
| Earl Grey Rg                     | Tea                    | 4,708                |


---
### 6. 📈 What are the top 10 worst selling products with their associated categories?
**Finding**:  

| Product Detail                    | Product Category      | Total Quantity Sold |
|----------------------------------|------------------------|----------------------|
| Peppermint                       | Loose Tea              | 153                  |
| Lemon Grass                      | Loose Tea              | 152                  |
| Traditional Blend Chai           | Loose Tea              | 153                  |
| Primo Espresso Roast             | Coffee beans           | 150                  |
| Columbian Medium Roast           | Coffee beans           | 148                  |
| Dark chocolate                   | Packaged Chocolate     | 118                  |
| Chili Mayan                      | Packaged Chocolate     | 148                  |
| Jamacian Coffee River            | Coffee beans           | 146                  |
| Spicy Eye Opener Chai            | Loose Tea              | 122                  |
| Guatemalan Sustainably Grown     | Coffee beans           | 134                  |
| Earl Grey                        | Loose Tea              | 142                  |



---
### 7. 📈 What’s the average transaction value?

- **Average   Transaction Value**: $5  


---

## 📊 Tools & Technologies  
- **Power BI** – Dashboarding and Visual Analytics  
- **DAX (Data Analysis Expressions)** – For calculated columns, KPIs, MoM metrics  


---


---


