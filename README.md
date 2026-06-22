# 📊 End-to-End Sales Analytics Dashboard

> A fully interactive Excel workbook featuring VBA automation, Pivot Tables, and dynamic data visualizations for tracking 136 sales executives across 8 regions in India.

---

## 📸 Dashboard Preview

![Sales Analytics Dashboard](https://img.shields.io/badge/Excel-VBA%20%7C%20Pivot%20Tables%20%7C%20Charts-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

> **Screenshot:** The dashboard displays real-time KPI cards, ranked bar charts for top performers and laggards, a region-wise breakdown, and a filterable raw data table — all driven by Pivot Tables and VBA macros.

---

## 🚀 Features

- **Interactive Dashboard Sheet** — Dynamically linked charts and KPI cards that update automatically when the raw data changes
- **Top Performers View** — Ranked bar chart showing top 5 Sales Executives by total sales (Target: 500 units/exec)
- **Laggard Tracker** — Highlights executives furthest from target, enabling quick managerial intervention
- **Target Hit % Analysis** — Percentage-based performance view across all 136 executives
- **Away From Target % View** — Gap analysis to identify coaching opportunities
- **VBA Automation** — Macros to refresh Pivot Tables, auto-sort rankings, and reset filters with a single click
- **Pivot Tables** — Aggregated summaries by region, executive name, and performance tier
- **Raw Data Sheet** — Structured daily sales data (Day 1–5) for 136 employees with auto-calculated totals

---

## 📁 File Structure

```
End-to-End_Sales_Analytics_Dashboard.xlsm
│
├── DASHBOARD          ← Interactive charts, KPI cards, ranked views
└── RAW DATA           ← Source data: 136 rows × 12 columns
```

---

## 📊 Dataset Overview

| Column | Description |
|---|---|
| `Emp Code` | Unique employee identifier (e.g., Mum-TCL001) |
| `Sales Executive` | Full name of the sales rep |
| `Region` | One of 8 Indian cities (Mumbai, Delhi, Nagpur, Chennai, Pune, Patna, Ranchi, Surat) |
| `Day1 – Day5` | Daily sales units for a 5-day cycle |
| `Total Sales` | Sum of Day1–Day5 |
| `Target` | Fixed target of 500 units per executive |
| `Target Hit %` | `Total Sales / Target` |
| `Away From Target %` | `1 - Target Hit %` |

**Dataset stats:**
- 136 Sales Executives
- 8 Regions
- Target per executive: 500 units
- Top performer: Jagdish Chandra — 389 units (77.8% of target)
- Lowest performer: Omprakash O — 143 units (28.6% of target)

---

## 🛠️ Tech Stack

| Tool | Usage |
|---|---|
| Microsoft Excel (.xlsm) | Core platform |
| VBA (Visual Basic for Applications) | Automation, macros, interactivity |
| Pivot Tables | Data aggregation and summary |
| Excel Charts | Bar charts, column charts, data visualization |
| Conditional Formatting | Color-coded performance indicators |
| XLOOKUP / SUMIF | Dashboard formula logic |

---

## 📂 How to Use

1. **Download** the `.xlsm` file from this repository
2. **Open** in Microsoft Excel (2016 or later recommended)
3. **Enable Macros** when prompted (required for VBA features to work)
4. Navigate to the **DASHBOARD** sheet to view the interactive analytics
5. To update data, edit values in the **RAW DATA** sheet — the dashboard refreshes automatically via Pivot Table connections

---

## 📈 Dashboard Sections

### 1. KPI Summary Cards
Displays high-level metrics at a glance:
- Total number of sales executives
- Average sales per executive
- Top performer name and score
- Number of active regions

### 2. Top Performers Chart
Ranked bar chart of the 5 best-performing executives by total sales volume, with percentage target achievement shown alongside.

### 3. Laggards / Away From Target Chart
Inverted ranking showing which executives are furthest from their 500-unit target — useful for coaching and performance management.

### 4. Target Hit % vs. Away From Target %
Side-by-side comparison allowing managers to see both the achievement and the gap for each executive in a single view.

---

## 🧑‍💼 About the Project

This project was built as part of an end-to-end data analytics portfolio to demonstrate proficiency in:

- Structuring and cleaning raw sales data in Excel
- Building automated, formula-driven dashboards
- Using Pivot Tables for fast, dynamic aggregation
- Writing VBA macros to enhance usability
- Creating professional data visualizations without external tools

---

## 📬 Connect

**GitHub:**(https://github.com/shubhamsonawane964-design)  
**LinkedIn:**https://www.linkedin.com/in/shubham-sonawane-186a00315?utm_source=share_via&utm_content=profile&utm_medium=member_android

