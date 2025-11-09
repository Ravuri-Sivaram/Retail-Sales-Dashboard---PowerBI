# Retail Sales Dashboard (Power BI)
Retail sales report analysis in Power BI featuring interactive KPIs, detailed trend analysis by month and weekday, top-selling products, and city-level sales performance. Designed to provide comprehensive insights, support data-driven decisions, and allow stakeholders to explore and understand all key metrics in the sales dataset interactively.
---

## 📊 Dashboard Overview

The dashboard contains the following sections:

### 1. Key Performance Indicators (KPIs)
- **Total Sales** – Overall revenue from all orders.
- **Total Profit** – Calculated profit (assumed 20% margin).
- **Total Cost** – Total cost of products sold (assumed 80% of sales).

### 2. Sales Trends
- **Monthly Sales** – Line chart showing sales per month.
- **Weekly Sales** – Bar chart showing sales per weekday.

### 3. Product Insights
- **Top 7 Products by Sales** – Bar chart of best-selling products.
- **Top 7 Products by Quantity Ordered** – Bar chart of most ordered products.
- **Product Slicers** – Drop-downs to filter by product category or name.

### 4. City Analysis
- **Top 5 Cities by Sales** – Bubble map showing city-wise sales performance.
- Interactive tooltips show sales, profit, and quantity for each city.

### 5. Interactivity
- Slicers for **Month, Weekday, Product, and City**.
- **Reset Filters Button** to return the dashboard to its default state.
- Clicking any visual updates related charts and KPIs dynamically.

---

## 💻 Dataset
- Source: [Sales Report and Analysis on Kaggle](https://www.kaggle.com/datasets/ilcaniaabreu/sales-report-and-analysis)  
- Columns include: `Order ID, Product, Quantity Ordered, Price Each, Order Date, Purchase Address, Month, Sales, City, Hour`.

---

## ⚡ Features
- Interactive visuals with dynamic measures.
- Proper sorting of months and weekdays for accurate trends.
- Compact layout suitable for management or business presentations.
- Top 5 city analysis for geographic sales insights.

---

## 🛠️ Tools Used
- **Power BI Desktop** (version 2.107.841.0, July 2022)
- DAX formulas for KPIs and calculated columns

---

## 📁 Files
- `RetailSalesDashboard.pbix` – Main Power BI file.
- `README.md` – Project documentation.

---

## 🔗 How to Use
1. Open `RetailSalesDashboard.pbix` in Power BI Desktop.  
2. Use the slicers to filter by month, product, weekday, or city.  
3. Click the **Reset Filters** button to return the dashboard to its default view.  
4. Hover over charts or map bubbles to see detailed tooltips.

---

## 📈 Insights
- Quickly identify top-performing products and cities.  
- Analyze sales trends by month and weekday.  
- Evaluate profit and revenue distribution interactively.

---

## ⚖️ Notes
- Profit is assumed as 20% of sales (no exact cost data available).  
- Data visualizations are interactive and fully responsive to slicer selections.
