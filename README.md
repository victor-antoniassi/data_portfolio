# My Data Portfolio
## 👋 About
Welcome to my data portfolio! I'm a data professional with experience in building data pipelines, data warehousing, data reporting and analytics solutions. This repository showcases some (but not all) of my knowledge in Business Intelligence, Data Analysis, and Data Engineering.

## 🚀 Latest Project

### [Postgres to Databricks CDC Pipeline](#2-chinook-sales-simulator)
A high-performance Data Ingestion Project built with the Python dlt library. It is designed to move data from PostgreSQL to Databricks using CDC (Change Data Capture) for efficient synchronization.
Orchestrated natively by Databricks Lakeflow Jobs, this project serves as a robust blueprint for enterprise data replication.

## 🗂️ Technical Assessment Projects
Projects developed as part of technical assessment processes, demonstrating comprehensive problem-solving abilities and technical skills.

### 1. [Video Game Sales](https://github.com/victor-antoniassi/junior_data_analyst_test_01) 🎮
*Data Analyst position at a food delivery platform, developed in September 2024*

A project that analyzes video game sales data to evaluate gaming partnership opportunities.

**Features**
- Data extraction automation
- Data preparation and cleaning
- Regional sales analysis
- Genre market share calculation
- Platform performance tracking

**Tech Stack**
- Python
- DuckDB
- Prefect
- Pandas
- wget
- Jupyter Notebook

**Skills Applied**
- Data/file extraction
- Data preparation
- SQL analysis
- Data workflow orchestration

### 2. [School Supplies Market](https://github.com/victor-antoniassi/junior_analytics_engineer_test_01)📚
*Analytics Engineer position at a Brazilian e-commerce company, developed in March 2024*

A data preparation project focusing on standardizing and integrating e-commerce school supplies sales data for planning purposes.

**Features**
- Automated header validation system
- Data quality analysis and standardization
- SQLite database implementation

**Tech Stack**
- Python
- SQLite
- Pandas
- Google Sheets

**Skills Applied**
- Data preparation and cleaning
- Database operations
- ETL processes
- Business analytics

## 💡 Code Snippets & Practice Projects
Smaller-scale projects and code examples showcasing specific technical skills and tools implementation.

### 1. [Cryptocurrencies Quotes](https://github.com/victor-antoniassi/coinmarketcap_api_to_duckdb) 💰
An EL (Extract, Load) pipeline that fetches market data (price, volume, market cap) for BTC, ETH, and LTC from CoinMarketCap API and stores it in DuckDB.

**Features**
- Automated data extraction from CoinMarketCap API
- Error handling and logging system
- Data storage in DuckDB database

**Tech Stack**
- Python 3.9+
- dlt
- DuckDB
- CoinMarketCap API

**Skills Applied**
- API integration
- Data pipeline development
- SQL querying

### 2. [Chinook Sales Simulator](https://github.com/victor-antoniassi/day-1_sales_data_generator)
A synthetic D-1 sales data generator for the Chinook database, simulating realistic daily transactions for data engineering practice.

**Features**
- Simulates the full data lifecycle: INSERT, UPDATE, and DELETE.
- Models UPDATEs/DELETEs as late-arriving changes within a 90-day window.
- Ensures ACID compliance (all-or-nothing) for each D-1 batch.
- Includes a verification script to audit simulation logs against the DB state.

### 3. [Postgres to Databricks CDC Pipeline](https://github.com/victor-antoniassi/postgres-to-databricks-cdc/)
A high-performance Data Ingestion Project built with the Python dlt library. It is designed to move data from PostgreSQL to Databricks using CDC (Change Data Capture) for efficient synchronization.
Orchestrated natively by Databricks Lakeflow Jobs, this project serves as a robust blueprint for enterprise data replication.
