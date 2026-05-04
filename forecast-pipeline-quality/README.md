# Forecast & Pipeline Quality Dashboard

## Project Overview
This project focuses on improving **sales pipeline quality, forecast reliability, and operational accountability** through analytics and automation.

The dashboard was built based on a deep understanding of Sales Operations processes and common pipeline management challenges.  
Its goal is not only to monitor pipeline health, but to actively drive better behaviors across the sales organization.

In addition to Power BI visualizations, this project integrates **Power Automate** to distribute personalized, actionable insights directly to Account Managers on a recurring basis.

---

## Business Problem
The sales pipeline presented several issues that negatively impacted forecast accuracy and operational efficiency:
- Inactive opportunities with no recent activity
- Opportunities aging beyond healthy sales cycles
- Poorly qualified deals in early pipeline stages
- Forecast category misalignment (Pipeline vs Best Case / Commit)
- Unrealistic or outdated close dates

These issues increased manual effort for Sales Operations and reduced trust in forecast numbers.

---

## Solution Approach
The dashboard consolidates pipeline data from multiple enterprise systems into a single, trusted analytical layer.  
It introduces **pipeline quality KPIs** designed to surface risks early and support data-driven conversations between Sales Operations and Account Managers.

The solution combines:
- Operational analytics
- Executive-level visibility
- Automated communication
- Behavioral reinforcement through regular review cycles

---

## KPI and Analytical Scope

### Pipeline Overview
- Total Pipeline value (active and inactive)
- Total number of opportunities
- Average deal size

### Pipeline Quality Indicators
- Inactive opportunities requiring follow-up
- Opportunities aging beyond 90 days  
  > Reaching 90 days does not necessarily mean the deal should be recreated.  
  > Some negotiations naturally take longer; the key factor is keeping activities updated.
- Opportunities in early stages requiring further qualification
- Opportunities flagged for forecast adjustment due to misclassification or close date issues

### Revenue Quality Analysis
- MRR from inactive opportunities
- MRR associated with aged opportunities
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
- Expected Churn Commit MRR for the same horizon

---

## Pipeline Growth Analysis
- Weekly MRR added to the pipeline
- Number of opportunities created per week
- Trend visibility to support volume and velocity analysis

---

## Data Architecture and Sources
This project was built using an enterprise-grade data architecture, integrating:
- A centralized Data Warehouse
- SharePoint-hosted operational and sensitive datasets
- Direct connection to the official CRM system

All data is modeled using a **star schema**, with clear separation between fact tables and dimensions, ensuring:
- Performance
- Consistency of metrics
- Scalability of the data model

---

## Refresh and Automation
- Automatic daily data refresh
- Always-on operational availability
- Power Automate workflows triggered on a recurring schedule
- Individualized distribution of insights to each Account Manager

Automation reduces manual reporting effort and increases ownership of pipeline data.

---

## Power Automate Integration
The solution includes automated workflows that:
- Generate personalized pipeline summaries
- Send formatted emails to the appropriate recipients
- Reinforce accountability and follow-up actions

Animated previews included in this repository demonstrate:
- Dashboard interaction
- Power Automate flow execution
- Final email format delivered to end users

---

## Data Volume and PBIX Availability
Due to:
- Large data volumes
- Multiple enterprise data sources
- Corporate security and governance constraints

PBIX files are not shared in this repository.

Instead, the project is demonstrated through:
- Animated GIFs of the dashboard in operation
- Visual walkthroughs of Power Automate workflows
- Examples of automated email delivery

This approach ensures a realistic representation of corporate BI scenarios without compromising performance or data privacy.

---

## Data Privacy
- All data shown is public, simulated, or fully anonymized
- Customer and segment names are replaced with generic identifiers
- No real company, customer, or confidential data is exposed
- This project is not connected to any production environment

---

## Key Outcomes
- Improved pipeline hygiene and data reliability
- Faster identification of forecast risks
- More effective Sales Ops and Account Manager 1:1 discussions
- Reduced manual effort through automation
- Increased accountability across the sales organization
