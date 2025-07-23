# 📊 Superstore Sales Dashboard (Power BI)

An interactive Power BI dashboard built using Superstore sales data to uncover business insights, forecast sales, and visualize KPIs across multiple dimensions.

![Dashboard Screenshot](./b7be8665-1aa3-43e2-9c83-d4d56e33b609.png)

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **Power Query** – For data transformation and cleaning
- **DAX (Data Analysis Expressions)** – For calculated columns and measures
- **Excel (.csv format)** – Raw dataset source

---

## 📂 Dataset Overview

The dataset includes:
- Sales, Profit, and Quantity
- Customer and Product details
- Regional segmentation
- Order and Shipping data
- Payment mode, returns, etc.

---

## 🚀 Project Workflow

### 1. **Data Cleaning & Transformation**
- Removed nulls and duplicates using **Power Query**
- Converted date fields into proper `datetime` format
- Created new columns using DAX (e.g., Month-Year from Order Date)

### 2. **DAX Calculations**
- Created **KPIs**: Total Sales, Profit, Quantity, Avg. Delivery Days
- Built calculated columns for Year, Month, and custom KPIs
- Used DAX for **forecasting** and **time intelligence**

### 3. **Data Modeling**
- Ensured appropriate data types and relationships between tables
- Set hierarchies (e.g., Region > State > City)

### 4. **Dashboard Creation**
- Used:
  - **Slicers** for Region, Segment, and Payment Mode
  - **Line & Bar Charts** for monthly trends
  - **Pie Charts** for share by Segment and Payment Mode
  - **Map Visual** for geographic sales analysis
  - **Forecast line** for sales prediction over 15 days

---

## 📈 Key Insights & Features

- Top-performing categories: Technology and Office Supplies
- Sales trend and profit analysis across 2019–2021
- Regional and segment-wise breakdown of KPIs
- Payment mode popularity and performance
- Sales forecasting using Power BI's built-in time series tools

---

## 📎 Future Enhancements

- Drill-down interactions by category and state
- Dynamic date range selector
- Integrate R or Python for advanced forecasting models

---

## 📄 PDF Export

[👉 View Full Dashboard PDF](./super%20store%20dashboard.pdf)

---

## 📬 Contact

For any queries, connect with me on [LinkedIn](https://linkedin.com) or reach out via email.

---

