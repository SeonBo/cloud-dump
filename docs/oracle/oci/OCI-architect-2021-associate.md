# Oracle Cloud Infrastructure - Architect Associate


####  Question 1
You have an Oracle Cloud Infrastructure (OCI) load balancer distributing traffic via an evenly-weighted round robin policy to your back-end web servers. You notice that one of your web servers is receiving more traffic than other web servers.
How can you resolve this to make sure traffic is evenly distributed across all back-end webservers?

```
A. Disable cookie-based session persistence on your backend set.
B. Change keep-alive setting between the load balancer and backend server.
C. Disable SSL configuration associated with your backend set.
D. Create separate listeners for each backend web server.
```
<span class="hidden">
Disable cookie-based session persistence on your backend set.
</span>



####  Question 2
You are a system administrator of your company and you are asked to manage updates and patches across all your compute instances running Oracle Linux in
Oracle Cloud Infrastructure (OCI). As part of your task, you need to apply all the latest kernel security updates to all instances.
Which OCI service will allow you to complete this task?

```
A. Resource Manager
B. OS Management
C. Storage Gateway
D. Streaming
E. Registry
```
<span class="hidden">
OS Management
</span>


###  Question 3
Which of the following statements is true about the Oracle Cloud Infrastructure (OCI) Object Storage server-side encryption?

```
A. Encryption of data encryption keys with a master encryption key is optional.
B. Customer-provided encryption keys are always stored in OCI Vault service.
C. Encryption is enabled by default and cannot be turned off.
D. Each object in a bucket
```
<span class="hidden">
Encryption is enabled by default and cannot be turned off.
</span>



####  Question 4
A financial firm is designing an application architecture for its online trading platform that must have high availability and fault tolerance. Their solutions architect configured the application to use an Oracle Cloud Infrastructure Object Storage bucket located in the US West (us-phoenix-1) region to store large amounts of financial data. The stored financial data in the bucket must not be affected even if there is an outage in one of the Availability Domains or a complete region. What should the architect do to avoid any costly service disruptions and ensure data durability?

```
A. Create a new Object Storage bucket in another region and configure lifecycle policy to move data every 5 days.
B. Copy the Object Storage bucket to a block volume.
C. Create a lifecycle policy to regularly send data from Standard to Archive storage.
D. Create a replication policy to send data to a different bucket in another OCI region.
``` 
<span class="hidden">
Create a replication policy to send data to a different bucket in another OCI region.
</span>


####  Question 5
As a solution architect, you are showcasing the Oracle Cloud Infrastructure (OCI) Object Storage feature about Object Versioning to a customer.
Which statement is true in regards to OCI Object Storage Versioning?

```
A. Object versioning does not provide data protection against accidental or malicious object update, overwrite, or deletion.
B. By default, object versioning is disabled on a bucket.
C. A bucket that is versioning-enabled can have only and always will have a latest version of the object in the bucket.
D. Objects are physically deleted from a bucket when versioning is enabled.
```
<span class="hidden">
By default, object versioning is disabled on a bucket.
</span>


####  Question 6
You are designing a lab exercise with an application that includes a large number of graphics with large file sizes. The application becomes unresponsive if the graphics are embedded in the application. You have uploaded the graphics to the Oracle Cloud Infrastructure Object Storage bucket and added the URL paths for the individual objects in the application. You need to ensure these graphics are accessible without requiring any authentication for an extended period of time. How can you achieve requirements?

```
A. Make the Object Storage bucket private, make all objects public, and use the URL found in the object “Details”.
B. Make the Object Storage bucket public and use the URL path for the individual objects.
C. Create pre-authenticated requests (PAR) and do not specify any expiration time.
D. Create pre-authenticated requests (PAR) and specify 00:00:0000 as the expiration time.
``` 
<span class="hidden">
Make the Object Storage bucket public and use the URL path for the individual objects.
</span>



####  Question 7
You have set up your environment as shown below with the Mount Target "MT" successfully mounted on both computer instances CLIENT-X and CLIENT-Y.
For security reasons you want to control the access to the File System A in such a way that CLIENT-X has READ/WRITE and CLIENT-Y has READ only permission.

