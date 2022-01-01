## OCI Developer 2021 Associate (1Z0-1084-21)


#####  Question 1
Which statement accurately describes Oracle Cloud Infrastructure (OCI) Load Balancer integration with OCI Container Engine for Kubernetes (OKE)?

```
A. OKE service provisions an OCI Load Balancer instance for each Kubernetes service with LoadBalancer type in the YAML configuration.
B. OCI Load Balancer instance provisioning is triggered by OCI Events service for each Kubernetes service with LoadBalancer type in the YAML configuration.
C. OCI Load Balancer instance must be manually provisioned for each Kubernetes service that requires traffic balancing.
D. OKE service provisions a single OCI Load Balancer instance shared with all the Kubernetes services with LoadBalancer type in the YAML configuration.
```
<span class="hidden">
OKE service provisions a single OCI Load Balancer instance shared with all the Kubernetes services with LoadBalancer type in the YAML configuration.
</span><br>


#####  Question 2
Per CAP theorem, in which scenario do you NOT need to make any trade-off between the guarantees? 

```
A. when the are no network partitions
B. when the system is running in the cloud
C. when the system is running on-premise
D. when you are using load balancers
```
<span class="hidden">
when the are no network partitions
</span><br>


#####  Question 3
You have two microservices, A and B running in production. Service A relies on APIs from service B. You want to test changes to service A without deploying all of its dependencies, which includes service B.
Which approach should you take to test service A?

```
A. Test against production APIs.
B. Test using API mocks.
C. There is no need to explicitly test APIs.
D. Test the APIs in private environments.
```
<span class="hidden">
Test using API mocks.
</span><br>


#####  Question 4
In a Linux environment, what is the default location of the configuration file that Oracle Cloud Infrastructure CLI uses for profile information?

```
A. /etc/.oci/config
B. /usr/local/bin/config
C. $HOME/.oci/config
D. /usr/bin/oci/config
```
<span class="hidden">
C. $HOME/.oci/config
</span><br>



#####  Question 5
Which statement is incorrect with regards to the Oracle Cloud Infrastructure (OCI) Notifications service?

```
A. Notification topics may be assigned as the action performed by an OCI Events configuration.
B. OCI Alarms can be configured to publish to a notification topic when triggered.
C. An OCI function may subscribe to a notification topic.
D. A subscription can forward notifications to an HTTPS endpoint.
E. A subscription can integrate with PagerDuty events.
F. It may be used to receive an email each time an OCI Autonomous Database backup is completed.
```
<span class="hidden">
It may be used to receive an email each time an OCI Autonomous Database backup is completed.
</span><br>


#####  Question 6
With the volume of communication that can happen between different components in cloud-native applications, it is vital to not only test functionality, but also service resiliency.
Which statement is true with regards to service resiliency?

```
A. Resiliency is about recovering from failures without downtime or data loss.
B. A goal of resiliency is not to bring a service to a functioning state after a failure.
C. Resiliency testing can be only done in a test environment.
D. Resiliency is about avoiding failures.
```
<span class="hidden">
Resiliency is about avoiding failures.
</span><br>


#####  Question 7
Which two are required to enable Oracle Cloud Infrastructure (OCI) Container Engine for Kubernetes (OKE) cluster access from the kubectl CLI? (Choose two.)

```
A. An SSH key pair with the public key added to cluster worker nodes.
B. Install and configure the OCI CLI
C. OCI Identity and Access Management Auth Token
D. Tiller enabled on the OKE cluster
E. A configured OCI API signing key pair
```
<span class="hidden">
B. Install and configure the OCI CLI <br>
E. A configured OCI API signing key pair
</span><br>


#####  Question 8
You have a containerized app that requires an Autonomous Transaction Processing (ATP) Database. Which option is not valid for connecting to ATP from a container in Kubernetes?

