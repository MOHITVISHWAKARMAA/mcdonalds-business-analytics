# McDonald's Business Analytics — FY 2024–2025

End-to-end Business Analytics & Business Intelligence portfolio case study delivered from a Business Analyst / BI Consultant perspective.

Power BI | SQL | DAX | Excel | Business Analysis

[Explore the Project](#%F0%9F%94%8E-explore-the-project) • [Executive Snapshot](#executive-snapshot) • [Dashboard Suite](#dashboard-suite) • [Project Files](#project-files)

---

## Executive Snapshot

This is a portfolio/academic analytics case study and does not represent proprietary McDonald's corporate data.

| KPI | Result |
|---|---:|
| Revenue | ~$9.53M |
| Orders | ~500K |
| Customers | ~95K |
| Stores | 250 |
| Products | 120 |
| Promotions | 80 |
| Repeat Customer Rate | 84.3% |
| Loyalty Members | ~55K |
| Avg Orders / Customer | 5.26 |
| CSAT | ~79.8 |
| Avg Drive-Thru Time | ~259 sec |

---

## Business Problem

How can McDonald's (sample dataset) improve revenue and operational efficiency by prioritizing high-value customers, optimizing product assortment, and measuring promotion effectiveness across stores?

## Business Objectives

- Quantify revenue drivers and high-value customer segments
- Identify underperforming products and stores
- Measure promotion effectiveness and loyalty program impact
- Provide executive reporting and actionable recommendations

## Analytical Approach

A mixed-method BI approach using SQL-based data validation and transformation, a semantic DAX layer for core KPIs, and Power BI dashboards for interactive executive and operational reporting. Validation and QA were performed against dataset row counts, referential integrity checks and sample DAX metrics.

---

## Dashboard Suite

The repository contains exported dashboard previews (PNG) and links to full Power BI artifacts. Where PNG previews are available in `05_Dashboard_Preview/` they will render below. If a preview image is not present in the repo the README links to the external Drive preview.

**Preferred story order:** Summary → Executive → Customer → Product → Store → Promotion

**Executive Business Summary**

> If `05_Dashboard_Preview/Summary.png` exists the image will render here. Otherwise open Dashboard Previews (link in Project Files).

![Executive Summary](<img width="1322" height="764" alt="Summary" src="https://github.com/user-attachments/assets/ff327f08-add4-44b7-a95e-b301e9416ba2" />

)


---

## �� Explore the Project

| Area | What it contains |
|---|---|
| Project Documentation | Business Analysis deliverables, requirements, artifacts (BA-001 … BA-018) |
| Data | Cleaned & analytical datasets (CSV), data dictionary |
| SQL | Analytical SQL scripts and validation queries |
| Power BI | PBIX files and architecture notes |
| Dashboard Previews | PNG exports of dashboard pages |
| Business Diagrams | Editable diagrams (PPTX / Visio) |
| Presentation | Consulting-style PPTX + PDF |
| Project Management | Tracker, milestones, status |
| QA | Data & dashboard QA artifacts |
| Reports | Executive & operational reports |

---

## 📂 Project Files

| Area | Description | Access |
|---|---|---|
| Project Documentation | BA-001 to BA-018 | [Open Documentation](01_Project_Documentation) |
| Dataset | Analytical datasets | [Open Dataset](02_Data) |
| SQL | SQL scripts & validation | [Open SQL](03_SQL) |
| Power BI | PBIX dashboard and notes | [Open Power BI](04_Power_BI) |
| Dashboard Previews | PNG dashboard exports (visuals) | [View Dashboards](05_Dashboard_Preview) |
| Business Diagrams | Editable diagrams | [Open Diagrams](06_Business_Diagram) |
| Presentation | Consulting presentation (PPTX + PDF) | [Open Presentation](07_Presentation) |
| Project Management | Tracker & project controls | [Open Project Management](08_Project_Management) |
| QA | Final QA documentation | [Open QA](09_QA) |
| Reports | Executive reports | [Open Reports](10_Reports) |

> Important: Please ensure Google Drive folders are set to **Anyone with the link → Viewer** so recruiters can access files without requesting permission.

---

## Data Landscape

Source: anonymized/representative transactional dataset included in the project dataset folder. Data model follows a star-like schema with dimensions for customers, products, stores and a fact table for transactions/orders.

## Tools & Technologies

Power BI, DAX, SQL (Postgres/MySQL-compatible), Excel, Google Drive for large artifacts, GitHub for portfolio hosting.

## QA & Validation

Key QA approaches are documented in `09_QA/README.md`. Validation includes row counts, duplicate checks, referential integrity and reconciliation of summary KPIs between SQL and Power BI.

## Presentation

A consulting-style presentation is available in the `07_Presentation` folder (PPTX + PDF). The presentation summarizes business context, approach, key insights and recommended next steps.

## Author

Mohit Vishwakarma — Business Analyst / BI Consultant

---

