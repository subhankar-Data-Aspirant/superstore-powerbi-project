# 🧠 Power BI + Python Superstore Dashboard Project

This is a complete end-to-end Business Intelligence project built using **Python** and **Power BI** on the real-world **Superstore Sales dataset**.  
The dashboard delivers actionable insights on customer segments, product performance, and regional sales trends.

---

## 📦 Dataset Used

- **Sample - Superstore.xls**  
- Source: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

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

```python```
df['Order Date'] = pd.to_datetime(df['Order Date'])
df['Ship Date'] = pd.to_datetime(df['Ship Date'])
df['Shipping Days'] = (df['Ship Date'] - df['Order Date']).dt.days
</pre>
---

## 📊 Power BI Dashboard (3 Pages)

### 📄 Page 1: Executive Summary
KPIs: Total Sales, Profit, Orders, Profit Margin

Sales & Profit by Category

Year-wise Sales Trend

Segment Filter Buttons

---
### 📄 Page 2: Customer & Product Insights
Top 10 Customers by Sales

Segment-wise Sales Distribution (Pie Chart)

Top 10 Products by Sales

----      
### 📄 Page 3: Regional Performance
Sales Distribution Map by State

Total Profit by Region

Shipping Days Distribution

Delivery Time Insights

---

## 📌 Key Features
### Advanced DAX Measures:

Total Profit, Profit Margin, Avg. Shipping Days

Clean and aesthetic UI design

Interactive filters and slicers

Tooltips and smooth layout

---

## 📈 Insights Delivered
Technology category has the highest revenue

West region is the most profitable

Consumer segment contributes highest sales volume

Standard Class is the most used shipping method

Delivery typically takes 2–4 days

## 🧠 Skills Demonstrated
Data Wrangling with Python

Insightful Visual Storytelling in Power BI

DAX Measures and Aggregations

Dashboard UI/UX Design

Business-Oriented Thinking

---

## 📸 Dashboard Preview

| Executive Summary | Customer & Product Insights | Regional Performance |
|-------------------|-----------------------------|----------------------|
| ![](images/page-1.png) | ![](images/page-2.png) | ![](images/page-3.png) |

---

## 🔗 Links
📊 View Full Dashboard (Optional Google Drive Link)

## 🧠 My LinkedIn Profile

🙋‍♂️ About Me
👨‍💻 Subhankar – Aspiring Data Analyst with a passion for building smart dashboards and deriving insights from messy data.
📬 Email: subhanakar2003g@Gmail.com
🌍 Portfolio:(https://www.linkedin.com/in/subhankarghosh-data-analyst/)

### ⭐ Want to Collaborate?
Open to freelance work, internships, or mentorships.
Feel free to fork this project or reach out if you liked it!
