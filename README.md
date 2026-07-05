# ☕ Coffee Sales Dashboard

An interactive Excel dashboard analyzing coffee sales data — built with Pivot Tables, XLOOKUP formulas, Slicers, and a Timeline filter to track revenue by country, coffee type, roast, and customer.

## 📊 Dashboard Preview

![Coffee Sales Dashboard](dashboard-overview.jpg)

## 🎯 Project Overview

This workbook analyzes coffee order data end-to-end — from raw orders, customers, and products tables to a single interactive dashboard — to help identify top-performing markets, products, and customers.

## 🛠️ Tools & Techniques Used

- **Microsoft Excel**
- Pivot Tables & Pivot Charts
- Slicers (Roast Type, Loyalty Card, Size) & Timeline (Order Date)
- **XLOOKUP** formulas to pull Customer Name, Email, Country, and Loyalty Card into the orders table
- Nested `IF` formulas to decode short codes into readable labels (e.g., "Ara" → "Arabica", "L" → "light")
- Calculated fields: `Sales = Unit Price × Quantity`

## 📁 Data Structure

| Sheet | Description |
|---|---|
| `Dashboard` | Main interactive dashboard view |
| `TotalSales` | Sales trends over time (2019–2022) |
| `Country By Sales` | Revenue breakdown by country |
| `Top5Customers` | Top 5 customers by total spend |
| `orders` | 1,000 order-level transactions with looked-up customer & product details |
| `customers` | Customer directory (name, email, country, loyalty status) |
| `products` | Product catalog (coffee type, roast, size, unit price, profit margin) |

## 📈 Key Insights

- **United States** is the top market by far, generating **$35,638** in sales — more than 5x Ireland ($6,697) and 12x the United Kingdom ($2,799)
- **Allis Wilmore** is the top customer by spend ($317), followed closely by Brenn Dundredge, Terri Farra, Nealson Cuttler, and Don Flintiff — all within a tight $278–$317 range
- Coffee types tracked: **Arabica, Excelsa, Liberica, Robusta**, each available across **Light, Medium, and Dark** roasts and 4 package sizes (0.2 kg, 0.5 kg, 1.0 kg, 2.5 kg)
- Sales show clear month-to-month volatility across 2019–2022, useful for spotting seasonal demand patterns

## 🔍 Dashboard Features

- **Timeline Slicer** — filter by month/year (2019–2022)
- **Roast Type, Loyalty Card & Size Slicers** — multi-level dynamic filtering
- **Total Sales Over Time** line chart split by coffee type
- **Sales by Country** and **Top 5 Customers** bar charts

## 📌 How to Use

1. Download the `.xlsx` file from this repository
2. Open in Microsoft Excel (2021 / Microsoft 365 recommended — file uses XLOOKUP)
3. Use the slicers and timeline on the Dashboard tab to explore the data interactively

## 👤 About Me

I'm Zahid Iqbal, an aspiring Data Analyst skilled in Excel, SQL, and Power BI.

- 🔗 [LinkedIn](https://linkedin.com/in/zahid-iqbal-5366a537a)
- 💻 [GitHub](https://github.com/zahidiqbal655)

---
⭐ If you found this project useful, feel free to star this repository!
