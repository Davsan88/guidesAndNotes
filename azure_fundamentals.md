# Microsoft Azure Fundamentals (AZ-900)

## Cloud Concepts

### What is Cloud Computing
Cloud computing is the delivery of computing services over the internet (the cloud), allowing for on-demand access to resources such as servers, storage, databases, networking, software, and analytics.

### Common Cloud Services
Common cloud services include Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). These services provide various levels of control, flexibility, and management.

### What is Microsoft and Azure
Microsoft Azure is a cloud computing platform and service created by Microsoft. It provides a range of cloud services, including those for computing, analytics, storage, and networking. Users can select and configure these services to meet their specific needs.

### Benefits of Cloud Computing
- **Cost-effective**: Reduces the need for upfront capital expenditure on hardware and software, offering a pay-as-you-go model.
- **Global**: Allows you to deploy applications in multiple regions worldwide, ensuring low latency and high availability.
- **Secure**: Provides robust security measures to protect data and applications, including compliance with various regulations.
- **Reliable**: Offers high availability and disaster recovery options to ensure business continuity.
- **Scalable**: Easily scales resources up or down to meet changing demand.
- **Elastic**: Automatically adjusts resources to handle variations in workload.
- **Current**: Ensures you always have access to the latest technologies and updates.

### Types of Cloud Computing
Cloud computing can be classified into three main types:

- **Public Cloud**: Services offered over the public internet and available to anyone who wants to purchase them.
- **Private Cloud**: Computing resources used exclusively by one business or organization.
- **Hybrid Cloud**: A combination of public and private clouds, allowing data and applications to be shared between them.

### Types of Cloud Computing Responsibilities
Cloud responsibilities are shared between the cloud provider and the customer:

- **Cloud Provider Responsibilities**: Physical infrastructure security, hardware maintenance, and network controls.
- **Customer Responsibilities**: Data security, access management, and application security.

### Cloud Deployment Models
Cloud deployment models include:

- **Public Cloud**: Fully managed by the cloud provider, accessible over the internet.
- **Private Cloud**: Exclusive to a single organization, offering greater control and privacy.
- **Hybrid Cloud**: Integrates public and private clouds to leverage the benefits of both.

### Total Cost of Ownership (TCO)
Total Cost of Ownership (TCO) evaluates the cost of owning and operating an IT infrastructure over its entire lifecycle, including hardware, software, maintenance, and labor. Cloud computing often reduces TCO by minimizing upfront capital expenditures and converting them into operational expenditures.

### CAPEX vs OPEX
- **CAPEX (Capital Expenditure)**: Upfront costs for physical infrastructure, including hardware and software licenses. These are fixed, long-term investments.
- **OPEX (Operational Expenditure)**: Ongoing costs for running and maintaining infrastructure, including utility bills, maintenance, and subscription services. Cloud computing shifts many IT expenses from CAPEX to OPEX, offering more flexibility and cost efficiency.

### Cloud Architecture Terminologies

#### Solutions Architect
A Solutions Architect designs and manages the implementation of solutions in the cloud. They focus on designing applications and services that meet specific business needs, ensuring that they are scalable, reliable, and cost-effective.

#### Cloud Architect
A Cloud Architect oversees an organization’s cloud computing strategy, including adoption plans, cloud application design, and cloud management and monitoring. They ensure that cloud solutions meet the company's technical and business requirements.

### High Availability
High Availability refers to systems that are continuously operational and accessible without interruption. It involves designing infrastructure to minimize downtime and ensure that applications are always available to users.

### High Scalability
High Scalability is the ability of a system to handle increased loads by adding resources as needed. This ensures that applications can grow and manage more users, data, or transactions without compromising performance.

### High Elasticity
High Elasticity is the capability of a system to automatically adjust resource levels to handle varying loads. This ensures that applications can scale up during peak times and scale down during off-peak times, optimizing resource usage and cost.