```
A. Update the OS firewall in CLIENT-X to allow READ/WRITE access.
B. Update the security list TWO to restrict CLIENT-Y access to read-only.
C. Update the mount target export options to restrict CLIENT-Y access to read-only.
D. Update the security list ONE to restrict CLIENT-Y access to read only.
```
<span class="hidden">
Update the mount target export options to restrict CLIENT-Y access to read-only.
</span>


####  Question 8
You are about to upload a large log file (5 TiB size) to Oracle Cloud Infrastructure object storage and have decided to use multipart upload capability for a more efficient and resilient upload. Which two statements are true about multipart upload?(Choose two)

```
A. The maximum size for an uploaded object is 10 TiB. 
B. You do not have to commit the upload after you have uploaded all the object parts. 
C. While a multipart upload is still active, you cannot add parts even if the total number of parts is less than 10,000. 
D. Individual object parts can be as small as 10 MiB or large as 50 GiB.
```
<span class="hidden">
The maximum size for an uploaded object is 10 TiB. <br>
Individual object parts can be as small as 10 MiB or large as 50 GiB.
</span>


####  Question 9
You are running an online gaming application hosted on a VM.Standard2.1 instance shape in Oracle Cloud Infrastructure. As the game becomes popular, you identify network throughput as a bottleneck on your instance when uploading user data.
Though you want to resolve the issue, you want to observe the demand for a week before adding new application instances.
Which action is the most efficient way to resolve this issue?

```
A. Add a secondary virtual network interface card (VNIC).
B. Change the shape of the instance to a higher network bandwidth instance.
C. Delete the instance while preserving boot volume and spin up a new higher network bandwidth instance with this boot volume.
D. Change the performance tier of attached block volume to High Performance.
```
<span class="hidden">
Change the shape of the instance to a higher network bandwidth instance.
</span>


####  Question 10
You have an AI/ML application running on Oracle Cloud Infrastructure. You identified that the application needs GPU and at least 20Gbps Network throughput.
The application is currently using a VM.Standard2.1 compute without any block storage attached to it.
Which two options allow you to get your required performance for your application? (Choose two.)

```
A. Terminate the compute instance preserving the boot volume. Create a new compute instance using the BM.GPU2.2 shape using the boot volume preserved, but no block volume attached.
B. Terminate the compute instance preserving the boot volume. Create a new compute instance using the VM.Standard2.2 shape using the boot volume preserved, but no block volume attached.
C. Terminate the compute instance preserving the boot volume. Create a new compute instance using the VM.GPU3.4 shape using the boot volume preserved and use the NVMe devices to host your application.
D. Terminate the compute instance preserving the boot volume. Create a new compute instance using the BM.HPC2.36 shape using the boot volume preserved and use the NVMe devices to host your application.
E. Terminate the compute instance preserving the boot volume. Create a new compute instance using the BM.GPU2.2 shape using the boot volume preserved and attach a new block volume to host your application.
``` 
<span class="hidden">
Terminate the compute instance preserving the boot volume. Create a new compute instance using the BM.GPU2.2 shape using the boot volume preserved, but no block volume attached. <br>
Terminate the compute instance preserving the boot volume. Create a new compute instance using the BM.GPU2.2 shape using the boot volume preserved and attach a new block volume to host your application.
</span>


####  Question 11
You deployed a database on a Standard Compute instance in Oracle Cloud Infrastructure (OCI) due to cost concerns. The database requires additional storage with high I/O and you decided to use OCI Block Volume service for it. With this requirement in mind, which elastic performance option should you choose for the Block Volume?

```
A. Lower cost 
B. Extreme performance 
C. Higher performance 
D. Balanced performance
``` 
<span class="hidden">
Higher performance 
</span>


####  Question 12
You created a virtual cloud network (VCN) with three private subnets. Two of the subnets contain application servers and the third subnet contains a DB System. The application requires a shared file system so you have provisioned one using the file storage service (FSS). You also created the corresponding mount target in one of the application subnets. The VCN security lists are properly configured so that the application servers can access file storage service (FSS). The security team changed the settings for the DB System to have read-only access to the file system. However when they went to test this they are unable to access the (FSS). What change should you make to allow access to (FSS)?

