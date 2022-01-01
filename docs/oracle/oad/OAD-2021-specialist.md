# Oracle Autonomous Database Specialist (1Z0-931-21)

######  Question 1
Which three are Oracle-recommended best practices for Autonomous Database alarms?

```
- Select the correnct alarm interval for your metric
- Routinely tune your alarm
- suppress alarms During Investgations
``` 
<br>

######  Question 2
Which set of options can be specified when defining the preferred maintenance schedule of the infrastructure for autonomous dedicated database?

```
- Month of the Quarter, Week of the month, Day of the Week, Start Hour
``` 
<br>


######  Question 3
Which three options are available to access data in an Autonomous JSON Database?

```
- NoSQL statements using Oracle SODA Drivers.
- OCI Console using JSON Online Developer Tool
- REST API calls to the database
``` 
<br>


######  Question 4
Which statement is true about the use of ACL`s with ADB on shared infrastructure?

```
- When restoring the database, the existing ACL`s are not overwritten by the restore.
``` 
<br>


######  Question 5
You have been tasked with analyzing a year`s worth of sales data stored in ana Autonomous data Warehouse instance.
Which tool would you use to automate data exploration and create pivot tables?

```
- Business MOdels 
``` 
<br>


######  Question 6
Which Statement is FALSE about Oracle Data Safe?

```
- It supports only Autonomous Databases.
``` 
<br>


######  Question 7
What happens with standby database when disabling Autonomous Data Guard? 

```
- Standby database is terminated.
``` 
<br>


######  Question 8
When Cloning from a backup, what is the earliest timestamp on the backup allowed?

```
- 2 hours
``` 
<br>



######  Question 9
Which Database action tool is used to get information about the entities in your Autonomous database and to see the effect that changing an object has on other objects?

```
- CATALOG
``` 
<br>



######  Question 10
Which two statements are TRUE about accessing Autonomous Database Tool? 

```
- SQL Developer Web is available excludsively on the Autonomous Database
- Database actions is accessible from the server running ont he same VCN when the autonomous database is configured with Private Endpoint.
``` 
<br>



######  Question 11
Which option should you use to create a graph with Graph Studio? 

```
- Tables in an Autonomous Database Instance
``` 
<br>



######  Question 12
Which three of the following data sources are available when using Data Load Page on Database actions? 

```
- Local Files
- Files in AWS S3 Storage
- Files in Oracle Cloud Storage
``` 
<br>



######  Question 13
You need to setup a notification for a scheduled shutdown of an Autonomous Database instance? 

```
- Create a rule for the OIC Event for "Autonomous Database STOP END"
``` 
<br>



######  Question 14
Which three advanced options can you enable or disable while creating a business model?

```
- Autonomous Aggregate Cache
- Analytic View Transiency views
- Analytic view base table query transformation
``` 
<br>



######  Question 15
Which three options do NOT change when enabling auto-scaling?

```
- Level of concurrency 
- Parallelism
- Amount of Storage
``` 
<br>



######  Question 16
Which three OCI resources you need to configure before provisioning Autonomous database with Private Endpoint?

```
- Network Security Group
- VCN
- Subnet
``` 
<br>



######  Question 16
Which three methods can be used to migrate your existing Oracle database to Autonomous database?

```
- Use Oracle Zero Downtime migration
- Use GoldenGate
- Use Datapump
``` 
<br>



######  Question 17
Which command should you use to enable application continuity in ADB.

```
- Exec dbms_cloud_admin.enable_app_cont('');
``` 
<br>



######  Question 17
Which three event types are supported in Autonomous Database?

```
- Change Compartment Begin
- Mantainence Begin
- Terminate End
``` 
<br>



######  Question 18
In the ADB on Dedicated Infrastructure service, what does the fleet administrator utilize to control OCPU utilization?

```
- Compartment Quotas
``` 
<br>



######  Question 19
Which two methods can you use to create database users and grant roles in services?

```
- SQL Plus
- SQL Developer 
``` 
<br>



######  Question 20
A customer wants to increase the throughput of their inserts. They have discovered that the bottleneck is in the storage I/Os of their environment.

What should they do to remove the bottleneck?

```
- Increase the number of OCPUs allocated to the database 
``` 
<br>



######  Question 21
You are the admin user of an ADB instance. A new business analyst has joined the team and would like to explore ADB tables using autonomous database data tools.
Which steps need to perform?

```
- Create a REST-enalbed database user with connect and object privileges and grant DWROLE 
``` 
<br>



######  Question 22
While provisioning a dedicated Autonomous Container Database, which backup retention can NOT be implemented?

```
- 120 days
``` 
<br>



######  Question 23
Which four file formats are supported from loading from cloud storage?

```
- JSON
- Parquet
- AVRO
- CSV
``` 
<br>



######  Question 24
Which set of OCI metrics is available only for ADB on Dedicated Infrastructure?

```
- IOPS, Storage space used by Tablespace, Apply and Transport Log 
``` 
<br>



######  Question 25
How do you change the tablespace quota for a user on Autonomous Database on Shared Infrastructure?

```
A. Execute alter tablespace DATA set quota = 10G;
B. Execute alter tablespace for user MTHEO tablespace DATA quota = 10G;
C. Execute DBMS_CLOUD_ADMIN.GRANT_TABLESPACE_QUOTA (username=>'MTHEO', tablespace_quota=>'UNLIMITED')
D. Execute alter user MTHEO quota unlimited on tablespace DATA;
``` 
<span class="hidden">
Execute DBMS_CLOUD_ADMIN.GRANT_TABLESPACE_QUOTA (username=>'MTHEO', tablespace_quota=>'UNLIMITED')
</span><br>


######  Question 26
During the provisioning of an ADB on dedicated hardware, what does the database administrator need to select to determine where the ADB is created on dedicated infrastructure?

```
- The container database in which the autonomous instance should run 
``` 
<br>


######  Question 27
Where are the customer-managed encryption keys are stored for ADB on Dedicated infrastructure?

```
- In a separate key vault external to the Exadata Infrasturct 
``` 
<br>



######  Question 28
Oracle Autonomous Database on Dedicated infrastructure is composed of which Oracle Cloud resources?

```
- Autonomous Exadata infrastructure, Autonomous backup, Autonomous container database, and Autonomous database
``` 
<br>



######  Question 29
Which statement is correct with respect to the required action to move ADB resources to a different compartment?

```
- Autonomous Exadata infrastructure and autonomous container database have no dependent resources to move with them.
``` 
<br>



######  Question 30
Which two statements are true about Data Insights?

```
- You can search for Data Insights against a base table or business model
- You can retrieve previously executed Data Insights serarches. 
``` 
<br>



######  Question 31
You see a clock icon in the status column on the SQL Monitoring table of the Performance Hub.
What does it indicate?

```
- The SQL statement is currently queued 
``` 
<br>



######  Question 32
Your customer has upgraded their on-premises 11.2 to 12.2 and during the migration, the database was migrated  to pluggalbe database and now is in production.
How should the customer unplug their database to migrate to ADB?

```
- Pluggalbe databases cannot be migrated to ADB using plug, unplug or clone. 
``` 
<br>



######  Question 33
In which four way can Oracle Database Optionally access data in Object Storage?

```
- Scan avoidance using columnar pruning for .csv files
- Optimized data archive using hybrid partitioned tables
- Scan avoidance using columnar pruning for columnar stores like parquet and orc
- Optimized data archive using partitioned external tables.
- Scan avoidance using partitioned external tables.
``` 
<br>



######  Question 34
Which two of the following statements are correct?

```
- OCI Web Edition can be installed from OCI Market place.
- The Data Transforms Card provides access to ODI Web Edition. 
``` 
<br>



######  Question 35
Which three are use cases for Graph Studio?

```
- Pattern matching
- Clustering 
- Churn analysis 
``` 
<br>



######  Question 36
A new python developer has joined your team and need to access ADB Data.
How does the developer connect to and interact with ADB from python?

```
- Using the Oracle client and cx_oracle interace. 
``` 
<br>



######  Question 37
What are two differentiators of Oracle ADB on Dedicated Infrastructure?

```
- It offers greater control and isolation starting at Exadata cloud infrastructure level.
- Users have more control over the maintenance schedule 
``` 
<br>



######  Question 38
Which two statements are true about using an Oracle Database with private endpoints?

```
- A Network Security Group is requried within VCN before provisioning a shared ADB using private endpoints.
- Private endpoints can be configured when you clone an ADB on shared infrastructure that initially crated with public endpoints. 
``` 
<br>



######  Question 39
Which two cloud services are supported to import Data Pump files to ADB on Oracle cloud infrastructure?

```
- OCI object storage
- OCI object storage classic 
``` 
<br>



######  Question 40
Which statement is correct about the service console in an ADB?

```
- You can use service console to manage runaway SQL statements on ADB 
``` 
<br>



######  Question 41
Which method will NOT permit you to change database ADMIN users password of an ADB on Shared infrastructure?

```
- OS command line from the database server 
``` 
<br>



######  Question 42
Which two actions are available to perform when an autonomous database is stopped?

```
- Start 
``` 
<br>



######  Question 43
You have a requirement to create ATP that can support up to 300 concurrent statements per OCPU as well as parallelism?  
Which service you need to connect to?
```
- TPURGENT
``` 
<br>





######  Question 44
Data guard is enabled for your ADB and Lifecyle state field for the primary database indicates that it is stopped.  
Which statement is true?

```
- The standby database is also stopped.
``` 
<br>



######  Question 45
Which statements is FALSE about setting up compartment quotas?

```
- Compartment quotas cannot be set on the root compartment 
``` 
<br>



######  Question 46
An autonomous database user with an instnace wallet has left the company. The user had shared a database user ID with other users when accessing ADB.  
Other than changing password, what can an administrator do to protect the instance? 

```
- Rotate the instance wallet and share the new wallet with remaining users. 
``` 
<br>



######  Question 47
Which statement is FALSE about ADB on Dedicated infrastructure? 

```
- Autonomous Exadata infrastructure maintenance runs are for infrastructure patching and include container database patching. 
``` 
<br>



######  Question 48
Which stage of the indexing pipeline divides text into tokens

```
- LEXER 
``` 
<br>


######  Question 49
Which statement is true about connecting marketplace OCI image to ADB on shared infrastructure?

```
- The marketplace OCI image can be used with an Always free autonomous database account.
``` 
<br>


######  Question 50
Which parameter is not required to create a new database using OCI CLI?

```
- Db-type
``` 
<br>



Appendix
--------------

[dump1](https://www.youtube.com/watch?v=GSF2r9XSkkA&t=66s)
[dump2](https://www.youtube.com/watch?v=7Ebr2AA5iO8)