### Fault Tolerance
Fault Tolerance is the ability of a system to continue operating properly in the event of a failure of some of its components. This involves designing systems that can detect failures and automatically recover from them, ensuring continuous operation.

### High Durability
High Durability refers to the ability of a system to protect and preserve data against failures. This involves using redundant storage, backups, and data replication to ensure that data is not lost or corrupted.

### Business Continuity Plan
A Business Continuity Plan (BCP) outlines procedures for maintaining business operations during and after a disaster. It ensures that critical business functions can continue or be restored quickly.

#### Recovery Point Objective (RPO)
Recovery Point Objective (RPO) is the maximum acceptable amount of data loss measured in time. It indicates how far back in time you must go to recover data in the event of a disruption.

#### Recovery Time Objective (RTO)
Recovery Time Objective (RTO) is the maximum acceptable amount of time to restore a service or system after a disaster. It indicates how quickly you need to recover operations.

### Disaster Recovery Options

#### Backup & Restore
- **RPO/RTO**: Hours
- **Description**: Involves regularly backing up data and restoring it in the event of a failure. Suitable for systems with less stringent recovery requirements.

#### Pilot Light
- **RPO/RTO**: 10 minutes
- **Description**: Keeps a minimal version of the environment running in the cloud. When needed, you can quickly scale it up to restore full operations.

#### Warm Standby
- **RPO/RTO**: Minutes
- **Description**: Keeps a scaled-down version of the fully functional environment running in the cloud. During a disaster, this environment can be quickly scaled up to take over full production workloads.

#### Multi-site Active/Active
- **RPO/RTO**: Real-time
- **Description**: Runs multiple active environments in different locations. In the event of a failure, traffic is redirected to the remaining active sites with no downtime.

>Understanding these terminologies and disaster recovery options helps ensure that your cloud infrastructure is robust, resilient, and capable of meeting business continuity requirements.


## Evolution of Compute

### Dedicated Servers
Dedicated Servers are physical servers allocated to a single customer, providing full control over the server's resources and configurations. They offer high performance and security but require significant management and maintenance efforts.

### Virtual Machines
Virtual Machines (VMs) abstract the physical hardware into multiple virtual instances, each running its own operating system and applications. VMs allow better utilization of physical resources and provide isolation between different workloads, reducing the need for physical hardware management.

### Containers
Containers package applications and their dependencies into a single unit, enabling them to run consistently across different environments. Containers share the host OS kernel, making them lightweight and more efficient than VMs. They are ideal for microservices architectures, allowing for easy deployment, scaling, and management.

### Functions
Functions, also known as serverless computing, allow you to run code in response to events without provisioning or managing servers. In this model, the cloud provider automatically scales and manages the infrastructure, charging only for the compute time consumed. This approach enables rapid development and deployment of applications with minimal operational overhead.

>Understanding these stages in the evolution of compute helps you choose the right compute model for your specific needs, balancing performance, scalability, and management requirements.


## Global Infrastructure
Azure's global infrastructure is designed to deliver high availability, performance, and resilience for cloud applications. It is composed of various regions, geographies, and availability zones to meet diverse customer needs.

### Regions and Geographies
Azure's infrastructure spans:

- **Regions**: Physical locations around the world where data centers are clustered. Azure has 58 regions across 140 countries, providing global coverage and data residency options.
- **Geographies**: Defined areas that contain two or more regions, ensuring compliance with data residency and sovereignty requirements.

### Paired Regions
Paired Regions are a feature of Azure's infrastructure design where each Azure region is paired with another region within the same geography. This setup provides several advantages:

- **Data Residency**: Ensures data remains within the same geography.
- **Disaster Recovery**: Provides redundancy and high availability, allowing for data replication and failover between paired regions.
- **Compliance**: Helps meet regulatory requirements for data handling and storage.

### Region Types and Service Availability
Azure regions are categorized based on the availability and scope of services they offer:

- **Recommended Region**: Regions with the broadest range of services and features, recommended for most users.
- **Alternate Region**: Additional regions that provide options if the recommended region is not suitable for specific needs.