```
A. Create an instance principal for the DB System. Write an Identity and Access Management (IAM) policy that allows the instance principal read-only access to the file storage service. 
B. Modify the security list associated with the subnet where the mount target resides. Change the ingress security rules corresponding to the DB System subnet to be stateful. 
C. Modify the security list associated with the subnet where the mount target resides. Change the ingress security rules corresponding to the DB System subnet to be stateless. 
D. Create an NFS export option that allows READ_ONLY access where the source is the CIDR range of the DB System subnet.
``` 
<span class="hidden">
Create an NFS export option that allows READ_ONLY access where the source is the CIDR range of the DB System subnet.
</span>


####  Question 13
Your company uses the Oracle Cloud Infrastructure (OCI) Object Storage service to share large data sets with its data science team. The data science team consists of 20 people who work from offices in Washington, D.C., and Tokyo. While working in these offices, employees are assigned an IP address from the public IP range 129.146.31.0/27
Which two steps should you take to ensure that the Object Storage bucket used in this scenario was only accessible from these office locations? (Choose two.)

```
A. Write an IAM policy that includes the conditional statement where request.networkSource.name = CorpNet
B. Set the bucket visibility to public and only share the URL with the data science team via email
C. Create a pre-authenticated request for each data set and only share with the data science team via email
D. Create a Network Source named CorpNetwork with a CIDR block of 129.146.31.0/27
E. Create a Network Source named CorpNetwork with a CIDR block of 129.146.0.0/16
F. Write an IAM policy that includes the conditional statement where request.region = 129.146.31.0/27
``` 
<span class="hidden">
Write an IAM policy that includes the conditional statement where request.networkSource.name = CorpNet <br>
Create a Network Source named CorpNetwork with a CIDR block of 129.146.31.0/27
</span>


####  Question 14
Which two resources reside exclusively in a single Oracle Cloud Infrastructure Availability Domain? (Choose two.)

```
A. Identity and Access Management Groups
B. Object Storage
C. Web Application Firewall policy
D. Block volume
E. Compute instance
``` 
<span class="hidden">
Block volume <br>
Compute instance
</span>



####  Question 15
Which two statements about Oracle Cloud Infrastructure File Storage Service are accurate? (Choose two.)

```
A. Customer can encrypt the communication to a mount target via export options.
B. Mount targets use Oracle-managed keys by default.
C. File systems use Oracle-managed keys by default.
D. Customer can encrypt data in their file system using their own Vault encryption key.
E. Communication with file systems in a mount target is encrypted via HTTPS.
``` 
<span class="hidden">
File systems use Oracle-managed keys by default. <br>
Customer can encrypt data in their file system using their own Vault encryption key.
</span>


####  Question 16
You deployed an Oracle Cloud Infrastructure (OCI) compute instance (VM.Standard2.16) to run a SQL database. After a few weeks, you need to increase disk performance by using NVMe disks but keeping the same number of CPUs. As a first step, you terminate the instance and preserve the boot volume. What is the next step?
```
A. Create a new instance using a VM.Standard1.16 shape using the preserved boot volume and move the SQL Database data to NVMe disks.
B. Create a new instance using a VM.DenseIO2.8 shape using the preserved boot volume and move the SQL Database data to NVMe disks.
C. Create a new instance using a VM.DenseIO2.16 shape using the preserved boot volume and move the SQL Database data to block volume.
D. Create a new instance using a VM.DenseIO2.16 shape using the preserved boot volume and move the SQL Database data to NVMe disks.
```
<span class="hidden">
Create a new instance using a VM.DenseIO2.16 shape using the preserved boot volume and move the SQL Database data to NVMe disks 
</span>



####  Question 17
Which two statements below are correct with respect to adding secondary Virtual Network Interface Cards (VNICs) to an existing compute instance in Oracle
Cloud Infrastructure? (Choose two.)

