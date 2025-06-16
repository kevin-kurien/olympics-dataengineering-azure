# 🏅 Olympics Data Engineering Project

This project is focused on analyzing the **Tokyo Olympics dataset** using modern cloud data engineering tools. We utilize **Azure Data Factory**, **Azure Synapse Analytics**, **Azure Databricks**, and **Power BI** (optional) to ingest, transform, and visualize Olympic data.

## 📁 Dataset

The dataset is sourced from Kaggle and contains several tables including:
- `tbl_medals`: Medal counts by country
- `tbl_entries_gender`: Gender participation by discipline
- `tbl_coaches`: Coach details by NOC and discipline
- `tbl_teams`: Team entries by event
- `tbl_athletes`: Athlete participation by country and sport

## 🔧 Tools & Technologies

- **Azure Storage Account**: For storing raw and cleaned data
- **Azure Data Factory**: For orchestrating data pipelines
- **Azure Synapse Analytics**: For querying and transforming data using SQL
- **Azure Databricks**: For advanced data transformation (optional)
- **Power BI**: For visualization (optional but recommended)
- **Git/GitHub**: For version control and collaboration

## 📊 Features

- Ingest `.csv` files from Azure Blob Storage
- Use Data Factory to copy and transform data
- Query using Synapse SQL scripts
- Perform advanced analysis on:
  - Medal distribution
  - Gender participation
  - Country-wise performance
  - Coach and team statistics
- Visualize insights using Synapse Studio or Power BI

## 💻 Project Structure

```text
📂 olympics-dataengineering-azure/
├── 📁 data/                  # Raw and cleaned CSV files
├── 📁 notebooks/             # Jupyter/Databricks notebooks
├── 📁 synapse-sql/           # SQL scripts used in Azure Synapse
├── 📁 powerbi/               # Power BI reports (if used)
├── 📄 Tokyo Olympic Transformation.ipynb
├── 📄 README.md
└── 📄 .gitignore
