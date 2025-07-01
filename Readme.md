# Data Warehouse Platform Development (Databricks, PySpark, Delta Lake)

Welcome to the **Data Warehouse Platform Development** project! 🚀  
This project showcases how to **design, build, and deploy** a modern cloud-based data warehouse on Databricks with a strong focus on **automation, modular ETL development, cloud integration, and scalable architecture**.  

As a Development Engineer portfolio project, it demonstrates **end-to-end pipeline design, CI/CD-style orchestration, and production-grade engineering best practices**.


---

## 🏗️ System Architecture

This platform follows the **Medallion Architecture** on Delta Lake with three modular layers stored in GCS:

- **Bronze Layer**: Ingest raw ERP and CRM datasets as Delta tables.
- **Silver Layer**: Transform and standardize data with quality checks and audit logging.
- **Gold Layer**: Star-schema data model optimized for BI tools and reporting.

It is designed for **scalability, maintainability, and clear separation of concerns** to support real-world production use cases.


---

## ⚙️ Key Features

- 🌐 **Cloud-Native Integration**: Built on Google Cloud Storage and Databricks, leveraging Delta Lake for versioned data management.
- 🏗️ **Modular ETL Pipelines**: PySpark-based ETL jobs with clear layer separation and reusable transformation logic.
- 🔄 **Automated Orchestration**: Databricks Workflows to schedule, monitor, and manage pipeline execution like CI/CD for data.
- 📈 **Data Modeling**: Fact and dimension tables in a Star Schema for analytical workloads.
- 🧪 **Data Quality & Audit Logs**: Integrated audit logging for traceability and reliability.
- 📜 **Documentation-First Approach**: Well-defined data catalog, integration diagrams, and ETL specs.

---

### 🧱 Data Engineering

**Goal**: Develop a production-grade, cloud-native data platform to consolidate, transform, and analyze ERP and CRM sales data.

- **Infrastructure as Code Mindset**: Modular, maintainable PySpark jobs and workflow configurations.
- **Automation**: Automated scheduling and monitoring with Databricks Workflows.
- **Cloud Integration**: Storage on GCS with Delta Lake's ACID guarantees.
- **Scalability**: Handle large datasets with optimized transformations and Delta Lake storage.
- **Maintainability**: Layered architecture, clean code, and audit logging to support evolving business needs.

---

## 📂 Repository Structure
```
Databricks/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── Data_flow.png                   # This image file for the data flow diagram
|   |-- Data_Integration.png            # This image shows the integration between the CRM and ERP sources
│   ├── Data_Mart.png                   # This image file for data models (star schema)
│
├── notebooks/                          # PySpark notebooks for ETL jobs
│   ├── bronze/                         # Ingestion and raw layer
│   ├── silver/                         # Cleaning and standardization
│   ├── gold/                           # Analytical model creation
│
├── README.md                           # Project overview and instructions
```

---

## 🧾 License

This project is licensed under the [MIT License](LICENSE).  
Feel free to use, modify, and share this project with proper attribution.


---

## 🙋 About the Author

Hi! I'm **Deepankar Singh**, a cloud-focused Development Engineer and data enthusiast.  
This project is part of my personal portfolio to demonstrate **production-grade engineering, data pipeline development, and cloud-native architecture** skills.

📫 Let's connect:
- [LinkedIn](www.linkedin.com/in/deepankar-singh-a35b14296)
- [GitHub](https://github.com/CodewithDeep23)

---

If you found this project helpful, feel free to ⭐ the repo!