Service Availability Levels:

1. **Foundational**: Basic services that are available in all regions.
2. **Mainstream**: A wider array of services suitable for general use.
3. **Specialized**: Specific services available in select regions, often for unique regulatory or performance needs.

### Special Regions

Special Regions cater to specific compliance, regulatory, and operational requirements:
- **US Government**: Dedicated regions for US government agencies and their partners.
- **China**: Operated by 21Vianet, compliant with Chinese regulations.
- **Germany**: Operated by a German data trustee, compliant with German data protection laws.
- **Azure Government Secret and DoD regions**: High-security regions for US government agencies handling classified information.

### Availability Zones
Availability Zones are physically separate locations within an Azure region. Each zone is composed of one or more data centers with independent power, cooling, and networking. They offer:

- **High Availability**: Ensures that applications and data are resilient to data center failures.
- **Fault Tolerance**: Protects against potential data center disruptions by distributing resources across multiple zones.

### AZ Supported Regions
Not all Azure regions support Availability Zones. Regions that do support Availability Zones are designed to provide enhanced availability and resilience for critical applications by offering multiple isolated locations within a region.

### Availability Sets Fault and Update Domains
Availability Sets are a mechanism to enhance the availability of VMs in Azure by grouping them into fault and update domains:

- **Fault Domain**: A logical group of hardware that shares a common power source and network switch. Distributing VMs across multiple fault domains ensures that a hardware failure does not affect all VMs.
- **Update Domain**: A group of VMs and underlying hardware that can be updated and rebooted at the same time. Spreading VMs across multiple update domains minimizes the impact of maintenance activities.
- **Availability Set**: A logical grouping of VMs that ensures they are distributed across multiple fault and update domains, providing redundancy and increasing application uptime.

Understanding Azure's global infrastructure, including regions, availability zones, and special regions, helps in designing robust, scalable, and compliant cloud applications.

## Compute Services

## Computing Services
Azure provides a range of computing services to support various workloads, from virtual machines to serverless computing.

### Azure Virtual Machines
Azure Virtual Machines (VMs) provide scalable computing resources in the cloud. You can use VMs when you need more control over the computing environment than the other compute resources offer.

- **NSG (Network Security Group)**: A security feature that acts as a virtual firewall to control inbound and outbound traffic to Azure resources.
- **NIC (Network Interface Card)**: A component that connects a VM to a virtual network.
- **VM Instance**: A virtual server that can run applications and services.
- **Public IP Address**: An address assigned to a VM for direct internet access.
- **Virtual Network (VNet)**: A logically isolated network within the Azure cloud where you can launch VMs and other resources.

### Azure Container Instances
Azure Container Instances (ACI) offer the fastest and simplest way to run a container in Azure without managing virtual machines or adopting a higher-level service.

### Azure Kubernetes Service (AKS)
Azure Kubernetes Service (AKS) simplifies deploying a managed Kubernetes cluster in Azure. It reduces the complexity and operational overhead of managing Kubernetes by offloading much of that responsibility to Azure.

### Azure Service Fabric
Azure Service Fabric is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and containers.

### Azure Functions
Azure Functions is a serverless compute service that allows you to run event-driven code without having to provision or manage infrastructure.

### Azure Batch
Azure Batch enables large-scale parallel and high-performance computing (HPC) applications efficiently in the cloud. You can use it to run large-scale jobs in parallel.

### Azure Virtual Machines
Azure Virtual Machines provide the ability to run applications and workloads in the cloud with flexible computing capacity.

- **NSG (Network Security Group)**: Controls inbound and outbound traffic to network interfaces (NIC), VMs, and subnets.
- **NIC (Network Interface Card)**: Connects VMs to VNets, enabling communication with other networked resources.
- **VM Instance**: Virtualized computing resources that can run various operating systems and applications.
- **Public IP Address**: Enables direct access to the internet for VMs.
- **Virtual Network (VNet)**: A private network in Azure that allows for secure communications between Azure resources.

