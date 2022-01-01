# OCD Services Specialist [1Z0-1093-21]

<br><br>

1. What information is required to connect to the NoSQL Database Cloud Service?

```
a) API signing key, admin ID, user ID
b) tenancy 1D, passphrase, handshake key
c) signing key fingerprint, API signing key, tenancy OCID
d) user ID, tenancy ID, component ID
```
<span class="hidden">signing key fingerprint, API signing key, tenancy OCID</span>

2. What NoSQL Database Cloud Service API statement can be used to adjust table capacity?

```
A. TableRequest
```


3. Which system configuration is offered by the Oracle Database Exadata Cloud Service?

```
A. Each system configuration is starts with a fixed amount of memory, storage, and network resources
```

4. Which TWO statements are true when enabling autonomous Data Guard on Autonomous Exadata

```
A. When in a Data Guard configuration patching will always take place on standby database first
B. Autonomous databases inherit their Data Guard configuration from their Autonomous container database.
```

5. Assume that there are no resource limits on your underlying Exadata Cloud@customer, the maximum number of Autonomous container databases that can be created on Exadata VM cluster

```
  
```
<span class="hidden">=== 12 ===</span>

6. Which is NOT a prerequisite for patching Grid Infrastructure or database home

```
a) Oracle Clusterware is down on the VM cluster.
b) All database compute nodes of the VM cluster are up and running.
c) The required patch is available on the Control Plane server.
d) The /uo1 directory on the database host file system has at least 15 GB of free space for the execution of Patching processes.
```
<span class="hidden">
Oracle Clusterware is down on the VM cluster
</span>

7. In Exadata Cloud Service, you use Oracle Data Guard for disaster recovery. What is the minimum egress requirement needed to enable Data Guard between Exadata Cloud Services?

```
A. 
```

<span class="hidden">
TCP Traffic only for port 1521
</span>

8. you notice that throttling is occurring on your NoSQL Database Cloud Service. What must you increase to solve this?

```
```
<span class="hidden">
A. OCPU for all servers in the cluster
</span>

9. Which statement is false about using compartments?

```
```
<span class="hidden">
A. They are a physical concept that separate users.
</span>

10. Which four storage options are available in OCI

```
a) EBS Storage
b) EFS Storage
c) Local storage
d) Block Storage
e) File Storage
f) Object Storage
```
<span class="hidden">
c) Local storage <br>
d) Block Storage <br>
e) File Storage <br>
f) Object Storage
</span>


11. You have been brought in to help a company with slow nightly processing in Exadata cloud service. You have determined that the workload is CPU-bound during the batch window.
    Which command line tool can be used to script increase or decrease OCPUs?

```
```
<span class="hidden">
A. OCI CLI
</span>


12. You want to permanently delete the DB System and its attached HeatWave cluster. What steps do you perform?

```
a) Terminate the DB system and drop the associated HeatWave Cluster.
b) Drop the DB system and terminate the associated HeatWave Cluster.
c) Delete the Heatwave Cluster and it will also delete the DB system.
d) Delete the DB system and it will also delete the attached HeatWave Cluster.
```
<span class="hidden">
Delete the DB System and it will automatically delete the Heatwave cluster
</span>


13. You want to move an Exadata Cloud@Customer VM to different OCI compartment for increased isolation from other teams that use Exadata. What happens when you use a console to do this?

```
A. The VM Cluster, compute nodes and the associated databases will move to a new compartment. All other resources will remain in the existing compartment.
```

14. Which network is used to facilitate the secure monitoring and administration of the oracle-managed infrastructure components in Exadata Cloud@Customer?

```
```
<span class="hidden">
A. Control plane network
</span>


15. Which THREE Oracle Cloud Infrastructure (OCI) services can be used to connect to on-premises networks?

```
```
<span class="hidden">
A. Fastconnenct
B. DRG
C. IPSec VPN
</span>

16. Resources are allocated to the DB System based on the shape selected. Which two are options for a DB system?

```
A. Two-node virtual machine X7 with Block storage which can be scaled up
B. One-node bare metal server with up to 52 OCPU cores and locally attached drives to the system
```

17. Your MySQL Database service system is automatically backed up between midnight and 1am.
    What must you do to change the starting time to 4am?

```
A. From the Edit MySQL DB System Details Page, select the Backup window and set the start time to 4am.
```


18. Which service is used by default by the MySQL Database Service to store user data which is resistant to failures?

```
```
<span class="hidden">
A. OCI Block Volumes
</span>


19. Which THREE are prerequisites for using the MySQL Database Service?

