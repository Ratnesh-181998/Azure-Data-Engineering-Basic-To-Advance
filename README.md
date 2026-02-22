# Azure Data Engineering: Basic to Advance 🚀

Welcome to the comprehensive repository for **Azure Data Engineering - Basic to Advance**. This project covers everything from foundational SQL and Big Data concepts to advanced cloud-based data orchestration, real-time streaming, and industrial-scale data pipelines using the Azure ecosystem.

---

## 🛠️ Tech Stack & Tools

![Tech Stack](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Tech Stack](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Tech Stack](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Tech Stack](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Tech Stack](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tech Stack](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Tech Stack](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)

### ☁️ Azure Service Tags
![ADLS Gen2](https://img.shields.io/badge/Azure_ADLS_Gen2-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Synapse Analytics](https://img.shields.io/badge/Azure_Synapse-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![SQL Database](https://img.shields.io/badge/Azure_SQL_DB-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Event Hubs](https://img.shields.io/badge/Azure_Event_Hubs-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Cosmos DB](https://img.shields.io/badge/Azure_Cosmos_DB-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Functions](https://img.shields.io/badge/Azure_Functions-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)
![Logic Apps](https://img.shields.io/badge/Azure_Logic_Apps-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white)


**Core Technologies Covered:**
- **Cloud:** Azure (Blob Storage, ADLS Gen2, Data Factory, Synapse, Event Hub, Cosmos DB, Logic Apps, Functions), GCP (Dataproc, BigQuery, Pub/Sub).
- **Data Processing:** Apache Spark (PySpark), Hive, Trino.
- **Modern Table Formats:** Delta Lake, Apache Iceberg, Apache Hudi.
- **Databases:** MySQL, MongoDB, Cassandra, Snowflake.
- **Streaming:** Confluent Kafka, GCP Pub/Sub, Azure Event Hubs.
- **Orchestration:** Apache Airflow (managed as Cloud Composer).
- **AI & Automation:** n8n, OpenAI/ChatGPT integration, Agentic AI.

---

## 📚 Course Curriculum & Modules

### 🔹 Module 1: SQL Mastery
- **Foundations:** Database vs. DBMS/RDBMS, ACID Properties.
- **MySQL:** Setup Workbench, Integrity Constraints.
- **Commands:** DDL, DML, DQL, DCL (CREATE, INSERT, ALTER, DROP, TRUNCATE, DELETE).
- **Advanced Querying:** Joins, Subqueries, Window Functions, CTEs (Recursive & Iterative), CASE Statements.

### 🔹 Module 2: Big Data Fundamentals (Hadoop & Hive)
- **Concepts:** Distributed Computation/Storage, Hadoop Architecture (HDFS, YARN, Map-Reduce).
- **Hive:** Architecture, Data Types, SerDe (CSV, JSON, Parquet, ORC), Partitioning (Static/Dynamic), Bucketing, and Joins.

### 🔹 Module 3: Confluent Kafka & Real-Time Streaming
- **Architecture:** Brokers, Topics, Partitions, Replicas, Offset Management.
- **Programming:** Producer/Consumer API (Sync/Async), Serialisation/Deserialisation (JSON, CSV).
- **Cloud Integration:** GCP Pub-Sub Setup and Producer/Consumer implementation.

### 🔹 Module 4: NoSQL Databases (MongoDB & Cassandra)
- **MongoDB:** Atlas Setup, MongoDB Compass, Queries via Python, KSQLdb Integration.
- **Cassandra:** CAP Theorem, Architecture (SSTables, Mem-tables), Gossip Protocol, Consistency Levels, and CQL queries.

### 🔹 Module 5: Apache Spark (PySpark)
- **Core Spark:** RDDs, Dataframes, Spark Ecosystem, Narrow vs. Wide Transformations, Lazy Evaluation, DAGs.
- **Optimizations:** Caching/Persisting, Skewness Handling, Salting, Repartition vs. Coalesce, Memory Management.
- **Streaming:** Structured Streaming, Checkpointing, Watermarking, Windowed Aggregations (Tumbling/Sliding).

### 🔹 Module 6: Apache Airflow (Orchestration)
- **Core Concepts:** DAGs, Operators (Bash, Python), Tasks Dependency.
- **Cloud Composer:** Running DAGs on GCP, parallel tasks, and backfilling.

### 🔹 Module 7: Databricks & Delta Lake
- **Unity Catalog:** Governance, Managed vs. External Tables, Volumes.
- **Delta Lake:** ACID transactions, Time Travel, Schema Evolution, Delta Sharing.
- **DLT:** Delta Live Tables Medallion Architecture.

### 🔹 Module 8: Data Warehousing
- **Modeling:** Start Schema, Snowflake Schema, Galaxy Schema.
- **Concepts:** OLAP vs. OLTP, Fact & Dimension tables, SCD Types (SCD1, SCD2).
- **Case Studies:** Expedia & Swiggy Data Modeling.

### 🔹 Module 9: Snowflake & BigQuery
- **Snowflake:** SnowPipe for event-driven ingestion, Storage Integration.
- **BigQuery:** Architecture (Capacitor, Colossus, Dremel), External vs. Managed Tables, ML/AI features (Gemini integration).

### 🔹 Module 10: Open Table Formats (Iceberg & Hudi)
- **Apache Iceberg:** Metadata Layer, Manifests, CoW vs. MoR, Compaction.
- **Apache Hudi:** Incremental Pipelines, Multi-modal Indexes, Storage Layout.

### 🔹 Module 11: Apache Trino
- **Distributed SQL:** Architecture (Coordinator/Workers), Physical/Logical Plans, Connector ecosystem (MongoDB, GCS, etc.).

### 🔹 Module 12: Azure Cloud Services Deep Dive
- **Storage:** Blob, ADLS Gen2.
- **Serverless:** Azure Functions (HTTP/Blob/Service Bus triggers), Logic Apps.
- **Messaging:** Service Bus (Queues/Topics), Event Hubs.
- **Data Engineering:** Data Factory (ADF), DataFlows, Synapse Analytics (SQL Pools, Spark Pools).
- **Global Database:** Cosmos DB.
- **Governance:** Key Vault, RBAC.

---

## 🚀 Industrial Projects (15+)

1.  **Flight Booking Data Pipeline:** Airflow, PySpark, Dataproc, BigQuery, CI/CD.
2.  **E-commerce Event-Driven Pipeline:** Databricks, Delta Lake, Workflows.
3.  **Travel Booking SCD2 Warehouse:** Databricks, Unity Catalog, PyDeequ.
4.  **Healthcare DLT Medallion Pipeline:** Databricks Delta Live Tables.
5.  **UPI Transactions CDC Streaming:** PySpark Structured Streaming, Delta CDF.
6.  **News Data Analysis:** Snowflake, SnowPipe, Airflow, GCS.
7.  **Car Rental Batch Ingestion:** GCP Dataproc, Airflow, Snowflake.
8.  **Movie Booking Real-time Aggregation:** Snowflake Dynamic Tables & Streams.
9.  **Weather Forecast Processing:** OpenWeather API, Airflow, PySpark, BigQuery.
10. **Unified Stock Trading Platform:** Trino, MongoDB, BigQuery, Airflow.
11. **Fintech SQL Migration:** Azure Synapse, SQL DB, Logic Apps.
12. **AirBnB CDC Ingestion:** Azure Data Factory, Cosmos DB, Synapse, Agentic AI.
13. **BookMyShow Real-Time Pipeline:** Azure Event Hub, Stream Analytics, n8n.
14. **Airlines Incremental Processing:** Azure DevOps CI/CD, ADF, ADLS.
15. **Ride Analytics Pipeline (Uber/Ola Clone):** FastAPI, Docker, Cloud Run, Artifact Registry, GitHub Actions.

---

## 🛠️ Getting Started
Detailed setup instructions for each module are located within their respective directories. Ensure you have your Azure and GCP free tier accounts ready to follow along!

---
*Created with ❤️ for Data Engineers.*
