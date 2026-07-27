<div align="center">

# 🍔 Competitive Pricing Intelligence Dashboard

### Uncovering hidden charges, fake discounts & real savings across Swiggy, Zomato & Toing

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](#-tech-stack)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)](#-tech-stack)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#-tech-stack)
[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](#-tech-stack)
[![DAX](https://img.shields.io/badge/DAX-FFCA28?style=for-the-badge&logoColor=black)](#-tech-stack)

![Status](https://img.shields.io/badge/status-completed-brightgreen?style=flat-square)
![Records](https://img.shields.io/badge/records-400%2B-blue?style=flat-square)
![Platforms](https://img.shields.io/badge/platforms-3-orange?style=flat-square)
![City](https://img.shields.io/badge/city-Noida-red?style=flat-square)

</div>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Tech Stack](#-tech-stack)
- [Dataset Information](#-dataset-information)
- [Dashboard Pages](#-dashboard-pages)
- [KPIs Created](#-kpis-created)
- [Repository Structure](#-repository-structure)
- [Dashboard Preview](#-dashboard-preview)
- [SQL Concepts Used](#-sql-concepts-used)
- [Power BI Features](#-power-bi-features)
- [Python Libraries Used](#-python-libraries-used)
- [Business Insights](#-business-insights)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 📌 Project Overview

Food delivery platforms often display attractive discounts while quietly applying multiple hidden charges — delivery fees, platform fees, GST, and inflated menu prices.

This project performs a **comprehensive comparative analysis** of **Swiggy**, **Zomato**, and **Toing** to identify:

| 🔍 What we're solving |
|---|
| Which platform provides the lowest final order cost |
| Which platform offers genuine discounts |
| Hidden pricing strategies used by each platform |
| Real customer savings vs. advertised savings |
| Delivery performance across platforms |
| Menu price inflation vs. in-store prices |
| Restaurant-level pricing trends |

Built end-to-end using **SQL, Python, Excel, and Power BI** to transform raw pricing data into decision-ready business insights.

---

## 🎯 Business Problem

Customers frequently compare prices across multiple food delivery apps before placing an order — but the comparison is rarely fair:

- 🎭 Discounts can be misleading
- 💸 Hidden charges quietly inflate the final bill
- 🚚 Delivery fees vary significantly between platforms
- 📉 Platform fees eat into customer savings
- 📈 Menu prices are sometimes higher than actual restaurant prices

**Goal:** Identify the platform that genuinely offers the best value for money.

---

## 🎯 Project Objectives

- ✅ Compare pricing across Swiggy, Zomato, and Toing
- ✅ Analyze hidden charges
- ✅ Evaluate discount effectiveness
- ✅ Measure real customer savings
- ✅ Identify menu price inflation
- ✅ Compare delivery performance
- ✅ Build an executive dashboard for business decision-making

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development |
| **SQL** | Data cleaning & analysis |
| **Python** (Pandas, NumPy) | Data processing |
| **Excel** | Data preparation |
| **DAX** | KPI calculations |
| **Power Query** | Data transformation |

---

## 📊 Dataset Information

<table>
<tr>
<td>

**Records:** 400+
**Platforms:** Swiggy · Zomato · Toing
**City Covered:** Noida

</td>
<td>

**Data Fields:**
Restaurant Name, Cuisine, Platform, Store Price, App Menu Price, Delivery Fee, Platform Fee, GST, Discount, Customer Savings, Delivery Time, Distance, Final Order Cost

</td>
</tr>
</table>

---

## 📈 Dashboard Pages

### 1️⃣ Executive Summary
**KPIs:** Total Restaurants · Total Orders · Avg Final Cost · Avg Savings · Hidden Charges · Delivery Fee · Avg Delivery Time · Avg Distance
**Visuals:** KPI Cards · Platform Comparison · Hidden Charge Breakdown · Restaurant Distribution · Cuisine Distribution

### 2️⃣ Pricing Analysis
**Analysis:** Avg Store Price · Avg App Menu Price · Price Inflation · Inflation % · Highest Menu Price · Lowest Platform Price
**Visuals:** Clustered Column Chart · Waterfall Chart · Scatter Plot

### 3️⃣ Fee Analysis
**KPIs:** Delivery Fee · Platform Fee · GST · Total Hidden Charges · Hidden Charges as % of Order Value
**Visuals:** Donut Chart · Clustered Bar Chart · Breakdown Matrix

### 4️⃣ Discount Analysis
**KPIs:** Avg Discount · Max Discount · Effective Discount · Customer Savings · Highest Saving Restaurant
**Visuals:** Donut Chart · Bar Chart · Heat Map

### 5️⃣ Delivery Analysis
**KPIs:** Avg Delivery Time · Delivery Fee · Distance · Fastest Delivery · Slowest Delivery
**Visuals:** Scatter Chart · Line Chart · Bubble Chart

---

## 📊 KPIs Created

`Total Orders` `Total Restaurants` `Avg Store Price` `Avg Menu Price` `Avg Final Order Cost` `Avg Discount %` `Avg Customer Savings` `Hidden Charges` `Delivery Fee` `GST` `Platform Fee` `Price Inflation` `Inflation %` `Delivery Time` `Delivery Distance`

---

## 📂 Repository Structure

```
Competitive-Pricing-Intelligence-Dashboard
│
├── Dataset/          # Raw and cleaned data files
├── SQL/              # Queries used for cleaning & analysis
├── Python/           # Data processing scripts
├── Power BI/         # .pbix dashboard file
├── Images/           # Dashboard screenshots
├── Documentation/    # Supporting docs
└── README.md
```

---

## 📷 Dashboard Preview

### Executive Summary
<img width="1312" height="738" alt="Executive Summary Dashboard" src="https://github.com/user-attachments/assets/dfdb453e-9a40-427b-8c98-890cbd324e01" />

### Pricing Analysis
<img width="1310" height="736" alt="Pricing Analysis Dashboard" src="https://github.com/user-attachments/assets/72e00e83-4896-4490-8e1a-0a4473577aa4" />

### Fee Analysis
<img width="1306" height="732" alt="Fee Analysis Dashboard" src="https://github.com/user-attachments/assets/93cf9be2-4130-4636-9546-923ad08e6b5f" />

### Discount Analysis
<img width="1303" height="757" alt="Discount Analysis Dashboard" src="https://github.com/user-attachments/assets/bafa07a6-0ef3-472e-81af-9f7b57559e0e" />

### Delivery Analysis
<img width="1310" height="732" alt="Delivery Analysis Dashboard" src="https://github.com/user-attachments/assets/643f050c-41ed-4497-af32-05144eca0035" />

---

## 🔍 SQL Concepts Used

`Joins` `CTEs` `CASE Statements` `Aggregate Functions` `Window Functions` `GROUP BY` `HAVING` `Subqueries`

---

## 📊 Power BI Features

`Interactive Dashboard` `Dynamic KPIs` `Drill Through` `Tooltips` `Bookmarks` `Dynamic Titles` `Slicers` `DAX Measures` `Conditional Formatting` `Storytelling Dashboard`

---

## 🐍 Python Libraries Used

`Pandas` `NumPy` `Matplotlib` `OpenPyXL`

---

## 📈 Business Insights

- ✔️ Hidden charges significantly impact the final order value
- ✔️ Higher discounts don't always result in the lowest payable amount
- ✔️ Some restaurants show noticeable menu price inflation across platforms
- ✔️ Delivery fees vary independently of delivery distance in several cases
- ✔️ Platform fees reduce the actual benefit customers receive from promotional discounts

---

## 🚀 Future Improvements

- 🔄 Live API integration
- ⏱️ Automated dashboard refresh
- 🌆 Multi-city analysis
- ⭐ Customer rating analysis
- 💬 Sentiment analysis
- 🔮 Price prediction model

---

## 👨‍💻 Author

<div align="center">

### **Bhupendra Kumar**
**Data Analyst | Business Intelligence**

**Skills:** SQL · Power BI · Tableau · Python · Excel · BigQuery · DAX

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/bhupenderneshu)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](#)

</div>

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star!

</div>
