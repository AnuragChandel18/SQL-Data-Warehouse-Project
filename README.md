# Data Warehouse Project

A modern Data Warehouse project built using **SQL Server** to transform raw ERP and CRM sales data into a structured analytical database for reporting and business analysis.

## 🏗️ Data Architecture

The project follows a **Medallion Architecture** with three layers:

- **Bronze:** Stores raw data loaded from CSV files.
- **Silver:** Cleans, standardizes, and transforms the raw data.
- **Gold:** Contains business-ready fact and dimension tables organized using a Star Schema.

![Data Architecture](docs/data_architecture.png)

## 📌 Project Objectives

- Build a modern SQL Server Data Warehouse.
- Load data from ERP and CRM CSV files.
- Perform ETL processes using SQL.
- Clean and validate data.
- Integrate data from multiple source systems.
- Design fact and dimension tables using a Star Schema.
- Create SQL-based analytics for business reporting.

## 🛠️ Technologies Used

- SQL Server
- SQL Server Management Studio (SSMS)
- SQL
- ETL
- Data Modeling
- Star Schema
- Git & GitHub
- Draw.io

## 📊 Analytics

The Gold layer is used to analyze:

- Customer behavior
- Product performance
- Sales trends
- Revenue and sales metrics

## 📂 Project Structure

```text
SQL-Data-Warehouse-Project/
│
├── datasets/
│   └── ERP and CRM CSV files
│
├── docs/
│   ├── data_architecture.drawio
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   └── data_catalog.md
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── tests/
│
├── README.md
├── LICENSE
└── .gitignore