```
A. The secondary VNIC is required to be in the same Virtual Cloud Network (VCN), but can be in a different subnet, as the primary VNIC.
B. The primary and secondary VNIC association can be in different virtual cloud networks (VCNs).
C. You cannot assign an Ephemeral Public IP to a secondary VNIC.
D. The primary and secondary VNIC association must be in the same availability domain.
E. You can remove the primary VNIC after the secondary VNIC's attachment is complete.
```
<span class="hidden">
The primary and secondary VNIC association can be in different virtual cloud networks (VCNs).
<br>
The primary and secondary VNIC association must be in the same availability domain.
</span>


####  Question 18
You provisioned an Oracle Autonomous Data Warehouse (ADW) on Oracle Cloud Infrastructure (OCI) and imported data into ADW.
You want to give your business analyst the ability to connect to the ADW database and run queries.
Which two actions can help you meet this requirement? (Choose two.)

```
A. Create a database user account for the business analyst.
B. Grant the predefined database role DWROLE to the database user.
C. Grant unlimited tablespace privilege to the database user.
D. Grant the predefined database role DWADW to the database user.
E. Grant the predefined database role DWUSER to the database user. 
``` 
<span class="hidden">
Create a database user account for the business analyst.
<br>
Grant the predefined database role DWROLE to the database user.
</span>


####  Question 19
Which two statements are true about restoring a volume from a block volume backup in Oracle Cloud Infrastructure Block Volume service? (Choose two.)

``` 
A. You can restore a volume to any availability domain within the same region where the backup is stored.
B. You can restore only one volume from a manual block volume backup.
C. You can restore a volume from any full volume backup but not from an incremental backup.
D. You can restore a block volume backup to a larger volume size.
E. You can only restore a volume to the same availability domain in which the original block volume resides.
``` 
<span class="hidden">
You can restore a volume to any availability domain within the same region where the backup is stored.
<br>
You can restore a block volume backup to a larger volume size.
</span>


####  Question 20
What happens after you successfully run the following command on your Oracle Cloud Infrastructure Container Engine for Kubernetes (OKE) using the YAML file defined below? kubectl create -f definition.yml

YAML file "" definition.yml –

``` 
A. A single Pod with a single container is created.
B. Two Pods with a container each are created.
C. A single Pod with two containers is created.
D. No Pod gets created.
``` 
<span class="hidden">
A single Pod with two containers is created.
</span>



####  Question 21
You create an autoscaling configuration of Linux compute instances in Oracle Cloud Infrastructure (OCI). You noticed that your application is running slow. After checking your compute instances, you noticed that autoscaling is not launching additional instances, even though the existing compute instances already have high memory usage. How can you resolve this issue?

```
A. Modify the scaling policy to monitor CPU usage and scale up the number of instances when it meets the threshold. 
B. install OCI SDK in all compute instances and create a script that will trigger the autoscaling event if there is high memory usage. 
C. Install the monitoring agent to all compute instances which will trigger the autoscaling group. 
D. Modify the scaling policy to monitor memory usage and scale up the number of instances when it meets the threshold.
```
<span class="hidden">
Modify the scaling policy to monitor memory usage and scale up the number of instances when it meets the threshold.
</span>



####  Question 22
As a solution architect, you designed the network infrastructure of a three-tier web application on Oracle Cloud Infrastructure (OCI) and the back-end database servers are put in a private subnet. One of your database administrators requests to have private access to OCI object storage service.
How should you fulfill this request?

```
A. Add a new route rule to the private subnet route table to route default traffic to the internet gateway.
B. Attach a public IP address to the instances in the private subnet, and then add a new route rule to the private subnet route table to route default traffic to the internet gateway.
C. Create a dynamic routing gateway (DRG) and attach it to your virtual cloud network (VCN). Add a default route rule to the private subnets route table and set the target as DRG.
D. Create a service gateway, add a new route rule to the private subnet route table that uses object storage as target type.
``` 
<span class="hidden">
Create a service gateway, add a new route rule to the private subnet route table that uses object storage as target type.
</span>



####  Question 23
You have multiple applications installed on a compute instance and these applications generate a large amount of log files. These log files must reside on the boot volume for a minimum of 15 days.
Any log files over 15 days shouldn't be on boot volume but still must be retained for at least 60 days. The 60-day retention requirement is causing an issue with available disk space.
What are two Oracle recommended methods to retain the log files for 60 days without filling up the boot volume? (Choose two.)

