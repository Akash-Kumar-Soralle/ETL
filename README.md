## 📌 Overview
This repository contains an ETL (Extract, Transform, Load) project developed using **SQL Server Integration Services (SSIS)**. The project demonstrates how to design, build, and execute ETL pipelines for moving and transforming data between source systems and target databases.

## 🛠️ Tools & Technologies
- SQL Server Integration Services (SSIS)
- SQL Server Database
- Visual Studio (SSDT)
- T-SQL

## 📂 Project Structure
- `ETL_Project2.dtproj` → SSIS Project configuration file  
- `Package1.dtsx` → ETL package handling data extraction, transformation, and loading  
- `Package.dtsx` → Another ETL package with additional transformations  
- `ETL_Project5.database` → Database configuration file for project  
- `Project.params` → Parameter file for runtime values  

## 🔄 ETL Process Flow
1. **Extract**  
   - Pulls raw data from source systems (e.g., CSV, Excel, or SQL Server tables).  

2. **Transform**  
   - Cleans, standardizes, and applies business rules (data type conversion, lookup, merging).  

3. **Load**  
   - Loads transformed data into a target SQL Server database for reporting and analysis.  

## 📊 Use Case Example
- Example scenario: Moving raw sales data into a data warehouse, applying currency conversion, removing duplicates, and generating fact/dimension tables for reporting.  

## 🚀 How to Run
1. Clone this repository.  
2. Open the `.dtproj` file in Visual Studio (SQL Server Data Tools).  
3. Configure connection managers for your source and target databases.  
4. Deploy and run the `.dtsx` packages in SSIS.  

## 📈 Results
- Automated ETL workflows reduce manual data processing.  
- Clean and standardized data is ready for BI tools (Power BI, Tableau, etc.).  
- Flexible design supports parameterization for multiple environments. 
