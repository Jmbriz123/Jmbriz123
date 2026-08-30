<div align="center">

# Hi, I'm Jemarco Briz 👋

### Aspiring Data Engineer | Data Engineer Intern @Springer Capital | Building AI Data Infrastructure | BS Computer Science @ UP Visayas

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=650&lines=Data+Engineer+Intern+%40+Springer+Capital;Building+AI%2FLLM+Data+Infrastructure;ETL+%2F+ELT+Pipelines+%7C+Airflow+%7C+dbt+%7C+Docker;Obsessed+with+Clean%2C+Reliable+Data" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jemarco-briz-52419a327/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jemarcobriz123@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Jmbriz123)

</div>

---

### 🚀 About Me

Data engineering isn't just what I'm studying — it's what I spend my free time doing. I'm drawn to the problem of turning messy, unreliable data into something a business (or a model) can actually trust, and I get genuinely excited digging into schema design, pipeline orchestration, and data quality checks.

- 🔭 Currently a **Data Engineer Intern at Springer Capital**, building the **AI data infrastructure** that powers an AI/LLM system — designing the pipelines that feed and structure data for the AI model
- 🌱 Pursuing a **B.S. in Computer Science** at the **University of the Philippines Visayas**, strengthening foundations in software engineering and computation fundamentals  — expected graduation July 2028
- 🛠️ I design **containerized, schema-validated ETL/ELT pipelines** using Python, Airflow, dbt, Docker, and PostgreSQL
- 🗄️ Deeply interested in **AI Data Infrastructure**, **Data Warehousing**, **medallion architecture (Bronze/Silver/Gold)**, and **scalable, idempotent pipeline design**
- 🧪 Building a **personal weather-data platform (SILID)** on the side, purely out of curiosity and love for the craft
- 📫 Reach me at **jemarcobriz123@gmail.com**

---

### 🧰 Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

### 📌 Featured Projects

#### 🔹 [Customer Care Email Data Pipeline](https://github.com/Jmbriz123/airflow-data-ingestion-pipeline)
A modular, containerized ETL pipeline that extracts customer-care email data from CSV, validates it against YAML-defined schemas, and loads **thoudands of rows validated records** into PostgreSQL Database.
- ⚙️ Designed an Airflow-orchestrated workflow with reusable Python pipeline modules, structured logging, and
automated schema checks for column names, nullability, and data types.
- 🐳 Configured the application with Docker Compose to provide a reproducible development environment, enabling the
complete pipeline and PostgreSQL infrastructure to run with minimal setup.

`Python` `Pandas` `PostgreSQL` `Apache Airflow` `Docker` `Docker Compose`

#### 🔹 [PostgreSQL Data Warehouse & Analytics Project](https://github.com/Jmbriz123/Data-Warehouse-Project)
A PostgreSQL data warehouse built on **Medallion (Bronze/Silver/Gold) architecture** using pure SQL ELT — no external orchestration tools — integrating CRM and ERP source systems into a unified star schema.
- 🔧 Architected a PostgreSQL data warehouse using Medallion (Bronze/Silver/Gold) architecture and pure SQL ELT
pipelines, integrating two disparate source systems (CRM and ERP) into a unified star schema without relying on
external ETL or orchestration tools.
- 📈 Engineered idempotent, atomic Silver-layer transformation procedures resolving cross-system data quality issues
(composite keys, delimiter mismatches, inconsistent codes, invalid dates) across 6 source tables, cutting join failures
and eliminating silent data loss in downstream reporting.
- 🚀 Implemented a scale-aware indexing strategy and non-blocking materialized view refresh (REFRESH CONCURRENTLY)
for the Gold star schema, along with SQL-based data quality tests, projecting ~80–95% query performance gains at
production scale while ensuring zero analyst downtime during batch loads.


`PostgreSQL` `SQL` `Data Warehousing` `ELT`

#### 🔹 [SILID — Weather Intelligence Platform for Productivity](https://github.com/Jmbriz123/SILID) `🚧 side project, WIP`
An ongoing passion project I build in my free time — a full Bronze/Silver/Gold data platform ingesting hourly Philippine weather data and turning it into productivity insights.
- 🌤️ Hourly ingestion from the Open-Meteo API, orchestrated end-to-end with **Apache Airflow**
- 🥉🥈🥇 Bronze (raw, auditable) → Silver (cleaned, typed, UTC+8) → Gold (productivity metrics) layered architecture
- 🔄 Gold-layer transformations built with **dbt**
- 📊 Insights served through a **Streamlit** dashboard
- 🐳 Fully containerized with Docker

`Python` `Airflow` `dbt` `PostgreSQL` `Docker` `Streamlit`

---

### 💼 Experience Snapshot

| Role | Company/Organization | Focus |
|---|---|---|
| Data Engineer Intern | Springer Capital | Architected high-reliability, idempotent ETL/ELT pipelines and scalable data infrastructure to power enterprise AI/LLM workloads. |
| Web Developer | UPV Komsai.org | Agile development workflows, Git/GitHub collaboration |
| Multi-Department Intern | San Pablo City Water District | Structured data handling across operations, HR, and customer support |

---

### 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Jmbriz123&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jmbriz123&layout=compact&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Jmbriz123&theme=tokyonight&hide_border=true" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Jmbriz123&theme=tokyo-night&hide_border=true" />

</div>

---

<div align="center">

*"Good pipelines don't just move data — they make sure you can trust it."*

⭐️ From [Jmbriz123](https://github.com/Jmbriz123)

</div>
