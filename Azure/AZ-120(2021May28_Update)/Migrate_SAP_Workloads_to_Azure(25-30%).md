** Migrate SAP Workloads to Azure (25–30%) **
---------------------------------------------

Identify requirements for target infrastructure
* estimate target database size
* determine supportability of operating systems and databases in Azure
* estimate compute, storage, and network requirements for the target database
* determine target SAPS by using EarlyWatchAlert (EWA) reports or Quick Sizer
* assess constraints imposed by subscription models and quota limits 
* evaluatelicensing and pricing across SAP tiers
* evaluate components, such as Azure Data Factory, Azure Data Lake, Microsoft Power BI, and SAP Cloud
  * Azure Data Factory:
    - Introduction: https://docs.microsoft.com/en-us/azure/data-factory/data-factory-introduction
    - Integration: https://azure.microsoft.com/en-us/blog/azure-data-factory-offer-sap-hana-and-business-warehouse-data-integration/
    - SAP HANA Support:
      - ADF v1: https://docs.microsoft.com/en-us/azure/data-factory/v1/data-factory-sap-hana-connector
      - ADF v2: https://docs.microsoft.com/en-us/azure/data-factory/connector-sap-hana
    - SAP BW Support:
      - ADF v1: https://docs.microsoft.com/en-us/azure/data-factory/v1/data-factory-sap-business-warehouse-connector 
      - ADF v2: https://docs.microsoft.com/en-us/azure/data-factory/data-factory-sap-business-warehouse-connector 
    - https://docs.microsoft.com/en-us/azure/data-factory/data-factory-data-movement-activities
  * Azure Data Lake
  * Microsoft Power BI
  * SAP Cloud
* specify a Microsoft support option for SAP on Azure

Design and implement identity and access for SAP workloads
* design and implement access control and authorization for SAP workloads
* design and implement authentication for SAP workloads
* manage access permissions to SAP systems

Design and implement an SAP migration strategy
* choose a migration scenario (lift-and-shift, lift-shift-migrate, lift-shift-migrate to HANA) or greenfield
* choose migration methods
* configure storage to support migration
* implement an SAP migration