```
A. Enable Oracle REST Data Services for the required schemas and connect via HTTPS.
B. Create a Kubernetes secret with contents from the instance Wallet files. Use this secret to create a volume mounted to the appropriate path in the application deployment manifest.
C. Use Kubernetes secrets to configure environment variables on the container with ATP instance OCID, and OCI API credentials. Then use the CreateConnection API endpoint from the service runtime.
D. Install the Oracle Cloud Infrastructure Service Broker on the Kubernetes cluster and deploy ServiceInstance and ServiceBinding resources for ATP. Then use the specified binding name as a volume in the application deployment manifest.
```
<span class="hidden">
Install the Oracle Cloud Infrastructure Service Broker on the Kubernetes cluster and deploy ServiceInstance and ServiceBinding resources for ATP. Then use the specified binding name as a volume in the application deployment manifest.
</span><br>


#####  Question 9
In order to effectively test your cloud-native applications, you might utilize separate environments (development, testing, staging, production, etc.)
Which Oracle Cloud Infrastructure (OCI) service can you use to create and manage your infrastructure?

```
A. OCI Compute
B. OCI Container Engine for Kubernetes
C. OCI Resource Manager
D. OCI API Gateway
```
<span class="hidden">
OCI Resource Manager
</span><br>


#####  Question 10
You are tasked with developing an application that requires the use of Oracle Cloud Infrastructure (OCI) APIs to POST messages to a stream in the OCI
Streaming service.
Which statement is incorrect?

```
A. The request must include an authorization signing string including (but not limited to) x-content-sha256, content-type, and content-length headers.
B. The Content-Type header must be set to application/json
C. An HTTP 401 will be returned if the client's clock is skewed more than 5 minutes from the server's.
D. The request does not require an Authorization header.
```
<span class="hidden">
The request does not require an Authorization header.
</span><br>


#####  Question 11
You are working on a serverless DevSecOps application using Oracle Functions. You have deployed a Python function that uses the Oracle Cloud Infrastructure
(OCI) Python SDK to stop any OCI Compute instance that does not comply with your corporate security standards. There are 3 non-compliant OCI Compute instances.
However, when you invoke this function none of the instances were stopped.
How should you troubleshoot this?

```
A. There is no way to troubleshoot a function running on Oracle Functions.
B. Enable function logging in the OCI console, include some print statements in your function code and use logs to troubleshoot this.
C. Enable function remote debugging in the OCI console, and use your favorite IDE to inspect the function running on Oracle Functions.
D. Enable function tracing in the OCI console, and go to OCI Monitoring console to see the function stack trace.
```
<span class="hidden">
Enable function remote debugging in the OCI console, and use your favorite IDE to inspect the function running on Oracle Functions.
</span><br>


#####  Question 12
Which is NOT a valid option to execute a function deployed on Oracle Functions?

```
A. Send a signed HTTP requests to the function's invoke endpoint
B. Invoke from Oracle Cloud Infrastructure CLI
C. Invoke from Docker CLI
D. Trigger by an event in Oracle Cloud Infrastructure Events service
E. Invoke from Fn Project CLI
```
<span class="hidden">
C. Invoke from Docker CLI
</span><br>


#####  Question 13
You are developing a polyglot serverless application using Oracle Functions.
Which language cannot be used to write your function code?

```
A. PL/SQL
B. Python
C. Node.js
D. Go
E. Java
```
<span class="hidden">
PL/SQL
</span><br>


#####  Question 14
Which two statements accurately describe an Oracle Functions application?

```
A. A small block of code invoked in response to an Oracle Cloud Infrastructure (OCI) Events service
B. A Docker image containing all the functions that share the same configuration
C. An application based on Oracle Functions, Oracle Cloud Infrastructure (OCI) Events and OCI API Gateway services
D. A common context to store configuration variables that are available to all functions in the application
E. A logical group of functions
```
<span class="hidden">
A common context to store configuration variables that are available to all functions in the application
<br>A logical group of functions
</span><br>


#####  Question 15
You are processing millions of files in an Oracle Cloud Infrastructure (OCI) Object Storage bucket. Each time a new file is created, you want to send an email to the customer and create an order in a database. The solution should perform and minimize cost.
Which action should you use to trigger this email?

```
A. Schedule a cron job that monitors the OCI Object Storage bucket and emails the customer when a new file is created.
B. Use OCI Events service and OCI Notification service to send an email each time a file is created.
C. Schedule an Oracle Function that checks the OCI Object Storage bucket every minute and emails the customer when a file is found.
D. Schedule an Oracle Function that checks the OCI Object Storage bucket every second and emails the customer when a file is found.
```
<span class="hidden">
Use OCI Events service and OCI Notification service to send an email each time a file is created.
</span><br>