```
A. You or your group must be granted the policies described in Mandatory Policies.
B. You must create a tenancy and be able to sign into it.
C. You must create a compartment to store your resources
```

20. Which statement is true about moving virtual machine database system from one compartment to another?

```
A. You can move DB system to different compartment if you have sufficient access permission on the compartment that the resource is being moved to as well as the current compartment
```

21. You are considering whether or not to implement bare metal or virtual machine DB systems.
    Which TWO statements are true about bare metal and virtual machine (VM) database systems.

```
A. Bare metal shapes determine the total raw storage allocated to bare metal DB systems.
B. The Console,API and OCI CLI are options for managing bare metal DB systems.
```

22. Which TWO statements are true about Interface for Exadata I/O Resource Management (lIORM)?

```
A. IORM allows workloads and databases to share I/O resources automatically according to the admin-defined policies.
B. IORM can be enabled across multiple databases using the cloud interface of Exadata cloud service.
```

23. You used the "Stop" option from the Console of an Exadata Cloud Service virtual machine within a VM cluster.
    What impact does this have?

```
A. The stopped virtual machine is not available to any other database deployment.
```

24. When you created your development database on Exadata Cloud@Customer, you selected "None" for backup location during provisioning. You now need to enable automatic backups on the development database with a retention period of 45 days.
    Which action should you perform?

```
A. No action can be taken, because a new backup location cannot be set after creation.
```

25. Which set of data types is supported by the NoSQL Database Cloud Service tables?

```
A. Enum, map, record
```

26. What TWO reasons do you need a minimum of three storage cells when using Exadata Cloud Service?

```
A. For high availability
B. For triple mirroring of data
```

27. What permissions do you need to perform actions on a NoSQL table?

```
A. NOSQL_ROWS_READ, NOSQL_ROWS_DELETE
```

28. You want to connect to your MySQL DB system's endpoint. You create an Oracle Linux compute instance on the same Virtual Cloud Network as your MySQL DB system.
    Which TWO actions must you perform to connect to your MySQL Database Service system?

```
A. Ssh into the compute instance from your local machine
B. Connect to your database system by using the MySQL client on the Linux computer instance.
```


29. You are asked to create a MySQL Database Service system. You can log in to the group's Oracle Cloud Infrastructure tenancy and access the assigned compartment, and all policies have been configured and tested.
    What is the next step to create a MySQL Database Service?

```
A. Create a virtual cloud network using VCN wizard
```

30. You are asked to measure useful quantitative data about a MySQL Database Service system. You must provide information such as current connection information, statement activity, latency, and host OCPU, memory, and disk I/O utilization.
    Which THREE Oracle Cloud Infrastructure monitoring methods should you use?

```
A. Alarms , notifications, metrics
```

31. Which are THREE strategies to migrate Oracle Database to Oracle Cloud Infrastructure (OCI)?

```
A. Zdm
B. Migration workbench
C. Goldengate
```

32. Which characteristic is NOT a factor that impacts the capacity units for provisioning a NoSQL Database Cloud Service table?

```
A. Durability level
```

33. Which two circumstances are FALSE when you use the Console to recover a DB system database from a backup stored in Oracle Cloud Infrastructure Object Storage?

```
A. The DB system has no access to the OCI object storage location where backup is stored.
B. Restore the database from an unmanaged backup in object storage created directly by using RMAN
```

34. You define a maintenance window for your MySQL DB systems. When the automatic maintenance process takes place, which TWO activities does the system perform while its status is set to UPDATING?

```
A. It patches the MySQL server itself along with any underlying hardware.
B. It patches the underlying operating system of MySQL database.
```

35. After you have provisioned a virtual machine (VM) database (DB) system, what action can you take to meet changes in block storage requirements?

```
a) Only bare metal DB systems can increase block storage at any time without impacting the system.
b) If a vm DB system requires more block storage, increase the storage at any time without impacting the system.
c) If a vm DB system has different requirements for block storage, increase or decrease the storage at any time without impacting the system.
d) After you have provisioned a VM DB system, you cannot increase or decrease block storage.
```
<span class="hidden">
If a vm DB system requires more block storage, increase the storage at any time without impacting the system.
</span>


36. Patching requires role permissions. However, since roles are not granted by default, which role needs to be added to someone patching the DB system?

```
A. Let database administrators manage the DB system.
```


37. Which three statements are true regarding MySQL Database Service
    HeatWave?

```
A. Heatwave is an in-memory, query-processing engine designed for fast execution of analytics queries.
B. Heatwave uses machine learning to automate operations, increase DBA productivity and reducing costs.
C. Heatwave is exclusively available in OCI
```

