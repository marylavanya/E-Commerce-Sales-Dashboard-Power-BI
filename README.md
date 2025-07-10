# 📊 E-Commerce Sales Dashboard | Power BI

An interactive Power BI dashboard that analyzes YTD sales, profit, margin, and product performance using sample e-commerce data. Designed to support business decision-making, the dashboard highlights customer segments, regional trends, shipping breakdowns, and top/bottom product insights.

## 🔗 Live Dashboard  👉 [View the interactive Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiMmE0M2ViNmQtMGE5NS00MTIzLWI1NDAtM2ExOTIxOWU0MTY5IiwidCI6ImU1NTlhMWUxLWRmNDAtNDJmMC05YzIyLTlhNmE4NGE3ZWVmYyIsImMiOjN9)

**No login or installation required — opens directly in the browser.**

### 📷 Dashboard Preview

<p align="center">
  <img src="https://github.com/marylavanya/E-Commerce-Sales-Dashboard-Power-BI/blob/main/Dashboard.png?raw=true" alt="E-Commerce Power BI Dashboard" width="800"/>
</p>



## 📥 Download the Power BI File
Explore the full Power BI project with data model and custom DAX measures : ** ➡️ [Download the pbix File](https://github.com/marylavanya/E-Commerce-Sales-Dashboard-Power-BI/blob/main/E-Commerce%20Sales%20Dashboard.pbix?raw=true)**

## 📚 Table of Contents
- [Executive Summary](#executive-summary)
- [Dashboard Overview](#dashboard-overview)
- [DAX Measures Implemented](#dax-measures-implemented)
- [Key Insights](#key-insights)


## 🧭Executive Summary

This Power BI dashboard empowers business leaders and analysts to make fast, data-driven decisions by providing:

- 📉 **Detect underperforming** regions, products, and categories in real time.
- 📈 **Monitor year-over-year (YoY)** growth trends across sales, profit, and quantity.
- 👥 **Analyze customer behavior** across segments (Consumer, Corporate, Home Office).  
- 🕒 **Enable time-based comparisons** using dynamic YTD and PYTD measures.  
- 📊 **Quickly assess KPIs** through conditional formatting and trend arrows.  



## 📈Dashboard Overview

| Section                  | Visual Type      | Description                                      |
|--------------------------|------------------|--------------------------------------------------|
| **KPI Summary Cards**     | Card + Sparkline | YTD Sales, Profit, Quantity, Profit Margin      |
| **Sales by Category**     | Matrix Table     | YTD & PYTD Sales, YoY % with trend icons        |
| **Sales by State**        |      Map         | Geographic bubble map with customer region keys |
| **YTD Sales by Region**   | Donut Chart      | % share by West, East, South, Central           |
| **YTD Sales by Shipping** | Donut Chart      | % by shipping class (Standard, First, etc.)     |
| **Top & Bottom Products** | Bar Charts       | Top 5 and Bottom 5 products by YTD sales        |
| **Segment Slicer**        | Button Slicer    | Filter report by Consumer, Corporate, Home Office|


## 🧮DAX Measures Implemented

Custom DAX measures were implemented to enhance analytical depth and interactive analysis:
- **Time Intelligence**: YTD, PYTD, and YoY % for Sales, Profit, Quantity, Profit Margin
- **Conditional Formatting**: KPI trend arrows and colored performance cards
- **Dynamic Segmentation**: Filters using button slicers (segment, region)
- **Calendar Table**: Marked date table for accurate time-based calculations


## 💡Key Insights

- 🥇 **West Region** leads with 32.22% of YTD Sales
- 🚚 **Standard Class Shipping** dominates with 60.51% share
- 💰 **Office Supplies** is the top-selling category at $6.92M
- 🧾 **Staple Envelopes** and **Staples** are highest-revenue products
- 📉 **Rediform SO** had the lowest sales at $0.18K
- 🔻 **Technology** category declined YoY by -1.37%
- 🔼 **Furniture** grew YoY by 0.73%, suggesting stable momentum