#####  Question 16
You are using Oracle Cloud Infrastructure (OCI) Resource Manager to manage your infrastructure lifecycle and wish to receive an email each time a Terraform action begins.
How should you use the OCI Events service to do this without writing any code?

```
A. Create an OCI Notifications topic and email subscription with the destination email address. Then create an OCI Events rule matching "Resource Manager Stack "" Update" condition, and select the notification topic for the corresponding action.
B. Create an OCI Notifications topic and email subscription with the destination email address. Then create an OCI Events rule matching "Resource Manager Job "" Create" condition, and select the notification topic for the corresponding action.
C. Create a rule in OCI Events service matching the "Resource Manager Stack "" Update" condition. Then, select "Action Type: Email" and provide the destination email address.
D. Create an OCI Email Delivery configuration with the destination email address. Then create an OCI Events rule matching "Resource Manager Job "" Create" condition, and select the email configuration for the corresponding action.
```
<span class="hidden">
Create an OCI Notifications topic and email subscription with the destination email address. Then create an OCI Events rule matching "Resource Manager Job "" Create" condition, and select the notification topic for the corresponding action.
</span><br>


#####  Question 17
A service you are deploying to Oracle Cloud Infrastructure (OCI) Container Engine for Kubernetes (OKE) uses a docker image from a private repository in OCI
Registry (OCIR).
Which configuration is necessary to provide access to this repository from OKE?

```
A. Add a generic secret on the cluster containing your identity credentials. Then specify a registryCredentials property in the deployment manifest.
B. Create a docker-registry secret for OCIR with API key credentials on the cluster, and specify the imagePullSecret property in the application deployment manifest.
C. Create a docker-registry secret for OCIR with identity Auth Token on the cluster, and specify the imagePullSecret property in the application deployment manifest.
D. Create a dynamic group for nodes in the cluster, and a policy that allows the dynamic group to read repositories in the same compartment.
```
<span class="hidden">
Create a docker-registry secret for OCIR with identity Auth Token on the cluster, and specify the imagePullSecret property in the application deployment manifest.
</span><br>


#####  Question 18
Given a service deployed on Oracle Cloud Infrastructure Container Engine for Kubernetes (OKE), which annotation should you add in the sample manifest file below to specify a 400 Mbps load balancer? (Choose the best answer.)

![1z0-1084-21-q18-01](images/1z0-1084-21-q18-01.png)

```
A. service.beta.kubernetes.io/oci-load-balancer-kind: 400Mbps
B. service.beta.kubernetes.io/oci-load-balancer-value: 400Mbps
C. service.beta.kubernetes.io/oci-load-balancer-shape: 400Mbps
D. service.beta.kubernetes.io/oci-load-balancer-size: 400Mbps
```
<span class="hidden">
service.beta.kubernetes.io/oci-load-balancer-shape: 400Mbps
</span><br>


#####  Question 19
You are developing a serverless application with Oracle Functions and Oracle Cloud Infrastructure Object Storage. Your function needs to read a JSON file object from an Object Storage bucket named "input-bucket" in compartment "qa-compartment". Your corporate security standards mandate the use of Resource
Principals for this use case.
Which two statements are needed to implement this use case? (Choose two.)

```
A. Set up a policy with the following statement to grant read access to the bucket: allow dynamic-group read-file-dg to read objects in compartment qa-compartment where target.bucket.name= "˜input-bucket'
B. Set up the following dynamic group for your function's OCID: Name: read-file-dg Rule: resource.id = "˜ocid1.fnfunc.oc1.phx.aaaaaaaakeaobctakezjz5i4ujj7g25q7sx5mvr55pms6f4da'
C. Set up a policy to grant all functions read access to the bucket: allow all functions in compartment qa-compartment to read objects in target.bucket.name= "˜input-bucket'
D. Set up a policy to grant your user account read access to the bucket: allow user XYZ to read objects in compartment qa-compartment where target.bucket.name= "˜input-bucket'
E. No policies are needed. By default, every function has read access to Object Storage buckets in the tenancy.
```
<span class="hidden">
Set up a policy with the following statement to grant read access to the bucket: allow dynamic-group read-file-dg to read objects in compartment qa-compartment where target.bucket.name= "˜input-bucket'
<br>
Set up a policy to grant all functions read access to the bucket: allow all functions in compartment qa-compartment to read objects in target.bucket.name= "˜input-bucket'
</span><br>


