# Olympics Data Engineering Project

This project is focused on analyzing the **Tokyo Olympics dataset** using modern cloud data engineering tools. We utilize **Azure Data Factory**, **Azure Synapse Analytics**, **Azure Databricks**, and **SQL** to ingest, transform, and visualize Olympic data.

## Dataset

The dataset is sourced from Kaggle and contains several tables including:
- `medals`: Medal counts by country
- `entries_gender`: Gender participation by discipline
- `coaches`: Coach details by NOC and discipline
- `teams`: Team entries by event
- `athletes`: Athlete participation by country and sport

## Tools & Technologies

- **Azure Storage Account**: For storing raw and cleaned data
- **Azure Data Factory**: For orchestrating data pipelines
- **Azure Synapse Analytics**: For querying and transforming data using SQL
- **Azure Databricks**: For advanced data transformation (optional)
- **Git/GitHub**: For version control and collaboration

## 📊 Features

- Ingest `.csv` files from Azure Blob Storage
- Use Data Factory to copy and transform data
- Query using Synapse SQL scripts
- Perform analysis on:
  - Medal distribution
  - Gender participation
  - Country-wise performance
  - Coach and team statistics

