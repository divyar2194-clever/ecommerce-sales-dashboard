# 🛒 E-Commerce Sales Dashboard

An interactive Power BI dashboard analyzing e-commerce sales performance — tracking YTD/YoY trends across sales, profit, quantity, and profit margin, with category, regional, and product-level breakdowns.

## 📊 Project Overview

This dashboard helps track business performance year-over-year and segment-wise (Consumer, Corporate, Home Office), highlighting top and bottom performing products, regional sales distribution, and shipping patterns to support inventory and sales strategy decisions.

## 🛠️ Tools Used

- **Power BI** - Dashboard design, data modeling, interactive visuals
- **DAX (Data Analysis Expressions)** - Custom measures for time-intelligence calculations
- **Conditional Formatting**- Dynamic icons and colors based on performance

## 🧮 DAX Measures Built

For each of the four core KPIs — **Sales, Profit, Quantity, and Profit Margin** — the following measures were created:

- **YTD (Year-to-Date)** value
- **PYTD (Previous Year-to-Date)** value for comparison
- **YoY (Year-over-Year) % change**
- **Conditional Icon Logic** using `IF` statements - dynamically showing an up/down arrow based on whether performance improved or declined
- **Conditional Color Logic** - icon and value colors change (green for growth, red for decline) based on the YoY result

This same measure pattern was applied consistently across all four KPIs, making the dashboard easy to extend to new metrics.

## 📈 Key Insights

- **YTD Sales:** $11.53M (-0.83% YoY)
- **YTD Profit:** $1.34M (+4.50% YoY) - profit grew even as sales dipped slightly, indicating improved cost efficiency
- **YTD Quantity Sold:** 107.2K units (-7.29% YoY)
- **YTD Profit Margin:** 11.58% (+5.37% YoY)
- **Top Category:** Office Supplies leads with $6.92M in YTD sales, though down -1.22% YoY
- **Top Product:** Staple Envelope is the highest revenue product at $57K YTD
- **Lowest Performer:** Rediform S.O.S. ranks among the bottom 5 products at $179.99 YTD
- **Regional Split:** West leads regional sales at 32.22%, followed by East (28.42%) and Central (23.19%)
- **Shipping:** Standard Class is the dominant shipping method at 60.51% of orders, followed by Second Class (19.22%) and First Class (15.1%)  indicating most customers prioritize cost over speed

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `e commerce sales dashboard.pbix` | Full Power BI file with data model, DAX measures, and dashboard visuals |

## 💡 Business Recommendation

Despite a slight dip in sales and quantity, profit and profit margin both grew suggesting better pricing or cost control. Investigating why Office Supplies sales declined YoY despite being the top category could reveal opportunities to recover lost volume without sacrificing the margin gains.

---
*Project by Divya R | [GitHub](https://github.com/divyar2194-clever)*