### Operation Systems
Azure Virtual Machines support a wide range of operating systems, including various distributions of Linux and Windows Server, providing flexibility for different workloads.

### Azure Scale Sets
Azure Scale Sets allow you to create and manage a group of identical, load-balanced VMs. Scale sets make it easy to build large-scale services that target big compute, big data, and containerized workloads.

### Load Balancer
Azure provides load balancers to distribute traffic across multiple servers to ensure high availability and reliability of applications.

- **Application Gateway (HTTP/HTTPS)**: A web traffic load balancer that enables you to manage traffic to your web applications.
- **Azure Load Balancer (TCP/UDP)**: A Layer 4 (TCP, UDP) load balancer that distributes incoming network traffic across multiple VMs.

### Scaling Policy
Scaling policies define how and when to scale the number of VM instances in your scale set.

- **Scale-In Policy**: Determines when to decrease the number of VM instances based on specific metrics or schedules.
- **Update Policy**: Manages how updates are applied to the VM instances, ensuring minimal disruption.

### Health Monitoring
Health monitoring ensures that your applications and services are running smoothly and helps detect and recover from failures.

- **Health Monitoring**: Continuously checks the health of applications and infrastructure.
  - **Application Health Extension**: Monitors the health of applications running on VMs.
  - **Load Balancer Probe**: Checks the status of VMs in a load balancer pool to ensure traffic is only sent to healthy instances.
- **Automatic Repair Policy**: Automatically repairs unhealthy VM instances based on health check results.

### Azure Virtual Desktop
Azure Virtual Desktop is a comprehensive desktop and app virtualization service running in the cloud. It enables you to deliver a full Windows experience and applications to any device.

>Understanding these computing services and their components helps you design, deploy, and manage applications effectively in the Azure cloud, ensuring high availability, scalability, and performance.

## Azure App Service

### Introduction to Azure App Service
Azure App Service is a fully managed platform for building, deploying, and scaling web apps. It supports multiple languages and frameworks, including .NET, .NET Core, Java, Ruby, Node.js, PHP, and Python. It offers integrated tools for DevOps, including continuous deployment from Azure DevOps, GitHub, Docker Hub, and other sources.

### Runtimes
Azure App Service supports a variety of runtimes, allowing developers to deploy applications written in different programming languages. It provides built-in support for popular languages and frameworks such as .NET, Node.js, PHP, Python, and Java, ensuring flexibility and compatibility for various application needs.

### Custom Containers
Azure App Service allows the use of custom containers for greater control over the application environment. Developers can deploy containerized applications using Docker containers, providing a consistent and isolated runtime environment. This enables the deployment of applications with specific dependencies and configurations.

### Deployment Slots
Deployment slots in Azure App Service enable staged deployment of applications. Each slot represents a different environment (e.g., development, staging, production), allowing you to deploy and test changes in isolation before swapping them into production. This feature minimizes downtime and reduces the risk of deployment errors.

### App Service Environment (ASE)
Azure App Service Environment (ASE) is a premium service offering that provides a fully isolated and dedicated environment for securely running App Service apps at high scale. ASE is ideal for applications that require high scalability, enhanced security, and network isolation.

### Azure App Service Plan
Azure App Service Plan defines the region, number of instances, and pricing tier for your web apps. The plan determines the compute resources and pricing for your App Service apps. You can choose from various pricing tiers based on your needs for scalability, performance, and features.

>Understanding Azure App Service and its components helps you build, deploy, and manage web applications efficiently, ensuring high performance, scalability, and security.


## Azure Container Instances

### Introduction to ACI
Azure Container Instances (ACI) is a service that allows you to run containers without managing the underlying virtual machines (VMs) or adopting a higher-level service. It provides a quick and easy way to deploy and run containers in the cloud. Unlike VMs, which require you to manage the operating system and infrastructure, ACI abstracts these details, enabling you to focus on your applications.

