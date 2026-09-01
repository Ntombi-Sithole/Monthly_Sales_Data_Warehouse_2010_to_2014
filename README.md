# Data Warehouse Project

Welcome to the Data Warehouse and Analytics Project repository! This portfolio project showcases a complete data warehousing and analytics solution—from designing and building the data warehouse to producing actionable insights. It demonstrates industry best practices in data engineering and analytics.

---
## Business Problem & Project Objective
* **The Challenge:** Enterprise data was fractured across two completely separate source systems: an *ERP system* and a *CRM system* (delivered via raw CSV files). Siloed datasets prevented leadership from achieving a single, unified view of business sales and customer metrics.
* **The Solution:** Developed a centralized, high-performance local Data Warehouse using *SQL Server Express*. Implemented a structured multi-layer architecture to clean, standardize, and model the data for executive-level analytical reporting.

---
## Data Architecture

<img width="962" height="578" alt="architecture drawio" src="https://github.com/user-attachments/assets/bca462f0-85cf-4e0c-92af-208bc14677b7" />

1. **Bronze Layer (Raw Ingestion):** Ingested raw datasets directly from the ERP and CRM systems into staging tables with minimal schema modification.
2. **Silver Layer (Cleanse & Transform):** Cleansed and standardized disparate records. Resolved data quality anomalies, aligned mismatched customer data across CRM/ERP, and normalized structural definitions.
3. **Gold Layer (Analytical Modeling):** Transformed cleaned tables into a business-ready *Star Schema* optimized for downstream Business Intelligence tools.
---
## Tech Stack & Tools
* **Database Engine:** SQL Server Express
* **Database Administration & Queries:** SQL Server Management Studio (SSMS)
* **Architecture & Data Modeling:** Draw.io
* **Project Management & Lifecycle Tracking:** Notion


## Key Features & Implementation
* **Data Integration:** Consolidated duplicate and overlapping records between legacy ERP and CRM source tables into single core entities.
* **Dimensional Modeling:** Engineered a structured *Star Schema* in the Gold Layer consisting of optimized Fact and Dimension tables.
* **Performance Handling:** Designed primary and foreign key structures to enable fast analytical queries while maintaining strict relational data integrity.
* **Project Governance:** Used Notion to actively plan out project steps, deadlines, data quality rules, and system mapping documentation.

---

## License
This project is licensed under the MIT License. You are free to use, modify, and share this project with proper attribution.


## About Me

Hi, I'm **Ntombikayise Sithole**
I am an aspiring Data Engineer with a background in Business Management and Finance. I am passionate about building efficient systems and solving complex technical challenges. I focus on continuous learning and practical application, which drives me to build hands-on projects like this one to expand my technical skill set.

---

## Acknowledgements
- This project was built as a hands-on practice initiative to sharpen my technical skills in Data Engineering.
- Guided instructions and architecture concepts were provided by @DataWithBaraa's step-by-step tutorial.
