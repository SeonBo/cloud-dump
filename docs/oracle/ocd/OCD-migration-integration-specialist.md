# OCD Migration and Integration Specialist (1Z0-1094-21)

<br><br>

1. Your data warehouse load consists of extracting data from the order header and order line items table. what kind of journalizing type should you use in Oracle Data Integration ( ODI ) to make sure referential integrity is maintained in the target?

```
Consistent
```
<span class="hidden">
Consistent
</span><br>

2. You have executed the mappings with Change Data Capture ( CDC ) on the source data store and you are now going through the code in the operator log for debugging. Which two tables or views do you need to inspect in the database to see whether the CDC process is writing changed data or not in Oracle Data Integration ( ODI )?

소스 데이터 저장소에서 변경 데이터 캡처( CDC )로 매핑을 실행했으며 이제 디버깅을 위해 운영자 로그의 코드를 살펴보고 있습니다. CDC 프로세스가 Oracle Data Integration(ODI)에서 변경된 데이터를 쓰고 있는지 여부를 확인하기 위해 데이터베이스에서 어떤 두 개의 테이블 또는 뷰를 검사해야 합니까?

```
JV$D
JV$
```
<span class="hidden">
JV$D <br>
JV$
</span><br>


3. Which four Oracle database versions are supported for source databases when migrating with Oracle Zero Downtime Migration?

```
11gR2 and above
```
<span class="hidden">
11gR2 and above
</span><br>


4. Which Three backup mediums are supported when migrating a database with oracle zero downtime migration?

```
A.	Oracle Zero data loss recovery appliance
B.	Object Storage
C.	NFS Storage
```
<span class="hidden">
Oracle Zero data loss recovery appliance <br>
Object Storage <br>
NFS Storage
</span><br>


5. Which FOUR Oracle Database Cloud Services are supported as a target database using Oracle Zero Downtime Migration ?

```
A.	Exadata cloud service
B.	Oracle database cloud service
C.	Exadata cloud @customer
D.	Autonomous database
```
<span class="hidden">
Exadata cloud service <br>
Exadata cloud @customer <br>
Autonomous database <br>
Oracle database cloud service
</span><br>

 
6. Which three Oracle technologies are leveraged by Oracle Zero Downtime Migration Physical Online Workflow?

Oracle Zero Downtime Migration Physical Online Workflow는 어떤 세 가지 Oracle 기술을 활용합니까?

```
``` 
<span class="hidden">
Recovery Manager <br>
Oracle Data Guard <br>
SQL*Net
</span><br> 


7. You have decided to use Oracle Data Integrator (ODI) on Marketplace to load data from an on-premises Oracle Database to Autonomous Database on Oracle Cloud Infrastructure (OCI). Which TWO methods can be used to connect to the on-premises Oracle Database from OCI? (Choose all correct answers)

Marketplace에서 ODI(Oracle Data Integrator)를 사용하여 온프레미스 Oracle Database에서 Oracle Cloud Infrastructure(OCI)의 Autonomous Database로 데이터를 로드하기로 결정했습니다. OCI에서 온프레미스 Oracle Database에 연결하는 데 사용할 수 있는 두 가지 방법은 무엇입니까? 

```
```
<span class="hidden">
Fast Connect <br>
VPN Connect
</span><br> 



8. Your source tables are in an on-premises Oracle Database. You are creating a data server in Oracle Data Integrator (ODI) topology. Which THREE configuration items are needed to successfully test an on-premises Oracle Database connection ?

소스 테이블은 온프레미스 Oracle Database에 있습니다. Oracle Data Integrator(ODI) 토폴로지에서 데이터 서버를 생성하고 있습니다. 온프레미스 Oracle Database 연결을 성공적으로 테스트하려면 어떤 3가지 구성 항목이 필요합니까?

```
```
<span class="hidden">
Network name or IP address* <br>
Oracle SID <br>
Listener port
</span><br>


9. Which TWO methods should you use when migrating a target database with different endianness than the source database?

