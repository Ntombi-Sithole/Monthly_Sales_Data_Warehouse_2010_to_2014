## Data Dictionary for Gold Layer

## Overview
The Gold Layer provides a business-oriented view of the data, designed to support reporting and analytics. It includes dimension and fact tables organized around specific business metrics

---

## 1. gold.dim_customers
* **Purpose:** Stores Customer Information enriched with geographic and demographic data.
* **Columns:**

| **Column Name**| **Data Type**| **Description**|
| :---| :---| :---|
| customer_key  | INT | Surrogate key uniquely identifying each customer record in the dimension table. |
