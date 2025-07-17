# 💸 Automated Financial Intelligence Pipeline

**An end-to-end data engineering and analytics project that transforms raw financial statements into CFO-grade insights using modern data tools.**

---

## 🚀 Project Overview

This project simulates how a modern finance team automates the collection, transformation, and analysis of financial data. It builds a full pipeline that:

- Ingests public financial statement data from APIs (e.g. Financial Modeling Prep)
- Cleans and models it using dbt
- Stores it in a cloud data warehouse (Supabase, BigQuery, or DuckDB)
- Surfaces KPIs in an interactive dashboard (Streamlit or Power BI)

🎯 **Target Use Case:** Startup CFO, FP&A Analyst, VC Analyst, or Financial Controller

---

## 📊 Example Insights

- Revenue Growth (YoY, QoQ)
- Gross and EBITDA Margin Trends
- Free Cash Flow (FCF) and Burn Rate
- Liquidity & Efficiency Ratios (ROE, ROIC, D/E)
- Peer Comparisons and Common-Size Analysis

---

## 🧰 Tech Stack

| Layer           | Tools Used                                              |
|----------------|----------------------------------------------------------|
| Data Ingestion  | Python, Financial Modeling Prep API, Airflow or Prefect |
| Transformation  | dbt (ELT-style models)                                  |
| Storage         | Supabase / PostgreSQL / BigQuery / DuckDB               |
| Visualization   | Streamlit / Power BI                                    |
| Automation & Tests | Airflow DAGs, dbt tests, Great Expectations (optional) |

---

## 📁 Project Structure