#####  Question 20
You created a pod called "nginx" and its state is set to Pending.
Which command can you run to see the reason why the "nginx" pod is in the pending state?

```
A. kubectl logs pod nginx
B. kubectl describe pod nginx
C. kubectl get pod nginx
D. Through the Oracle Cloud Infrastructure Console
```
<span class="hidden">
kubectl describe pod nginx
</span><br>


#####  Question 21
A pod security policy (PSP) is implemented in your Oracle Cloud Infrastructure Container Engine for Kubernetes cluster.
Which rule can you use to prevent a container from running as root using PSP?

```
A. NoPrivilege
B. RunOnlyAsUser
C. MustRunAsNonRoot
D. forbiddenRoot
```
<span class="hidden">
MustRunAsNonRoot
</span><br>


#####  Question 22
What is one of the differences between a microservice and a serverless function?

```
A. Microservices are used for long running operations and serverless functions for short running operations.
B. Microservices always use a data store and serverless functions never use a data store.
C. Microservices are stateless and serverless functions are stateful.
D. Microservices are triggered by events and serverless functions are not.
```
<span class="hidden">
Microservices are used for long running operations and serverless functions for short running operations.
</span><br>


#####  Question 23
Which two "Action Type" options are NOT available in an Oracle Cloud Infrastructure (OCI) Events rule definition? (Choose two.)

```
A. Notifications
B. Functions
C. Streaming
D. Email
E. Slack
```
<span class="hidden">
Email
<br>
Slack
</span><br>


#####  Question 24
Which is NOT a supported SDK on Oracle Cloud Infrastructure (OCI)?

```
A. Go SDK
B. Java SDK
C. .NET SDK
D. Ruby SDK
E. Python SDK
```
<span class="hidden">
.NET SDK
</span><br>


#####  Question 25
You want to push a new image in the Oracle Cloud Infrastructure (OCI) Registry.
Which two actions do you need to perform? (Choose two.)

```
A. Assign a tag via Docker CLI to the image.
B. Generate an auth token to complete the authentication via Docker CLI.
C. Generate an API signing key to complete the authentication via Docker CLI.
D. Assign an OCI defined tag via OCI CLI to the image.
E. Generate an OCI tag namespace in your repository.
```
<span class="hidden">
A. Assign a tag via Docker CLI to the image.
<br>
B. Generate an auth token to complete the authentication via Docker CLI.
</span><br>


#####  Question 26
How can you find details of the tolerations field for the sample YAML file below?

![1z0-1084-21-q26](images/1z0-1084-21-q26.png)

```
A. kubectl list pod.spec.tolerations
B. kubectl explain pod.spec.tolerations
C. kubectl describe pod.spec.tolerations
D. kubectl get pod.spec.tolerations
```
<span class="hidden">
B. kubectl explain pod.spec.tolerations
</span><br>


#####  Question 27
You are building a container image and pushing it to the Oracle Cloud Infrastructure Registry (OCIR). You need to make sure that these images never get deleted from the repository.
Which action should you take?

```
A. Create a group and assign a policy to perform lifecycle operations on images.
B. Set global policy of image retention to "Retain All Images".
C. In your compartment, write a policy to limit access to the specific repository.
D. Edit the tenancy global retention policy.
```
<span class="hidden">
Set global policy of image retention to "Retain All Images".
</span><br>


#####  Question 28
You are deploying an API via Oracle Cloud Infrastructure (OCI) API Gateway and you want to implement request policies to control access.
Which is NOT available in OCI API Gateway?

```
A. Limiting the number of requests sent to backend services
B. Enabling CORS (Cross-Origin Resource Sharing) support
C. Providing authentication and authorization
D. Controlling access to OCI resources
```
<span class="hidden">
Controlling access to OCI resources
</span><br>


#####  Question 29
You are developing a distributed application and you need a call to a path to always return a specific JSON content. To fulfill the requirement you deploy an Oracle
Cloud Infrastructure API Gateway with the below API deployment specification.

