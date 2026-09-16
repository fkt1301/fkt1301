# Hi, I'm Olivier 👋

**Data Engineer** based in Berlin, building reliable, production-grade data platforms — batch, streaming, and everything in between.

4+ years shipping cloud data platforms (AWS, GCP, Snowflake), ETL/ELT pipelines (Airflow, Spark, dbt), and LLM/RAG applications, on top of 6+ years in strategy consulting. I like turning messy, real-world data problems into systems people can actually trust.

📍 Berlin, Germany · 🌐 EN / FR / ES · 💬 [LinkedIn](https://www.linkedin.com/in/olivier-sansamat-79158554/)

---

## 🚀 Featured projects

These three repos deliberately cover the main shapes of data engineering work — a batch ELT warehouse, a real-time streaming pipeline, and a production data service.

### 📊 [emissions-analytics](https://github.com/fkt1301/emissions-analytics) — Batch ELT on GCP
Modern ELT pipeline analysing global CO2 emissions. Ingests OWID + World Bank data into BigQuery, transforms it through layered dbt models (staging → intermediate → marts), and orchestrates the whole thing with Airflow. Includes data quality tests, CI, and dbt lineage docs.
**Stack:** Airflow · dbt · BigQuery · GCP · Python · GitHub Actions

### ⚡ [streaming-data-analysis](https://github.com/fkt1301/streaming-data-analysis) — Real-time streaming pipeline
Schema-first streaming pipeline: records flow through Kafka (Avro + Schema Registry) into Spark Structured Streaming, get validated against business rules, and land in PostgreSQL — with invalid records routed to a dead-letter queue and Airflow handling the batch/monitoring layer on top.
**Stack:** Kafka · Avro · Spark Structured Streaming · PostgreSQL · Airflow · Docker

### 🏭 [plantdata-backend](https://github.com/fkt1301/plantdata-backend) — Production data service on Kubernetes
A FastAPI service that ingests messy cement-plant CSV exports, quarantines every row it can't accept (never silently dropped), and flags anomalies with a plain-language explanation. Deployed to Kubernetes with migrations as a Job, StatefulSet-backed Postgres, and tests running against real PostgreSQL.
**Stack:** FastAPI · SQLAlchemy · PostgreSQL · polars · pydantic · Docker · Kubernetes

---

## 🛠️ Tech stack

**Demonstrated in the repos above**
- **Languages:** Python · SQL
- **Orchestration & processing:** Airflow · dbt · Apache Spark (Structured Streaming) · Kafka (Avro, Schema Registry) · polars · Pandas
- **Storage & warehouses:** PostgreSQL · BigQuery
- **Backend:** FastAPI · SQLAlchemy · Alembic · pydantic
- **Infra & tooling:** Docker · Kubernetes · GitHub Actions (CI/CD) · uv · ruff · mypy · pytest · pre-commit

**Also experienced with** *(production work, not all shown in public repos)*
- **AWS:** Redshift · Glue · Lambda · Step Functions · Athena · S3 · MWAA
- **GCP:** Dataflow · Cloud Composer · Cloud Run · Cloud Functions
- **Warehousing / ELT:** Snowflake · Fivetran
- **GenAI / ML:** LangChain (RAG, embeddings, agents) · ChromaDB · scikit-learn · TensorFlow/Keras · MLflow
- **BI:** Power BI · Tableau · Plotly
- **DevOps:** Terraform

---
