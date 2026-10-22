### Nicolás Duarte

I build people analytics on SQL, Python and dbt, and reconcile every number against the source before anyone sees it.

**Projects** (all data synthetic)

- **[pa-warehouse](https://github.com/nicolasduarte-data/pa-warehouse)** — People analytics warehouse on BigQuery + dbt + Looker Studio, also built on Snowflake: 26 of 26 aggregate columns match across the two warehouses. SCD2 employee snapshot, a contract-enforced ML feature view, and a join fanout caught inflating headcount 2.33× before it shipped. [Live dashboard](https://datastudio.google.com/reporting/c38e267f-ec30-478b-9d08-4878f2dad4b3)
- **[workforce-analytics](https://github.com/nicolasduarte-data/workforce-analytics)** — 419 employees and 2,728 HR tickets of deliberately messy data, cleaned in Python + DuckDB and analyzed in SQL: three findings, each with its number. [Tableau Public dashboard](https://public.tableau.com/app/profile/nicol.s.duarte/viz/Book1_17785524067300/Dashboard1)
- **[hr-ops-agent](https://github.com/nicolasduarte-data/hr-ops-agent)** — Claude agent on native tool-use that routes HR operations questions across four tools, with BGE-M3 hybrid retrieval: 100% routing on 82 scored queries, recall@3 0.97 / 0.94, 0.0% attack success across 50 red-team probes.

**Background:** a global Fortune 500 HR IT function. About 75 data issues a week across SuccessFactors and SAP, an HR IT audit service built from zero (500+ audits, 10+ countries), and a 22,000-employee payroll data load with zero errors.

[LinkedIn](https://linkedin.com/in/nicolasduarte-ferreira)