38. You can manage and monitor performance of an autonomous database running on autonomous Exadata Cloud @ Customer using the Performance Hub.
    Which two actions can be undertaken by the Performance Hub?

```
A. Kill a running sql session
B. view ASH analytics
```

39. You want to scale within the Exadata System. Which of the following two statements are true?

```
A. Modifying the number of enabled OCPU cores does not require database downtime.
B. The setting of database parameter CPU_Count is affected by modifying the number of enabled OCPU cores
```

40. Which tool should you use to run the LIST FLASHCACHE DETAIL command in the Exadata Cloud Service environment?

```
A. exacli
```

41. Which system configuration is offered by the Oracle Database Exadata Cloud Service?

```
A. Each system configuration starts with a fixed number of OCPU, memory, storage and network resources.
```

42. How many IP addresses do you need at a minimum for the client subnet when you plan to have four Exadata compute nodes on Exadata Cloud Service?

```
A. 18 ((3 addresses * 2 nodes) + 3 for SCANs + 3 reserved in subnet )
```

43. What can you use to enable an on-premises Enterprise Manager instance to monitor Exadata Cloud Service in a private OCI subnet?

```
A. FastConnect
```

44. In a two-node Real Applications Cluster environment, the Internet and VCN Resolver are supported for DNS in the DB system.
    Which TWO tasks are required for the network setup?

```
A. When creating the database, specify the value in the Hostname prefix.
B. Select “Use DNS Hostnames in this VCN” as the VNC being created.
```

45. While using virtual machines (VMs), the next step after selecting a shape for the DB system is to select storage options and configuration.
    Which TWO configurations can be selected and used?

```
A. Configure the storage to assign 40% to DATA and rest to redo logs and archive logs.
B. Use ASM for the storage management software.
```

46. In addition to the automatic backup of your Oracle Database associated with a database deployment, you are planning to take an on-demand backup of a database on Exadata Cloud Service.
    How do you do this?

```
a) Use the Create Backup button in the backup section of the Database Details page.
b) Disable the automatic backup configuration and then take an on-demand backup.
c) Perform a recovery operation to a specific long-term backup.
d) First connect to the Exadata Cloud Instance as the oracle user and then take a backup.
```
<span class="hidden">
Use the create backup button in the backup section of the Database details page.
</span>

47. How many DB systems must you provision before you can enable Oracle Data Guard for a virtual machine DB system database?

```
a) Three, first for the primary database, second for the standby database, and a third for the staging database in the Oracle Data Guard configuration.
b) TWo for both the primary and standby database, because a DB system with the database that you want to use as the standby must already exist before you enable Oracle Data Guard.
c) One with the primary database, because a new DB system with the standby database is created and associated with the primary database when you enable Oracle Data Guard.
d) It depends on how many standby databases you want for your primary database in the Oracle Data Guard configuration in Oracle Cloud Infrastructure.
```
<span class="hidden">One with the primary database,</span>

48. Which THREE actions can you perform on a DB system that has an Oracle Data Guard association with a standby database?

```
A. If the primary database becomes unavailable, then you can use oracle data guard to failover the standby to primary role.
B. You can use the reinstate command to return a failed database into standby role after correcting the cause of failure.
C. You can switch over the primary database to the standby role, perform maintenance on the standby database, and then switch it back to the primary role.
```

49. Which tool can be used to monitor a storage server in Exadata Cloud Service?

```
A. exacli
```

50. Your company’s security policy requires you to patch the database within a month of a relevant database patch being released by Oracle.
    Which method requires the least amount of down time?

```
A. Create a new database home, patch it to the version you want, and then move the database to the new home.
```

51. The /u02 directory containing Oracle Homes (OH) is 80% utilized and you need to free up space in it. you own two Oracle Homes (OH193_A and OH193_B), each with a test database (193A and 193B respectively).
    You decide to consolidate both databases into a single Oracle Home (OH193. |_A) to free up space. Which TWO actions must you perform?

```
a) Copy the sqinet.ora file from OH193_B to OH193_A.
b) Use the Move Database option from the console.
c) Schedule a downtime window with the Test teams who use the 193B database.
d) Create a new container under 0H193B and migrate the pluggable databases (PDBs) from 193B to 193A.
```
<span class="hidden">
b) Use the Move Database option from the console.<br>
c) Schedule a downtime window with the Test teams who use the 193B database.
</span>


<br><br>

Glossary
-----------

- ASM : Automatic Storage Management
- ASH : Active Session History
- VCN : Virtual Cloud Network
- VNC : Virtual Network Computing
- DRG : Dynamic Routing Gateway
- ZDM : Zero Downtime Migration 