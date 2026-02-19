# IT-Expenditure-Analysis-PowerBI

# IT Expenditure Analysis Dashboard (Power BI)

## 📌 Project Overview
This project focuses on analyzing IT expenditure across different business areas, regions, IT functions, and cost categories using **Power BI**.  
The objective is to provide transparency into **Actual vs Plan vs Forecast IT costs**, identify spending variances, and highlight key cost drivers to support better budgeting and financial decision-making.

This project includes two dashboards:
1. **IT Financial Performance Dashboard (Actual vs Plan vs Forecast)**
2. **IT Spend Forecast Dashboard (Future Data Analysis)**

---

## 🎯 Problem Statement
The organization is facing challenges in effectively managing IT expenditure due to significant variances between:
- Actual spending
- Planned budgets
- Forecasted budgets

There is a need to identify:
- Where overspending or underspending is occurring
- Which regions/countries consume the highest IT budget
- Which cost categories drive most IT spending
- How future spending is expected to behave

---

## 🗂 Dataset Description
The dataset contains IT expenditure details across multiple dimensions, including:

- Date / Month
- Region and Country
- Business Area
- IT Area and IT Sub Area
- Cost Element Group and Cost Element Name
- Actual, Forecast, and Plan values

---

## 🧹 Data Cleaning & Preparation
The raw Excel data was imported into Power BI and cleaned using **Power Query**.

Key data preparation steps:
- Standardized column names for consistency
- Handled missing values (Actual/Plan/Forecast blanks)
- Converted month values into proper date format
- Created a Date Table for time-series analysis
- Built relationships for an optimized data model
- Developed DAX measures for KPIs and variance calculations

---

## 📊 Key KPIs Created
The following key metrics were calculated using DAX:

- **Total Actual Spend**
- **Total Plan Spend**
- **Total Forecast Spend**
- **Plan Variance (Actual - Plan)**
- **Forecast Variance (Actual - Forecast)**
- **Variance Percentage**
- Spend breakdown by Region, IT Area, and Cost Element Group

---

## 🔍 Key Insights (Current Dashboard)
### Overall Spend Summary
- **Total Actual Spend:** 555.73M  
- **Total Plan Spend:** 900.40M  
- **Total Forecast Spend:** 890.54M  
- **Plan Variance:** -344.67M (Under Budget)

### Monthly Trend
- Spending trend is stable with a peak in **June (75.50M)**
- Lowest spend observed in **January (58.46M)**
- Actual data is available mainly till August (future months handled separately)

### Region Insights
- IT expenditure is heavily concentrated in the **USA region (~470M)**
- **Europe** is the second highest spending region (~70M)

### Cost Driver Insights
- **Labor is the biggest cost driver (290.29M)**
- Hardware/Software and Depreciation are also major contributors

### IT Area Insights
Highest spending IT Areas:
- Functional IT
- BU Support
- Infrastructure

---

## 🔮 Future Dashboard Insights
The Future Spend Dashboard provides a view of expected IT spending in upcoming months.
It helps identify:
- Projected spending trends by month
- Future region-wise and IT area-wise cost distribution
- Future major cost drivers for proactive budget planning

---

## 📌 Dashboard Features
- Interactive slicers for Month, Region, Country, Business Area, IT Area, and Cost Group
- KPI cards for quick executive summary
- Trend line chart for month-wise comparison
- Bar charts for region and IT area distribution
- Treemap / pie chart for cost group contribution
- Top 10 cost element drill-down

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop**
- **Excel Dataset**
- **Power Query (ETL & Data Cleaning)**
- **DAX (Measures and Calculations)**

---

## 📁 Files Included
- `IT_Expenditures_Analysis.pbix` → Power BI report file
- `dashboard_current.png` → Current dashboard screenshot
- `dashboard_future.png` → Future dashboard screenshot
- `IT_Expenditures_Analysis.pdf` → Exported dashboard report

---

## 🚀 How to Use
1. Download the `.pbix` file from this repository
2. Open it in **Power BI Desktop**
3. Refresh the dataset if needed
4. Use slicers to interact with the dashboard and explore insights

---

## 📌 Author
**Aman K**  
Data Analyst | Power BI Developer  

