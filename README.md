# 📊 Sales, Customer & Product Insights Dashboard (Power BI)

An end-to-end **Power BI analytics project** that analyzes sales performance, customer behavior, and product trends using transactional order data.

This project focuses on **building accurate KPIs, proper data modeling, and executive-ready dashboards**.

---

## 📌 Project Overview

Businesses often struggle to answer:
- How is the business performing year over year?
- Which customers drive the most value?
- Which products and suppliers contribute most to revenue?

This dashboard addresses those questions by building a **two-page Power BI report**:
1. **Sales Dashboard** – C-suite level performance overview  
2. **Customer & Product Insights Dashboard** – Analytical deep dive
   
---

## 🎯 Objectives

- Analyze overall sales performance and YoY trends  
- Understand customer activity and repeat behavior  
- Identify top-performing products and suppliers  

---

## 🗂️ Data Model

The project follows a **star schema** design.

### 🧾 Orders (Fact Table)
- Order ID  
- Order Date  
- Customer ID  
- Product ID  
- Quantity  
- Total Sales  

### 👤 Customers (Dimension)
- Customer ID  
- Customer Name  
- Age  
- Gender  
- Region  
- Customer Since (Member Since)  

### 📦 Products (Dimension)
- Product ID  
- Product Name  
- Category  
- Supplier  
- Unit Price  

A **dedicated Date and Age Group Sort table** was also created.

---

## 📊 Dashboards Built

### 1️⃣ Sales Dashboard (Executive Overview)

**KPIs**
- Total Revenue  
- Total Orders  
- Average Order Value  
- Year-over-Year (YoY) Growth %

**Visuals**
- Revenue by Quarter  
- Revenue by Category  
- Revenue & Orders by Region  
- Average Order Value by Month
  
**Purpose:**  
Provide leadership with a quick, reliable view of business performance.

---

### 2️⃣ Customer & Product Insights Dashboard

**KPIs**
- Products Sold
- Revenue per Product
- Active Customers  
- Repeat Customer Rate %
  
**Product Insights**
- Top Products by Revenue  
- Revenue by Supplier
  
**Customer Insights**
- Total Orders by Age Group  
- Top Customers by Revenue, Orders, and Tenure
  
**Purpose:**  
Explain *who* is driving revenue and *what* products contribute most to performance.

---

## 🔍 Key Insights from the Dashboards

- Year-over-Year growth shows a **decline in the latest year by 11%**, indicating a slowdown in overall performance.
- Revenue peaked in **Q2 and Q3**, with a noticeable drop in **Q4**, suggesting seasonality or demand softening.
- **Repeat Customer Rate declined in 2024** (from 42% in 2023 to 34% in 2024) indicates moderate retention but clear room for improvement.
- The highest number of orders comes from the **25–34 age groups**, making them the core customer segment.
- Younger (<25) and older (65+) customers contribute significantly fewer orders.
- The YoY decline appears to be driven more by **reduced customer activity and retention**, rather than pricing.
- Revenue concentration across products and suppliers introduces risk if top performers underdeliver.

---

## 🧰 Tech Stack

- **Power BI**
- **DAX** – KPIs, YoY Growth, customer metrics, time intelligence  
- **Power Query** – Data transformation  
- **Data Modeling** – Star schema with Date dimension  

---

## 📊 Dashboard Preview

<img width="1058" height="594" alt="Screenshot 2026-01-07 at 10 46 17 AM" src="https://github.com/user-attachments/assets/ccc646d1-fefb-4088-8cd5-8e5e145d8e6c" />

<img width="1055" height="594" alt="Screenshot 2026-01-07 at 10 46 52 AM" src="https://github.com/user-attachments/assets/8f560346-56df-444a-8353-39fe82f482d8" />

---

## 📬 Contact

**Prachi Holkar**  
📧 Email: holkarprachi@hotmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/prachi-holkar/
