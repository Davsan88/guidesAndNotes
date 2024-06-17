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
### Regions and Geographies
    58 regions across 140 countries
### Paired Regions
### Region Types and Service Availability
    Recommended region / Alternate region
    General availability (GA)
        1. Foundational 
        2. Mainstream
        3. Specialized
### Special Regions
### Availability Zones
### AZ Supported Regions
### Availability Sets Fault and Update Domains
    * Fault Domain
    * Update Domain
    * Availability Set


## Compute Services
### Computing Services
* Azure Vitual Machines
* Azure Container Instances
* Azure Kubernetes Service (AKS)
* Azure Service Fabric
* Azure Functions
* Azure Batch
### Azure Virtual machines
* NSG
* NIC
* VM instance
* Public IP address
* Virtual Network (VNet)
### Operation Systems
### Azure Scale Sets
### Load Balancer
* Application Gateway HTTP/HTTPS
* Azure Load Balancer TCP/UDP
### Scaling Policy
* Scale-In Policy
* Update policy
### Health Montoring
* Health monitoring
    * Application health extension
    * Load Balancer Probe 
* Automatic repair policy
### Azure Virtual Desktop






https://www.youtube.com/watch?v=5abffC-K40c&t=11s