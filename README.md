<h1 align="center">Hi, I'm Jemarco Briz 👋</h1>

<p align="center">
  <strong>Data Engineer · AI Data Infrastructure · ETL/ELT · RAG Systems</strong>
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

I'm a **Computer Science student at the University of the Philippines Visayas** focused on **Data Engineering and AI infrastructure**.

I enjoy building reliable data systems that sit between raw data and AI applications — from ingestion and validation to transformation, vector retrieval, and LLM processing.

I worked as a **Data Engineer Intern at Springer Capital (US)**, where I helped build an AI-powered compliance document review platform, designing and implementing the data and RAG infrastructure that enabled the system to process documents, retrieve relevant compliance information, and generate AI-assisted analysis.


**Focus areas:** Data Engineering · AI Infrastructure · ETL/ELT · RAG · Data Quality · Pipeline Reliability

---

## 💼 Experience
### Software Engineer Intern (Backend, Data, AI) — Acumen Strategy (US)

**Oct 2026 - Present**

Building the **data infrastructure** for the organization

### Data Engineer Intern — Springer Capital (US)

**Jun 2026 – Sept 2026**

Worked on the **data and AI infrastructure** behind an AI-powered compliance document review platform.

* Designed an end-to-end document analysis pipeline covering **document ingestion, format-specific extraction, PII detection/masking, semantic chunking, embeddings, vector retrieval, LLM inference, validation, and persistence**.
* Built the **RAG retrieval layer** using **PostgreSQL + pgvector + Sentence Transformers**, supporting compliance-rule retrieval, precedent search, and disclosure-by-absence detection.
* Implemented **HNSW vector indexes** and semantic similarity search to efficiently retrieve relevant compliance rules and precedents.
* Orchestrated asynchronous document processing with **Celery + Redis**, decoupling computationally expensive AI workloads from the API request lifecycle.
* Implemented a **privacy-preserving AI pipeline** where PII is detected and masked before embeddings and third-party LLM calls, while mappings remain stored internally for controlled restoration.
* Improved retrieval reliability through **reviewer-labeled evaluation**, measuring **precision, recall, and F1** for disclosure-threshold tuning.
* Added **grounding checks** to prevent unsupported LLM-generated compliance flags from being persisted.
* Contributed to the architecture and integration of the **Data Engineering and AI pipeline** within a cross-functional team.

**Tech:** `Python` `PostgreSQL` `pgvector` `MinIO` `Celery` `Redis` `Docker` `Sentence Transformers` `RAG` `LLMs`

---

### Web Developer — UPV Komsai.org

**Feb 2026 – Apr 2026**

* Built and maintained the organization's website using **HTML, CSS, and JavaScript**.
* Collaborated using **Git/GitHub** within an Agile development workflow.

**Tech:** `HTML` `CSS` `JavaScript` `Git` `GitHub`

---

## 🚀 Featured AI/Data Engineering Projects

### 🤖 AI Compliance Document Review Platform

An AI-powered compliance document review platform built during my internship, designed to analyze uploaded documents using a privacy-preserving **RAG pipeline**.

**My role:** Data Engineer & Team Lead

* Led a cross-functional team of **Data, AI, Backend, and Frontend engineers**, owning data architecture and technical decisions.
* Designed and built the **end-to-end RAG pipeline**: document ingestion → extraction → PII masking → semantic chunking → embeddings → vector retrieval (Compliance Rules, Missing Disclosure Detection, Precedent Search) → LLM generation → validation → persistence.
* Built the retrieval layer with **PostgreSQL + pgvector + Sentence Transformers**, supporting compliance-rule retrieval, precedent search, and disclosure-by-absence detection.
* Implemented **HNSW vector indexing** and semantic similarity search for efficient retrieval.
* Orchestrated asynchronous processing using **Celery + Redis**, keeping heavy AI workloads separate from the API request lifecycle.
* Implemented a **privacy-preserving data flow** that masks PII before embeddings and third-party LLM calls while retaining mappings internally.
* Evaluated retrieval quality using reviewer-labeled data and **precision, recall, and F1** to tune retrieval thresholds.
* Added **retry logic and safer failure handling** to improve pipeline reliability.

**Tech:** `Python` `PostgreSQL` `pgvector` `Celery` `Redis` `MinIO` `Docker` `FastAPI` `Sentence Transformers` `RAG` `LLMs`

---

### 📥 Customer Care Email Data Pipeline

A modular, containerized ETL pipeline that extracts customer-care emails from CSV data, validates records against YAML-defined schemas, transforms the data, and loads validated records into PostgreSQL.

**Tech:** `Python` `Pandas` `Apache Airflow` `Docker` `PostgreSQL` `YAML`

---

### 🏗️ PostgreSQL Data Warehouse & Analytics

A **Medallion Architecture** data warehouse integrating CRM and ERP sources into a dimensional/star-schema model.

* Bronze → Silver → Gold data layers
* SQL-based ELT transformations
* Idempotent transformation logic
* Materialized views for analytical workloads
* Designed for improved query performance and reproducibility

**Tech:** `PostgreSQL` `SQL` `Data Warehousing` `ETL/ELT`

---

## 🛠️ Technical Skills 

### Data & Backend
`Python` · `SQL` · `PostgreSQL` · `FastAPI` · `Alembic` · `MinIO` · `Pandas`

### Data Engineering
`Apache Airflow` · `Docker` · `ETL/ELT` · `Data Warehousing`

### AI Infrastructure
`pgvector` · `RAG` · `Sentence Transformers` · `Embeddings` · `Celery` · `Redis`
### Other Tools

`Git` · `GitHub` · `Jira` 

---

## 📊 GitHub

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Jmbriz123&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />

<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jmbriz123&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Jmbriz123&theme=tokyonight&hide_border=true" />

</div>

---

<p align="center">
  <i>"Good pipelines don't just move data — they make sure you can trust it."</i>
</p>
