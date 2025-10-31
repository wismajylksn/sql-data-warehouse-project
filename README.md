# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏛️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:


Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis. 
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

## 📖 Project Overview
This project involves:

- **Data Architecture:** Designing a Modern Data Warehouse Using Medallion Architecture (Bronze, Silver, Gold layers).
- **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase expertise in:

- SQL Development
- Data Architect
- Data Engineering
- ETL Pipeline Developer
- Data Modeling
- Data Analytics

## 🛠️ Important Links & Tools
Everything is for Free!

- [Datasets](https://github.com/DataWithBaraa/sql-data-warehouse-project/blob/main/datasets): Access to the project dataset (csv files).
- [SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads): Lightweight server for hosting your SQL database.
- [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16): GUI for managing and interacting with databases.
- [Git Repository](https://github.com/): Set up a GitHub account and repository to manage, version, and collaborate on your code efficiently.
- [DrawIO](https://www.drawio.com/): Design data architecture, models, flows, and diagrams.
- [Notion](https://www.notion.com/templates/sql-data-warehouse-project): Get the Project Template from Notion
- [Notion Project Steps](https://thankful-pangolin-2ca.notion.site/SQL-Data-Warehouse-Project-16ed041640ef80489667cfe2f380b269?pvs=4): Access to All Project Phases and Tasks.


## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

**Objective**

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

**Specifications**

- **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

**Objective**

Develop SQL-based analytics to deliver detailed insights into:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

For more details, refer to docs/requirements.md.

---

## 🗂️ Repository Structure

```bash
data-warehouse-project/
│
├── datasets/                      # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                          # Project documentation and architecture details
│   ├── etl.drawio                 # ETL process diagram (staging → silver → gold)
│   ├── data_architecture.drawio   # Overall project architecture
│   ├── data_catalog.md            # Dataset catalog with field descriptions
│   ├── data_flow.drawio           # Data flow diagram from source to analytics
│   ├── data_models.drawio         # Star schema data model (fact & dimension tables)
│   └── naming_conventions.md      # Standard naming conventions for tables and columns
│
├── scripts/                       # SQL scripts for ETL and transformations
│   ├── bronze/                    # Scripts for extracting and loading raw data
│   ├── silver/                    # Scripts for cleaning and transforming data
│   └── gold/                      # Scripts for creating analytical models
│
├── tests/                         # Test scripts and data quality checks
│
├── README.md                      # Project overview and documentation
├── LICENSE                        # License information for the repository
├── .gitignore                     # Files and directories ignored by Git
└── requirements.txt               # Dependencies and requirements for the project
```

---

## 🛡️ License

This project is licensed under the MIT License.  
You’re free to use, modify, and share this project with proper attribution.

---

## 🌟 About Me

Hi there! 👋  
I’m Wisma Jaya Laksana, a passionate learner and aspiring Data Engineer from Jakarta.

I enjoy exploring data engineering, SQL, and analytics, and I’m currently building projects to strengthen my understanding of modern data architecture—from ETL pipelines to insightful analytics dashboards.

I believe that learning by building is the best way to grow, and this project is part of that journey 🚀

### 📫 Let’s Connect:
- 💼 [LinkedIn](#)
- 💻 [GitHub](#)
- ✉️ [Email](#)