#### Differences with VMs
- **Infrastructure Management**: ACI abstracts the underlying infrastructure, whereas VMs require you to manage the OS and infrastructure.
- **Startup Time**: Containers in ACI start faster than VMs, providing quicker deployment and scaling.
- **Resource Efficiency**: Containers are more lightweight than VMs, sharing the host OS kernel and using fewer resources.
- **Isolation**: While VMs offer full isolation at the hardware level, containers provide application-level isolation.

### Container Groups
In ACI, a container group is a collection of containers that share the same lifecycle, network, and storage resources. Containers in a group can communicate with each other over local network interfaces and can be managed as a single entity.

### Container Restart Policies
Restart policies determine the behavior of containers when they exit or fail.

- **Always**: Always restart the container when it exits, regardless of the exit status.
- **Never**: Never restart the container when it exits.
- **OnFailure**: Restart the container only if it exits with a non-zero exit status, indicating an error.

### Container Environment Variables (Env Vars)
Environment variables (Env Vars) are key-value pairs used to pass configuration settings to containers at runtime. They allow you to dynamically configure containerized applications without hardcoding values, making it easier to manage different environments and settings.

### Container Persistent Storage
Container Persistent Storage in ACI allows containers to persist data beyond the lifecycle of the container instance. You can attach Azure Files or Azure Disks to container groups, providing durable storage that can be shared across multiple containers or persist data even after the container is stopped.

> Understanding Azure Container Instances and its features helps you deploy and manage containerized applications efficiently, ensuring scalability, quick startup times, and simplified infrastructure management.


## Virtual Networking

### Introduction to VNets
Azure Virtual Network (VNet) is the fundamental building block for your private network in Azure. VNets enable many types of Azure resources, such as Azure VMs, to securely communicate with each other, the internet, and on-premises networks. 

#### Components of VNets
- **Azure DNS**: Azure DNS is a hosting service for DNS domains, providing name resolution using Microsoft Azure infrastructure.
- **Virtual Network (VNet)**: A logically isolated network that allows you to securely connect Azure resources.
- **Network Security Groups (NSG)**: NSGs contain security rules that allow or deny inbound and outbound network traffic to/from several types of Azure resources.
- **ExpressRoute**: ExpressRoute is a service that provides a private connection between your on-premises networks and Azure data centers.
- **Virtual WAN**: Virtual WAN provides a unified wide area network (WAN) architecture for connecting different branches to Azure and each other.
- **Virtual Network Gateway**: A gateway that provides connectivity between VNets or between a VNet and on-premises networks.
- **Network Interfaces**: Network Interfaces are the interconnections between VMs and VNets, enabling communication.

### VNet Peering
VNet Peering allows you to seamlessly connect two or more Virtual Networks in Azure.

- **Regional**: Connects VNets within the same Azure region, enabling resources in both VNets to communicate with each other.
- **Global**: Connects VNets across different Azure regions, facilitating communication between resources in globally distributed VNets.

### Network Interfaces
Network Interfaces (NICs) are the point of connection between a VM and a VNet. Each NIC can have multiple IP addresses, including private and public IPs.

### Subnets
Subnets are segments of a VNet that allow you to divide the network into smaller, manageable sections. Subnets enable you to organize and secure resources within the VNet.

### Introduction to Azure DNS
Azure DNS is a cloud-based service for hosting DNS domains and providing name resolution using Microsoft Azure infrastructure. Azure DNS allows you to manage your DNS records using the same credentials, billing, and support contract as your other Azure services.

### Introduction to Virtual Network Gateways
Virtual Network Gateways provide connectivity between VNets and on-premises networks or between different VNets. They facilitate site-to-site, point-to-site, and VNet-to-VNet connections.

### Azure ExpressRoute
Azure ExpressRoute enables you to create private connections between Azure data centers and infrastructure on your premises or in a colocation environment. ExpressRoute connections do not go over the public Internet, offering more reliability, faster speeds, and lower latencies.