![1z0-1084-21-q29](images/1z0-1084-21-q29.png)

```
What is the correct value for type? (Choose the best answer.)
A. STOCK_RESPONSE_BACKEND
B. CONSTANT_BACKEND
C. JSON_BACKEND
D. HTTP_BACKEND
```
<span class="hidden">
STOCK_RESPONSE_BACKEND
</span><br>


#####  Question 30
Which two are benefits of distributed systems? (Choose two.)

```
A. Privacy
B. Security
C. Ease of testing
D. Scalability
E. Resiliency
```
<span class="hidden">
D. Scalability
<br>
E. Resiliency
</span><br>


#####  Question 31
You are building a cloud native, serverless travel application with multiple Oracle Functions in Java, Python and Node.js. You need to build and deploy these functions to a single application named travel-app.
Which command will help you complete this task successfully?

```
A. oci fn function deploy """"app travel""app """"all
B. fn deploy """"app travel""app """"all
C. oci fn application """"application""name travel""app deploy """"all
D. fn function deploy """"all """"application""name travel""app
```
<span class="hidden">
fn deploy """"app travel""app """"all
</span><br>


#####  Question 32
A developer using Oracle Cloud Infrastructure (OCI) API Gateway must authenticate the API requests to their web application. The authentication process must be implemented using a custom scheme which accepts string parameters from the API caller.
Which method can the developer use in this scenario?

```
A. Create an authorizer function using request header authorization.
B. Create an authorizer function using token-based authorization.
C. Create a cross account functions authorizer.
D. Create an authorizer function using OCI Identity and Access Management based authentication.
```
<span class="hidden">
Create an authorizer function using token-based authorization.
</span><br>


#####  Question 33
Your Oracle Cloud Infrastructure Container Engine for Kubernetes (OKE) administrator has created an OKE cluster with one node pool in a public subnet. You have been asked to provide a log file from one of the nodes for troubleshooting purpose.
Which step should you take to obtain the log file?

```
A. ssh into the node using public key.
B. ssh into the nodes using private key.
C. It is impossible since OKE is a managed Kubernetes service.
D. Use the username opc and password to login.
```
<span class="hidden">
ssh into the nodes using private key.
</span><br>


#####  Question 34
You have been asked to create a stateful application deployed in Oracle Cloud Infrastructure (OCI) Container Engine for Kubernetes (OKE) that requires all of your worker nodes to mount and write data to persistent volumes.
Which two OCI storage services should you use? (Choose two.)

```
A. Use OCI File Services as persistent volume.
B. Use GlusterFS as persistent volume.
C. Use OCI Block Volume backed persistent volume.
D. Use open source storage solutions on top of OCI.
E. Use OCI Object Storage as persistent volume.
```
<span class="hidden">
A. Use OCI File Services as persistent volume.
<br>
C. Use OCI Block Volume backed persistent volume.
</span><br>


#####  Question 35
As a cloud-native developer, you are designing an application that depends on Oracle Cloud Infrastructure (OCI) Object Storage wherever the application is running. Therefore, provisioning of storage buckets should be part of your Kubernetes deployment process for the application.
Which should you leverage to meet this requirement?

```
A. OCI Service Broker for Kubernetes
B. OCI Container Engine for Kubernetes
C. Open Service Broker API
D. Oracle Functions
```
<span class="hidden">
A. OCI Service Broker for Kubernetes
</span><br>


#####  Question 36
You are implementing logging in your services that will be running in Oracle Cloud Infrastructure Container Engine for Kubernetes.
Which statement describes the appropriate logging approach?

```
A. Each service logs to its own log file.
B. All services log to an external logging system.
C. All services log to standard output only.
D. All services log to a shared log file.
```
<span class="hidden">
All services log to standard output only.
</span><br>


#####  Question 37
Which concept is NOT -
related to Oracle Cloud Infrastructure Resource Manager?

```
A. Job
B. Stack
C. Queue
D. Plan
```
<span class="hidden">
Queue
</span><br>


#####  Question 38
Your organization uses a federated identity provider to login to your Oracle Cloud Infrastructure (OCI) environment. As a developer, you are writing a script to automate some operation and want to use OCI CLI to do that. Your security team doesn't allow storing private keys on local machines.
How can you authenticate with OCI CLI?

