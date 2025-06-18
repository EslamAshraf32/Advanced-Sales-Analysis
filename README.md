<!-- ----------------------------------------------------------
 README | Trend Cart — Advanced Sales Analysis (Excel)
 Author: ELSAHM 32 • Last update: 2025‑06‑17
----------------------------------------------------------- -->

<h1 align="center">📊 Trend Cart — Advanced Sales Analysis (Dashboard in Excel) </h1>

<p align="center">
  <img src="https://img.shields.io/badge/Built with-Excel,%20Power Query,%20Power Pivot,%20DAX,%20VBA-00aaff?style=flat-square"/>
  <img src="https://img.shields.io/badge/Refresh‑time-<3s-brightgreen?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square"/>
</p>

> **A recruiter‑ready showcase** of what can be achieved when data engineering, analytics, and design converge inside a single Excel workbook.  
> The project demonstrates the *complete analytics life‑cycle*—from raw data to board‑level insights—**without** relying on external BI platforms.

---

## 🚀 Why This Project Matters
| Value for Business | How I Delivered It |
|--------------------|--------------------|
| **Instant answers** to *when, what, who & why* questions. | Three laser‑focused views: **Time Analysis**, **Detailed Dashboard**, **Urgent Report**. |
| **40 + ready‑to‑use KPIs** (YoY, MoM, margin, segment splits). | Crafted in **DAX** and bound to slicers & drill‑through paths. |
| **Sub‑second interactivity** on a 50 k + row dataset. | Efficient star‑schema modelling + optimised measures + macros. |
| **Zero‑click refresh** for end‑users. | `Ctrl + Shift + R` macro triggers Power Query refresh → pivots update → report exported to PDF. |

Recruiters & hiring managers will instantly see **the breadth of skills** (ETL → Modelling → Analytics → Automation → Storytelling) and **the depth of execution** (code quality, performance tuning, UX polish).

---

## 🗂️ At‑a‑Glance

| 💼 Domain           | ⚙️ Techniques & Tech          | 📈 Deliverables                            |
|---------------------|-------------------------------|--------------------------------------------|
| Retail / e‑commerce | Power Query, Power Pivot, DAX, VBA, Pivot Charts | • Executive dashboard<br>• Automated urgent report (PDF)<br>• Re‑usable data model |
| Time Series & Cohorts| YoY / MoM, time intelligence | • Seasonality & weekday patterns<br>• Quarterly contribution analysis |
| Profitability       | Pareto, top‑N ranking, cost analysis | • Product & customer profitability visuals<br>• 1‑click “unprofitable SKUs” drill‑down |

---

## ✨ Visual Preview
*(Add your own files under `/assets` and adjust the paths.)*

| Time Analysis | Detailed Dashboard | Urgent Report |
|---------------|-------------------|---------------|
| <img src="assets/time‑analysis.png" width="300"/> | <img src="assets/detailed‑dashboard.png" width="300"/> | <img src="assets/urgent‑report.png" width="300"/> |

---

## 🔑 Selected Insights & Targeted Recommendations

| # | Insight (from Dashboard) | Actionable Recommendation |
|---|--------------------------|---------------------------|
| 1 | **Profit margin = 11.8 %** on \$1.94 M revenue. | Negotiate supplier discounts & adjust pricing on low‑elastic SKUs. |
| 2 | **Q4 → 48 %** of yearly profit; spikes in **June & December**. | Align inventory & marketing; launch mid‑year promos each **June**. |
| 3 | **Weekdays → 56.7 %** of profit; **Friday** alone \$62 k. | Schedule flash sales & e‑mail blasts every **Friday**. |
| 4 | **25‑30 age group → 58.3 %** of profit. | Double‑down on social advertising (TikTok/Instagram) & loyalty perks. |
| 5 | **4‑day shipping peak (446 orders)**. | Introduce premium next‑day option and renegotiate SLAs for standard tier. |
| 6 | **87.3 % profit from >\$150 items; 48.5 % SKUs unprofitable.** | Discontinue red‑flag SKUs, upsell high‑value bundles. |

---

## 🛠️ How It Works

1. **Power Query** pulls & cleans raw CSV → splits into dimension & fact tables.  
2. **Power Pivot** hosts a star‑schema (incl. Calendar) enabling DAX time logic.  
3. 40 + **DAX measures** power pivot charts & KPI cards.  
4. **VBA macros** (`modDashboard.bas`) • one‑touch refresh • slicer resets • PDF export.  

> Typical end‑user workflow: *Open → Click “Refresh Dashboard” → Decision‑making.*

---

## 📂 Repository Layout
