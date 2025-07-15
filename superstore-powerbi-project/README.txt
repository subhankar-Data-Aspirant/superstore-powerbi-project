# 🧠 Power BI + Python Superstore Dashboard Project

This is a complete end-to-end Business Intelligence project built using **Python** and **Power BI** on the real-world **Superstore Sales dataset**.  
The dashboard delivers actionable insights on customer segments, product performance, and regional sales trends.

---

## 📦 Dataset Used

- **Sample - Superstore.xls**  
- Source: [Tableau Public Dataset](https://public.tableau.com/app/sample-data)

---

## 🚀 Project Overview

### 🔧 Tools & Technologies
- Python (Pandas, NumPy)
- Power BI
- DAX (Data Analysis Expressions)
- Excel

---

## 🔍 Project Highlights

### 🐍 Python: Data Cleaning & Preparation
- Handled missing values
- Converted date columns
- Created new features like:
  - `Shipping Days` = `Ship Date - Order Date`
- Cleaned and exported data to CSV for Power BI use

```python
df['Order Date'] = pd.to_datetime(df['Order Date'])
df['Ship Date'] = pd.to_datetime(df['Ship Date'])
df['Shipping Days'] = (df['Ship Date'] - df['Order Date']).dt.days
```

---

### 📊 Power BI Dashboard (3 Pages)

#### 📄 Page 1: Executive Summary
- KPIs: Total Sales, Profit, Orders, Profit Margin
- Category-wise Sales & Profit
- Sales Trend over Time
- Segment slicer

#### 📄 Page 2: Customer & Product Insights
- Top Customers by Sales
- Best-Selling Products
- Segment-wise Sales Share

#### 📄 Page 3: Regional Performance
- Sales by State (Map Visual)
- Profit by Region (Bar Chart)
- Shipping Mode Distribution
- Delivery Time Analysis

---

## 📌 Key Features

- Advanced DAX Measures:
  - `Total Profit`, `Profit Margin`, `Avg. Shipping Days`
- Conditional Formatting for Profit Visuals
- Geo Maps with custom tooltips
- Grid-aligned layout for professional design

---

## 📈 Insights Delivered

- **Technology** is the highest revenue-generating category
- **West** region leads in both sales and profit
- **Standard Class** is the most preferred shipping mode
- **Corporate** segment yields higher profits than others

---

## 🧠 Skills Demonstrated

- Data Wrangling & Cleaning (Python)
- Business Intelligence Reporting (Power BI)
- Analytical Thinking & Insight Building
- Dashboard UI/UX Design

---

## 🖼️ Dashboard Screenshots

| Executive Summary | Product Insights | Regional View |
|-------------------|------------------|---------------|
| ![Page 1](images/page1.png) | ![Page 2](images/page2.png) | ![Page 3](images/page3.png) |

---

## 📬 Contact

**Created by:** Subhankar  
**LinkedIn:** [linkedin.com/in/yourusername](https://linkedin.com/in/yourusername)  
**Email:** your@email.com

---

## ⭐ Want to Collaborate?

Open to feedback, suggestions, or freelance Power BI projects. Feel free to fork this project or reach out!

---

## 📸 Dashboard Preview

| Executive Summary | Customer & Product Insights | Regional Performance |
|-------------------|-----------------------------|----------------------|
| ![](images/page1.png) | ![](images/page2.png) | ![](images/page3.png) |
