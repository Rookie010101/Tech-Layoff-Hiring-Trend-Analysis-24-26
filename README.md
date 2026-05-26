# 📊 Layoff & Hiring Trend Dashboard

An interactive **Excel dashboard** analyzing tech industry layoffs, hiring trends, and AI-driven workforce disruption across 12,000 records spanning 2024–2026.

---

![Layoff Hiring Trend Dashboard](dashboard.png)

---

## 🔍 Overview

This project explores the evolving landscape of tech workforce changes — from mass layoffs driven by AI automation to emerging hiring patterns across industries and geographies. The dashboard surfaces key signals for HR leaders, data analysts, and tech professionals tracking the future of work.

## 📁 Dataset

**File:** `tech_layoffs_hiring_trends_elite_v2.csv`

| Attribute | Detail |
|-----------|--------|
| **Rows** | 12,000 records |
| **Columns** | 23 features |
| **Years Covered** | 2024, 2025, 2026 |
| **Industries** | AI, Cloud, Cybersecurity, E-Commerce, FinTech, Gaming, Social Media |
| **Company Sizes** | Startup, Mid-size, Enterprise, Big Tech |
| **Countries** | 6 (USA, Canada, UK, Germany, India, Singapore) |

### Key Columns

| Column | Description |
|--------|-------------|
| `company_name` | Name of the company |
| `industry` | Tech sector |
| `country` | Country of operation |
| `company_size` | Size tier of the company |
| `layoffs_count` | Number of employees laid off |
| `reason_for_layoffs` | AI Automation, Cost Cutting, Restructuring, etc. |
| `ai_replacement_risk` | Risk score for AI job displacement |
| `open_roles` | Number of open positions |
| `hiring_trend` | Upward / Downward / Stable |
| `remote_jobs_percentage` | % of roles offered remotely |
| `salary_budget_change` | YoY change in salary budgets |
| `employee_sentiment` | Employee satisfaction score (0–10) |
| `job_security_score` | Perceived job security (0–10) |
| `market_condition` | Bull Market / Bear Market / Recession |

---

## 📈 Dashboard Highlights

| Metric | Value |
|--------|-------|
| 🔴 Total Layoffs | **60,114,865** |
| 🟢 Total Open Positions | **34,612,740** |
| ⚠️ Major Layoff Reason | **AI Automation** |
| 😐 Avg Employee Sentiment | **6.5 / 10** |

### Visuals Included

- **KPI Cards** — Total layoffs, open positions, layoff reason, and sentiment at a glance
- **AI Replacement Risk Radar** — Sector-by-sector AI disruption risk profile
- **Revenue Growth Donut Chart** — Geographic revenue contribution breakdown
- **Salary Budget Change Bar Chart** — Budget shifts across company size tiers
- **Layoffs Per Year Line Chart** — Trend lines by industry (2024–2026)
- **Industry Slicer** — Filter all visuals dynamically by sector

---

## 🛠️ Tools Used

- **Microsoft Excel** — Data modeling, pivot tables, and dashboard design
- **Power Query** — Data cleaning and transformation
- **Charts & Slicers** — Interactive filtering and visualization

---

## 🚀 How to Use

1. Clone or download this repository
2. Open the `.xlsx` file in **Microsoft Excel 2016 or later**
3. Navigate to the **Dashboard** worksheet for the interactive view
4. Use the **Industry slicer** on the left panel to filter by sector
5. Explore individual worksheets for raw data and pivot analysis

> ⚠️ Enable macros if prompted, and ensure your Excel version supports slicers and radar charts.

---

## 💡 Key Insights

- **AI Automation** is the #1 driver of layoffs across all sectors, overtaking traditional cost-cutting
- **Big Tech** commands the highest salary budget growth (+6.15%), while Startups lag at +5.56%
- **Cybersecurity and Cloud** show the lowest AI replacement risk, making them relatively safer sectors
- **India and Singapore** are gaining revenue share, reflecting shifting tech investment eastward
- Despite high layoffs, **34.6M open roles** indicate a significant skills-gap dynamic rather than pure job loss

---

## 📂 Repository Structure

```
📦 layoff-hiring-trend-dashboard
 ┣ 📊 tech_layoffs_hiring_trends_elite_v2.csv   ← Raw dataset
 ┣ 📊 Layoff_Hiring_Dashboard.xlsx              ← Excel dashboard file
 ┣ 🖼️ dashboard.png                             ← Dashboard screenshot
 ┗ 📄 README.md                                 ← You are here
```

---

## 🙋 About

Built as a data analytics portfolio project to demonstrate skills in data storytelling, dashboard design, and workforce trend analysis using real-world inspired tech layoff data.

Feel free to ⭐ star this repo if you found it useful, or open an issue for suggestions!
