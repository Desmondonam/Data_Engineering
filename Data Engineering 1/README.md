# Data Engineering Curriculum
# 1: Foundations
### 1. Introduction to Data Engineering
- What is Data Engineering?

- Role of a Data Engineer.

- Difference between Data Engineering, Data Science, and Data Analysis.

- Data Engineering Workflow:

    - Data ingestion, storage, transformation, and analysis.

- Key Concepts:

    - Data pipelines, ETL (Extract, Transform, Load), ELT (Extract, Load, Transform).

### 2. Programming Basics
- Python for Data Engineering:

    - Basics of Python (syntax, data structures, functions).

    - Libraries: Pandas, NumPy, Requests.

    - Working with APIs (e.g., HubSpot API).

- SQL Fundamentals:

    - Basic queries (SELECT, INSERT, UPDATE, DELETE).

    - Joins, aggregations, and subqueries.

### 3. Data Storage and Databases
- Relational Databases:

    - Introduction to SQL databases (e.g., MySQL, PostgreSQL).

    - Database design and normalization.

- Cloud Data Warehousing:

    - Introduction to Snowflake.

- Key features: scalability, separation of storage and compute.

## 2: Data Integration and ETL/ELT
### 1. Data Integration Tools
- Airbyte:

    - Introduction to Airbyte (open-source data integration).

    - Setting up connectors for data sources (e.g., HubSpot, APIs, databases).

    - Building data pipelines with Airbyte.

- HubSpot Integration:

    - Extracting data from HubSpot (CRM, marketing, sales data).

    - Using HubSpot APIs for custom data extraction.

### 2. Data Transformation
- DBT (Data Build Tool):

    - Introduction to DBT.

    - Building data transformation pipelines.

    - Writing SQL models and tests in DBT.

    - Version control and collaboration in DBT.

### 3. Data Orchestration
- Introduction to Orchestration Tools:

    - Apache Airflow (scheduling and monitoring workflows).

    - Prefect (modern workflow orchestration).

## 3: Data Analysis and Visualization
### 1. Excel for Data Analysis
- Data Cleaning and Preparation:

    - Removing duplicates, handling missing data.

- Data Analysis:

    - Pivot tables, charts, and conditional formatting.

- Advanced Excel:

    - VLOOKUP, HLOOKUP, INDEX-MATCH.

    - Macros and VBA for automation.

### 2. Data Visualization
- Introduction to BI Tools:

    - Tableau, Power BI, or Looker.

- Creating Dashboards:

    - Connecting to Snowflake and visualizing data.

## 4: Advanced Topics
### 1. Cloud Computing
- AWS/GCP/Azure Basics:

    - Cloud storage (S3, Google Cloud Storage).

    - Compute services (EC2, Lambda).

    - Data services (RDS, BigQuery).

- Snowflake Deep Dive:

    - Snowflake architecture and best practices.

    - Snowflake SQL and performance optimization.

### 2. Big Data Tools
- Introduction to Big Data:

    - Hadoop ecosystem (HDFS, MapReduce).

    - Apache Spark (distributed data processing).

- Streaming Data:

    - Apache Kafka (real-time data streaming).

### 3. Data Governance and Security
- Data Governance:

    - Data quality, metadata management.

- Data Security:

    - Encryption, access control, compliance (GDPR, HIPAA).

## 5: Capstone Project
### End-to-End Data Engineering Project
- Objective: Build a complete data pipeline using HubSpot, Airbyte, Snowflake, DBT, and Excel.

#### Steps:

- Data Ingestion:

    - Extract data from HubSpot using Airbyte.

- Data Storage:

    - Load data into Snowflake.

- Data Transformation:

    - Transform data using DBT.

- Data Analysis:

    - Analyze data in Snowflake and Excel.

- Visualization:

    - Create dashboards in Tableau or Power BI.

- Automation:

    - Schedule and monitor the pipeline using Airflow or Prefect.