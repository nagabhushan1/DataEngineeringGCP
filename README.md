# Spark Lakehouse

This repository demonstrates a **Spark Lakehouse** built on the **Medallion Architecture** . It adopts **PySpark DataFrame**–driven ETL.

---

## High-Level Architecture

**Flow at a glance**

- **Sources**: Databases, flat files, APIs, and streaming inputs land as-is.  
- **Bronze**: Raw, append-only ingestion with minimal transformation; focuses on auditability and replay.  
- **Silver**: Cleansed, standardized, and conformed tables with business-ready columns and keys.  
- **Gold**: Curated marts and aggregates tailored for BI dashboards, analytics and reporting.  


---

## Lakehouse Architecture Components

- **Data Storage**: Cloud object storage.
- **Compute & ETL**: Spark clusters running batch and pipelines using PySpark DataFrame API.
- **Serving**: SQL warehousing for BI, ML/feature stores, and APIs/exports for downstream systems.

---