```
A. Terminate the instance while preserving the boot volume. Create a new instance from the boot volume and select a DenseIO shape to take advantage of local NVMe storage.
B. Resize the boot volume of the instance.
C. Create and attach a block volume to the compute instance and copy the log files.
D. Create an object storage bucket and use a script that runs daily to move log files older than 15 days to the bucket.
E. Write a custom script to remove the log files on a daily basis and free up the space on the boot volume.
```
<span class="hidden">
Resize the boot volume of the instance.
<br>
Create an object storage bucket and use a script that runs daily to move log files older than 15 days to the bucket.
</span>



####  Question 24
You are responsible for creating and maintaining an enterprise application that consists of multiple storage volumes across multiple compute instances in Oracle
Cloud Infrastructure (OCI).
The storage volumes include boot volumes and block volumes for your data storage. You need to create backups of these storage volumes in the most time- efficient manner.
How can you meet this requirement?

```
A. Create clones of all boot volumes and block volumes one at a time.
B. Create on-demand full backups of boot volumes, and copy data in block volumes to Object Storage using OCI CLI.
C. Create on-demand full backups of block volumes, and create custom images from the boot volumes.
D. Group together multiple storage volumes in a volume group and create volume group backups.
```
<span class="hidden">
Group together multiple storage volumes in a volume group and create volume group backups.
</span>


####  Question 25
1. Which OCI Identity and Access Management(IAM) policy is invalid?

```
A. Allow any-user to inspect users in tenancy
B. Allow all-groups to inspect users in tenancy
C. Allow group A-Admins to manage all-resources in compartment Dev
D. Allow dynamic-group FrontEnd to manage instance-family in compartment Dev
```
<span class="hidden">
Allow all-groups to inspect users in tenancy
</span>



####  Question 26
Your organization has set up the following tag namespace and key to tag each group by its role: EmployeeGroup.Role All your admin groups are tagged with EmployeeGroup.Role='Admin' Now you want to set up a Test compartment for members of the three projects to share and need to give admin access to all three of your existing admin groups. Which policy should you write to accomplish this task?

```
A. allow any-user to manage all-resources in compartment Test where request.principal.group.tag.EmployeeGroup.Role='Admin’
B. allow any-group to manage all-resources in compartment Test where request.principal.group.tag.EmployeeGroup.Role='Admin’
C. allow group any-group to manage all-resources in compartment Test where request.principal.group.tag.EmployeeGroup.Role='Admin’
D. allow an-group any-group to manage all-resources in compartment Test where request.principal.group.tag.EmployeeGroup.Role='Admin'
```
<span class="hidden">
allow any-group to manage all-resources in compartment Test where request.principal.group.tag.EmployeeGroup.Role='Admin’
</span>



####  Question 27
You want to create a policy to allow the NetworkAdmins group to manage VCN in Compartment C. You want to attach this policy to the tenancy. The compartment hierarchy is shown as below: Which policy statement can be used to accomplish this task?

```
A. Allow group NetworkAdmins to manage virtual-network-family in compartment A:B:C 
B. Allow group NetworkAdmins to manage virtual-network-family in tenancy 
C. Allow group NetworkAdmins to manage virtual-network-family in compartment B:C 
D. Allow group NetworkAdmins to manage virtual-network-family in compartment C
```
<span class="hidden">
Allow group NetworkAdmins to manage virtual-network-family in compartment A:B:C 
</span>



####  Question 28
Which is not a valid option for an Oracle Cloud Infrastructure (OCI) compute shape?
```
A. Bare metal 
B. Dedicated VM Host 
C. VM(Virtual Machine) 
D. Exadata VM
```
<span class="hidden">
Exadata VM
</span>



####  Question 29
You just got a last-minute request to create a set of instances in OCI. The configuration and installed software are identical for every instance and you already have a running instance in your OCI tenancy. Which image option will allow to you achieve this task with the least amount of effort?

```
A. Use Oracle-provided images and customize the installation using a third-party tool. 
B. Select an image from the OCI marketplace. 
C. Bring your own image and use it as a template for new instances. 
D. Create a custom image and use it as a template for the new instances.
```
<span class="hidden">
Create a custom image and use it as a template for the new instances.
</span>



