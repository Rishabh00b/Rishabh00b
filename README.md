<div align="center">

<img src="./banner.svg" width="100%" alt="Rishabh Kumar Singh – Data Engineer"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=2E86C1&center=true&vCenter=true&width=700&lines=Data+Engineer+%7C+AWS+Certified+(DEA-C01);Apache+Airflow+Contributor+(2+Merged+PRs);Medallion+Pipelines+at+10M%2B+Row+Scale;Snowflake+%C2%B7+dbt+%C2%B7+Airflow+%C2%B7+AWS+%C2%B7+Python;LLM-Augmented+Analytics+on+Real+Warehouses" alt="Typing SVG"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/Rishabh0b)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Rishabh_0b)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Rishabh00b@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=Rishabh00b&color=8E44AD&style=for-the-badge&label=PROFILE+VIEWS)

</div>

---

## `whoami`

```yaml
name:        Rishabh Kumar Singh
role:        Data Engineer (student) — pipelines, warehousing, AI-augmented analytics
education:   B.Tech CSE (AI), KIET Group of Institutions · 2024 → 2028
location:    Delhi, India
certified:   AWS Certified Data Engineer – Associate (DEA-C01)
open_source: Apache Airflow contributor — 2 merged PRs
stack:       [Snowflake, dbt, Airflow, AWS, Python, SQL, Docker]
learning:    [Apache Spark, System Design, Advanced dbt + CI/CD]
status:      Open to Data Engineering / Analytics / Cloud internships
```

I build batch data platforms the way production teams do: layered models, tested transformations, orchestrated and containerised, with an AI layer on top for people who don't write SQL.