```
A. Run oci setup keys and provide your credentials
B. Run oci session refresh """"profile <profile_name>
C. Run oci session authenticate and provide your credentials
D. Run oci setup oci""cli""rc """"file path/to/target/file
```
<span class="hidden">
Run oci session authenticate and provide your credentials
</span><br>


#####  Question 39
You are developing a serverless application with Oracle Functions. You have created a function in compartment named prod. 
When you try to invoke your function you get the following error:
```
Error invoking function. status: 502 message: dhcp options
ocid1.dhcpoptions.oc1.iad.aaaaaaanprvvpxpsxlabcgdg does not
exist or Oracle Functions is not authorized to use it
```
How can you resolve this error? 

```
A. Create a policy: Allow function-family to use virtual-network-family in compartment prod
B. Create a policy: Allow any-user to manage function-family and virtual-network-family in compartment prod
C. Create a policy: Allow service FaaS to use virtual-network-family in compartment prod
D. Deleting the function and redeploying it will fix the problem
```
<span class="hidden">
Create a policy: Allow service FaaS to use virtual-network-family in compartment prod
</span><br>


#####  Question 40
Which one of the statements describes a service aggregator pattern?

```
A. It is implemented in each service separately and uses a streaming service
B. It involves implementing a separate service that makes multiple calls to other backend services
C. It uses a queue on both sides of the service communication
D. It involves sending events through a message broker
```
<span class="hidden">
It involves implementing a separate service that makes multiple calls to other backend services
</span><br>



#####  Question 41
Which two handle Oracle Functions authentication automatically? (Choose two.)

```
A. Oracle Cloud Infrastructure SDK
B. cURL
C. Oracle Cloud Infrastructure CLI
D. Signed HTTP Request
E. Fn Project CLI
```
<span class="hidden">
C. Oracle Cloud Infrastructure CLI
<br>
E. Fn Project CLI
</span><br>


#####  Question 42
You have written a Node.js function and deployed it to Oracle Functions. Next, you need to call this function from a microservice written in Java deployed on
Oracle Cloud Infrastructure (OCI) Container Engine for Kubernetes (OKE).
Which can help you to achieve this? 

```
A. Use the OCI CLI with kubectl to invoke the function from the microservice.
B. Oracle Functions does not allow a microservice deployed on OKE to invoke a function.
C. OKE does not allow a microservice to invoke a function from Oracle Functions.
D. Use the OCI Java SDK to invoke the function from the microservice.
```
<span class="hidden">
Use the OCI Java SDK to invoke the function from the microservice.
</span><br>


#####  Question 43
How do you perform a rolling update in Kubernetes?  

```
A. kubectl rolling-update
B. kubectl upgrade <deployment-name> """"image=image:v2
C. kubectl update ""c <container>
D. kubectl rolling-update <deployment-name> """"image=image:v2
```
<span class="hidden">
kubectl rolling-update &lt;deployment-name&gt; image=image:v2
</span><br>


#####  Question 44
In the sample Kubernetes manifest file below, 
what annotations should you add to create a private load balancer in Oracle Cloud Infrastructure Container Engine for Kubernetes?

```
apiVersion: v1
kind: Service
metadata:
  name: my-nginx-svc
  labels:
    app: nginx
  annotations:
    <Fill in>
spec:
  type: LoadBalancer
  ports:
  - port: 80
  selector:
    app: nginx

---
apiVersion: v1
kind: Service
metadata:
  name: my-nginx-svc
  labels:
    app: nginx
  annotations:
    <Fill in>
spec:
  type: LoadBalancer
  ports:
  - port: 80
  selector:
    app: nginx
```

```
A. service.beta.kubernetes.io/oci-load-balancer-private:"true"
B. service.beta.kubernetes.io/oci-load-balancer-private: "true" service.beta.kubernetes.io/oci-load-balancer-subnet1: "ocid1.subnet.oc1..aaaaa....vdfw"
C. service.beta.kubernetes.io/oci-load-balancer-internal: "true"
D. service.beta.kubernetes.io/oci-load-balancer-internal: "true" service.beta.kubernetes.io/oci-load-balancer-subnet1: "ocid1.subnet.oc1..aaaaa....vdfw"
```
<span class="hidden">
service.beta.kubernetes.io/oci-load-balancer-internal: "true" service.beta.kubernetes.io/oci-load-balancer-subnet1: "ocid1.subnet.oc1..aaaaa....vdfw"
</span><br>


