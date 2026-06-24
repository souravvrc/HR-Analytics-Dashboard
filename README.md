# 📊 HR Analytics Dashboard | Power BI Project

An end-to-end data analytics project built on a **real-world HR dataset**. The project involves gathering requirements from an HR stakeholder, transforming raw Excel data, and delivering an interactive Power BI dashboard that provides actionable employee presence insights.

---

## 🎯 Project Overview

This project simulates a real data analyst workflow:

- **Requirement gathering** directly from an HR stakeholder at AtliQ Technologies
- **Data transformation** using Power Query in Power BI
- **DAX measures** to build a dynamic presence/attendance matrix
- **Dashboard design** with interactive visuals for HR decision-making

The goal was to help the HR team monitor employee attendance patterns, work-from-home trends, and sick leave across the organization.

---

## 📁 Project Structure

```
hr-analytics-powerbi/
│
├── data/
│   └── Attendance Sheet 2022-2023_Masked.xlsx   # Raw HR attendance data
│
├── HR Analytics.pbix                             # Power BI dashboard file
└── README.md
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Power BI Desktop | Data modeling, DAX, and dashboard creation |
| Power Query (M Language) | Data gathering and transformation |
| DAX | Creating calculated measures and KPIs |
| Microsoft Excel | Source data format |

---

## 📐 Key Steps

### 1. Understanding HR Requirements
Collaborated with an HR manager to identify key business questions:
- What is the overall employee presence percentage?
- What are the work-from-home (WFH) trends?
- How many sick leaves are employees taking, and when?

### 2. Data Transformation
- Loaded and cleaned the raw Excel attendance sheet using Power Query
- Unpivoted date columns to create a proper tabular format
- Created a reusable transformation template for multiple months of data

### 3. DAX Measures
Key measures created:
- **Presence %** — Percentage of days employees were present
- **WFH %** — Percentage of days worked from home
- **Sick Leave %** — Percentage of sick leave days taken
- Day-of-week breakdowns for all three metrics

### 4. Dashboard
The final dashboard includes:
- KPI cards for Presence %, WFH %, and Sick Leave %
- Area charts showing trends over time
- Day-of-week analysis to identify patterns
- Employee-level breakdown table

---

## 📊 Dashboard Preview

> _Add a screenshot of your Power BI dashboard here_

---

## 📥 Data Source

The input Excel file and output `.pbix` file can be downloaded from:
🔗 [codebasics.io Resources](https://codebasics.io/resources/resume-project-data-analytics)

> **Note:** The dataset has been masked to protect employee privacy.

---

## 🚀 How to Run

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone this repository:
   ```bash
   git clone https://github.com/souravvrc/hr-analytics-dashboard.git
   ```
3. Open `HR Analytics.pbix` in Power BI Desktop
4. If prompted, update the data source path to point to the local Excel file

---

## 💡 Key Insights (Sample)

- Employee presence tends to dip on **Mondays and Fridays**
- **WFH rates** have been gradually increasing over the tracked period
- Sick leave spikes are visible during certain months, helping HR plan coverage

---



---

## 📄 License

This project is for educational purposes. Dataset is used with permission from Codebasics.