### Private Links
Azure Private Link provides private connectivity from a virtual network to Azure services.

- **Private Link Endpoint**: A private endpoint in your VNet, which is a private IP address within a specified subnet.
- **Private Link Service**: Allows you to access Azure services (like Azure Storage and SQL Database) over a private endpoint in your VNet, ensuring secure and private connections.

> Understanding Azure Virtual Networking components and features helps you design and implement secure, scalable, and efficient network architectures in the Azure cloud.


## Storage Accounts

Azure Storage Accounts provide a scalable, durable, and secure cloud storage solution for a wide variety of data objects. 

### Storage Services

Azure offers various storage services to meet different needs:

- **Azure Blob Storage**: Optimized for storing large amounts of unstructured data, such as text or binary data.
- **Azure Disk Storage**: Provides block-level storage volumes for Azure VMs.
- **Azure File Storage**: Fully managed file shares that you can access via the industry-standard SMB protocol.
- **Azure Queue Storage**: Allows for storing large numbers of messages that can be accessed from anywhere via authenticated calls.
- **Azure Table Storage**: Provides structured NoSQL data storage for storing large amounts of data.
- **Azure Data Box / Azure Data Box Heavy**: Solutions for transferring large amounts of data to Azure using physical storage devices.
- **Azure Archive Storage**: Offers low-cost, long-term storage for rarely accessed data.
- **Azure Data Lake Storage**: Combines the power of a high-performance file system with massive scale and economy to help speed data-driven innovation.

### Introduction to Storage Accounts

Azure Storage Accounts provide a unique namespace for your Azure Storage data, accessible from anywhere in the world over HTTP or HTTPS. All objects in a storage account are billed together as a group.

### Storage Comparison

Azure Storage offers different types of storage to meet various needs, from unstructured Blob storage to structured Table storage, and from message Queue storage to Disk storage for VMs.

### Core Storage Services

- **Azure Blob Storage**: For storing large amounts of unstructured data.
- **Azure File Storage**: Managed file shares accessible via SMB.
- **Azure Queue Storage**: For storing large numbers of messages.
- **Azure Table Storage**: NoSQL data storage for large amounts of structured data.
- **Azure Disk Storage**: Provides durable, high-performance block storage for VMs.

### Performance Tiers

Azure Storage provides different performance tiers to meet varying needs:

- **Standard Performance (HDDs)**: Cost-effective storage for infrequent access.
- **Premium Performance (SSDs)**: High-performance storage for latency-sensitive applications.

### Access Tiers (Blob Storage)

Blob Storage access tiers help manage storage costs by allowing you to store blob object data in different access tiers based on its access patterns:

- **Hot**: Optimized for data that is accessed frequently.
- **Cool**: Optimized for data that is infrequently accessed and stored for at least 30 days.
- **Archive**: Lowest-cost storage for data that is rarely accessed and stored for at least 180 days.

#### Tiering Options

- **Account Level Tiering**: Sets the default access tier for all blobs in the account.
- **Blob-Level Tiering**: Sets the access tier at the individual blob level.
- **Rehydrating a Blob**: Moving a blob from the Archive tier to Hot or Cool to access the data.
- **Blob Lifecycle Management**: Automates the transition of blobs to different access tiers based on specified policies.

### Replication Data Redundancy

Azure provides several options for replicating your data to ensure durability and high availability:

#### Primary Region Redundancy

- **LRS (Locally Redundant Storage)**: Data is replicated three times within a single data center in the primary region.
- **ZRS (Zone-Redundant Storage)**: Data is replicated synchronously across three Azure availability zones in the primary region.

#### Secondary Region Redundancy

- **GRS (Geo-Redundant Storage)**: Data is replicated to a secondary region, ensuring durability even in the event of a region-wide outage.
- **GZRS (Geo-Zone-Redundant Storage)**: Combines the high availability of ZRS with the protection of GRS.

#### Secondary Region Redundancy with Read Access

