🏅 Olympic Data Analytics – End-to-End Azure Data Engineering Project

📌 Project Overview
This project demonstrates an **end-to-end Data Engineering pipeline** built on **Microsoft Azure** using **Tokyo Olympics datasets**.  
The goal was to ingest raw data, perform cleaning and transformation, and analyze insights using modern cloud data engineering tools.

---

🛠️ Tech Stack / Azure Services Used
- **Azure Data Lake Gen2** – Storage for raw & transformed data
- **Azure Data Factory** – Data ingestion & orchestration
- **Azure Databricks (Spark)** – Data cleaning, transformation & schema validation
- **Azure Synapse Analytics** – SQL-based analytics & querying
- **Python (PySpark)** – Transformation logic in Databricks

---

🔄 Data Pipeline Workflow
1. 📥 Ingested CSV datasets (`Athletes`, `Coaches`, `Teams`, `Entries by Gender`, `Medals`) into **Azure Data Lake (Raw Zone)** using Data Factory.  
2. ⚙️ Used **Databricks** notebooks (PySpark) to clean, validate, and transform data into the **Transformed Zone**.  
3. 🗄️ Stored processed data back into **Data Lake Gen2**.  
4. 📊 Connected **Azure Synapse Analytics** to query & analyze data (medal counts, athlete participation, gender statistics, etc.).  
5. 🔗 Designed a complete **ETL pipeline** from raw → transformed → analytics.  

---

📚 Learnings & Outcomes
- Hands-on with **end-to-end Data Engineering workflows** on Azure.  
- Built practical **ETL pipelines** with Data Factory & Databricks.  
- Organized data in **raw vs transformed zones** for scalability.  
- Applied **PySpark** for large-scale data cleaning & transformation.  
- Used **Synapse SQL** for querying and insights generation.  
