# Tristen Campayne
**Product Analytics Candidate - Experimentation, Causal Inference & SQL**

I build experiment pipelines and causal analyses that turn ambiguous product questions into defensible revenue decisions.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/tristen-campayne/)
[![Tableau](https://img.shields.io/badge/Tableau-Public-orange?logo=tableau)](https://public.tableau.com/app/profile/tristen.campayne)
[![Email](https://img.shields.io/badge/Email-red?logo=gmail)](mailto:tcampayne@gmail.com)

---

## About

I'm a UCF Business Administration student focused on product analytics, experimentation, and causal inference. I design randomized experiments, build reproducible SQL pipelines, and translate statistical results into product and revenue decisions.

Incoming analytics internships: **Walmart Merchandising Analytics** (Summer 2026) and **Universal Destinations & Experiences - Audience Science** (Fall 2026), focused on customer behavior, A/B testing, personalization, and Snowflake/Databricks workflows.

---

## Featured Work

### A/B Promotion Incrementality Analysis
**[View Project Repo](https://github.com/tcampayne/targeted-promotion-incrementality-experiment)**

**Business question:** Does a 10% discount for high-LTV users drive incremental revenue, or mostly subsidize behavior that would have happened anyway?

**Impact:**
- Measured **+$28.50 incremental revenue per user** over 6 weeks, 95% CI: [$23.90, $33.11]
- Estimated **+8.2% simulated revenue lift** across **61.9K users**
- Projected **$1.7M gross revenue lift** before discount costs
- Found the blanket 10% discount was **not profitable under the simplified cost model**: estimated net impact of **-$9.29 per user**
- Used heterogeneous treatment effect analysis to identify where targeted discounting may outperform broad rollout

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

- Built a SQL analytics mart spanning 20 years of data across 500+ public companies
- Created an executive Tableau dashboard for profitability trends, KPI drill-downs, and cross-industry benchmarking
- Applied OLS regression to estimate the relationship between R&D investment, advertising spend, and revenue growth
- Improved forecast accuracy by 30% and reduced KPI refresh time by 40%

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
