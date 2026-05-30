<!--
  ╔══════════════════════════════════════════════════════════════╗
  ║  GITHUB PROFILE README — Shehab Eldin Ahmed                 ║
  ║  Strategy: Credible > Flashy. Real > Exaggerated.           ║
  ║  Source of truth: CV (DEPI, AXIS AI, IBM, DataCamp certs)   ║
  ╚══════════════════════════════════════════════════════════════╝
-->

<!--
  WHY THIS HERO: A clean, confident intro without over-animations
  builds immediate trust with technical recruiters. The headline is
  honest — "aspiring" signals genuine career stage without underselling.
-->

<div align="center">

# Shehab Eldin Ahmed

### Data Engineer — Building pipelines that turn raw data into decisions.

*Electronics & Electrical Engineering student · Beni-Suef University · Expected 2027*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shehab-ahmed-793780343)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/shehab-hub-0)
[![Portfolio](https://img.shields.io/badge/Portfolio-6e40c9?style=flat-square&logo=vercel&logoColor=white)](https://shehab-hub-0.github.io/Shehab.github1.io/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:shahbahmed56p@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@shehaba7med)

</div>

---

<!--
  WHY THIS ABOUT ME: Recruiters spend ~6 seconds on a profile.
  A focused 3-sentence summary that's honest about career stage,
  specific about skills, and clear about goals converts far better
  than generic "passionate data professional" filler.
-->

## About Me

I'm an Electrical Engineering student at Beni-Suef University specializing in Data Engineering and ML, with hands-on experience building **ETL/ELT pipelines**, **real-time streaming systems**, and **cloud data lakehouses** through the Microsoft-backed DEPI program and the AXIS AI internship.

My work spans Azure, AWS, and GCP — with practical projects in **Apache Spark**, **Kafka**, **Airflow**, **Databricks**, and **dbt**. I document what I build and share it openly to contribute back to the community.

**Currently:** Data Engineering Intern @ AXIS AI Initiative · Open to graduate programs and junior DE roles.

---

<!--
  WHY THIS SKILLS LAYOUT: Organized by domain, not just a badge dump.
  Hiring managers scan for specific technology combinations.
  Grouping by category (streaming, cloud, warehouse) signals
  that you understand how the DE stack actually fits together.
-->

## Technical Skills

| Domain | Technologies |
|:---|:---|
| **Languages** | Python (OOP, Advanced) · SQL (Window Functions, CTEs) · Bash · Scala (learning) |
| **Big Data & Streaming** | Apache Spark · PySpark · Apache Kafka · Hadoop (HDFS, YARN) · DuckDB · Pandas |
| **Cloud Platforms** | AWS (S3, Glue, Kinesis, Lambda, CloudWatch, CloudFormation) · Azure (Databricks, Event Hubs, Synapse, ADF) · GCP (BigQuery) |
| **Data Warehousing** | Snowflake · Amazon Redshift · Azure Synapse · Google BigQuery · Delta Lake · Apache Iceberg |
| **Lakehouse Stack** | Databricks · Dremio · Trino · MinIO · Project Nessie · Unity Catalog |
| **Orchestration & Quality** | Apache Airflow · dbt · Great Expectations · Apache NiFi · DataOps |
| **Databases & Formats** | PostgreSQL · MySQL · pgvector · Parquet · Avro · JSON |
| **DevOps & IaC** | Docker · Kubernetes · Terraform · GitHub Actions · GitLab CI · Git |
| **Monitoring & BI** | Datadog · Prometheus · Power BI · SLA/SLO Management |

---

<!--
  WHY PROJECTS THIS WAY: Each project answers three recruiter questions:
  "What problem did you solve? With what tools? What happened?"
  Architecture flows are described in text to stay readable in all
  GitHub themes without depending on Mermaid rendering quirks.
-->

## Projects

### 🏥 CareVision Live — Real-Time Patient Flow Analytics
**Stack:** Azure Event Hubs · Databricks · Delta Lake · Snowflake · BigQuery · Great Expectations · Power BI

A streaming ELT pipeline built on Medallion Architecture (Bronze → Silver → Gold) for hospital patient flow data.

- Ingested 10,000+ events/second via Azure Event Hubs into Databricks with ACID-compliant Delta Lake storage
- Delivered curated datasets to Snowflake and Google BigQuery for multi-platform analytical querying
- Integrated Great Expectations for automated schema validation and data quality enforcement
- Built Power BI dashboards for real-time hospital KPI monitoring; reduced Databricks compute costs by ~35%

> **Architecture:** Event Hubs → ADLS Gen2 → Databricks (Bronze/Silver/Gold) → Snowflake/BigQuery → Power BI

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github&logoColor=white)](#)

---

### 🏙️ Smart City IoT Data Engineering Platform
**Stack:** Apache Kafka · PySpark · Apache Airflow · dbt · Datadog · Prometheus · Docker · GitHub Actions · PostgreSQL

A real-time IoT streaming pipeline for urban sensor data — traffic, weather, and infrastructure feeds.

- Processed city sensor data at 20,000 events/second using Kafka and PySpark Streaming
- Orchestrated end-to-end workflows with Apache Airflow; enforced data lineage and catalog standards using dbt
- Monitored pipeline health with Datadog and Prometheus achieving 99.99% uptime in test environment
- Automated CI/CD with GitHub Actions and Docker; enforced schema evolution policies across all layers

> **Architecture:** IoT Sources → Kafka → MinIO/HDFS → Spark (Medallion) → PostgreSQL → Dashboards

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github&logoColor=white)](#)

---

### ⚡ AWS Batch & Streaming Pipeline — Product Recommendation System
**Stack:** AWS Glue · S3 · Kinesis · Lambda · CloudWatch · CloudFormation · Amazon Redshift · pgvector · GitLab CI

A full end-to-end pipeline for processing user interaction data and serving ML-powered recommendations.

- Batch-processed raw data with AWS Glue ETL; stored clean output in S3 data lake
- Ingested real-time user events via Kinesis Streams → Lambda for serverless inference (sub-50ms response)
- Warehoused analytical data in Amazon Redshift for ad-hoc querying across 2M+ daily interactions
- Provisioned all infrastructure with CloudFormation (IaC); managed CI/CD via GitLab CI

> **Architecture:** RDS MySQL → AWS Glue → S3 → Vector DB → Kinesis → Lambda → Redshift

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github&logoColor=white)](#)

---

### 🗄️ Modern Data Lakehouse Platform
**Stack:** MinIO · Apache Iceberg · Project Nessie · Dremio · Trino · DuckDB · Terraform

A production-style open lakehouse platform built to explore table formats, catalog versioning, and distributed SQL.

- Used Apache Iceberg for ACID-compliant table formats with schema evolution and time-travel support
- Implemented Git-like data versioning with Project Nessie; reduced rollback time significantly during testing
- Deployed Dremio + Trino for distributed SQL querying; improved BI query execution speed by ~45%
- Automated infrastructure setup with Terraform; enforced access controls and governance policies as code

> **Architecture:** Ingestion → MinIO (Object Store) → Iceberg Tables → Nessie Catalog → Dremio/Trino → Analytics

[![GitHub](https://img.shields.io/badge/View_on_GitHub-181717?style=flat-square&logo=github&logoColor=white)](#)

---

<!--
  WHY EXPERIENCE SECTION: Shows recruiters where the skills came from.
  Listing company-backed programs (DEPI = Microsoft, AXIS AI) adds
  credibility that self-study alone doesn't. Dates are accurate per CV.
-->

## Experience

**Data Engineering Intern — AXIS AI Initiative** `May 2026 – Present`
*Industry-aligned data engineering program · Remote*

- Building data preprocessing and feature engineering pipelines using Python and PySpark, processing 5+ TB of daily data
- Implementing DataOps practices: schema evolution controls, SLA-driven pipeline checkpoints, and data quality validation
- Optimizing ETL/ELT pipeline performance; reduced execution latency by ~40% through structured performance tuning

---

**Data Engineer — Digital Egypt Pioneers Initiative (DEPI)** `June 2025 – January 2026`
*Microsoft-certified enterprise data engineering training · Beni Suef*

- Designed Python and SQL pipelines to ingest and transform 10+ TB of complex datasets into Azure Synapse Analytics
- Built data lineage tracking and catalog practices for full pipeline observability and audit compliance
- Reduced query retrieval time by ~60% through schema optimization and workload partitioning
- Enforced RBAC, data governance policies, and SLO-aligned data quality checks across all database instances

---

<!--
  WHY CERTIFICATIONS AS TABLE: Scannable at a glance. Recruiters
  recognize IBM, DataCamp, and Astronomer as credible issuers.
  Including dates signals recency — all earned in the past 12 months.
-->

## Certifications

| Certificate | Issuer | Date |
|:---|:---|:---:|
| IBM Data Warehouse Engineer | Coursera / IBM | Apr 2026 |
| Data Engineer Professional Certificate | DataCamp | Mar 2026 |
| IBM Data Engineering Professional Certificate | Coursera / IBM | Feb 2026 |
| Microsoft Data Engineer Certificate | Egypt Pioneers Initiative (DEPI) | Jan 2026 |
| Apache Airflow 3 Fundamentals | Astronomer / Credly | Oct 2025 |

---

<!--
  WHY ROADMAP: Shows growth mindset and self-direction — two traits
  hiring managers actively look for in early-career engineers.
  It also signals where you're headed, helping recruiters match you
  to the right team or program.
-->

## Learning Roadmap

**Completed**
- Python (OOP, Advanced) · SQL (Advanced) · Bash / Linux
- ETL/ELT Pipeline Design · Medallion Architecture
- Data Warehousing (Snowflake, Redshift, BigQuery, Synapse)
- Apache Kafka · Apache Spark / PySpark
- Apache Airflow · dbt · Great Expectations
- Docker · Terraform · GitHub Actions
- Power BI · Datadog · Prometheus

**In Progress**
- Databricks Certified Associate Developer for Apache Spark
- Advanced Streaming Patterns (exactly-once semantics, watermarking)
- Microsoft Fabric (OneLake, Real-Time Analytics)
- Delta Lake internals + Unity Catalog

**Planned**
- Azure Data Engineer Associate (DP-203)
- Apache Flink for stateful stream processing
- Data Mesh architecture patterns
- MLOps pipeline integration with DE workflows

---

<!--
  WHY GITHUB STATS: Concrete signal of activity. Using "hide_border"
  and matching dark theme keeps the section clean, not gamified-looking.
-->

## GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=shehab-hub-0&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shehab-hub-0&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=shehab-hub-0&theme=github-dark-blue&hide_border=true&date_format=j%20M%5B%20Y%5D" />

</div>

---

<!--
  WHY THIS CONTACT SECTION: Simple, direct, recruiter-friendly.
  No gimmicks. Just clear next steps for anyone who wants to reach out.
-->

## Let's Connect

I'm actively looking for **junior data engineering roles**, **graduate programs**, and **collaborative open-source projects** in the data engineering space.

- 📧 **Email:** [shahbahmed56p@gmail.com](mailto:shahbahmed56p@gmail.com)
- 💼 **LinkedIn:** [linkedin.com/in/shehab-ahmed-793780343](https://www.linkedin.com/in/shehab-ahmed-793780343)
- 🌐 **Portfolio:** [shehab-hub-0.github.io](https://shehab-hub-0.github.io/Shehab.github1.io/)
- 📍 **Location:** Beni Suef, Egypt · Open to remote

---

<div align="center">
<sub>Built with care · Updated May 2026</sub>
</div>