소스 데이터베이스와 엔디안이 다른 대상 데이터베이스를 마이그레이션할 때 어떤 두 가지 방법을 사용해야 합니까?

```
```
<span class="hidden">
RMAN CONVERT <br>
RMAN Transportable Tablespaces with Data Pump
</span><br>



10. What can you use to quickly load data into a cloud database by dragging and dropping a file in a web browser?

웹 브라우저에서 파일을 끌어다 놓아 클라우드 데이터베이스에 데이터를 빠르게 로드하려면 무엇을 사용할 수 있습니까?

```
```
<span class="hidden">
Data Load tab of the SQL worksheet in Database actions
</span><br>


11. You have a requirement to join data from an Oracle database table and a flat file and load it into the target DB2 table, using Oracle Data Integrator (ODI). Which statement is correct about this?

Oracle 데이터베이스 테이블과 플랫 파일의 데이터를 결합하고 Oracle Data Integrator(ODI)를 사용하여 대상 DB2 테이블에 로드해야 하는 요구사항이 있습니다. 이에 대한 설명으로 옳은 것은?

```
It is possible to mix heterogeneous source connection type and load into any supported target connection type in a single mapping.
단일 매핑에서 이기종 소스 연결 유형을 혼합하고 지원되는 대상 연결 유형으로 로드할 수 있습니다.
```
<span class="hidden">
mix heterogeneous, single mapping
</span><br>


12. You are trying to load a denormalized target table C and the source attributes come from table A and Table B in Oracle Data Integrator (ODI). Which statement is true?

비정규화된 대상 테이블 C를 로드하려고 시도하고 있으며 소스 속성은 Oracle Data Integrator(ODI)의 테이블 A 및 테이블 B에서 제공됩니다. 어떤 진술이 사실입니까

```
You can join table A and table B, as required by the data model and load target C in a single mapping
```
<span class="hidden">
join table A and table B, target C in a single mapping
</span><br>


13. You are migrating an on-premises Linux 11.2.0.4 Database to a Database Cloud Service by using the Cross-Platform Transportable Tablespace Backup Set. Which statement is true?

플랫폼 간 전송 가능한 테이블스페이스 백업 세트를 사용하여 온프레미스 Linux 11.2.0.4 데이터베이스를 데이터베이스 클라우드 서비스로 마이그레이션하고 있습니다. 어떤 말이 진실이야?

```
The database could service target version must be 11.2.0.4 (짧은 답변)
```
<span class="hidden">
</span><br>


14. Which TWO methods support a difference in endian format when migrating a database from on premises to Oracle Cloud? (Choose all correct answers)

```
RMAN cross-Platform Transportable PDB
Datapump Conventional export/import
```
<span class="hidden">
RMAN cross-Platform .. PDB, 
Datapump Conventional export/import
</span><br>


15. Which THREE methods can be used to migrate an on-premises Oracle Database to Oracle Autonomous Database? (Choose all correct answers)

온프레미스 Oracle Database를 Oracle Autonomous Database로 마이그레이션하는 데 사용할 수 있는 세 가지 방법은 무엇입니까? (정답 모두 선택)

```
Enterprise manager
Datapump export and import
Oracle zero downtime migration
```
<span class="hidden">
Enterprise manager<br>
Datapump export and import<br>
Oracle zero downtime migration<br>
</span><br>

16. Which TWO target database environments provide both high availability (HA) and disaster recovery (DR) options in the cloud? (Choose all correct answers)

클라우드에서 고가용성(HA) 및 재해 복구(DR) 옵션을 모두 제공하는 두 대상 데이터베이스 환경은 무엇입니까?

```
Exadata Cloud service 
Autonomous database 
```
<span class="hidden">
Exadata Cloud service <br>
Autonomous database <br>
</span><br>


17. You run a database instance on Oracle Database 11.2 and you want to migrate to Oracle Cloud. In which case is it required to upgrade your source database before migrating to the cloud? 

