# Tristen Campayne
**Product Analytics | Experimentation, Causal Inference & Scalable SQL**

I build experiment pipelines and causal analyses that help teams decide what to launch, who to target, and when measured lift is actually profitable.

UCF Business Administration: Marketing student graduating December 2026. Incoming analytics internships with **Walmart Merchandising Analytics** and **Universal Destinations & Experiences Audience Science**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/tristen-campayne/)
[![Tableau](https://img.shields.io/badge/Tableau-Public-orange?logo=tableau)](https://public.tableau.com/app/profile/tristen.campayne)
[![Email](https://img.shields.io/badge/Email-red?logo=gmail)](mailto:tcampayne@gmail.com)

---

## About

I'm focused on product analytics roles where experimentation, causal inference, and SQL-backed decision systems matter. My work centers on A/B testing, incrementality measurement, heterogeneous treatment effects, and reproducible analytics pipelines.

Current focus areas:
- Experiment design and causal measurement
- SQL pipelines for experiment-ready datasets
- Revenue, basket size, AOV, and customer behavior analysis
- Translating statistical results into launch, targeting, and pricing recommendations

---

## Featured Work

### A/B Promotion Incrementality Analysis
**[View Project Repo](https://github.com/tcampayne/targeted-promotion-incrementality-experiment)**

Designed and analyzed a randomized promotion experiment to determine whether a 10% discount created incremental revenue or subsidized purchases users would have made anyway.

**Decision outcome:** The promotion generated gross lift but was not profitable under the simplified cost model, leading to a recommendation against blanket rollout and toward targeted retesting.

**Impact:**
- Measured **+$28.50 incremental revenue per user** over 6 weeks, 95% CI: [$23.90, $33.11]
- Estimated **+8.2% simulated gross revenue lift** across **61.9K users**
- Projected **$1.7M gross revenue lift before discount costs**
- Found estimated **net impact of -$9.29 per user** under the simplified cost model
- Used causal forest HTE analysis to identify segments where targeted discounting may outperform broad rollout

**Approach:**
- Designed a randomized experiment across ~61.9K users
- Built an end-to-end SQL pipeline from staging to core tables to experiment-ready marts
- Validated treatment/control balance and diagnosed pre-treatment trends through event-study analysis
- Connected statistical results to a clear business recommendation: avoid blanket rollout; test lower discount levels or targeted offers

**Methods:**
- Difference-in-Differences with pre-trend diagnostics
- Two-way fixed effects regression with user and time fixed effects
- Cluster-robust standard errors
- Exploratory heterogeneous treatment effects via causal forests

**Tools:** SQL | Python | Pandas | EconML | Streamlit

---

### FP&A Profitability & Competitive Trends Dashboard
**[View Repo](https://github.com/tcampayne/fpa-profitability-market-trends-dashboard)**

Built a SQL-backed Tableau dashboard to analyze profitability, investment efficiency, and competitive trends across 500+ public companies and 20 years of financial data.

- Modeled company-level profitability and growth trends using reusable SQL marts
- Created executive views for KPI drill-downs, industry benchmarking, and trend diagnosis
- Applied OLS regression to estimate relationships between R&D, advertising spend, and revenue growth
- Reduced recurring KPI refresh time by 40%

**Tools:** SQL | Tableau | Excel

---

## Skills

| Area | Tools & Methods |
|---|---|
| Experimentation | A/B Testing, Difference-in-Differences, Event Studies, TWFE, Causal Forests |
| Analytics Engineering | SQL Pipelines, Experiment Marts, Reproducible Analysis Workflows |
| Languages | SQL (PostgreSQL), Python, R |
| Libraries | Pandas, EconML, scikit-learn, Streamlit |
| BI & Visualization | Tableau, Power BI |
| Platforms | Snowflake, Databricks |

---

## Connect

- [LinkedIn](https://www.linkedin.com/in/tristen-campayne/)
- [Tableau Public](https://public.tableau.com/app/profile/tristen.campayne)
- [GitHub](https://github.com/tcampayne/)
- [tcampayne@gmail.com](mailto:tcampayne@gmail.com)
