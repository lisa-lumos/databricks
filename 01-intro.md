# Azure databricks intro
The core of Azure Databricks is Apache Spark. Databricks is a company created by teh founders of Apache Spark, to make it easier to work with Spark by providing necessary management layers. 

Microsoft makes databricks service available on it Azure cloud platform as a first party service. 

You can spin up clusters easily in databricks. You can choose the runtime, and choose from a wide range of cluster types, such as general purpose, memory optimized, compute optimized, or GPU enabled, etc.

It provides a Jupyter Notebook style IDE, with additional capabilities to create your application. 

You can collaborate with other colleagues, and integrate with configuration management tools, such as Git. 

Admin controls allow you to restrict/provide access to users/workspaces/clusters, etc. 

Databricks provides the Spark runtime, which is highly optimized for the databricks platform, and is up to 5x faster than the vanilla Apache Spark. 

With metastore, databricks also provides the ability to create databases, tables, etc. 

It comes with the open source project Delta lake.

It has SQL Analytics, which provides a sql based analytics environment. They can explore data, create dashboards, schedule regular refresh of the dashboards, etc. 

It has managed ML flow, which allows us to manage the machine learning lifecycle, including experimentation, deployment, model registry, etc. 

databricks is available on all 3 major cloud platforms. But Azure's integration is deeper than others - databricks is a first party service on Azure.

On Azure you will be buying databricks directly from Microsoft and all support requests are handled by Microsoft. As a result, it provides a unified Azure Portal for databricks and a single unified bill for all your Azure services, including databricks. 

Azure databricks provides seamless integration between various Azure data services, such as Azure Data Lake, Blob Storage, Cosmos DB, SQL DB and Synapse, Messaging services such as Event Hub and IoT Hub, Power BI and Azure ML. You can seamlessly run databricks notebooks from Azure Data Factory, and integrate with the rest of the data workflow in your data project. It also connects with Azure DevOps. 