Oracle Database 11.2에서 데이터베이스 인스턴스를 실행하고 Oracle Cloud로 마이그레이션하려고 합니다. 어떤 경우에 클라우드로 마이그레이션하기 전에 소스 데이터베이스를 업그레이드해야 합니까?

```
```
<span class="hidden">
If your target is Exadata Cloud Service OR<br>
If you are using unplug/plug
</span><br>


18. When selecting a migration method for moving your database to the cloud, what would you NOT take into consideration?

데이터베이스를 클라우드로 이동하기 위한 마이그레이션 방법을 선택할 때 고려하지 않는 것은 무엇입니까?
```
A.	 High Availability
B.	 Database Size
C.	 Database version
D.	 Schema name
```
<span class="hidden">
Schema name
</span><br>


19. Which TWO methods are supported by Oracle Zero Downtime Migration (ZDM) for migrating on-premises databases to Autonomous Database? (Choose all correct answers)

온프레미스 데이터베이스를 Autonomous Database로 마이그레이션하기 위해 Oracle ZDM(Zero Downtime Migration)에서 지원하는 두 가지 방법은 무엇입니까?

``` 
```
<span class="hidden">
Logical online or offline migration using database link <br>
Logical online or offline migration using OCI Object storage
</span><br>



20. Which TWO products/utilities does Oracle Zero Downtime Migration use as part of its migration workflows to Autonomous Database? (Choose all correct answers)

Oracle Zero Downtime Migration이 Autonomous Database로의 마이그레이션 워크플로의 일부로 사용하는 두 가지 제품/유틸리티는 무엇입니까?

```
```
<span class="hidden">
Golden gate<br>
Data pump
</span><br>



21. For a source database to be successfully migrated, you must view and apply the prerequisites. Which TWO prerequisites must pass before the source database can be migrated using Oracle Zero Downtime Migration (ZDM)

원본 데이터베이스를 성공적으로 마이그레이션하려면 전제 조건을 보고 적용해야 합니다. Oracle ZDM(Zero Downtime Migration)을 사용하여 소스 데이터베이스를 마이그레이션하기 전에 통과해야 하는 두 가지 전제 조건

```
```
<span class="hidden">
Port 22 on source database server must allow incoming connections from ZDM <br>
Archivelog must be enabled
</span><br>




22. Which are THREE target database prerequisites for database cloud migration with Oracle Zero Downtime Migration?

Oracle Zero Downtime Migration을 사용한 데이터베이스 클라우드 마이그레이션을 위한 세 가지 대상 데이터베이스 전제 조건은 무엇입니까?

```
A.	 The TDE wallet must be open
B.	 The database db_name must be same as source
C.	 TDE must be enabled
```
<span class="hidden">
The TDE wallet must be open <br>
The database db_name must be same as source <br>
TDE must be enabled
</span><br>



23. When migrating an Oracle database, you must be aware of source and target requirements. Which TWO statements are true about using Oracle Zero Downtime Migration (ZDM)?

Oracle 데이터베이스를 마이그레이션할 때 소스 및 대상 요구 사항을 알고 있어야 합니다. Oracle ZDM(Zero Downtime Migration) 사용에 대한 설명으로 옳은 것은?

``` 
A.	 Source Oracle single instance can be migrated to Oracle RAC
B.	 Oracle RAC can be migrated to single instance database
```
<span class="hidden">
Source Oracle single instance can be migrated to Oracle RAC <br>
Oracle RAC can be migrated to single instance database
</span><br>



24. Which Autonomous Data Warehouse (ADW) package is leveraged by the Business Intelligence Cloud Connector (BICC) Loading Knowledge Modules, when using Oracle Data Integrator (ODI)?

Oracle Data Integrator(ODI)를 사용할 때 BICC(Business Intelligence Cloud Connector) Loading Knowledge Modules 에서 활용하는 Autonomous Data Warehouse(ADW) 패키지는? 

```
```
<span class="hidden">
Dbms_cloud_admin
</span><br>



25. Which THREE Fusion SaaS components from the Oracle Data Integrator (ODI) Loading Knowledge Modules can be used to extract data out of Fusion SaaS applications and load it into Autonomous Data Warehouse (ADW)?

