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

Understanding these computing services and their components helps you design, deploy, and manage applications effectively in the Azure cloud, ensuring high availability, scalability, and performance.

## Azure App Service
### Introduction to Azure App Service
### Runtimes
### Custom Containers
### Deployment Slots
### App Service Enviroment (ASE)
### Azure App Service Plan


## Azure Container Instances
### Introduction to ACI
(Include differences with VMs)
Container groups
### Container Restart Policies
* Always
* Never
* OnFailure
### Container Environment Variables (Env Vars)
### Container Persistent Storage


## Virtual Networking
### Introduction to VNets
* Azure DNS
* Virtual Network (vNET)
* Network Security Groups
* ExpressRoute
* Virtual WAN
* Virtual Network Gateway
* Network Interfaces
### VNet Peering
* Regional
* Global
### Network Interfaces
### Subnets
### Introduction to Azure DNS
### Introduction to Virtual Network Gateways
### Azure Express Routes
### Private Links
* Private Link Endpont
* Private Link Service



## Storage Accounts
### Storage Services
* Azure Blob Storage
* Azure Disk Storage
* Azure File Storage
* *Azure Queue Storage
* *Azure Table Storage
* Azure Data Box / Azure Databox Heavy
* Azure Archive Storage
* Azure Data Lake Storage
### Introduction to Storage Accounts
### Storage Comparsion
### Core Storage Services
* Azure Blob Storage
* Azure File Storage
* *Azure Queue Storage
* *Azure Table Storage
* Azure Disk Storage
### Performance Tiers
* Standard Performance: HHDs
* Premium Performance: SSDs
### Access Tiers (Blob Storage)
* Hot
* Cool
* Archive
- Account Level Tiering
- Blob-LEvel Tiering
- Rehydrating a Blob
- Blob Lifecycle Management
### Replication Data Redundancy  3h05
### LRS ZRS
### GRS GZRS
### RAGRS_RA GZRS
### Introduction to Azure Blob
### Azure Blob Types
### AZCopy
### Azure Storage Explorer
### Introduction to Azure Files
### Azure Files Use Cases
### Azure File Sync
### Storing files in Blob Storage



https://www.youtube.com/watch?v=5abffC-K40c&t=11s