####  Question 30
You have a high-demand web application running on OCI. Your tenancy administrator has set up a schedule-based autoscaling policy on instance pool with initial size of 5 instances for the application.

```
policy 1: Target pool size : 10 
Instances Execution time : 8:30 a.m.
on every Monday through Friday, in every month, in every year Cron expression : 0 30 8 ? * MON-FRI *
```

which statement accurately explains the goal of this policy?

```
A. Goal: A recurring monthly schedule. On all days of the month, set the initial pool size to 5 instances. At 8.30 a.m., on every day of the month, scale out to 10 instances. 
B. Goal: A one-time schedule with only one scaling out event. At 8:30 a.m., on December 31, 2021, scale the instance pool to 10 instances from 5. 
C. Goal: A recurring daily schedule. On weekday mornings at 8.30 a.m., scale out to 10 instances. 
D. Goal: A recurring weekly schedule. On all days of the week at 8.30 a.m., scale out the pool to 10 instances from the initial size of 5
```
<span class="hidden">
Goal: A recurring daily schedule. On weekday mornings at 8.30 a.m., scale out to 10 instances.
</span>



####  Question 31
Which two statements are true about Oracle Cloud Infrastructure IPSec VPN Connect?(Choose two)

```
A. Each OCI IPSec VPN consists of multiple redundant IPSec tunnels 
B. OCI IPSec VPN tunnel supports only static routes to route traffic 
C. OCI IPSec VPN can be configured in tunnel mode only 
D. OCI IPSec VPN can be configured in transport mode only
```
<span class="hidden">
Each OCI IPSec VPN consists of multiple redundant IPSec tunnels <br> 
OCI IPSec VPN can be configured in tunnel mode only 
</span>



####  Question 32

Which TWO statements are true about private IP objects?(Choose two)

```
A. You can add a secondary private IP to either the primary VNIC or a secondary VNIC of an instance after it's launched. 
B. Each instance receives a primary private IP object and a secondary private IP object at launch. 
C. Secondary private IPs must be manually deleted when you terminate the mapped instance. 
D. A private IP can have a public IP assigned to it.
```
<span class="hidden">
You can add a secondary private IP to either the primary VNIC or a secondary VNIC of an instance after it's launched.<br>
A private IP can have a public IP assigned to it.
</span>



####  Question 33
Which three protocols are supported by the OCI network load balancer? (Choose three)

```
A. ISCSI 
B. TCP 
C. HTTP 
D. UDP 
E. BGP 
F. ICMP
```
<span class="hidden">
TCP, UDP, ICMP
</span>


####  Question 34
Your DevOps team needs to interconnect the on-premises network to OCI resources such as a managed database that reside in a private subnet. They indicated that they have a low budget and their bandwidth requirements are minimal, so you decide that site-to-site VPN is the best option. They provided you with their router IP address. You need to create an object in OCI that represents this router.
What object should you create?

```
A. Bastion Host 
B. Internet Gateway 
C. Customer Premises Equipment (CPE) 
D. Virtual Network Interface Card 
E. Dynamic Routing Gateway(DRG) 
F. IPSec Tunnel
```
<span class="hidden">
Customer Premises Equipment (CPE) 
</span>


####  Question 35
What two use cases to use FastConnect when connecting to a Virtual Cloud Network from on-premises?(Choose two)

```
A. Deploy small scale production applications. 
B. Serve applications that are latency sensitive and require consistent network performance. 
C. Provide encrypted communication over the internet. 
D. Support solutions that require large amounts of data transfer.
```
<span class="hidden">
Serve applications that are latency sensitive and require consistent network performance. <br>
Support solutions that require large amounts of data transfer.
</span>



####  Question 36
Which RFC 1918 CIDR range is allowed in OCI?

```
A. 0.0.0.0/0 
B. 8.8.8.8/8 
C. 10.0.0.0/8 
D. 172.16.0.0/12 
E. 192.168.0.0/16
```
<span class="hidden">
192.168.0.0/16
</span>


####  Question 37
When creating an OCI VCN with the VCN wizard, what three gateways get created automatically?(Choose three)

