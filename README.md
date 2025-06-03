
# Azure Data Platform Project: End-to-End Data Pipeline with Unity Catalog

This repository demonstrates a modular, production-ready data platform built on **Azure** and **Databricks**, featuring an end-to-end data pipeline architecture with **Unity Catalog** for secure governance.

##  Project Structure

```

📁 set-up/                    → Initial resource configuration & environment setup  
📁 ingestion/                 → Data ingestion scripts (e.g. Azure Data Factory, Databricks AutoLoader)  
📁 raw/                       → Raw data zone definitions (Bronze layer)  
📁 trans/                     → Transformation logic (Silver/Gold layer ETL scripts)  
📁 analysis/                  → Analytical workflows, aggregations & KPI dashboards  
📁 demo/                      → Demo datasets or notebook-based walkthroughs  
📁 includes/                  → Shared config, parameters, constants  
📁 utils/                     → Utility functions and helper modules  
📁 unity-catalog-introduction/ → Basics of Unity Catalog & governance setup   
📁 unity-catalog-capabilities/ → Access control, lineage, schema enforcement examples  
📁 unity-catalog-mini-project/ → A mini project using Unity Catalog on a small dataset  

```

##  Technologies Used

- **Azure Data Factory** (ADF) – Batch ingestion from SQL sources  
- **Azure Data Lake Gen2** – Staging, raw, and curated storage zones  
- **Databricks** – Notebooks, AutoLoader, Delta Lake, PySpark transformations  
- **Unity Catalog** – Centralized governance, fine-grained access control  
- **Python** – Transformation and utility scripts  
- **SQL** – Analytical queries & transformations

##  Key Features

- Modular folder-based pipeline
- Multi-layer architecture (Bronze → Silver → Gold)
- Unity Catalog security policies and usage examples
- Reusable utilities for data quality and monitoring
- Demo notebooks and mini-projects for hands-on practice

##  Who is this for?

This repository is ideal for:

- Data engineers working with Azure and Databricks
- Learners exploring modern data lakehouse architectures
- Teams implementing Unity Catalog for secure governance
- Professionals preparing for data engineer interviews

##  Getting Started

1. Clone the repository  
2. Follow `set-up/README.md` to configure your Azure + Databricks environment  
3. Start from `unity-catalog-introduction/` if you’re new to Unity Catalog  
4. Explore `ingestion/` and `trans/` for pipeline implementation  
5. Check `analysis/` for visualization or reporting logic

---

##  Future Work

- Stream ingestion with Event Hub
- CI/CD with GitHub Actions for Databricks Notebooks
- Metadata lineage with Unity Catalog APIs

---

##  License

MIT License. See `LICENSE` for details.

---

> Built with ❤️ to explore enterprise-grade data solutions on Azure + Databricks.




