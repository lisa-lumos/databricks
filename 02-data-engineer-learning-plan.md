# Data Engineer Learning Plan
## Data Ingestion with Lakeflow Connect
Built-in connectors inside the platform
- Upload Files. manual. 
- Standard Connectors. S3, kafka. batch/incremental-batch/streaming. 
- Managed Connectors. Saas-apps/databases. efficient incremental reads/writes. 

Ingestion methods:
- batch ingestion: all data is re-ingested each run. 
- incremental batch ingestion: only new data in ingested. 
- streaming ingestion. continuous loads as data is generated. near real-time. micro-batch. 

Delta Lake. Open source protocol, read/write files to cloud storage as UC tables. 

UC tables store data as parquet files, in a folder directory. 
- acid transactions
- dml
- time travel
- schema evolution/enforcement
- ...

Delta Lake loads json logs (track transactions, table versions) along the files. 

Medallion architecture: ingest -> data processing/transformation (bronze, silver, gold) -> consumers. 

Catalog -> schema -> tables/views/volumes...

```sql
describe schema extended my_schema; -- show owner, etc
describe table extended my_table; -- show owner, columns, created time, row count, location (s3://... if aws), table type (managed/external)  etc
describe volume my_catalog.my_schema.my_volume; -- show owner, location, etc
list '/Volumes/catalog_name/schema_name/volume_name/.../folder_name'; -- list files in a folder
```














## Deploy Workloads with Lakeflow Jobs



## Build Data Pipelines with Apache Spark Declarative Pipelines



## DevOps Essentials for Data Engineering



## Advanced Techniques with Apache Spark Declarative Pipelines



## Databricks Data Privacy



## Databricks Performance Optimization



## Automated Deployment with Declarative Automation Bundles





















