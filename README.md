# Data Repositories Overview
  
#### Table of Contents:
  
1. [Six Data Repository Types/Architectures](#data-repository)
2. [Data-Characteristic Terms](#data-terms)
  
<hr />
  
## 1. <a name="data-repository">Six Data Repository Types/Architectures</a>
  
* **Data Fabric:** Allows for distributed data to be quickly and easily accessed, managed, and integrated, uniting data from various sources and providing integration, orchestration, governance, and virtualization.
  + Data silos (data that are disconnected from other parts/units of an organization and its system) can have their data analyzed and readily accessed to support concentrated and informed decision-making.
* **Data Lake:** Stores structured, semi-structured, *and* unstructured ('raw') data in a large and centralized manner. Pulls data from multiple (or even many) sources, for both analysis and processing purposes.
  + Data models and schemas are not applied here (in this regard, the data are in their native formats).
    - This allows for quick and adaptive data analysis and reading. Machine learning and complex analytics/reporting that are capable of pulling from various kinds of data can benefit from data lake integrations.
* **Data Mart:** A data warehouse subset that is of specialized purpose (and smaller in size and scope, due to its subject-concentrated nature).
  + Data marts are intended to satisfy both departmental and specific business needs, reading/selecting relevant data.
  + Schemas and data models are tailored to specific data analysis/reporting/decision-making purposes.
* **Data Mesh:** A scalable and accessible architecture, decentralized and with the purpose of domain-driven data ownership (thus, owners/managers across an organization can claim it).
  + Data are self-service and envisioned as products, distributed to data owners like a service for collaboration and potential for data sharing and feedback.
  + Data meshes are popular in enterprise environments in which matters of data governance and scalability can get complicated and potentially bottleneck organizational productivity.
* **Data Pipeline:** Transfers data from source to destination systems, for data storage and/or analysis.
* **Data Warehouse:** Stores structured data in an organized system with potential for data tracking/logging. A popular integration for business intelligence (BI), decision support, and reporting tools (and a convenient solution for them, courtesy of consistent data formatting).
  + Data structure is provided through the use of schemas and models, which are predefined by developers/engineers.
  + The transforming of data from source systems to a consistent format used by data warehouses is called 'extracted, transformed, and loaded', or 'ETL'.

<hr />
  
## 2. <a name="data-terms">Data-Characteristic Terms</a>

* **Data Observability:** Observing the performance of and tracking/monitoring data at any point in its lifecycle.
* **Data Quality:** How accurate and consistent data are. Can the data be used to perform reliable analysis and make informed decisions?

TODO: Add examples of different data repo types and how they operate.
