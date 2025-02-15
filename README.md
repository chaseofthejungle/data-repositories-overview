# Data Repositories Overview
  
#### Table of Contents:
  
1. [Six Data Repository Types/Architectures](#data-repository)
2. [Data-Characteristic Terms](#data-terms)
  
<hr />
  
## 1. <a name="data-repository">Six Data Repository Types/Architectures</a>
  
* **Data Fabric**
  + Allows for distributed data to be quickly/easily accessed, managed, and integrated.
    - This unites data from various sources and provides orchestration, governance, and virtualization.
  + Data silos (data separated from other parts of an organization's system) can be easily accessed and have their data analyzed.
    - This supports concentrated and informed decision-making.
* **Data Lake**
  + Stores structured, semi-structured, *and* unstructured ('raw') data in a large and centralized manner.
  + Pulls data from multiple (or even many) sources, for both analysis and processing.
  + Data models and schemas are not applied (data are in their native formats).
    - This allows for quick and adaptive data analysis and reading.
      + Machine learning and complex analytics/reporting can pull from various kinds of data, due to data lake integration.
* **Data Mart**
  + A specialized data warehouse subset (smaller in size and scope and concentrated on a single purpose/subject).
  + Data marts can satisfy both departmental *and* specific business needs by focusing on directly relevant data.
    - Schemas and data models are tailored to specific data analysis/reporting/decision-making purposes.
* **Data Mesh**
  + Scalable, accessible, and decentralized through a domain-driven data ownership model.
    - Data are distributed to data owners as self-service products, with potential for data sharing/collaboration and feedback.
      + Owners/managers across an organization can conveniently claim their data.
    - Popular in enterprise environments, because data governance and scalability can get complicated (and bottleneck productivity).
* **Data Pipeline**
  + Transfers data from source to target/destination systems, for convenient data storage and/or analysis.
* **Data Warehouse**
  + Stores structured data in an organized system, with the potential for data tracking/logging.
    - Popular for business intelligence (BI), decision support, and reporting tools (especially due to consistent data formatting).
    - Data structure is provided through the use of schemas and models, which are predefined by developers/engineers.
    - Data transformation from source systems to a consistent data warehouse format is referred to as an 'extracted, transformed, and loaded', or 'ETL', process.

<hr />
  
## 2. <a name="data-terms">Data-Characteristic Terms</a>

* **Data Observability**
  + Observing the performance of, and tracking/monitoring, data at any point in its lifecycle.
* **Data Quality**
  + How accurate and consistent data are.
    - Can the data be used to perform reliable analysis and make informed decisions?
  
TODO: Add examples of different data repo types and how they operate.