```
A. Internet Gateway(IGW) 
B. Service Gateway(SGW) 
C. NAT Gateway 
D. DRG 
E. Bastion Host 
F. Local Peering Gateway 
G. Storage Gateway
```
<span class="hidden">
Internet Gateway(IGW) <br> 
Service Gateway(SGW) <br>
NAT Gateway 
</span>



####  Question 38
Which is NOT a valid Oracle Cloud Infrastructure Virtual Cloud Network (VCN) approach?

```
A. Private subnets are recommended to have individual route tables to control the flow of traffic within and outside of VCN. 
B. Use OCI tags to tag VCN resources so that all resources are following organizational tagging/naming conventions. 
C. Ensure VCN CIDR prefix overlaps with other VCNs in your tenancy or with your organizations private IP network ranges. 
D. Ensure not all IP addresses are allocated at once within a VCN or subnet, instead plan to reserve some IP addresses for future use
```
<span class="hidden">
Ensure VCN CIDR prefix overlaps with other VCNs in your tenancy or with your organizations private IP network ranges
</span>



####  Question 39
Which is NOT a valid action within the Oracle Cloud Infrastructure (OCI) Block Volume service?

```
A. Restore from a volume backup to a larger volume. 
B. Attach a block volume to an instance in a different availability domain. 
C. Clone an existing volume to a new, larger volume. 
D. Expand an existing volume in place with offline resizing.
```
<span class="hidden">
Attach a block volume to an instance in a different availability domain. 
</span>


####  Question 40
Which of the following statements is true about cloning a volume in Oracle Cloud Infrastructure Block Volume service? Please select two.(Choose two)

```
A. Creating a clone takes longer than creating a backup of a volume. 
B. You can clone a volume to another region. 
C. You need to detach a volume before cloning it. 
D. Creating a clone of a boot volume requires you to stop the instance. 
E. Cloning a volume is faster than creating a backup. 
F. You can clone a boot volume while the instance is still running.
```
<span class="hidden">
Cloning a volume is faster than creating a backup. <br>
You can clone a boot volume while the instance is still running.
</span>



####  Question 41
Database admins and app developers want to run OLTP and OLAP workloads directly from their MySQL database, thus eliminating the need for complex, time-consuming, and expensive data movement and integration with a separate analytics database? Which feature of MySQL database service enables this?

```
A. ElastiCache
B. Heatwave
C. Automatic Memory Management
D. Exalogic****
``` 
<span class="hidden">
Heatwave
</span>



####  Question 42
What version of the database includes Active Data guard in OCI?

```
A. Enterprise Edition - Extreme Performance
B. Enterprise Edition - High Performance
C. Enterprise Edition
D. Standard Edition
```
<span class="hidden">
Enterprise Edition - Extreme Performance
</span>



####  Question 43
Which TWO predefined service names can you use when connecting to an Oracle Cloud Infrastructure Autonomous Data Warehouse?

```
A. Medium for a lower level of resources to process each SQL statement.
B. TP for a connection service for when you do not want to run with parallelism.
C. High for the highest level of resources to process each SQL statement.
D. TPUrgent for a connection service for when you do want to run with parallelism.
``` 
<span class="hidden">
Medium for a lower level of resources to process each SQL statement.<br>
High for the highest level of resources to process each SQL statement.
</span>



####  Question 44
Which statement is true about patching an OCI DB system?

```
A. Once you pre-check the patches for your database, the system will automatically apply the patches for you.
B. There is no automation with patching, you need to check for patches and manually check and schedule when to apply the patches.
C. Patching is automatically pre-checked and applied to the database.
D. Once you pre-check the patches for your database, you can decide to apply the patches immediately or schedule a time to apply the patches.
```
<span class="hidden">
Once you pre-check the patches for your database, you can decide to apply the patches immediately or schedule a time to apply the patches.
</span>


####  Question 45
Which statement is NOT true about the Oracle Cloud Infrastructure Object Storage service?

```
A. Object storage resources can be shared across tenancies.
B. Immutable option for data stored in the Object Storage can be set via retention rules.
C. Object versioning is enabled at namespace level.
D. Object lifecycle rules can be used to either archive or delete objects.
```
<span class="hidden">
Object versioning is enabled at namespace level.
</span>



