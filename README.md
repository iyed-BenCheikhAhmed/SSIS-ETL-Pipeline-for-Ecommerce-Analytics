#  Ecommerce Data Warehouse ETL Pipeline with SSIS

![SSIS](https://img.shields.io/badge/Microsoft-SSIS-0078D4?logo=sqlserver&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-2019+-CC2927?logo=microsoftsqlserver)
![License](https://img.shields.io/badge/License-MIT-green)



##  Project Overview
A comprehensive **SQL Server Integration Services (SSIS)** solution that:
1. Extracts data from operational ecommerce database (`EcommerceDB`)
2. Transforms through staging area (`EcommerceStaging`)
3. Loads into star schema warehouse (`EcommerceDW`)

**Key Features**:
✅ Slowly Changing Dimensions (Type 2)  
✅ Error handling with logging  
✅ Incremental loading capabilities  
✅ Data quality validation checks  


⚙️ **ETL Process Flow**:
Extract Phase:

 -Full/delta load from source tables

 -Preserve raw data in staging

Transform Phase:

 -Handle SCD Type 2 for dimensions

-Data cleansing and standardization

 -Surrogate key generation

Load Phase:

 -Fact table loading with proper grain

 -Referential integrity validation


