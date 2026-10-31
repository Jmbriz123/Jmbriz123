<h1 align="center">Hi, I'm Jemarco Briz 👋</h1>

<p align="center">
  <strong>Data Engineering · AI Infrastructure · ETL/ELT · RAG Systems</strong>
</p>

<p align="center">
  <a href="mailto:jemarcobriz123@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/jemarco-briz-52419a327/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/Jmbriz123">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## About Me

I'm a **Computer Science student at the University of the Philippines Visayas** focused on **Data Engineering and AI Infrastructure**.

I build data systems that bridge raw data and intelligent applications, with interests in reliable data ingestion, transformation, storage, orchestration, and retrieval-augmented generation (RAG).

Currently, I'm a **Data Engineering Intern at Glynac AI (US)**, working on Salesforce CRM data ingestion infrastructure for downstream intelligence applications.

Previously, I worked as a **Data Engineer Intern at Springer Capital Investments (US)**, contributing to the data and RAG infrastructure of an AI-powered compliance document review platform.

I'm also developing **SolNexus**, a data engineering platform for SolTech EMR that consolidates lead and client communication data into a unified, structured system through automated ingestion, data transformation, and identity resolution.

**Areas of Interest:** Data Engineering · Data Platforms · AI Infrastructure · ETL/ELT · Data Quality · Distributed Processing · RAG Systems

---

## 💼 Professional Experience

### Data Engineering Intern — Glynac AI (US)

**October 2026 – Present**

Working on Salesforce CRM data ingestion infrastructure to support downstream AI-powered intelligence applications.

- Building data ingestion pipelines using **Salesforce Bulk API 2.0**.
- Implementing incremental synchronization using SystemModstamp watermarks, including deletion handling and resumable ingestion workflows.
- Working on privacy-preserving data pipelines with **PII masking and deduplication** before data persistence.
- Integrating ingested CRM data into a structured **MinIO-based Bronze storage layer**.

**Tech:** `Python` `Salesforce Bulk API 2.0` `PostgreSQL` `MinIO` `Apache Airflow` `Docker`

### Data Engineer Intern — Springer Capital Investments (US)

**June 2026 – September 2026**

Contributed to the data and AI infrastructure of an AI-powered compliance document review platform.

- Designed and implemented an end-to-end document processing pipeline covering ingestion, extraction, PII masking, semantic chunking, embedding generation, retrieval, and persistence.
- Built the **RAG retrieval infrastructure** using PostgreSQL, pgvector, and Sentence Transformers for compliance-rule retrieval and precedent search.
- Implemented **HNSW vector indexing** and semantic similarity search for efficient retrieval.
- Orchestrated asynchronous document processing using **Celery and Redis**, decoupling computationally intensive workloads from API requests.
- Implemented privacy-preserving data flows by masking PII before embedding generation and external LLM processing.
- Evaluated retrieval quality using reviewer-labeled datasets and precision, recall, and F1 metrics.
- Implemented grounding checks and safer failure handling to improve the reliability of AI-generated compliance analysis.

**Tech:** `Python` `PostgreSQL` `pgvector` `MinIO` `Celery` `Redis` `Docker` `FastAPI` `Sentence Transformers`

---

## 🚀 Featured Projects

### ☀️ [SolNexus — Unified Lead & Client Communication Intelligence Pipeline](https://github.com/CMSC128-NexusWorks/SolNexus)

**Data Engineering Project · SolTech EMR · Team Project**

A data integration platform designed to centralize SolTech's fragmented clinic lead and client communication data into a unified, structured, and searchable system.

SolNexus replaces manual spreadsheet-based lead tracking with an orchestrated data pipeline and an authenticated dashboard for managing clinic relationships, follow-ups, and communication history.

**Data Engineering & Architecture**

- **Multi-Source Ingestion:** Building automated Gmail API ingestion and spreadsheet migration workflows to consolidate existing lead records and communication data.
- **Bronze Layer:** Implementing raw message storage in PostgreSQL, preserving source information, timestamps, and data provenance.
- **Silver Layer:** Developing dbt transformation models to normalize, deduplicate, and structure raw data into relational lead and interaction datasets.
- **Pipeline Orchestration:** Using Apache Airflow to schedule ingestion and transformation workflows, with retry mechanisms for failure handling.
- **Identity Resolution:** Designing staff-confirmed identity mapping to associate external communication participants with the correct clinic records, preventing incorrect lead associations.
- **Data Integrity:** Implementing validation, deduplication, audit trails, and safeguards to preserve operational data across pipeline rebuilds.

**Application & Serving Layer**

- Building a FastAPI REST backend to expose structured lead and interaction data.
- Developing a React dashboard with prioritized follow-up views and searchable lead history.
- Implementing authenticated access and editable lead records for SolTech staff.

**Planned Extensions (Phase 2):** Facebook Messenger and Viber ingestion, LLM-based information extraction, Gold-layer analytics, and pipeline failure alerting.

**Tech:** `Python` `PostgreSQL` `Apache Airflow` `dbt` `FastAPI` `React` `Alembic` `Docker` `Gmail API`

---

### 🤖 AI Compliance Document Review Platform

**Springer Capital Investments · Data Engineering & AI Infrastructure**

An AI-powered platform that analyzes compliance documents, retrieves relevant regulatory information, and generates AI-assisted compliance analysis.

- Designed and built the document processing and RAG pipeline, from ingestion and extraction to embeddings, retrieval, and LLM inference.
- Developed semantic retrieval using **PostgreSQL, pgvector, and Sentence Transformers**.
- Implemented asynchronous processing with Celery and Redis.
- Designed privacy-preserving PII masking before embedding generation and external LLM calls.
- Evaluated retrieval quality using reviewer-labeled data and retrieval metrics.
- Added grounding checks and safer failure handling to improve the reliability of generated results.

**Tech:** `Python` `FastAPI` `PostgreSQL` `pgvector` `MinIO` `Celery` `Redis` `Docker` `Sentence Transformers`

---

## 🛠️ Technical Skills

**Programming & Query Languages**

`Python` `SQL` 

**Data Engineering**

`PostgreSQL` `Apache Airflow` `dbt` `Pandas` `ETL/ELT` `Data Modeling` `Data Warehousing`

**Storage & Infrastructure**

`MinIO` `Docker` `Redis` `Alembic`

**AI & Retrieval Infrastructure**

`pgvector` `Sentence Transformers` `Embeddings` `RAG` `LLM Integration`

**Backend & Development Tools**

`FastAPI` `Git` `GitHub` `Jira` `Linux`

---

## 📊 GitHub Statistics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Jmbriz123&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jmbriz123&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Jmbriz123&theme=tokyonight&hide_border=true" />

</div>

---

<p align="center">
  <i>"Good pipelines don't just move data — they make sure you can trust it."</i>
</p>
