# Tristen Campayne
**Data Analyst — Experimentation & Causal Inference**

Building experiment infrastructure and causal models that turn ambiguous product questions into defensible revenue decisions.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/tristen-campayne/)
[![Tableau](https://img.shields.io/badge/Tableau-Public-orange?logo=tableau)](https://public.tableau.com/app/profile/tristen.campayne)
[![Email](https://img.shields.io/badge/Email-red?logo=gmail)](mailto:tcampayne@gmail.com)

---

## About

I design randomized experiments, build reproducible SQL pipelines, and apply causal inference methods to quantify product and revenue impact.

Incoming: **Walmart Merchandising Analytics** (Summer 2026) · **Universal Destinations & Experiences — Audience Science** (Fall 2026), where I'll be working on A/B testing, personalization models, and Snowflake/Databricks pipelines.

---

## Featured Work

### A/B Promotion Incrementality Analysis
👉 **[View Project Repo](https://github.com/tcampayne/targeted-promotion-incrementality-experiment)**

**Business question:** Does a 10% discount on high-LTV users drive incremental revenue, or just subsidize existing behavior?

**Results:**
- **+$28.50 incremental revenue per user** (6-week cumulative ATE) · 95% CI: [$23.90, $33.10]
- **+8.2% revenue lift** across 61.9K users · **$1.7M projected impact**
- Causal forest HTE revealed top-spend users drove disproportionate lift — suggesting targeted discount tiers would outperform blanket rollout

**Approach:**
- Designed randomized experiment across ~61.9K users
- Built end-to-end SQL pipeline (staging → core → marts) for experiment-ready data
- Validated treatment/control balance and diagnosed pre-treatment trends via event-study analysis

**Causal methods:**
- Difference-in-Differences with parallel trends diagnostics
- Two-way fixed effects regression (user + time FE)
- Cluster-robust standard errors
- Heterogeneous treatment effects via causal forests (EconML)

**Tools:** SQL · Python · Pandas · EconML · Streamlit

---

### FP&A Profitability & Competitive Trends Dashboard
👉 **[View Repo](https://github.com/tcampayne/fpa-profitability-market-trends-dashboard)**

- SQL analytics mart spanning 20 years of data across 500+ public companies
- Executive-level Tableau dashboard with drill-down KPI views and cross-industry benchmarking
- OLS regression quantifying impact of R&D and ad spend on revenue growth
- 30% improvement in forecast accuracy · 40% faster KPI refresh

**Tools:** SQL · Tableau · Excel

---

## Skills

| Area | Tools & Methods |
|---|---|
| Experimentation | A/B Testing, Difference-in-Differences, Event Studies, TWFE, Causal Forests |
| Languages | SQL (PostgreSQL), Python, R |
| Libraries | Pandas, EconML, scikit-learn, Streamlit |
| BI & Visualization | Tableau, Power BI |
| Platforms | Snowflake, Databricks *(Universal internship, Fall 2026)* |

---

## Connect

- [LinkedIn](https://www.linkedin.com/in/tristen-campayne/)
- [Tableau Public](https://public.tableau.com/app/profile/tristen.campayne)
- [GitHub](https://github.com/tcampayne/)
- [tcampayne@gmail.com](mailto:tcampayne@gmail.com)

