# 🏅 Paris Olympics Data Engineering Project

![Azure DevOps](https://img.shields.io/badge/CI%2FCD-Azure%20DevOps-blue)
![ADF](https://img.shields.io/badge/Data%20Pipeline-Azure%20Data%20Factory-0078D4)
![Databricks](https://img.shields.io/badge/ETL-PySpark%20%7C%20Delta%20Live%20Tables-orange)

## 📌 Overview
This project demonstrates the implementation of a **modern data engineering solution** on **Azure**, using the **Paris Olympics dataset**. The pipeline leverages **CI/CD practices via Azure DevOps**, combines **Azure Data Factory** for orchestration, **Databricks and PySpark** for ETL, and applies the **Medallion Architecture** to ensure robust, scalable, and maintainable data processing.

---

## 🚀 Tech Stack & Tools
| 🔧 **Tool**               | 💼 **Function** |
|-------------------------|----------------|
| 🔄 **Azure DevOps**     | Implements CI/CD to automate ADF pipeline deployment |
| ⚙️ **Azure Data Factory** | Manages orchestration of data ingestion and transformation workflows |
| 🔥 **Databricks (PySpark)** | Performs ETL using distributed processing |
| 🪙 **Delta Lake**        | Enables storage of structured and versioned data across Bronze, Silver, and Gold layers |
| 💡 **Delta Live Tables** | Automatically manages data quality, lineage, and dependencies in the Gold Layer |

---

## 🔄 Pipeline Architecture (Medallion Pattern)

1. **CI/CD Pipeline**
   - 🛠 Configured in **Azure DevOps** to manage version control and deployment of ADF pipelines

2. **Bronze Layer**
   - 📥 Raw data ingested into **ADLS** using **ADF**

3. **Silver Layer**
   - 🔍 Cleaned and enriched using **PySpark notebooks** in **Databricks**

4. **Gold Layer**
   - 🪙 Created using **Delta Live Tables** for high-quality, analytics-ready datasets

![OlympicArch](https://github.com/user-attachments/assets/00eda7e9-1e5f-4d46-97d3-9fb7d8186b9f)

---

## 🧪 ETL Process
- 📄 **Read** raw Paris Olympics data from source
- 🧹 **Transform** using PySpark: filtering, cleaning, and joining datasets
- 📝 **Write** intermediate outputs to ADLS following the Medallion architecture
- 🪄 **Delta Live Tables** applied on top of Silver Layer to automate creation of Gold Layer tables

---

## ✅ Key Highlights
- 🔁 **End-to-end CI/CD pipeline** using Azure DevOps for ADF
- 🔄 **ETL workflow using PySpark** ensures scalability and maintainability
- 🧱 **Medallion architecture** brings structure and clarity to data flow
- 🪙 **Delta Live Tables** automate high-quality data delivery

---

## 🔚 Conclusion
This project exemplifies a **cloud-native, scalable data engineering pipeline**, built for handling real-world data using modern architectural practices. The integration of **CI/CD**, **ADF orchestration**, **PySpark transformations**, and **Delta Live Tables** ensures a production-grade solution that is maintainable, efficient, and analytics-ready.

---

🚀 **Happy Building!**