#####  Question 45
You have created a repository in Oracle Cloud Infrastructure Registry in the us-ashburn-1 (iad) region in your tenancy with a namespace called "heyoci".
Which three are valid tags for an image named "myapp"? (Choose three.)

```
A. iad.ocir.io/heyoci/myproject/myapp:0.0.1
B. us-ashburn-1.ocir.io/heyoci/myapp:0.0.2-beta
C. us-ashburn-1.ocir.io/heyoci/myproject/myapp:0.0.2-beta
D. us-ashburn-1.ocir.io/myproject/heyoci/myapp:latest
E. iad.ocir.io/myproject/heyoci/myapp:latest
F. iad.ocir.io/heyoci/myapp:0.0.2-beta
G. iad.ocir.io/heyoci/myapp:latest
```
<span class="hidden">
A. iad.ocir.io/heyoci/myproject/myapp:0.0.1
<br>
F. iad.ocir.io/heyoci/myapp:0.0.2-beta
<br>
G. iad.ocir.io/heyoci/myapp:latest
</span><br>


#####  Question 46
You are developing a serverless application with Oracle Functions. Your function needs to store state in a database. Your corporate security standards mandate encryption of secret information like database passwords.
As a function developer, which approach should you follow to satisfy this security requirement?

```
A. Use the Oracle Infrastructure Console and enter the password in the function configuration section in the provided input field.
B. Use Oracle Cloud Infrastructure Key Management to auto-encrypt the password. It will inject the auto-decrypted password inside your function container.
C. Encrypt the password using Oracle Cloud Infrastructure Key Management. Decrypt this password in your function code with the generated key.
D. All function configuration variables are automatically encrypted by Oracle Functions.
```
<span class="hidden">
Encrypt the password using Oracle Cloud Infrastructure Key Management. Decrypt this password in your function code with the generated key.
</span><br>


#####  Question 47
You are working on a cloud native e-commerce application on Oracle Cloud Infrastructure (OCI). Your application architecture has multiple OCI services, including
Oracle Functions. You need to trigger these functions directly from other OCI services, without having to run custom code.
Which OCI service cannot trigger your functions directly?

```
A. OCI Events Service
B. OCI Registry
C. OCI API Gateway
D. Oracle Integration
```
<span class="hidden">
Oracle Integration
</span><br>


#####  Question 48
Which two statements are true for serverless computing and serverless architectures? (Choose two.)

```
A. Long running tasks are perfectly suited for serverless
B. Serverless function state should never be stored externally
C. Application DevOps team is responsible for scaling
D. Serverless function execution is fully managed by a third party
E. Applications running on a FaaS (Functions as a Service) platform
```
<span class="hidden">
B. Serverless function state should never be stored externally
<br>
E. Applications running on a FaaS (Functions as a Service) platform
</span><br>


#####  Question 50
You need to execute a script on a remote instance through Oracle Cloud Infrastructure Resource Manager.
Which option can you use?

```
A. Use /bin/sh with the full path to the location of the script to execute the script.
B. It cannot be done.
C. Download the script to a local desktop and execute the script.
D. Use remote-exec
```
<span class="hidden">
Use remote-exec
</span><br>


#####  Question 51
You are a consumer of Oracle Cloud Infrastructure (OCI) Streaming service.
Which API should you use to read and process the stream? 

```
A. ListMessages
B. GetMessages
C. GetObject
D. ReadMessages
```
<span class="hidden">
GetMessages
</span><br>


#####  Question 52
Which Oracle Cloud Infrastructure (OCI) load balancer shape is used by default in OCI Container Engine for Kubernetes? (Choose the best answer.)

```
A. 400 Mbps
B. 8000 Mbps
C. There is no default. The shape has to be specified.
D. 100 Mbps
```
<span class="hidden">
100 Mbps
</span><br>


#####  Question 53
Which two statements are true for service choreography? (Choose two.)

