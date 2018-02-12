# Turnover

### Current Projects
Find A Doc (PhysicianRepo) Version 2  
Description: Code based on the current FAD workgroup.  ETL is pulling data from Visual Cactus and IDX nightly.  API can be run locally until integrated with Datica routes.  Front end is a working start to update custom data fields stored by SBM.
  * [ETL](https://github.com/sbm-it/PhysicianRepoETL)  
  * [API](https://github.com/sbm-it/PhysicianRepoAPI)  
  * [FrontEnd](https://github.com/sbm-it/PhysicianRepoClient)  

DocMiner  
Description: Creation of a repository of reports.  Pulling metadata from source systems (starting with Crystal Reports).  Metadata to be stored in Box.com for a Jonas front end.  Test API calls are trying to pull data from the Crystal Reports server.
  * [ETL](https://github.com/sbm-it/docminer_backend)  
  * [Test API Calls (Postman)](https://www.getpostman.com/collections/57d1ee6560859244e185)
  
Business Intelligence Gateway  
Description:  Dashboard of all Tableau vizualizations (both on-prem and HealtheIntent).  
  * [Trusted Ticket](https://github.com/sbm-it/Catalyze-PROD/tree/development/routes/tableautt) - included in Datica Development route (to be merged into Master when ready)
  * [FrontEnd](https://github.com/sbm-it/BIG-Dashboard) - uses Tableau API for on-prem content access and CSV for HealtheIntent content access  
  * [FrontEnd Prototype](https://github.com/sbm-it/BIG-Portal-Prototype) - uses CSV for managing content access  
  * [Trusted Ticket Prototype](https://github.com/sbm-it/tableauAuthentication)  

### Production Support  
Patient Messaging System  
Switchboard Distribution Requests  
Stony Brook Directory  
Sourhtampton Directory  
FAD (currently running in production)
  * [Visual Data Flow](https://github.com/sbm-it/Turnover/blob/master/Find%20A%20Doctor%20Data%20Flow.png)
  * ETL Scripts (prod) - \\sbm16db2p.uhmc.sbuh.stonybrook.edu\FindADoc\etl
  * ETL Scripts (dev) - \\dev16db1.uhmc.sunysb.edu\FindADoc\etl
  
  








### Contracts
