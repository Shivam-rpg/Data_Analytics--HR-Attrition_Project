# 📊 HR Attrition Analysis Project (Excel + Power Pivot)
## 📌 Overview

This project analyzes employee attrition using a structured data model in Microsoft Excel. It focuses on identifying patterns and key drivers behind employee turnover using Power Pivot, DAX, and interactive dashboards.

The dataset is organized in a star schema format, making it scalable and industry-relevant.

# 🧱 Data Model Structure
##🔹 Fact Table

Fact_Attrition
Contains core transactional data:

- Attrition_ID – Unique record ID
- Employee_ID – Employee identifier
- Date_ID – Time reference
- Attrition_Status – Attrition flag (Yes/No)
- Monthly_Income – Employee salary
- OverTime – Overtime status
- YearsAtCompany – Total tenure
- YearsSinceLastPromotion – Promotion gap
- JobSatisfaction – Satisfaction score

## 🔹 Dimension Tables

- Dim_Employee – Employee details
- Dim_Date – Time-based analysis
- Dim_Satisfaction – Satisfaction categories
- Dim_Performance – Performance ratings

## 🔹 Pivot Tables / Analysis Sheets

- Pivot_Dept_Attrition – Attrition by department
- Pivot_Dept_Attr_Over_Rate – Attrition vs overtime
- Pivot_Gender_Attrition – Gender-based attrition
- Pivot_Satisfaction – Satisfaction impact
- Pivot_Avg_Performance – Performance trends

## 🎯 Objectives

- Identify key factors influencing employee attrition
- Analyze impact of:
- Salary
- Overtime
- Job Satisfaction
- Promotion delays
- Build an interactive HR dashboard
- Support data-driven HR decisions

## 🛠️ Tools & Technologies

- Microsoft Excel
- Power Pivot
- DAX (Data Analysis Expressions)
- Pivot Tables
- Data Visualization

## 📊 Key Features

- ✅ Star Schema Data Model (Fact + Dimension tables)
- ✅ DAX Measures for KPIs
- ✅ Department-wise Attrition Analysis
- ✅ Overtime Impact Study
- ✅ Satisfaction vs Attrition Insights
- ✅ Interactive Dashboard with Filters

## 📈 Key Insights

- Employees working overtime show higher attrition rates
- Low job satisfaction strongly correlates with attrition
- Employees with long promotion gaps are more likely to leave
- Certain departments have consistently higher turnover

## 📷 Dashboard

The project includes an interactive Dashboard sheet where you can:

Filter by department, satisfaction, and performance
Analyze trends visually using charts

--------

## 🚀 How to Use
--------

- Download the Excel file
- Open in Microsoft Excel (2016 or later)
- Explore:
- Dashboard for insights
- Pivot Tables for analysis
- Data Model via Power Pivot
- Use slicers to interact with data