Oracle Data Integrator(ODI) Loading Knowledge Module 에서 Fusion SaaS 애플리케이션에서 데이터를 추출하고 이를 ADW(Autonomous Data Warehouse)에 로드하는 데 사용할 수 있는 3가지 Fusion SaaS 구성 요소는 무엇입니까?

```
A.	 REST API
B.	 Enterprise Scheduler Service SOAP API
C.	 BI Cloud connector
```
<span class="hidden">
REST API <br>
... SOAP API <br>
BI Cloud connector
</span><br>


26. You are looking at migrating a large data centre to the Oracle Cloud while trying to consolidate many Oracle Databases at the same time. Which Oracle Data Management Service helps you achieve this?

많은 Oracle Database를 동시에 통합하는 동시에 대규모 데이터 센터를 Oracle Cloud로 마이그레이션하려고 합니다. 이를 달성하는 데 도움이 되는 Oracle Data Management Service는 무엇입니까?

```
```
<span class="hidden">
Oracle Exadata cloud service
</span><br>


27. You have an on-premises non-TDE-encrypted Linux 19c container database (CDB) that is already being regularly backed up to Oracle Cloud Infrastructure (OCI) Object Storage via the Database Backup Cloud Service. You plan on using Recovery Manager (RMAN) to migrate it to Database Cloud Service. What is the valid strategy to migrate?

데이터베이스 백업 클라우드 서비스를 통해 이미 정기적으로 Oracle Cloud Infrastructure(OCI) Object Storage에 백업되고 있는 온프레미스 비 TDE 암호화 Linux 19c 컨테이너 데이터베이스(CDB)가 있습니다. RMAN(복구 관리자)을 사용하여 데이터베이스 클라우드 서비스로 마이그레이션할 계획입니다. 마이그레이션을 위한 유효한 전략은 무엇입니까

```
A.	 Create New DB instance, delete the existing database, manually install the DB cloud backup service, perform a complete RMAN restore as encryption enabled
```
<span class="hidden">
Create New DB instance, ...  RMAN restore as encryption enabled
</span><br>


28. You are migrating a non TDE ae a on-premises Database to an OCT Database Service Instance using RMAN   
    You set up the DB Cloud Backup Module, but when executing the RMAN command to create your Cloud Backup you see the following error:
    AANA RMAN-03009:
    failure of backup command on ORA_SBT_TAPE 1 channel at:
    08/18/2014 11: ORA~19914: unable to encrypt backup ORA~29361
    master key not yet set
    What are the TWO causes of this error?

```
A.	 Set encryption is on
B.	 set encryption identified by command was executed.
```
<span class="hidden">
Set encryption is on <br>
set encryption identified by command was executed.
</span><br>


29. You are planning the migration of a 19c Oracle Database from Amazon Web Services Relational Database Service (AWS RDS) using RMAN backups. What is the correct sequence of operations?

RMAN 백업을 사용하여 Amazon Web Services Relational Database Service(AWS RDS)에서 19c Oracle 데이터베이스를 마이그레이션할 계획입니다. 올바른 작업 순서는 무엇입니까?

```
Using the AWS tooling, take an RMAN backup of the RDS DB local file storage and move it AWS s3 bucket, copy contents of S3 bucket to OCI object storage, restore the backup from OCI bucket to OCI DB service instance
```
<span class="hidden">
Using the AWS tooling > take an RMAN backup of the RDS DB local file storage and move it AWS s3 bucket > copy contents of S3 bucket to OCI object storage 
> restore the backup from OCI bucket to OCI DB service instance
</span><br>



30. Which are TWO benefits of Extract-Load-Transform (E-L-T) over traditional Extract-Transform-Load (ETL) architectures?

기존 ETL(Extract-Transform-Load) 아키텍처에 비해 E-L-T(Extract-Load-Transform)의 두 가지 이점은 무엇입니까?

