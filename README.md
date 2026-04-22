# Hi, I'm Alan Almeida 👋

Data Engineer based in Mumbai, India. I build end-to-end cloud data pipelines
on Azure and Microsoft Fabric — from raw ingestion to Delta Lakehouses to
Power BI. Currently expanding my stack and working toward new certifications.

---

## 🛠️ Tech Stack

**Languages**
`Python` `SQL`

**Data Engineering**
`Apache Spark` `PySpark` `Delta Lake` `Medallion Architecture`

**Cloud & Platforms**
`Azure Data Factory` `Azure Databricks` `ADLS Gen2` `Azure Synapse Analytics`
`Microsoft Fabric` `OneLake` `Google Cloud Platform`

**Databases**
`MySQL` `MongoDB`

**Tools**
`Git` `GitHub` `Google Colab` `Power BI`

---

## 📁 Projects

### 🔷 Azure End-to-End Data Engineering Project
> Multi-source ingestion pipeline built on Azure with a Medallion Lakehouse architecture

- Ingested 8 datasets from GitHub REST API, MySQL, and MongoDB into ADLS Gen2 via Azure Data Factory
- Config-driven pipeline using Lookup + ForEach + JSON manifest — no hardcoded paths
- PySpark transformations in Databricks: deduplication, feature engineering, 7-table star schema joins, NoSQL enrichment
- OAuth2 Service Principal auth · Snappy Parquet Silver layer · Gold served via Synapse Analytics external tables

🔗 [View Repository](https://github.com/Alan9920/Data-Engineering-Project)

---

### 🟣 Microsoft Fabric End-to-End Lakehouse Project
> Full Medallion Lakehouse built natively on Microsoft Fabric with Direct Lake Power BI reporting

- Ingested Wide World Importers Parquet data from Azure Blob Storage via Fabric Data Factory Copy Activity into OneLake
- PySpark notebooks: raw Parquet → partitioned Delta tables with engineered date dimensions → pre-aggregated Gold tables
- Incremental load using Delta Lake's native MERGE operation — upserts updated monthly records without full reloads
- Direct Lake Semantic Model (5 dimensions + fact, star schema) · Power BI report with bar chart, map, and table visuals

🔗 [View Repository]([#](https://github.com/Alan9920/Microsoft-Fabric-Project))

---

## 🏅 Certifications

| Certification | Badge |
|---|---|
| Microsoft Certified: Fabric Data Engineer Associate | DP-700 |
| Google Cloud: Associate Cloud Engineer | GCP ACE |
| Microsoft Certified: Azure Data Fundamentals | DP-900 |
| Microsoft Certified: Azure Fundamentals | AZ-900 |

---

## 📊 GitHub Stats

![Alan's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Alan9920&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Alan9920&theme=tokyonight&hide_border=true&layout=compact)

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alan-almeida-92bbb7290/)
