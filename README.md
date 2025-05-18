# 🛍️ RetailPulse: Power BI Sales Dashboard

This repository contains Task 8 of the Data Analyst Internship project – a **Power BI dashboard** built using the *Retail Insights* dataset. The goal was to create an interactive and clean dashboard that showcases sales performance across time, region, and product category.

---

## 📊 Project Overview

**Objective:**  
To build a visually appealing and functional sales dashboard using Power BI that highlights sales performance trends by month, region, and product category.

---

## 📁 Dataset Used

- **Name:** Retail Insights – A Comprehensive Sales Dataset  
- **Source:** [Kaggle](https://www.kaggle.com/datasets/rajneesh231/retail-insights-a-comprehensive-sales-dataset)  
- **File:** `data.csv`  
- **Rows:** 5000  
- **Columns:** 24  
- Includes details such as:  
  - Order and ship dates  
  - Customer and region info  
  - Product categories  
  - Cost, profit, discount, total sales  

---

## 🛠 Tools & Technologies

- **Power BI Desktop** (for dashboard design)
- **Power Query** (for data cleaning and transformation)
- **Excel/CSV** (for source data)

---

## 🔍 Data Cleaning & Processing

- Converted date columns (`Order Date`, `Ship Date`) to proper date formats
- Created a custom `Month-Year` column for trend analysis
- Converted pricing and total columns from text/object to decimal numbers
- Ensured null values in non-critical fields were handled or ignored

---

## 📈 Dashboard Features

The dashboard includes the following interactive visuals:

- 📉 **Line Chart** – Sales trend over time (`Month-Year`)
- 📊 **Bar Chart** – Sales performance by `State`
- 🍩 **Donut Chart** – Sales distribution by `Product Category`
- 🔘 **Slicer** – Filter visuals dynamically by `Product Category`

---

## 💡 Key Insights

1. The **East region** consistently led in sales performance throughout the year.
2. **Furniture** and **Technology** categories made up the bulk of total sales.
3. A clear seasonal spike in sales can be observed during **Q3**.
4. Discounts and shipping costs did not significantly impact overall profits.

---

## 📎 Files Included

| File Name       | Description                                 |
|----------------|----------------------------------------------|
| `data.csv`      | Cleaned retail dataset                      |       
| `README.md`     | Project overview and documentation          |
| `.pbix` | Power BI dashboard file (if included)               |

---

## 🚀 How to Use

1. Clone or download this repo.
2. Open the `.pbix` file in Power BI Desktop (if shared).
3. Or review the `Dashboard.pdf` and `insights.txt` for final results.

---

## ✅ Outcome

This project helped in strengthening skills in:
- Data cleaning and transformation
- Visual storytelling using Power BI
- Creating business-ready dashboards