```
A.	 ELT doesn’t require dedicated hardware and leverages native data management engines, such as Big data and RDBMS
B.	 ELT architecture reduces the amount of network traffic over the other ETL tools, which use a dedicated server
```
<span class="hidden">
ELT doesn’t require <br>
ELT architecture
</span><br>


31. If unplug and plug was decided to be used as the tool for the migration to Oracle Cloud Infrastructure (OCD), which two constraints are part of this migration process for using unplug and plug?

Oracle Cloud Infrastructure(OCD)로의 마이그레이션을 위한 도구로 언플러그 및 플러그를 사용하기로 결정한 경우 언플러그 및 플러그 사용에 대한 이 마이그레이션 프로세스의 일부인 두 가지 제약 조건은 무엇입니까?

```
A.	Target and Source have the same Endianness.
B.	Source and target needs to be a container database.
```
<span class="hidden">
Target and Source .. Endianness.<br>
Source and target .. container database
</span><br>


32. You are using Oracle Data Integrator (ODI). Which three topology elements are required to extract data out of Fusion SaaS applications and load it into the Autonomous Data Warehouse

Oracle Data Integrator(ODI)를 사용하고 있습니다. Fusion SaaS 애플리케이션에서 데이터를 추출하고 이를 Autonomous Data Warehouse에 로드하는 데 필요한 세 가지 토폴로지 요소는 무엇입니까?

```
A.	 Object storage
B.	 Bl cloud connector
C.	 File
```
<span class="hidden">
A.	 Object storage<br>
B.	 Bl cloud connector<br>
C.	 File
</span><br>


33. Which two migration methodologies can you use for migrating on-premises databases to Autonomous Database with Oracle Zero Downtime Migration (ZDM)?

Oracle ZDM(Zero Downtime Migration)을 사용하여 온프레미스 데이터베이스를 Autonomous Database로 마이그레이션하는 데 사용할 수 있는 두 가지 마이그레이션 방법은 무엇입니까?

```
A.	 Logical online
B.	 Physical online
C.	 Physical offline
D.	 Logical offline
```
<span class="hidden">
Logical online <br>
Logical offline
</span><br>


34. Which Oracle Database Cloud Service takes care of all routine database tasks ensuring higher performance, reliability, security, and operational efficiency?

더 높은 성능, 안정성, 보안 및 운영 효율성을 보장하는 모든 일상적인 데이터베이스 작업을 처리하는 Oracle Database Cloud Service는 무엇입니까?

```
```
<span class="hidden">
Oracle autonomous database
</span><br>



35. Which type of checks is NOT supported by Oracle Data Integrator (ODI)?

```
```
<span class="hidden">
A.	Business rules
</span><br>



36. Which supported platform can the source Oracle Database be running on when migrating with Oracle Zero Downtime Migration?

Oracle Zero Downtime Migration으로 마이그레이션할 때 소스 Oracle Database를 실행할 수 있는 지원 플랫폼은 무엇입니까?

```
```
<span class="hidden">
A.	Linux x86-64
</span><br>



37. Which TWO options are valid when using the unplug/plug a PDB method to migrate?

마이그레이션을 위해 PDB 분리/플러그 방법을 사용할 때 유효한 두 가지 옵션은 무엇입니까?

```
A.	 Non-CDB databases can be consolidated and migrated
B.	 Source database versions are 12c and higher
```
<span class="hidden">
Non-CDB <br>
12c
</span><br>


38. Which TWO statements are true about online pluggable database (PDB) relocation?

온라인 플러그형 데이터베이스(PDB) 재배치에 대한 설명으로 옳은 것은?

```
A.	 Online PDB relocation can achieve a zero downtime upgrade
B.	 PDB relocation with no version change can be performed with near-zero downtime
```
<span class="hidden">
Online PDB ... zero downtime  <br>
PDB .. near-zero downtime
</span><br>

39. When integrating data from multiple sources into a Data Warehouse schema, you want to check a length constraint that you have imposed on one of the target columns before the rows arrive in the target table. All the rows that do not pass this quality check will have to be isolated in error tables.
    For this, you have chosen an Integration Knowledge Module (IKM) that supports flow control. 
    You have also chosen the value true for this parameter to enable this check.
    At compile time, you see that Oracle Data Integrator (ODI) throws an error and the execution cannot start. What is the reason?