- **RA-GRS (Read-Access Geo-Redundant Storage)**: Provides read access to the data in the secondary region.
- **RA-GZRS (Read-Access Geo-Zone-Redundant Storage)**: Provides read access to the data in the secondary region with zone redundancy.

### Introduction to Azure Blob

Azure Blob Storage is optimized for storing massive amounts of unstructured data, such as text or binary data.

### Azure Blob Types

- **Block Blobs**: Store text and binary data, and are optimized for upload and download operations.
- **Append Blobs**: Optimized for append operations, such as logging.
- **Page Blobs**: Store random access files up to 8 TB in size and are optimized for read and write operations.

### AZCopy

AZCopy is a command-line utility designed for copying data to and from Azure Blob and File storage, enabling efficient data transfer.

### Azure Storage Explorer

Azure Storage Explorer is a standalone app that allows you to easily work with Azure Storage data on Windows, macOS, and Linux. It provides a graphical interface for managing your storage accounts and the data they contain.

### Introduction to Azure Files

Azure Files provides fully managed file shares in the cloud that are accessible via the industry-standard SMB and NFS protocols.

### Azure Files Use Cases

Azure Files can be used for various scenarios, including file sharing, lift and shift migrations, and cloud applications that require a shared storage solution.

### Azure File Sync

Azure File Sync centralizes your organization's file shares in Azure Files, while keeping the flexibility, performance, and compatibility of an on-premises file server.

### Storing Files in Blob Storage

Azure Blob Storage is ideal for storing large amounts of unstructured data, such as documents, images, videos, and backups. It offers scalable, durable, and secure storage solutions for a wide range of applications.

Understanding these storage services and their features helps you choose the right storage solution for your needs, ensuring data durability, availability, and cost efficiency in the Azure cloud.



## Migration Options
### Azure Cloud Adoption Framework
### Security Roles and Responsibilities
### Azure Migrate
### Azure Migrate Integrated tools
### Azure Databox


## Microsoft Entra ID
### Microsoft Entra ID Name Change
### Introduction to Entra ID
### Use Cases
### AD vs AAD
### Terminology
### AD DS Microsoft Entra Domain Services
### Single Sign On SSO
### SSO protocols
* OpenID Connect and OAuth
* SAML
* Password-based authentication
* Link authentication
* Integrated Windows Authentication (IWA)
* Header-based authentication
### External Identities
### Conditional Access
### Conditional Access Signals
* User or group memebership
*Named location indormation / IP Location Information
* Device
* Application
* Real-time sing-in risk detection
* Cloud apps or actions
* User risk
### Conditional Access - Common Decisions
* Block access
* Grant access



## Security
### Zero Trust Model
### Zero Trust Principles
### Defense In Depth
The 7 Layers of Security
### Azure Defender
* Coverage
* Security Alerts
* Insights
* Advanced Protection
#### Scope of Azure Defender
#### Azure Defender - Network Map
#### Azure Defender - Hybrid Cloud Protection
* Azure Arc
### MFA
### Azure Security Center
### Key Vault
* Azure Key Vaut
* Secrets Management
* Key Management
* Certificate Management
* Hardware Security Module
### Azure DDoS Protection
#### What's a DDoS
#### Frequent Types
* Volumetric attacks
* Protocol attacks
* Application layer attacks
#### Two Tiers
* Basic
* Standard
### Azure Firewall
### Application Gateway
### Application Gateway - Routing Rules
* Listeners
  * Basic
  * Multi-site
* Backend targets
* HTTP Settings
### Role Based Access Control RBAC
#### RBAC Elements
* Security principal
  * User
  * Group
  * Service Principal
  * Managed identity
* Role definition
* Scope
#### RBAC Fundamental Roles
* Owner
* Contributor
* Reader
* User Access Administrator
### Azure Management Groups
### Azure Service Health
#### Azure Status
#### Azure Service Health
#### Azure Resource Health
### Azure Advisor




https://www.youtube.com/watch?v=5abffC-K40c&t=11s