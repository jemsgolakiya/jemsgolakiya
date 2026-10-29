<div align="center">

# Hi, I'm Jemish Golakiya

### Data Analyst · Marketing Analytics, Power BI & Business Intelligence

I turn messy marketing and operational data into numbers teams trust, and reporting they actually use.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-golakiya--jemish-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/golakiya-jemish)
![Location](https://img.shields.io/badge/Frankfurt%20am%20Main-Germany-1f2937?style=for-the-badge&logo=googlemaps&logoColor=white)
![Status](https://img.shields.io/badge/Open%20to-full--time%20roles-16a34a?style=for-the-badge)

</div>

---

## About me

I own measurement end to end. I define what success looks like, make sure the tracking behind it is actually correct, and turn the results into decisions.

For two years I was a **Data Analyst in Digital Marketing Analytics** at an international B2B marketing agency (Mannheim · Strasbourg · Shanghai). I rebuilt unreliable event tracking until teams trusted their conversion data. I merged four ad and analytics sources into one model and replaced manual reporting with automated SQL and Python pipelines.

On the BI side, I build governed self-service setups: clean SQL models, Power BI semantic models with solid DAX, and the governance and coaching that keep self-service from turning into chaos.

## Impact highlights

- **Fixed conversion measurement end to end.** I audited the GA4 and Matomo event schema against the real customer journey and rebuilt the tracking plan. A KPI stakeholders used to question became a basis for budget decisions.
- **One data model for four sources.** I blended Google Ads, Meta, LinkedIn and GA4 with shared definitions of spend, conversion and attribution window. That removed **10+ hours** of manual reconciliation every week.
- **40% less weekly reporting work.** Automated Python and SQL ETL pipelines replaced Excel workflows, so decisions across **50+ active campaigns** run on current data.
- **Data quality caught before it reaches a report.** pandas-based anomaly detection runs over campaign datasets with **100,000+ rows**.
- **Self-service BI.** Looker Studio and Power BI models let **10+ stakeholders** answer routine questions without waiting for an analyst.

## Featured projects

### [Cross-Channel Marketing Analytics Pipeline](https://github.com/jemsgolakiya/marketing-analytics-pipeline)

Google Ads, Meta, LinkedIn and GA4 blended into one SQL model, with quality gates that run before anything reaches a report.

- Automatically detects a **GA4 tracking break** (sessions normal, sign-ups gone) and a **spend anomaly** (robust MAD z-scores).
- Compares **4 attribution models** in SQL. LinkedIn's ROAS is 0.68× on last click but 4.55× on first click.
- Reconciles platform-reported conversions against GA4: Meta over-reports by 70%.

`Python` `SQL` `DuckDB` `pandas` `GitHub Actions` · synthetic data, real problems

[![Marketing analytics dashboard](https://raw.githubusercontent.com/jemsgolakiya/marketing-analytics-pipeline/main/docs/img/dashboard_overview.png)](https://github.com/jemsgolakiya/marketing-analytics-pipeline)

### [ATLAS: Analytics & Trusted Layer for Asset Services](https://github.com/jemsgolakiya/atlas-bi-platform)

A governed self-service BI platform for a fictional industrial maintenance company with 12 sites, 943 assets and 33k work orders.

- Snowflake RAW → SILVER → GOLD layers with SCD2 history, masking and row-access policies, and automated data-quality tests. A Databricks version is included.
- A certified Power BI model: star schema, 38 KPIs defined once as code, RLS/OLS and a time-intelligence calculation group.
- An audit-proof Power Apps CRUD app on Azure SQL temporal tables with four-eyes approval.
- Governance and CI/CD: DEV → TEST → PROD lifecycle, Best Practice Analyzer quality gates, and KPI reconciliation against an independent reference.

`Snowflake` `Databricks` `Power BI` `DAX` `Power Apps` `Azure SQL` `GitHub Actions`

### [RenovAlte: Smart Renovation & Financing Assistant for Germany](https://github.com/jemsgolakiya/Smart-renovation-Germany)

An AI assistant that turns a German home renovation into one guided workspace, covering KfW funding, GEG/EnEV standards, state permits and contractor offers.

- Two RAG pipelines over KfW programmes, GEG/EnEV standards and state building rules. Every recommendation traces back to a citable source.
- Automated contractor sourcing: Google Places matching, requests sent through Gmail OAuth 2.0, and PDF quote parsing with price and risk comparison.
- Django 5.2 / DRF backend with 72 REST endpoints, plus a React 19 + TypeScript frontend.

`Django` `React` `TypeScript` `ChromaDB` `Qdrant` `Gemini / Vertex AI`

## Tech stack

**Data and analytics**

![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**BI and visualisation**

![Power BI](https://img.shields.io/badge/Power%20BI%20%C2%B7%20DAX-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Power Apps](https://img.shields.io/badge/Power%20Apps-742774?style=flat-square&logo=powerapps&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel%20%C2%B7%20Power%20Query-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

**Measurement and marketing platforms**

![GA4](https://img.shields.io/badge/GA4-E37400?style=flat-square&logo=googleanalytics&logoColor=white)
![Matomo](https://img.shields.io/badge/Matomo-3152A0?style=flat-square&logo=matomo&logoColor=white)
![Search Console](https://img.shields.io/badge/Search%20Console-458CF5?style=flat-square&logo=googlesearchconsole&logoColor=white)
![Google Ads](https://img.shields.io/badge/Google%20Ads-4285F4?style=flat-square&logo=googleads&logoColor=white)
![Meta Ads](https://img.shields.io/badge/Meta%20Ads-0467DF?style=flat-square&logo=meta&logoColor=white)
![LinkedIn Ads](https://img.shields.io/badge/LinkedIn%20Ads-0A66C2?style=flat-square&logo=linkedin&logoColor=white)
![SEMrush](https://img.shields.io/badge/SEMrush-FF642D?style=flat-square&logo=semrush&logoColor=white)

**AI and engineering**

![Vertex AI](https://img.shields.io/badge/Gemini%20%C2%B7%20Vertex%20AI-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-ChromaDB%20%C2%B7%20Qdrant-DC244C?style=flat-square)
![Django](https://img.shields.io/badge/Django%20%2F%20DRF-092E20?style=flat-square&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Education and certifications

- **B.E. Information Technology**, Gujarat Technological University, India. First Class with Distinction (CGPA 8.87 / 10)
- **Certifications:** Power BI · Tableau · Data Analytics with Pandas · Data Visualisation in Python · Data Science with R (GUVI) · JavaScript (Udemy)

## Languages

English (fluent) · German (B1) · Hindi (fluent) · Gujarati (native)

---

<div align="center">

**Looking for a data analyst who makes your numbers trustworthy?** Let's talk on [LinkedIn](https://www.linkedin.com/in/golakiya-jemish).

</div>