여러 소스의 데이터를 데이터 웨어하우스 스키마로 통합할 때 행이 대상 테이블에 도착하기 전에 대상 열 중 하나에 부과한 길이 제약 조건을 확인하려고 합니다. 
이 품질 검사를 통과하지 못한 모든 행은 오류 테이블에서 격리되어야 합니다. 이를 위해 흐름 제어를 지원하는 IKM(통합 지식 모듈)을 선택했습니다.
또한 이 검사를 활성화하기 위해 이 매개변수에 대해 true 값을 선택했습니다. 컴파일 시 ODI(Oracle Data Integrator)에서 오류가 발생하고 실행을 시작할 수 없음을 알 수 있습니다.
이유는 무엇입니까?

```
A.	The check knowledge module was not set in physical design
```
<span class="hidden">
The check knowledge ... physical design
</span><br>


40. Which TWO statements are true about cross-endian migration using Transportable Tablespaces?

다음 중 Transportable Tablespace를 사용한 교차 엔디안 마이그레이션에 대한 설명으로 옳은 것은?

```
A.	 Tablespaces must be converted by either RMAN CONVERT or DBMS_FILE_TRANSFER
B.	 Tablespaces may not be encrypted
```
<span class="hidden">
Tablespaces .. RMAN CONVERT or DBMS_FILE_TRANSFER <br>
Tablespaces may not be encrypted
</span><br>


41. What TWO ways does Data Pump use to move data to the cloud

Data Pump가 데이터를 클라우드로 이동하는 데 사용하는 두 가지 방법


```
A.	 Import dump file from OCI object storage
B.	 Import over database link
```
<span class="hidden">
Tablespaces .. OCI object storage<br>
Import over database link
</span><br>


42. Which FOUR key parameters should you include in your export command when migrating an Oracle Database to the Oracle Cloud? (Choose all correct answers)

오라클 데이터베이스를 오라클 클라우드로 마이그레이션할 때 내보내기 명령에 포함되어야 하는 4가지 주요 매개 변수는 무엇입니까? 

```
A.	Exclude=statistics
B.	Metrics=yes
C.	LOGTIME=all
D.	FLASHBACK_TIME=SYSTIMESTAMP
```
<span class="hidden">
Exclude, Metrics, LOGTIME, FLASHBACK_TIME
</span><br>


43. Which process does Oracle Data Integrator Enterprise Edition use to process and transform data for disparate relational database management systems or Big Data Engines?

Oracle Data Integrator Enterprise Edition은 서로 다른 관계형 데이터베이스 관리 시스템 또는 빅 데이터 엔진의 데이터를 처리하고 변환하기 위해 어떤 프로세스를 사용합니까?

```
```
<span class="hidden">
E-LT
</span><br>


44. Which view is used to measure the replication latency between source and target when using the automatic heartbeat table feature, in GoldenGate?

GoldenGate 에서 자동 하트비트 테이블 기능을 사용할 때 소스와 대상 간의 복제 지연을 측정하는 데 사용되는 보기는 무엇입니까?

```
```
<span class="hidden">
GG_LAG
</span><br>

45. Which FOUR Oracle Data Pump impdp parameters should you use when migrating to Autonomous Database?

자율 데이터베이스로 마이그레이션할 때 사용해야 하는 4가지 오라클 Data Pump impdp 매개 변수는 무엇입니까?

```
A.	 Remap_tablespace=DATA
B.	 Transform=CONSTRAINT_USE_DEFAULT_INDEX:Y
C.	 Transform=segment_attributes:N
D.	 Transform=DWCS_CVT_IOTS:Y
```
<span class="hidden">
Remap_tablespace=DATA
CONSTRAINT_USE_DEFAULT_INDEX:Y
segment_attributes:N
DWCS_CVT_IOTS:Y
</span><br>


