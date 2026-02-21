# E-Commerce Sales Analytics Dashboard – Task 1

![Dashboard Preview]()

---

## 📌 Project Overview
This project presents a comprehensive analysis of e-commerce sales data using Power BI. The goal is to transform raw transactional data into meaningful business insights through interactive visualizations and structured metrics.

The dashboard provides a clear overview of sales performance, customer behavior, and product-level trends to support strategic decision-making.

---

## 🎯 Project Objectives

- Identify **top-performing products** based on sales and quantity.
- Analyze **sales trends over time** to detect growth patterns.
- Evaluate **customer-level sales distribution**.
- Calculate key business metrics like:
  - Total Sales
  - Total Orders
  - Total Quantity Sold
  - Average Order Value
- Build a visually appealing and professional dashboard layout.

---

## 📊 Dataset Details

- **Source:** Kaggle – E-Commerce Sales Dataset  
- **Format:** CSV / Excel  
- **Key Columns Used:**
  - Customer ID
  - Description (Product Name)
  - Invoice Number
  - Invoice Date
  - Quantity
  - Unit Price
  - Stock Code

---

## 🧹 Data Preparation Process

1. Removed null and duplicate records.
2. Converted date columns into proper Date format.
3. Ensured numerical consistency in Price and Quantity.
4. Created calculated measures in Power BI using DAX.

---

## 📈 Key Measures Created

- **Total Sales** = SUM(Quantity × Price)
- **Total Orders** = DISTINCTCOUNT(Invoice)
- **Total Quantity** = SUM(Quantity)
- **Average Order Value** = Total Sales ÷ Total Orders

---

## 🎨 Dashboard Design & Visualization

The dashboard includes:

- KPI Cards for quick performance overview
- Line chart for Sales Trend Analysis
- Clustered bar/column charts for Product-level comparison
- Sales distribution by Customer ID
- Invoice-level sales breakdown
- Clean navy + teal theme for professional presentation

The layout is structured to highlight KPIs at the top and detailed analysis below for better readability.

---

## 💡 Business Insights

- Certain products consistently generate higher revenue.
- Sales show a positive growth trend over the analyzed period.
- A small segment of customers contributes significantly to total revenue.
- Monitoring invoice-level sales helps identify high-value transactions.

---

## 🛠 Tools Used

- **Power BI Desktop** – Dashboard creation and analysis
- **Excel** – Initial data inspection and formatting

---

## 📦 Deliverables

- Interactive Power BI Dashboard
- KPI Metrics Overview
- Trend Analysis Visualizations
- Product and Customer Performance Analysis
- Business insights for decision-making

---

## 🚀 Conclusion

This dashboard demonstrates how raw e-commerce data can be transformed into actionable insights using visualization tools. It provides a structured and interactive way for businesses to monitor performance, identify growth opportunities, and optimize decision-making strategies.
