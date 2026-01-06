# 📊 Sales, Customer & Product Insights Dashboard (Power BI)

An end-to-end **Power BI analytics project** that analyzes sales performance, customer behavior, and product trends using transactional order data.

This project focuses on **building accurate KPIs, proper data modeling, and executive-ready dashboards**.

---

## 📌 Project Overview

Businesses often struggle to answer:
- How is the business performing year over year?
- Which customers drive the most value?
- Which products and suppliers contribute most to revenue?

This project addresses those questions by building a **two-page Power BI report**:
1. **Sales Dashboard** – C-suite level performance overview  
2. **Customer & Product Insights Dashboard** – Analytical deep dive  

A **dedicated Date table** was created and used to enable correct time intelligence and YoY analysis.

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

### 📅 Date (Dimension)
- Date  
- Year  
- Quarter  
- Month  
- Month Name  
- Year-Month  

---

## 📊 Dashboards Built

### 1️⃣ Sales Dashboard (Executive Overview)

**KPIs**
- Total Revenue  
- Total Orders  
- Average Order Value  
- Year-over-Year (YoY) Growth %

**Visuals**
- Total Revenue by Quarter  
- Revenue by Category  
- Revenue & Orders by Region  
- Average Order Value by Month  

**Purpose:**  
Provide leadership with a quick, reliable view of business performance.

---

### 2️⃣ Customer & Product Insights Dashboard

**KPIs**
- Active Customers  
- Repeat Customer Rate %  
- Total Revenue (contextual)  
- Product-level metrics  

**Customer Insights**
- Total Orders by Age Group  
- Top Customers by Revenue, Orders, and Tenure  

**Product Insights**
- Top Products by Revenue  
- Revenue by Supplier  
- Product Revenue Concentration  

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


## 📬 Contact

**Prachi Holkar**  
📧 Email: holkarprachi@hotmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/prachi-holkar/
