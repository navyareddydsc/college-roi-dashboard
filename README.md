# 🎓 College ROI Analysis – SQL + Power BI Project

---

## 📘 Overview

This project showcases my SQL and Power BI skills by analyzing the **Return on Investment (ROI)** of colleges across India. It involves **database setup, data integration, feature engineering**, and **Power BI dashboard creation**. The goal is to help prospective students and educational analysts make data-driven decisions about college selection.

---

## 📁 Project Structure

### 🔹 Database Setup
- Created a MySQL database `college_roi_db` and set up 4 relational tables:
  - `college_table`
  - `fees_table`
  - `placements_table`
  - `cutoffs_table`

### 🔹 Data Import
- Imported CSV data for each table into MySQL
- Ensured foreign key relationships for accurate joins

### 🔹 Data Cleaning
- Filtered for "General" category records
- Handled null values and ensured consistency in fee and placement figures

### 🔹 SQL Integration
- Joined all 4 tables using `college_id` as primary key
- Created a **view** to export cleaned, joined data for Power BI

---

## 🛠 Feature Engineering

- Introduced a custom metric for ROI:
  ```sql
  ROI (%) = (Average Package / Total Fee) * 100
  ```
- Added this ROI calculation directly in the SQL view for seamless integration with Power BI
- Applied grouping and filtering to handle government/private segmentation and stream categories

---

## 📊 Dashboard Insights (Power BI)

Visuals & Components:
- 📌 **Top 5 Colleges by ROI**
- 📍 **State-wise Average ROI**
- ⚙️ **Stream-wise ROI vs Average Package** (combo chart)
- 🎯 **Cutoff Rank vs ROI** (scatter plot)
- 💡 **KPI Cards**: Highest ROI %, Average ROI, Total Colleges
- 🔄 Slicers: Stream, State, Exam, Type

---

## 🧠 Business Questions Solved

1. Which colleges provide the highest return on investment?
2. How does stream type affect ROI (Engineering vs MBA vs Medical)?
3. What is the relationship between cutoff rank and ROI?
4. Are government colleges offering better ROI than private ones?
5. What are the average ROI figures across states and streams?

---

## 📈 Key Insights

- **IIM Ahmedabad** tops with ROI of **767%**
- **Engineering** and **Government** colleges show higher ROI than MBA/Private colleges
- **AIIMS** delivers high ROI with very low cutoff ranks
- Clear trend: **lower cutoff ranks = higher ROI**
- State-wise variations show opportunity for localized recommendations

---

## ✅ Actionable Recommendations

- 🎓 Choose colleges with lower fees and strong placement records to maximize ROI
- 📍 Focus on Engineering streams for better ROI prospects
- 📊 Consider both **ROI and cutoff ranks** when choosing institutions
- 🎯 Government colleges tend to outperform private in ROI

---

## 🔗 Tools Used

- **SQL (MySQL)** – data modeling, joins, views, aggregations
- **Power BI** – dashboards, filters, DAX-based KPIs
- **Power Query** – data transformation
- **Excel/CSV** – source data structure

---

## 📷 Screenshot

*(Insert your dashboard screenshot here)*

---

## 📁 Files Included

- `college_table.csv`
- `fees_table.csv`
- `placements_table.csv`
- `cutoffs_table.csv`
- `college_roi_dashboard.pbix`
- `README.md`

---

## ⚠️ Notice

All data in this project is artificially created for educational purposes and does not reflect real college data. This project is not affiliated with any academic institution or organization.
