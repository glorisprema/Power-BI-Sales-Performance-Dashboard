# Sales Performance Dashboard | Power BI PL-300

![Dashboard](dashboard.png)

## 📊 Project Overview
Executive Sales Performance Dashboard built in Power BI Desktop analyzing 700 orders.
Created for PL-300 portfolio to demonstrate DAX, Power Query & Data Visualization.

## 🎯 KPIs
- **Total Orders:** 700 📦
- **Total Profit:** $41K
- **Total Sales:** $187K

## 🔍 Key Insights
- **Top Region:** South - 67K (36% of revenue), East - 55K
- **Top Product:** Mouse - 66K, Keyboard - 60K - Accessories drive volume
- **Monthly Trend:** Sales growth from Jan (3K) to Dec (24K) - strong Q4 performance

## 🛠️ Tools & Techniques
- Power BI Desktop, DAX, Power Query
- Visuals: KPI Cards, Bar Chart, Donut Chart, Line Chart
- Data Cleaning & Modeling

## 📐 DAX Measures Used
```dax
Total Sales = SUM(Sales[Sales])
Total Profit = SUM(Sales[Profit])
Total Orders = COUNTROWS(Sales)📂 Files in this Repo
dashboard.png - Final Dashboard ScreenshotSales_Dashboard_700Orders.pbix - Power BI Filedataset.xlsx - Raw Data (700 rows)👩‍💻 Author
glorisprema | Aspiring Data Analyst | PL-300 Certified Journey
