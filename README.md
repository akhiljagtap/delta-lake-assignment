# Delta Lake Assignment

## Overview
This project demonstrates incremental data processing using **Delta Lake** in **Azure Databricks** with **PySpark**. The workflow includes data loading, cleaning, creating an incremental dataset, performing MERGE (SCD Type 1), validating the results, and displaying the final dataset.

## Technologies Used
- Azure Databricks
- PySpark
- Delta Lake

## Project Workflow
1. Load the Superstore dataset.
2. Perform basic data cleaning.
3. Create an incremental dataset with updated and new records.
4. Apply Delta Lake MERGE (SCD Type 1).
5. Validate row count and duplicate records.
6. Display the final dataset and summary.

## Project Structure
```
delta-lake-assignment/
├── data/
├── notebooks/
├── screenshots/
└── README.md
```

## Features
- Data Cleaning
- Delta Table Creation
- Incremental Data Processing
- MERGE (SCD Type 1)
- Data Validation
- Final Dataset Summary
