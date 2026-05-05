# Forecast & Pipeline Quality Dashboard

https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=000000
https://img.shields.io/badge/Power%20Automate-0066FF?style=for-the-badge&logo=powerautomate&logoColor=FFFFFF
https://img.shields.io/badge/DAX-2B2B2B?style=for-the-badge&logoColor=FFFFFF
https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=FFFFFF
https://img.shields.io/badge/Data%20Warehouse-374151?style=for-the-badge&logoColor=FFFFFF
https://img.shields.io/badge/Sales%20Operations-6B7280?style=for-the-badge&logoColor=FFFFFF

forecastpreview.gif

## Project Overview
This project focuses on improving sales pipeline quality, forecast reliability, and operational accountability through analytics and automation.

The dashboard was built based on a deep understanding of Sales Operations processes and common challenges related to pipeline hygiene, qualification, and forecast accuracy.

In addition to Power BI analytics, the solution integrates Power Automate to distribute personalized, actionable insights directly to Account Managers on a recurring basis.

---

## Business Problem
The sales pipeline presented multiple issues that negatively impacted forecast accuracy and operational efficiency:
- Inactive opportunities with no recent activity
- Opportunities aging beyond healthy sales cycles
- Poor qualification in early pipeline stages
- Forecast category misalignment (Pipeline vs Best Case / Commit)
- Unrealistic or outdated close dates

These issues reduced trust in the pipeline and increased manual intervention by Sales Operations teams.

---

## Solution Approach
The solution consolidates pipeline data from multiple enterprise systems into a single analytical model and introduces pipeline quality KPIs designed to surface risks early.

The dashboard enables structured, data-driven conversations between Sales Operations and Account Managers, reinforcing accountability and continuous pipeline maintenance.

---

## KPI and Analytical Scope

### Pipeline Overview
- Total pipeline value (active and inactive)
- Number of opportunities
- Average deal size

### Pipeline Quality Indicators
- Inactive opportunities requiring follow-up
- Opportunities aging beyond 90 days  
  Reaching 90 days does not necessarily mean recreating the opportunity. Some deals require longer cycles; the critical factor is maintaining up-to-date activities.
- Opportunities in early stages requiring better qualification
- Opportunities flagged for forecast adjustment due to misclassification or close-date misalignment

### Revenue Quality Analysis
- MRR from inactive opportunities
- MRR from opportunities aging beyond 90 days
- MRR requiring qualification
- MRR needing forecast adjustment

### New Logo Pipeline
- New logo pipeline MRR
- Number of new logo opportunities
- Revenue distribution for new customers

### Product Mix
- Pipeline breakdown by product
- Visibility into concentration and portfolio balance

---

## Forecast View
The dashboard includes forward-looking views to support planning and leadership alignment:
- Sales Commit MRR for the current month and next five months
- Expected Churn Commit MRR for the same period

---

## Pipeline Growth Analysis
- Weekly MRR added to the pipeline
- Number of opportunities created per week
- Volume and velocity trend analysis

---

## Data Architecture and Sources
This project was built using an enterprise-grade data architecture integrating:
- Centralized Data Warehouse
- SharePoint-hosted operational and sensitive datasets
- Direct connection to the official CRM system

All data is modeled using a star schema, ensuring performance, consistency, and scalability.

---

## Refresh and Automation
- Automatic daily data refresh
- Continuous operational availability
- Power Automate workflows triggered on a recurring schedule
- Individualized distribution of insights to each Account Manager

Automation significantly reduces manual reporting effort and increases ownership of pipeline data.

---

## Power Automate Integration

salespipelinepowerautomate.jpg

The solution includes automated flows that:
- Generate personalized pipeline summaries
- Deliver formatted insights to the correct recipients
- Reinforce follow-up and pipeline ownership

---

## Automated Email Delivery

outlookweeklyforecast.jpg

Account Managers receive structured, role-specific emails containing their pipeline quality indicators, enabling faster action and data-driven discussions.

---

## Data Volume and PBIX Availability
Due to large data volumes, multiple enterprise data sources, and corporate governance constraints, PBIX files are not shared in this repository.

Instead, the project is demonstrated through:
- Animated GIFs showing dashboard interaction
- Visual walkthroughs of Power Automate flows
- Examples of automated email delivery

This approach reflects realistic corporate BI environments without compromising data privacy or performance.

---

## Data Privacy
- All data shown is public, simulated, or fully anonymized
- Customer and segment names are replaced with generic identifiers
- No real company, customer, or confidential information is disclosed
- This project is not connected to any production environment

---

## Key Outcomes
- Improved pipeline hygiene and data reliability
- Faster identification of forecast risks
- More effective Sales Ops and Account Manager 1:1 discussions
- Reduced manual effort through automation
- Increased accountability across the sales organization
