# Yashwanth Naidu Kanajam

**Data Analytics · Business Intelligence · Python & SQL**

Data Analyst with 4+ years across healthcare and enterprise analytics. My work spans payer-side claims analysis, cohort definition, data quality and reconciliation, KPI reporting, forecasting, and reporting automation, supporting clinical, operations, finance, and leadership teams.

Alongside that professional experience, I maintain a set of independent case studies that extend it into data quality, public-data analysis, decision support, and analytics software. They are separate from any employer systems or data.

## Core capabilities

- **Analytics & programming:** SQL, Python, PySpark, Advanced Excel.
- **BI & reporting:** Power BI, Tableau, KPI and executive reporting.
- **Data quality & engineering:** validation, reconciliation, ETL/ELT, Airflow, Databricks, Delta Lake, Azure Data Factory.
- **Analytics methods:** cohort analysis, forecasting, variance analysis, regression, EDA.

## Case studies

Source repositories for these case studies are private. I am happy to walk through any of them on request.

### Claims Data Quality & Financial Reconciliation

A Python and DuckDB SQL workflow generates synthetic claims, detects controlled data-quality defects, and reconciles spending and utilization before reporting. A Tableau dashboard presents the validated results.

The reconciliation shows how an incorrect claim header-to-line join inflates payment totals, and checks the corrected totals independently against one another. All data are synthetic, with no real patient, payer, or employer records.

### Massachusetts Primary Care Access Planning

Census/ACS and HRSA public data joined on county FIPS to compare primary-care capacity against population context across all 14 Massachusetts counties, with Python, SQL, and Tableau supporting the analysis, sensitivity testing, and a two-page decision memo.

Franklin and Hampden remained on the investigation shortlist across all eight tested parameter settings, which produced five distinct shortlist outcomes. This supports further investigation; it does not establish unmet need or an optimal clinic location.

### Healthcare Analytics API

A small Python/FastAPI service so applications can consume validated quality, spending, and access aggregates without rerunning the analytical pipelines. Typed responses carry units, periods, denominators, and dataset provenance, with explicit input validation and structured errors.

Returned metrics are reconciled against the source artifacts they are served from. This is a portfolio analytics service, not a production clinical system.

## Contact

[GitHub: yashwanth-kanajam](https://github.com/yashwanth-kanajam)