🌐 **Open-source contributor to [Apache Airflow](https://github.com/apache/airflow)** — 2 pull requests merged into the orchestrator behind my own pipelines.

---

## 🏆 Highlights

| | |
|:--|:--|
| 🌐 **Open Source** | **2 merged PRs in [Apache Airflow](https://github.com/apache/airflow)** |
| ☁️ **Certified** | AWS Certified Data Engineer – Associate (DEA-C01) and Cloud Practitioner (CLF-C02) |
| 📦 **Scale** | Pipeline handling **10M+ orders · 23M+ order items · 300K+ reviews** |
| 🤖 **AI on the warehouse** | LLM review enrichment, RAG review chat, and NL→SQL with a SELECT-only guard |
| 🥇 **Leadership** | 1st Prize, InnoTech Tech Fest — led the ZeroMile logistics concept |
| 🧪 **Industry exposure** | Software QA Engineering intern at FabHotels |

---

## 🚀 Featured Project — Zomato Data Engineering & AI Platform

**`Python` `AWS S3` `Snowflake` `dbt` `Apache Airflow` `Docker` `OpenAI` `Streamlit`**

A production-style batch platform that takes raw CSVs to AI-powered analytics.

```mermaid
flowchart LR
    A[Raw CSVs] --> B[(AWS S3)]
    B --> C[Snowflake<br/>Bronze]
    C --> D[dbt<br/>Silver]
    D --> E[dbt<br/>Gold]
    E --> F[OpenAI<br/>Enrichment · RAG · NL→SQL]
    F --> G[Streamlit App]
    H{{Airflow DAG<br/>daily · 4 tasks}} -.orchestrates.-> C
    H -.-> D
    H -.-> E
    H -.-> F
```

| Area | What it does |
|:--|:--|
| **Architecture** | Medallion (Bronze → Silver → Gold), 15+ dbt models |
| **Loading** | Incremental `MERGE`, SCD Type 2 snapshot |
| **Quality** | Automated dbt tests across every layer |
| **Orchestration** | Daily 4-task Airflow DAG, fully Dockerized |
| **AI layer** | LLM review enrichment · RAG review chat · NL→SQL with SELECT-only safety guard |

[**→ View Repository**](https://github.com/Rishabh00b/zomato-end-to-end-data-engineering)

---

## 🌐 Open Source — Apache Airflow

[![Airflow](https://img.shields.io/badge/Apache%20Airflow-Contributor-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)](https://github.com/apache/airflow/pulls?q=is%3Apr+author%3ARishabh00b+is%3Amerged)
![Merged PRs](https://img.shields.io/badge/Merged%20PRs-2-2EA043?style=for-the-badge&logo=github&logoColor=white)

I contribute to [Apache Airflow](https://github.com/apache/airflow), the workflow orchestrator I use daily in my own data pipelines. Two of my pull requests have been reviewed by maintainers and merged upstream.

[**→ See my merged pull requests**](https://github.com/apache/airflow/pulls?q=is%3Apr+author%3ARishabh00b+is%3Amerged)

---

## 🧩 More Projects

| Project | Stack | Summary |
|:--|:--|:--|
| 📊 **Sales Data Analysis Dashboard** | `Python` `SQL` `Pandas` `Power BI` | ETL workflow for raw sales data, with Power BI dashboards for KPIs, revenue trends and regional performance. |
| 👨‍🏫 **Teacher Data Management System** | `Java` `Spring Boot` `MySQL` | REST APIs over a normalized relational schema with a query-optimized backend. |
| 🚚 **ZeroMile** — *1st Prize, InnoTech Fest* | `Logistics` `Team Leadership` | Led a team to design a marketplace matching shippers with trucks on return routes, cutting empty trips and costs. [Repo](https://github.com/kastwaru/ZeroMile) |

---

## 🏅 Certifications

| Certification | Issuer | Level |
|:--|:--|:--:|
| **AWS Certified Data Engineer – Associate** (DEA-C01) | Amazon Web Services | Associate |
| **AWS Certified Cloud Practitioner** (CLF-C02) | Amazon Web Services | Foundational |
| Data Analytics Job Simulation | Deloitte × Forage | Simulation |
| Machine Learning Foundations | AWS Academy | Foundational |
| AI for Everyone | DeepLearning.AI | Foundational |

---

## 🛠️ Tech Stack

<div align="center">

**Data Engineering & Warehousing**<br/>
<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white"/>
<img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>

**Cloud**<br/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/>
<img src="https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS%20Glue-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>

**Languages & Data**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>

**AI / LLM**<br/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/RAG-6E56CF?style=flat-square&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>

**Backend & Tools**<br/>
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white"/>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white"/>

</div>

---

## 🗺️ Roadmap

- [x] Medallion pipeline with Snowflake, dbt and Airflow
- [x] AWS Certified Data Engineer – Associate
- [x] LLM layer on a real warehouse (RAG + NL→SQL)
- [x] First contributions merged into Apache Airflow
- [ ] Keep contributing upstream — deeper core / provider work
- [ ] Apache Spark / PySpark for large-scale processing
- [ ] dbt CI/CD (slim CI, state-based runs, automated docs)
- [ ] System design for data platforms (streaming, lakehouse patterns)

---

## 📈 GitHub Analytics

<div align="center">

<img src="https://img.shields.io/github/followers/Rishabh00b?style=for-the-badge&logo=github&color=2E86C1&labelColor=0D1117"/>
<img src="https://img.shields.io/github/stars/Rishabh00b?style=for-the-badge&logo=github&color=8E44AD&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/Apache%20Airflow-2%20Merged%20PRs-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white&labelColor=0D1117"/>
<img src="https://img.shields.io/badge/AWS-DEA--C01-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=0D1117"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Rishabh00b&theme=tokyonight&hide_border=true&background=0D1117"/>

<img src="https://ghchart.rshah.org/2E86C1/Rishabh00b" alt="Rishabh00b contribution calendar" width="85%"/>

</div>

---

## 📬 Let's Connect

Open to **Data Engineering, Data Analyst and Cloud internships**, and to collaborating on pipelines, warehouses or AI-augmented analytics. Happy to talk AWS, dbt, Airflow, Snowflake, or anything data.

<div align="center">

[![Email](https://img.shields.io/badge/Email%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Rishabh00b@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/Rishabh0b)
[![X](https://img.shields.io/badge/Follow%20on%20X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/Rishabh_0b)

*Turning raw, messy data into pipelines people can trust.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E44AD,100:2E86C1&height=100&section=footer" width="100%"/>

</div>
