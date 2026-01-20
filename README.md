# 2.4 Set Up GitHub Repository

## Project Overview
This repository is part of my coursework in data engineering and analytics using **Databricks**, **Python**, and **SQL**.  
The goal of this project is to practice building **reproducible, well-documented ETL workflows** while following industry-style repository organization.

The project focuses on:
- Extracting structured data from CSV files
- Cleaning and transforming data using Pandas and/or PySpark
- Loading processed data into structured outputs
- Applying logging, reproducibility, and version control best practices
- Integrating Databricks notebooks directly with GitHub

This repository is designed to grow throughout the course as new ETL concepts, automation steps, and analytics techniques are introduced.

---

## Repository Structure
```
├── notebooks/
├── sql/
├── etl_pipeline/
├── data_samples/
└── README.md
```

### Folder Descriptions

#### 📒 notebooks/
Contains **Databricks or Jupyter notebooks** used for ETL tasks, data exploration, logging, and reproducibility labs.  
These notebooks are connected directly to Databricks and version-controlled through GitHub.

#### 🗄️ sql/
Holds **standalone SQL scripts** used for transformations, table creation, validation queries, or analytics.  
Keeping SQL separate allows reuse across notebooks and workflows.

#### ⚙️ etl_pipeline/
Contains **Python scripts or workflow-related files** that represent ETL logic outside of notebooks.  
This folder is intended for automation, scheduled jobs, or modular ETL components.

#### 📊 data_samples/
Stores **small sample datasets** (such as CSV files) used for testing and development.  
These datasets are intentionally lightweight to support reproducibility and fast iteration.

#### 📄 README.md
Provides an overview of the project, explains the repository structure, and documents how to run or reproduce the work.

---

## How This Project Is Used
- The repository is connected directly to **Databricks Repos**
- All notebook changes are committed and pushed from Databricks to GitHub
- Logging and reproducibility practices are applied to ensure consistent results
- GitHub is used to track changes, branches, and collaboration history

---

## Tools & Technologies
- Databricks
- Python (Pandas, logging, hashlib)
- SQL
- Git & GitHub
- Jupyter / Databricks Notebooks

---

## Purpose
The purpose of this repository is to demonstrate **organized, reproducible, and ethical data engineering practices**, preparing for more advanced analytics and AI workflows later in the course.

> “Let all things be done decently and in order.” — 1 Corinthians 14:40