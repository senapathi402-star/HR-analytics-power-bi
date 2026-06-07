# HR Analytics Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

## 📊 Project Overview
An interactive HR Analytics Dashboard built with Power BI using a 1000-row HR dataset across 10 departments. The dashboard provides real-time insights into employee headcount, attrition, salary, and gender distribution with interactive department filtering.

## 🖥️ Dashboard Preview
![HR Analytics Dashboard](hr_dashboard.png)

## ✨ Features

### 📌 KPI Cards
| Metric | Value |
|--------|-------|
| Total Employees | 1,000 |
| Average Salary | $1,813,251 |
| Attrition Count | 201 |
| Attrition Rate | 20.1% |

### 📊 Visualizations
- **Headcount by Department** — Sorted bar chart showing employee distribution
- **Gender Distribution** — Pie chart showing Male/Female split
- **Attrition by Department** — Identifying high risk departments
- **Avg Salary by Department** — Compensation analysis across departments

### 🎯 Interactive Features
- **Department Slicer** — Filter entire dashboard by any department
- **Cross Filtering** — Click any visual to filter all others automatically
- **Dynamic KPI Cards** — All metrics update instantly with filters

## 🔍 Key Insights
- 📊 Marketing has highest headcount (112 employees)
- 💰 HR department has highest avg salary ($19,53,047)
- 📉 Engineering has highest attrition rate (23.7%)
- 👥 Male/Female split: 56.8% / 43.2%
- ⚠️ Overall attrition rate: 20.1% — needs attention!

## 🛠️ Tools & Technologies
- **Power BI Desktop** — Dashboard creation
- **DAX** — Custom measures and calculations
- **Excel** — Data source (.xlsx)

## 📐 DAX Measures Used

```dax
Attrition Count = 
COUNTROWS(FILTER(HR_Data, HR_Data[Attrition] = "Yes"))

Attrition Rate = 
DIVIDE([Attrition Count], COUNTROWS(HR_Data)) * 100
```

## 🚀 How to Use
1. Download `HR_Analytics_Dashboard.pbix`
2. Open with **Power BI Desktop** (free)
3. Use **Department slicer** to filter by department
4. Click any visual to cross-filter others

## 📁 Dataset
- **Rows:** 1,000 employees
- **Columns:** 23 features
- **Departments:** 10 (HR, IT, Finance, Engineering, Marketing, Sales, Operations, Legal, Product, Customer Support)

## 🔗 Links
- 📊 [LinkedIn](https://linkedin.com/in/senapathi-krishna-sai)
- 🐙 [GitHub](https://github.com/senapathi402-star)

## 👨‍💻 Author
**Senapathi Krishna Sai**
Data Analyst | SQL | Python | Tableau | Power BI | Excel

## 🗂️ Related Projects
- [HR Analytics — Excel Dashboard](https://github.com/senapathi402-star/hr-analytics-dashboard)
- [HR Analytics — Google Sheets & Apps Script](https://github.com/senapathi402-star/hr-analytics-google-sheets)
