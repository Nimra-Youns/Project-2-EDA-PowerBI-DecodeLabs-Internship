# 📊 Project 2: Exploratory Data Analysis — E-Commerce Orders Dataset

**Tool:** Microsoft Power BI  
**Submitted by:** Nimra Youns  
**Internship:** Decode Lab  
**Date:** 14 May 2025  

---

## 📌 Overview

Performed EDA on a dataset of **1,200 e-commerce orders** recorded between
January 2023 and June 2025. The goal was to uncover patterns, trends,
distributions, and outliers to support business decision-making.

---

## 📁 Dataset Summary

| Detail | Value |
|---|---|
| Total Records | 1,200 Orders |
| Total Columns | 14 |
| Date Range | Jan 2023 – Jun 2025 |
| Products | Monitor, Phone, Tablet, Chair, Printer, Laptop, Desk |
| Order Statuses | Shipped, Cancelled, Returned, Delivered, Pending |
| Payment Methods | Debit Card, Online, Credit Card, Gift Card, Cash |
| Referral Sources | Instagram, Referral, Email, Facebook, Google |

---

## 📈 Descriptive Statistics

| Metric | Value |
|---|---|
| Total Revenue | $1,264,761.96 |
| Total Orders | 1,200 |
| Mean Order Value | $1,053.97 |
| Median Order Value | $823.62 |
| Max Order Value | $3,456.40 |
| Min Order Value | $11.39 |
| Cancellation Rate | ~19.25% |
| Coupon Usage Rate | ~74.25% |

> The mean ($1,053.97) is significantly higher than the median ($823.62),
> indicating a **right-skewed distribution** driven by a small number of
> high-value orders.

---

## 💡 Key Insights

- **Chair and Printer** generated the highest total revenue across all categories
- **Cancellation rate of ~19.25%** is a critical business risk — nearly 1 in 5 orders does not complete
- **Instagram** is the highest-performing referral channel in both order volume and revenue
- **74.25% of orders used a coupon**, highlighting strong price sensitivity among customers
- **SAVE10 and FREESHIP** are the most used coupons; WINTER15 has the lowest adoption
- Monthly revenue was **stable with no strong seasonal peaks**, suggesting a consistent customer base
- **Outliers detected**: High-value orders above $2,800 (bulk purchases) and low-value orders below $50 (minimal single-item purchases)

---

## 📊 Dashboard Preview

![Dashboard](https://raw.githubusercontent.com/Nimra-Youns/Project-2-EDA-PowerBI-DecodeLabs-Internship/main/Dashboard.png)

---

## 🛠️ Tools & Methodology

- **Power BI Desktop** — end-to-end analysis and dashboarding
- **Power Query Editor** — data type validation, null handling, derived columns
- **DAX Measures** — SUM, AVERAGE, MEDIAN, COUNT, DIVIDE
- **Visualizations** — Card visuals, Line Chart, Bar Charts, Donut Chart, Scatter Chart, Slicers
- **Outlier Detection** — Scatter plot (Unit Price vs Total Price)

---

## 📂 Files in This Repository

| File | Description |
|---|---|
| `Dataset for Data Analytics.xlsx` | Raw e-commerce orders dataset |
| `EDA_Report_Nimra_Youns.docx` | Full written EDA report |
| `dashboard.png` | Power BI dashboard screenshot |

---

*Completed as part of the DecodeLabs Data Analytics Internship — Project 2*