####  Question 46
Which option is NOT a valid action within the Oracle Cloud Infrastructure (OCI) Block Volume service?

```
A. Clone an existing volume to a new, larger volume.
B. Restore from a volume backup to a larger volume.
C. Shrink an existing volume in place with offline resizing.
D. Expand an existing volume in place with offline resizing.
```   
<span class="hidden">
Shrink an existing volume in place with offline resizing.
</span>



####  Question 47
Which statement is true about Data Guard implementation in Oracle Cloud Infrastructure (OCI) bare metal and virtual machine database systems?

```
A. Both database systems must be in the same compartment.
B. Primary and standby database versions and editions need not be identical.
C. Primary and standby databases must be in the same OCI region.
D. Database systems need not be the same shape type (e.g., primary database can be a virtual machine, and standby database a bare metal shape, and vice versa).
``` 
<span class="hidden">
Both database systems must be in the same compartment.
</span>


####  Question 48
Your company decided to move a few applications to Oracle Cloud Infrastructure (OCI) in the US West (us-phoenix-1) region.
You need to design a cloud-based disaster recovery (DR) solution with a requirement to deploy the DR resources in the US East (us-ashburn-1) region to minimize network latency.
What is the recommended deployment?

```
A. Deploy production and DR applications in two separate virtual cloud networks (VCNs), each in different regions, and then use VCN local peering gateways for connectivity.
B. Deploy production and DR applications in two separate VCNs, each in different regions. Connect them using a VCN remote peering connection.
C. Deploy production and DR applications in the same VCN. Create production subnets in one AD, and DR subnets in another AD (assume a multi-AD region).
D. Deploy production and DR applications in two separate VCNs in different availability domains (ADs) within the primary region, and then use a VCN remote peering connection for connectivity.
``` 
<span class="hidden">
Deploy production and DR applications in two separate VCNs, each in different regions. Connect them using a VCN remote peering connection.
</span>


####  Question 49
A customer launched a compute instance in the Virtual Cloud Network (VCN), which has an internet gateway, a service gateway, a default security list and a default route table. The customer opened up Port 22 in the security lists attached to the compute instance subnet, however is still unable to connect to compute instances using SSH.
Which action can resolve this issue?

```
A. Modify the security list associated with the VCN subnet in which the instance resides. Add a stateful egress rule to allow ICMP traffic in addition to the port 22.
B. Modify the route table associated with the VCN subnet in which the instance resides. Add a following route to the route table: Destination CIDR: 0.0.0.0/0 Target: Service Gateway (SGW)
C. Modify the route table associated with the VCN subnet in which the instance resides. Add a following route to the route table: Destination CIDR: 0.0.0.0/0 Target: Dynamic Routing Gateway (DRG)
D. Modify the route table associated with the VCN subnet in which the instance resides. Add a following route to the route table: Destination CIDR: 0.0.0.0/0 Target: Internet Gateway (IGW)
``` 
<span class="hidden">
Modify the route table associated with the VCN subnet in which the instance resides. Add a following route to the route table: Destination CIDR: 0.0.0.0/0 Target: Internet Gateway (IGW)
</span>


##  Question 50
Your company has been running several small applications in Oracle Cloud Infrastructure and is planning a proof-of-concept (POC) to deploy Oracle PeopleSoft.
If your existing resources are being maintained in the root compartment, what is the recommended approach for defining security for the upcoming POC?

```
A. Create a new compartment for the POC and grant appropriate permissions to create and manage resources within the compartment.
B. Create a new tenancy for the POC and provision all new resources into the root compartment. Grant appropriate permissions to create and manage resources within the root compartment.
C. Provision all new resources into the root compartment. Use defined tags to separate resources that belong to different applications.
D. Provision all new resources into the root compartment. Grant permissions that only allow for creation and management of resources specific to the POC.
```
<span class="hidden">
Create a new compartment for the POC and grant appropriate permissions to create and manage resources within the compartment.
</span>



##  Question 51
Which two are Regional resources in Oracle Cloud Infrastructure? (Choose two.)

A. Ephemeral public IPs
B. Compartments
C. Compute images
D. Dynamic groups
E. Block volume backups
