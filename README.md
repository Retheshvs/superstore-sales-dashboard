# 📊 SuperStore Sales & Revenue Analysis Dashboard

> **Data Analysis Internship — Task #1**  
> Built using: Microsoft Power BI Desktop | Dataset: SuperStore Global Orders

---

## 📌 Project Overview

An interactive multi-page sales and revenue analysis dashboard built on the SuperStore global orders dataset (51,290 orders across 2011–2014). The dashboard provides KPI tracking, revenue trend analysis, regional breakdowns, and business insight generation.

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `SuperStore_Dashboard.pbix` | Power BI dashboard file (open with Power BI Desktop) |
| `SuperStore_Orders.csv.xlsx` | Source dataset — 51,290 orders, 22 columns |

---

## 📈 Dashboard Pages

| Page | Content |
|------|---------|
| **Overview** | KPI cards — Total Sales, Profit, Margin %, Orders, Quantity + Business Insights |
| **Sales Trend** | Yearly Sales vs Profit line chart (2011–2014) |
| **Category Analysis** | Revenue by category (donut) + Profit margin by category (bar) |
| **Market & Products** | Sales by global market + Top sub-categories by revenue |
| **Customer Segments** | Revenue split across Consumer, Corporate, Home Office |
| **Monthly Performance** | Monthly sales trend showing seasonality |
| **Filters** | Year, Market, Category, Segment slicers |

---

## 🔢 Key KPIs

| Metric | Value |
|--------|-------|
| Total Sales | $12.64M |
| Total Profit | $1.47M |
| Profit Margin | 11.62% |
| Total Orders | 51,290 |
| Total Quantity | 178K units |

---

## 💡 Key Business Insights

- 📈 Sales grew **90% from 2011 to 2014** ($2.26M → $4.30M)
- ⚠️ **Furniture has only 7% profit margin** vs 14% for Technology — review discounting strategy
- 🌏 **APAC & EU** are the highest revenue markets globally
- 📱 **Phones & Copiers** lead sub-category sales under Technology
- 🛍️ **Consumer segment** drives 51.48% of total order volume
- 📅 **Q4 (Oct–Dec)** is the peak sales period across all years

---

## 🛠️ Tools Used

- **Microsoft Power BI Desktop** — dashboard creation, DAX measures, slicers
- **Power Query** — data cleaning and type formatting
- **DAX** — custom measures (Profit Margin %, Avg Discount %, etc.)

---

## 🚀 How to Open

1. Download `SuperStore_Dashboard.pbix`
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop) (free)
3. If prompted about data source, point it to `SuperStore_Orders.csv.xlsx`
