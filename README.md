<div align="center">
  <img src="./assets/banner.gif" width="100%" alt="Header Banner" />

  # Hi, I'm Pakkarasit Watjang

  **4th-year Business Information Technology Student @ KMITL**

  *Aspiring Data Engineer | Streaming, Cloud & Data Pipelines*

  <br />

  [![LANGUAGE](https://img.shields.io/badge/LANGUAGE-THAI%20%7C%20ENGLISH-8A2BE2?style=flat-square)](#)
  [![TOEIC](https://img.shields.io/badge/TOEIC-835%2F990-blue?style=flat-square)](#)
  [![STATUS](https://img.shields.io/badge/STATUS-OPEN%20TO%20INTERNSHIP-2ea44f?style=flat-square)](#)
  [![EDUCATION](https://img.shields.io/badge/STUDYING%20AT-KMITL-orange?style=flat-square)](#)

</div>

---

### About Me

I am a 4th-year **Business Information Technology** student at the **Faculty of Information Technology, King Mongkut's Institute of Technology Ladkrabang (KMITL)**, focusing on **Data Engineering**.

I build end-to-end data pipelines, from streaming ingestion and data lakes to warehouse modelling, orchestration and dashboards, using both managed platforms (Databricks) and open-source tools on Google Cloud.

- 🎯 **Career Interest:** Data Engineering, streaming pipelines and Lakehouse architecture
- 📖 **Current Focus:** Completing the **DataTalksClub Data Engineering Zoomcamp** and preparing for the **Databricks Certified Data Engineer Associate**
- 🎓 **Education:** Business Information Technology, Faculty of IT, KMITL
- 📫 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/pakkarasit-watjang-b5416b3b7/) | [GitHub](https://github.com/pestrocheese-WJ) | [Email](mailto:wjpakkarasit@gmail.com)

---

### 🛠 Tech Stack & Tools

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Data Processing & Streaming**

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)

**Cloud & Data Warehouse**

![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**DevOps & Visualization**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=flat-square&logo=looker&logoColor=white)

---

### Projects

#### 1. [Streaming E-commerce Funnel Analytics](https://github.com/pestrocheese-WJ/ecommerce-funnel-streaming)
> **Streaming pipeline on Google Cloud: Kafka → Spark Structured Streaming → GCS → BigQuery → dbt → Looker Studio**

- Streamed 500K real clickstream events through **Kafka** and **Spark Structured Streaming** into a **GCS** data lake, landing within about 1 minute.
- Modelled the data in **BigQuery** with **dbt** (staging, fact and aggregate layers, with tests) and orchestrated hourly loads with **Airflow**. All infrastructure is provisioned with **Terraform**.
- Designed an **idempotency key** at the producer so dbt removes re-sent events without dropping genuine repeat purchases (505,000 raw rows → 500,000 clean).
- Found that **92% of shopping sessions that add to cart never purchase** (3.19% session conversion). [Live dashboard](https://datastudio.google.com/reporting/827b2e7a-515e-43c2-b522-fd263f2b22ef)
- **Tech Stack:** `Kafka` `Spark Structured Streaming` `GCS` `BigQuery` `dbt` `Airflow` `Terraform` `Docker` `Looker Studio`

#### 2. [Flight Aviation Pipeline](https://github.com/pestrocheese-WJ/flight-aviation-pipeline)
> **Flight data pipeline on Databricks using Delta Lake and Medallion Architecture (Bronze, Silver, Gold)**

- Built an end-to-end batch pipeline for aviation records using the **Medallion Architecture**:
  - **Bronze:** raw data ingestion
  - **Silver:** cleaned, parsed and enriched data
  - **Gold:** business-level aggregations ready for querying
- Used **Databricks**, **Delta Lake** and **PySpark** for distributed processing with ACID transactions.
- **Tech Stack:** `Databricks` `PySpark` `Delta Lake` `SQL` `Python`

#### 3. [Weather Content Automation](https://github.com/pestrocheese-WJ/weather-content-automation)
> **n8n workflow that turns daily weather forecasts into AI-generated Facebook posts**

- Automated a daily workflow that pulls weather forecasts, writes captions with **Gemini** and generates images with **Hugging Face** models.
- **Tech Stack:** `n8n` `Gemini API` `Hugging Face` `REST APIs`

---

### 🗣 Language Proficiency

- **Thai:** Native
- **English:** Professional working proficiency
  - **TOEIC:** **835 / 990**
  - Comfortable reading technical documentation and collaborating in English.