46. Which TWO object types should be excluded from an Autonomous Transaction Processing database? (Choose all correct answers)

자율 트랜잭션 처리 데이터베이스에서 제외할 두 가지 개체 유형을 선택하십시오. (정답은 모두 선택)

```
```
<span class="hidden">
A.	 Cluster<br>
B.	 DB-LINK
</span><br>

47. You have a security requirement within your organization to separate your resources. There is a team that supports each resource and they are not allowed access to the other resources. Which security control with Oracle Cloud Infrastructure meets this requirement?

조직 내에 리소스를 분리하기 위한 보안 요구사항이 있습니다. 각 리소스를 지원하는 팀이 있으며 다른 리소스에 액세스할 수 없습니다. Oracle Cloud Infrastructure를 사용하여 이러한 요구사항을 충족하는 보안 제어 기능은 무엇입니까?

```
```
<span class="hidden">
A.	Compartments and Policies
</span><br>


48. When building out your private subnet, you realize you need a host within your network in order to get access to the rest of your Oracle Cloud Infrastructure instances. Which type of host should you set up to get around this constraint?

프라이빗 서브넷을 구축할 때 나머지 Oracle Cloud Infrastructure 인스턴스에 액세스하려면 네트워크 내에 호스트가 필요하다는 것을 알게 됩니다. 이 제약 조건을 해결하려면 설정할 호스트 유형을 선택하십시오.

```
```
<span class="hidden">
A.	Baston Host
</span><br>



49. In Oracle Zero Downtime Migration, the migrate database command provides several options to ensure a successful Oracle source and target data migration.
    Which FOUR are valid parameters to use with migrate database?

Oracle 제로 다운타임 마이그레이션에서 migrate database 명령은 Oracle 원본 및 대상 데이터 마이그레이션을 성공적으로 수행하기 위한 몇 가지 옵션을 제공합니다.
다음 중 마이그레이션 데이터베이스에 사용할 수 있는 유효한 매개 변수 4가지는 무엇입니까?

```
A.	-tdemasterkey
B.	-sourcedb
C.	-sourcesid
D.	-tgrroot
```
<span class="hidden">
masterkey 
db 
sid 
root 
</span><br>


50. Which TWO statements are true about the Oracle Zero Downtime command line?

Oracle ZD 명령에대해 2가지 옳은것은?

```
A.	Upon execution of zdmcli , the only way to track the status of migration is querying the ZDM service using the provided job ID
B.	When the source is a single instance deployed on non-grid, the sourceid option should be used to specify the database name.
```
<span class="hidden">
Upon execution of zdmcli ... ZDM .. job ID<br>
When the source ... non-grid
</span><br>



51. Which TWO statements are true about the Oracle Zero Downtime command line?

A.	Root user or ssh key-based access to source and target.


52. Oracle Zero Downtime Migration (ZDM) uses MySQL internally, configuring a default port number. What will ZDM proceed to, if a port number is not specified and the default is not available?

Oracle ZDM(Zero 다운타임 마이그레이션)은 MySQL을 내부적으로 사용하여 기본 포트 번호를 구성합니다. 포트 번호가 지정되지 않고 기본값을 사용할 수 없는 경우 ZDM은 어떻게 진행됩니까?

```
A.	Increase the default port number by one and retry five times.
```
<span class="hidden">
Increase .. retry five times.
</span><br>



53. Which migration method gives you the least down time?

```
```
<span class="hidden">
A.	Data guard
</span><br>


54. Planning a database migration to Oracle Cloud Infrastructure (OCI) requires understanding the source

```
A.	On-premise host operating system version
B.	Characterset of database
```
<span class="hidden">
On-premise host <br>
Characterset of
</span><br>

<br><br>

Glossary
-----------

- ASM : Automatic Storage Management
- ASH : Active Session History
- VCN : Virtual Cloud Network
- VNC : Virtual Network Computing
- DRG : Dynamic Routing Gateway
- ZDM : Zero Downtime Migration 
- CDB : Container Database 
- PDB : Pluggable Database 