```
A. Service choreographer is responsible for invoking other services.
B. Services involved in choreography communicate through messages/messaging systems.
C. Service choreography relies on a central coordinator.
D. Service choreography should not use events for communication.
E. Decision logic in service choreography is distributed.
```
<span class="hidden">
D. Service choreography should not use events for communication.
<br>
E. Decision logic in service choreography is distributed.
</span><br>


#####  Question 54
Which testing approaches is a must for achieving high velocity of deployments and releases of cloud-native applications? (Choose the best answer.)

```
A. Integration testing
B. A/B testing
C. Automated testing
D. Penetration testing
```
<span class="hidden">
Integration testing
</span><br>


#####  Question 55
As a cloud-native developer, you have written a web service for your company. You have used Oracle Cloud Infrastructure (OCI) API Gateway service to expose the HTTP backend. However, your security team has suggested that your web service should handle Distributed Denial-of-Service (DDoS) attack. You are time- constrained and you need to make sure that this is implemented as soon as possible.
What should you do in this scenario? 

```
A. Use OCI virtual cloud network (VCN) segregation to control DDoS.
B. Use a third party service integration to implement a DDoS attack mitigation.
C. Use OCI API Gateway service and configure rate limiting.
D. Re-write your web service and implement rate limiting.
```
<span class="hidden">
Use OCI API Gateway service and configure rate limiting.
</span><br>


#####  Question 56
A leading insurance firm is hosting its customer portal in Oracle Cloud Infrastructure (OCI) Container Engine for Kubernetes with an OCI Autonomous Database.
Their support team discovered a lot of SQL injection attempts and cross-site scripting attacks to the portal, which is starting to affect the production environment.
What should they implement to mitigate this attack? 

```
A. Network Security Lists
B. Network Security Groups
C. Network Security Firewall
D. Web Application Firewall
```
<span class="hidden">
Network Security Firewall
</span><br>


#####  Question 57
A programmer is developing a Node.js application which will run in a Linux server on their on-premises data center. This application will access various Oracle
Cloud Infrastructure (OCI) services using OCI SDKs.
What is the secure way to access OCI services with OCI Identity and Access Management (IAM)? 

```
A. Create a new OCI IAM user associated with a dynamic group and a policy that grants the desired permissions to OCI services. Add the on-premises Linux server in the dynamic group.
B. Create an OCI IAM policy with the appropriate permissions to access the required OCI services and assign the policy to the on-premises Linux server.
C. Create a new OCI IAM user, add the user to a group associated with a policy that grants the desired permissions to OCI services. In the on-premises Linux server, generate the keypair used for signing API requests and upload the public key to the IAM user.
D. Create a new OCI IAM user, add the user to a group associated with a policy that grants the desired permissions to OCI services. In the on-premises Linux server, add the user name and password to a file used by Node.js authentication.
```
<span class="hidden">
Create a new OCI IAM user, add the user to a group associated with a policy that grants the desired permissions to OCI services. In the on-premises Linux server, generate the keypair used for signing API requests and upload the public key to the IAM user.
</span><br>


#####  Question 58
Which header is NOT required when signing GET requests to Oracle Cloud Infrastructure APIs? (Choose the best answer.)

```
A. date or x-date
B. (request-target)
C. content-type
D. host
```
<span class="hidden">
content-type
</span><br>


#####  Question 59
Which two are characteristics of microservices? (Choose two.)

```
A. Microservices are hard to test in isolation.
B. Microservices can be independently deployed.
C. All microservices share a data store.
D. Microservices can be implemented in limited number of programming languages.
E. Microservices communicate over lightweight APIs.
```
<span class="hidden">
B. Microservices can be independently deployed.
<br>
E. Microservices communicate over lightweight APIs.
</span><br>


#####  Question 60
You encounter an unexpected error when invoking the Oracle Function named "myfunction" in application "myapp".
Which can you use to get more information on the error? 

```
A. fn """"debug invoke myapp myfunction
B. DEBUG=1 fn invoke myapp myfunction
C. fn """"verbose invoke myapp myfunction
D. Call Oracle support with your error message
```
<span class="hidden">
DEBUG=1 fn invoke myapp myfunction
</span><br>