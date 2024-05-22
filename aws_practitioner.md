# AWS Certified Cloud Practitioner

## Cloud Concepts

### What is Cloud Computing?

Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services, such as computing power, storage, and databases, on an as-needed basis from a cloud provider like AWS.

### Evolution of Cloud Hosting

Cloud hosting has evolved from traditional physical servers to virtualized infrastructure and now to fully managed cloud services. This progression has led to increased scalability, flexibility, and cost-efficiency, allowing businesses to adapt quickly to changing needs and demands.

### What is Amazon?

Amazon.com, Inc. is a multinational technology company based in Seattle, Washington, that focuses on e-commerce, cloud computing, digital streaming, and artificial intelligence. It is one of the Big Five companies in the U.S. information technology industry.

### What is AWS?

Amazon Web Services (AWS) is a subsidiary of Amazon providing on-demand cloud computing platforms and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis. AWS offers scalable, reliable, and low-latency cloud services.

### What is a CSP?

A Cloud Service Provider (CSP) is a company that offers a component of cloud computing—typically Infrastructure as a Service (IaaS), Software as a Service (SaaS), or Platform as a Service (PaaS)—to other businesses or individuals.

### Landscapes of CSPs

The landscape of CSPs includes several major players, each offering a range of cloud services. Key players include AWS, Microsoft Azure, Google Cloud Platform (GCP), IBM Cloud, and Oracle Cloud. Each provider has its own strengths and specialties.

### Gartner Magic Quadrant for Cloud

The Gartner Magic Quadrant (MQ) for Cloud Infrastructure and Platform Services (CIPS) evaluates cloud providers based on their completeness of vision and ability to execute. AWS consistently ranks as a leader in this quadrant, highlighting its strong market presence and comprehensive service offerings.

### Common Cloud Services

Common cloud services provided by CSPs include:

- **Compute**: Virtual machines, containers, serverless computing.
- **Storage**: Object storage, file storage, block storage.
- **Databases**: Managed relational and NoSQL databases.
- **Networking**: Virtual private clouds, load balancers, VPNs.
- **Security**: Identity and access management, encryption, compliance services.

### AWS Technology Overview

AWS provides a comprehensive suite of cloud services that support a wide range of applications, including computing, storage, databases, analytics, networking, mobile, developer tools, management tools, IoT, security, and enterprise applications.

### Evolution of Computing

- **Dedicated Servers**: Dedicated servers are physical machines allocated to a single application or task, often resulting in underutilized resources and high operational costs.
- **Virtual Machines**: Virtual Machines (VMs) allow multiple virtual servers to run on a single physical machine through a hypervisor, improving resource utilization and scalability.
- **Containers**: Containers provide OS-level virtualization, enabling multiple isolated applications to run on a single OS kernel, offering faster start-up times and efficient resource utilization.
- **Functions**: Serverless computing, or Functions as a Service (FaaS), lets developers run code in response to events without managing servers, with automatic scaling and pay-as-you-go pricing.

### Types of Cloud Computing

Cloud computing services are generally categorized into three types:

- **Infrastructure as a Service (IaaS)**: Provides virtualized computing resources over the internet.
- **Platform as a Service (PaaS)**: Provides hardware and software tools over the internet, typically for application development.
- **Software as a Service (SaaS)**: Delivers software applications over the internet, on-demand, and typically on a subscription basis.

### Cloud Computing Deployment Models

- **Private Cloud**: Cloud infrastructure operated solely for a single organization.
- **Public Cloud**: Cloud infrastructure made available to the general public or a large industry group and owned by an organization selling cloud services.
- **Hybrid Cloud**: A composition of two or more distinct cloud infrastructures (private, community, or public) that remain unique entities but are bound together by standardized or proprietary technology.
- **Cross-Cloud**: When using multiple cloud providers.

>Understanding these core concepts provides a solid foundation for leveraging AWS services effectively and aligns with the AWS Certified Cloud Practitioner exam requirements.

## Digital Transformation

### Innovation Waves

Innovation waves refer to the successive phases of technological advancements that drive significant changes in industries, such as the shift from mainframes to personal computers, the internet, and now to cloud computing and AI.

### Burning Platform

A burning platform is a compelling and urgent need for change within an organization, often driven by market pressures, competition, or technological advancements, necessitating a rapid transformation strategy.

### Digital Transformation Checklist

A digital transformation checklist includes key steps such as assessing current capabilities, setting clear objectives, leveraging cloud technologies, fostering a culture of innovation, and continuously measuring and optimizing the transformation efforts.

### Evolution of Computing Power

The evolution of computing power highlights the dramatic improvements in processing capabilities from mainframes and personal computers to today's cloud-based infrastructures, enabling more complex and large-scale computations.

### Amazon Bracket

Amazon Bracket is a fully managed service that provides a development environment for quantum algorithms, helping researchers and developers to explore and experiment with quantum computing using simulators and quantum hardware.


## The Benefits of Cloud

### The 6 Advantages of Cloud

1. **Trade Capital Expense (CAPEX) for Operational Expense (OPEX)**:
   Move from large upfront capital investments to pay-as-you-go pricing, reducing financial risk and improving cash flow.

2. **Benefit from Massive Economies of Scale**:
   AWS aggregates usage from hundreds of thousands of customers, achieving higher economies of scale and passing the savings onto customers.

3. **Stop Guessing Capacity**:
   Eliminate the need to guess infrastructure capacity needs, reducing the risk of over-provisioning or under-provisioning resources.

4. **Increase Speed and Agility**:
   Quickly deploy new resources and scale infrastructure in minutes, allowing for rapid innovation and time-to-market.

5. **Stop Spending Money on Running and Maintaining Data Centers**:
   Focus on projects that differentiate your business, not the infrastructure, by outsourcing data center operations to AWS.

6. **Go Global in Minutes**:
   Easily deploy applications in multiple regions around the world to provide lower latency and a better experience for customers.

### The 7 Advantages of Cloud

In addition to the six advantages mentioned above, the seventh advantage is often cited as:

7. **Improved Security**:
   Benefit from a data center and network architecture built to meet the requirements of the most security-sensitive organizations, with comprehensive security and compliance controls.

>Understanding these advantages helps organizations leverage cloud computing effectively, aligning with business goals and enhancing overall efficiency and innovation.


## Global Infrastructure

### Global Infra Overview

AWS Global Infrastructure is designed to provide a secure, scalable, and highly available environment for deploying cloud applications and services.

### Regions

Regions are separate geographic areas that AWS uses to host data centers, enabling data redundancy and locality for compliance and latency purposes.

### Regions vs Global Services

Regions provide localized services within specific geographic areas, while global services, such as IAM, Route 53, and CloudFront, operate across multiple regions.

### Availability Zones

Availability Zones (AZs) are distinct locations within a region, each with independent power, cooling, and networking, providing high availability and fault tolerance.

### Regions vs AZ Visualized

Regions consist of multiple AZs, and visualizing this setup helps understand how AWS ensures high availability by distributing resources across multiple AZs within a region.

### Fault Tolerance

Fault tolerance refers to the ability of a system to continue operating without interruption when one or more of its components fail, which AWS achieves through its AZs and regions.

### AWS Global Network

The AWS Global Network is a highly available, low-latency global network infrastructure that interconnects AWS regions, AZs, and edge locations.

### Points of Presence (PoP)

Points of Presence (PoPs) are data centers used by AWS to deliver low-latency content to users globally, primarily through services like CloudFront and Route 53.

### PoP's Tier 1

Tier 1 PoPs are strategically located to provide optimal performance and reliability for content delivery and other global services.

### AWS Direct Connect

AWS Direct Connect provides a dedicated network connection from your premises to AWS, offering more consistent network performance and lower latency compared to internet-based connections.

### Direct Connect Locations

Direct Connect Locations are specific facilities where AWS Direct Connect is available, enabling customers to establish private connectivity to AWS.

### AWS Local Zones

AWS Local Zones place compute, storage, and other select AWS services closer to large population, industry, and IT centers for applications that require single-digit millisecond latency.

### Wavelength Zones

Wavelength Zones extend AWS infrastructure to the edge of the 5G network, minimizing latency to deliver ultra-low latency applications for mobile and connected devices.

### Data Residency

Data residency refers to the physical or geographic location of data and its implications for data sovereignty and compliance with local regulations.

### AWS for Government

AWS for Government provides cloud services that meet the unique regulatory, security, and compliance requirements of government agencies.

### GovCloud

AWS GovCloud (US) is an isolated AWS region designed to host sensitive data and regulated workloads in the cloud, ensuring compliance with US government requirements.

### AWS in China

AWS operates AWS China (Beijing) and AWS China (Ningxia) regions in compliance with Chinese regulations, through a partnership with local providers.

### Sustainability

AWS is committed to sustainability through initiatives like achieving 100% renewable energy usage for global infrastructure and continuous efforts to improve energy efficiency.

### AWS Ground Station

AWS Ground Station provides fully managed ground station services, enabling customers to control satellite communications, process data, and scale operations without managing ground station infrastructure.

### AWS Outposts

AWS Outposts extends AWS infrastructure, services, APIs, and tools to virtually any datacenter, co-location space, or on-premises facility for a truly consistent hybrid experience.


## Cloud Architecture

### Cloud Architecture Terminologies

#### Solutions Architect
A Solutions Architect designs comprehensive cloud solutions, ensuring they meet business requirements, are cost-effective, and leverage AWS services optimally.

#### Cloud Architect
A Cloud Architect focuses on designing and implementing cloud environments, ensuring that they are scalable, secure, and aligned with best practices.

### High Availability
Refers to systems that are durable and likely to operate continuously without failure for a long time. AWS ensures high availability through services like Elastic Load Balancer (ELB).


#### Elastic Load Balancer
An Elastic Load Balancer (ELB) automatically distributes incoming application traffic across multiple targets, such as Amazon EC2 instances, ensuring high availability and reliability.

### High Scalability

High scalability refers to the ability of a cloud system to handle growing amounts of work by adding resources dynamically, ensuring performance remains consistent.

### High Elasticity
Allows systems to automatically adapt to workload changes by provisioning and de-provisioning resources in an automatic manner.


#### Auto Scaling Groups (ASG)
Auto Scaling Groups (ASG) allow automatic scaling of Amazon EC2 instances based on demand, ensuring the application can handle varying loads efficiently.

### Highly Fault Tolerant
Highly fault-tolerant systems can continue operating properly in the event of the failure of some of its components. AWS enhances fault tolerance with services like Amazon RDS Multi-AZ.


#### RDS Multi-AZ
Amazon RDS Multi-AZ deployments provide enhanced availability and durability for database instances, automatically replicating data to a standby instance in a different Availability Zone.

### High Durability
High durability ensures that data is stored reliably and remains intact over long periods. AWS services like Amazon S3 and CloudEndure Disaster Recovery offer high durability by replicating data across multiple devices and locations, safeguarding against data loss and corruption.

#### CloudEndure Disaster Recovery
CloudEndure Disaster Recovery enables fast and reliable recovery of physical, virtual, and cloud-based servers into AWS, ensuring data durability and minimizing downtime.

### Business Continuity Plan (BCP)

#### Recovery Point Objective (RPO)
Recovery Point Objective (RPO) defines the maximum acceptable amount of data loss measured in time, ensuring that data can be recovered within a specified timeframe before a disruption.

#### Recovery Time Objective (RTO)
Recovery Time Objective (RTO) specifies the maximum acceptable amount of time to restore a system or service after a disruption, minimizing downtime and ensuring business continuity.

### Discover Recovery Options

#### Backup & Restore (Hours)
Backup & Restore involves regularly backing up data and restoring it in case of failure, suitable for recovery times measured in hours.

#### Pilot Light (10 mins)
Pilot Light involves maintaining a minimal version of an environment always running, allowing quick scaling up in the event of a disaster, typically within 10 minutes.

#### Warm Standby (Minutes)
Warm Standby maintains a scaled-down but fully functional version of a production environment, allowing rapid scaling and minimal downtime, typically within minutes.

#### Multi-site Active/Active (Real-time)
Multi-site Active/Active refers to running multiple instances of an application across multiple locations simultaneously, providing real-time data synchronization and seamless failover.

>Understanding these concepts and strategies is crucial for designing resilient, scalable, and efficient cloud architectures that meet business needs and ensure operational continuity.


## Management and Developer Tools

### AWS API
The AWS API allows developers to interact with AWS services programmatically, enabling automation and integration with various applications through RESTful APIs.

### AWS Mgmt Console
The AWS Management Console is a web-based user interface that allows users to manage and configure their AWS services and resources easily.

### Service Console
Service consoles are specific sections within the AWS Management Console dedicated to individual AWS services, providing targeted interfaces for managing those services.

### AWS Account ID
An AWS Account ID is a unique identifier assigned to each AWS account, used to distinguish resources and users within the AWS environment.

### AWS Tools for PowerShell
AWS Tools for PowerShell enable developers and administrators to manage AWS services from the PowerShell command line, facilitating automation and scripting.

### Amazon Resource Names (ARNs)
Amazon Resource Names (ARNs) uniquely identify AWS resources, allowing users to specify resources across all AWS services in a standardized format.

### AWS CLI
The AWS Command Line Interface (CLI) is a unified tool to manage AWS services, enabling users to control multiple AWS services from the command line and automate tasks through scripts.

### AWS SDK
The AWS Software Development Kit (SDK) provides language-specific APIs that simplify the process of integrating AWS services into your applications, supporting languages like Python, Java, JavaScript, and more.

### AWS CloudShell
AWS CloudShell is a browser-based shell that provides a command-line environment pre-configured with AWS CLI and other essential tools, making it easy to manage AWS resources without local setup.

### Infrastructure as Code
Infrastructure as Code (IaC) is the practice of managing and provisioning computing infrastructure through machine-readable definition files, rather than physical hardware configuration or interactive configuration tools.

### CloudFormation
AWS CloudFormation is a service that enables you to model and set up your AWS resources using templates, automating the process of resource creation and management.

### CDK (Cloud Development Kit)
The AWS Cloud Development Kit (CDK) is an open-source software development framework that allows you to define cloud infrastructure using familiar programming languages.

### AWS Toolkit for VSCode
The AWS Toolkit for Visual Studio Code (VSCode) is an extension that integrates AWS services with the VSCode IDE, providing tools to create, debug, and deploy applications on AWS.

### Access Keys
Access keys are a combination of an access key ID and a secret access key used to sign programmatic requests to AWS, providing secure access to AWS services.

### AWS Documentation
AWS Documentation is the comprehensive and official resource for learning about AWS services, including guides, tutorials, API references, and best practices to help users effectively utilize AWS services.


## Shared Responsibility Model

### AWS Shared Responsibility Model
The AWS Shared Responsibility Model defines the division of security responsibilities between AWS and the customer.

- **Customers are responsible for Security in the Cloud**: This includes securing data, managing user access, configuring security settings, and ensuring application security.
- **AWS is responsible for Security of the Cloud**: AWS manages and secures the infrastructure that runs all of the services offered in the AWS Cloud, including hardware, software, networking, and facilities.

### Types of Cloud Responsibilities
Cloud responsibilities are divided between AWS and the customer:

- **Customer Responsibilities**:
  - Data protection and encryption.
  - Identity and access management (IAM).
  - Application security and network traffic protection.
  - Operating system and network configuration.
  - Client-side and server-side data protection.

- **AWS Responsibilities**:
  - Physical security of data centers.
  - Hardware and software infrastructure.
  - Network infrastructure and virtualization.
  - AWS global network security.

### Shared Responsibility for Compute
In compute services, AWS manages the underlying physical infrastructure, including servers, storage, and networking, while customers are responsible for managing their operating systems, applications, and data.

- **AWS Responsibilities**:
  - Physical server management.
  - Network infrastructure.
  - Hypervisor security.

- **Customer Responsibilities**:
  - Instance operating system (OS) patches and updates.
  - Application software and utilities.
  - Data encryption and security.


### Shared Responsibility Model Alternate
In Platform as a Service (PaaS) and Software as a Service (SaaS) models, the balance of responsibilities shifts more towards AWS:

- **PaaS**: AWS manages the infrastructure, operating systems, and platform services, while customers manage the applications they deploy and their data.
- **SaaS**: AWS handles most of the responsibilities, including infrastructure, platform services, and application management, while customers focus on data protection and user access management.

### Shared Responsibility Model Architecture
The architecture of the Shared Responsibility Model ensures clear delineation of responsibilities:

- **Infrastructure as a Service (IaaS)**: Customers manage the most aspects, including the OS, applications, and data.
- **Platform as a Service (PaaS)**: AWS manages the infrastructure and platform, with customers focusing on applications and data.
- **Software as a Service (SaaS)**: AWS handles almost everything, with customers managing user access and data.

>Understanding the Shared Responsibility Model is crucial for securing AWS environments, ensuring that both AWS and the customer fulfill their respective security obligations.


## Compute

### VMs, Containers & Serverless

#### VMs
Virtual Machines (VMs) allow you to run applications in isolated environments, providing control over the operating system and installed software.

- **Amazon LightSail**: Provides easy-to-use cloud resources like virtual private servers, storage, and networking for simple web applications and websites.


#### Containers
Containers provide a lightweight way to encapsulate and run applications with their dependencies, ensuring consistency across multiple environments.

- **Elastic Container Service (ECS)**: A highly scalable container orchestration service that supports Docker containers.
- **Elastic Container Registry (ECR)**: A fully managed Docker container registry that makes it easy to store, manage, and deploy container images.
- **ECS Fargate**: A serverless compute engine for containers that works with ECS to run containers without managing servers.
- **Elastic Kubernetes Service (EKS)**: A managed service that makes it easy to run Kubernetes on AWS without needing to install and operate your own Kubernetes control plane.

#### Serverless
Serverless computing lets you run code without provisioning or managing servers, automatically scaling with demand and charging only for the compute time used.

- **AWS Lambda**: Lets you run code without provisioning or managing servers, charging you only for the compute time you consume.

### High Performance Compute (HPC)
HPC on AWS provides the infrastructure and tools needed to run large-scale compute and data-intensive workloads efficiently.

#### Bottlerocket
- **Bottlerocket**: An open-source, Linux-based operating system designed specifically for running containers, ensuring security and efficiency.

#### AWS ParallelCluster
- **AWS ParallelCluster**: An AWS-supported open-source cluster management tool that makes it easy to deploy and manage HPC clusters on AWS.

### Edge & Hybrid
AWS offers solutions like Outposts, Wavelength, and Local Zones to extend AWS services to edge locations and on-premises environments, ensuring low-latency and hybrid cloud capabilities.

- **AWS Outposts**: Extends AWS infrastructure and services to virtually any data center, co-location space, or on-premises facility for a truly consistent hybrid experience.
- **AWS Wavelength**: Enables developers to build applications that deliver ultra-low latencies to mobile and connected devices by deploying AWS compute and storage services at the edge of telecom networks.
- **VMWare Cloud on AWS**: Allows you to run a VMware software-defined data center (SDDC) on AWS infrastructure, enabling seamless migration and hybrid cloud strategies.
- **AWS Local Zones**: Places AWS compute, storage, database, and other select services closer to large population, industry, and IT centers for applications that require single-digit millisecond latency.

### Cost & Capacity Management

#### EC2 Spot Instances, Reserved Instances, and Savings Plan
- **EC2 Spot Instances**: Allow you to use spare AWS compute capacity at reduced rates, ideal for flexible and fault-tolerant applications.
- **Reserved Instances**: Offer significant discounts compared to on-demand pricing in exchange for a commitment to use AWS compute capacity for a one- or three-year term.
- **Savings Plans**: Provide flexible pricing with lower rates for a commitment to consistent usage (measured in $/hour) for a one- or three-year term.

#### AWS Batch
AWS Batch enables you to run batch computing workloads on the AWS Cloud, efficiently provisioning resources based on the volume and specific resource requirements of the jobs submitted.

#### AWS Compute Optimizer
AWS Compute Optimizer analyzes your AWS resources and usage patterns to recommend optimal configurations to reduce cost and improve performance.

#### EC2 Auto Scaling Group (ASGs)
Auto Scaling Groups (ASGs) ensure you have the right number of EC2 instances available to handle the load for your applications, automatically scaling up or down based on demand.

#### Elastic Load Balancer (ELB)
Elastic Load Balancer (ELB) automatically distributes incoming application traffic across multiple targets, such as EC2 instances, containers, and IP addresses, enhancing fault tolerance and availability.

#### AWS Elastic Beanstalk (EB)
AWS Elastic Beanstalk (EB) is an easy-to-use service for deploying and scaling web applications and services, automatically handling capacity provisioning, load balancing, and scaling.

>Understanding these compute services and cost management tools helps you efficiently leverage AWS resources to build, deploy, and manage applications.





## Storage Services

### Types of STorate Services
   - **Block**: Elastic Block Store (EBS) provides persistent block storage volumes for use with Amazon EC2 instances, offering high performance for both throughput and transaction-intensive workloads.

   - **File**: AWS Elastic File System (EFS) provides scalable file storage for use with AWS Cloud services and on-premises resources, allowing you to create and configure file systems quickly and easily.

   - **Object**: Amazon Simple Storage Service (S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance, making it easy to store and retrieve any amount of data from anywhere.

### Intro to S3
Amazon S3 stores data as objects within buckets. An object consists of a file and optionally any metadata that describes that file. Buckets are containers for objects, and each object is identified by a unique key.

### S3 Storage Classes
Amazon S3 offers a range of storage classes designed for different use cases:

- **S3 Standard**: General-purpose storage for frequently accessed data.
- **S3 Intelligent-Tiering**: Automatically moves data between two access tiers when access patterns change.
- **S3 Standard-IA (Infrequent Access)**: For data that is accessed less frequently but requires rapid access when needed.
- **S3 One Zone-IA**: Lower-cost option for infrequently accessed data that does not require multiple Availability Zone resilience.
- **S3 Glacier**: Low-cost storage designed for data archiving, offering retrieval times from minutes to hours.
- **S3 Glacier Deep Archive**: Lowest-cost storage class for long-term data archiving with retrieval times of 12 hours or more.

### AWS Snow Family
The AWS Snow Family includes physical devices to help physically transport up to exabytes of data into and out of AWS. These services are designed for customers who need to move large amounts of data in situations where network transfer is impractical or impossible:

- **AWS Snowcone**: Small, portable edge computing and data transfer device.
- **AWS Snowball Edge**: Data transfer device with on-board storage and compute capabilities.
- **AWS Snowmobile**: Exabyte-scale data transfer service using a 45-foot shipping container.

### Storage Services
- **Simple Storage Service (S3)** - scalable object storage with high durability, availability, and security.

- **S3 Glacier** - low-cost storage for data archiving, with flexible retrieval times ranging from minutes to hours.

- **Elastic Block Store (EBS)** - high-performance block storage for use with EC2 instances, suitable for a wide range of workloads.

- **AWS Elastic File System (EFS)** - scalable file storage for use with AWS Cloud services and on-premises resources, supporting file-based workloads.

- **Storage Gateway** - connects on-premises software appliances with cloud-based storage, providing seamless integration between on-premises IT environments and the AWS storage infrastructure.
   + *File Gateway*: Offers file-based access to objects in S3 with local caching.
   + *Volume Gateway*: Provides block storage volumes that can be mounted as iSCSI devices from on-premises servers.
   + *Tape Gateway*: Enables customers to use S3 and Glacier as a scalable, cost-effective, and durable virtual tape infrastructure.

- **AWS Backup** - automates and centrally manages backups across AWS services, ensuring data protection and compliance.

- **CloudEndure Disaster Recovery** - minimizes downtime and data loss by enabling fast and reliable recovery of physical, virtual, and cloud-based servers into AWS.

- **Amazon FSx**
   + *FSx for Windows File Server (SMB)*: Provides fully managed, highly reliable, and scalable file storage accessible over the industry-standard Server Message Block (SMB) protocol.
   + *FSx for Lustre*: Offers high-performance file systems optimized for fast processing of workloads such as machine learning, high-performance computing (HPC), and media data processing workflows.

>Understanding these storage services and their use cases enables you to choose the right storage solution for your needs, ensuring optimal performance, cost-efficiency, and scalability.


## Databases
Databases are organized collections of structured or unstructured data that can be easily accessed, managed, and updated, serving as the backbone for storing and retrieving information in various applications and services.

### Data Warehouses
A data warehouse is a central repository for structured and unstructured data that is used for reporting and data analysis. Amazon Redshift is AWS's fast, scalable data warehouse that makes it simple and cost-effective to analyze all your data across your data warehouse and data lake.

### Key-Value Store
Key-value stores are non-relational databases that store data as key-value pairs, enabling fast retrieval of data. Amazon DynamoDB is a fully managed key-value and document database that delivers single-digit millisecond performance at any scale.

### Document Database
Document databases store data in JSON-like document formats, allowing for flexible and semi-structured data models. Amazon DocumentDB (with MongoDB compatibility) is a fast, scalable, highly available, and fully managed document database service that supports MongoDB workloads.

### NoSQL Database Services
NoSQL databases provide a mechanism for storage and retrieval of data that is modeled in means other than the tabular relations used in relational databases. 

- **DynamoDB**: A fully managed key-value and document database that delivers single-digit millisecond performance at any scale.
- **DocumentDB**: A fast, scalable, highly available, and fully managed document database service that supports MongoDB workloads.
- **Amazon Keyspaces**: A scalable, highly available, and managed Apache Cassandra-compatible database service.

### Relational Database Services
Relational databases store data in tables and use SQL for database access. A

- **Relational Database Service (RDS)**: Simplifies the setup, operation, and scaling of a relational database in the cloud, supporting engines like PostgreSQL, MySQL, MariaDB, Oracle, and Microsoft SQL Server.
- **Aurora**: A MySQL and PostgreSQL-compatible relational database built for the cloud, offering high performance and availability.
- **Aurora Serverless**: An on-demand, auto-scaling configuration for Aurora where the database automatically starts up, shuts down, and scales capacity based on your application's needs.
- **RDS on VMware**: Allows you to deploy managed databases in on-premises VMware environments using Amazon RDS technology.

### Other Database Services
- **Redshift**: A fast, scalable data warehouse that makes it simple and cost-effective to analyze all your data across your data warehouse and data lake.
- **ElastiCache**: A fully managed in-memory data store and cache service that supports Redis and Memcached.
- **Neptune**: A fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets.
- **Amazon Timestream**: A fast, scalable, and fully managed time series database service for IoT and operational applications that makes it easy to store and analyze trillions of events per day.
- **Amazon Quantum Ledger Database (QLDB)**: A fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log.
- **Database Migration Service (DMS)**: Helps you migrate databases to AWS easily and securely, supporting homogeneous migrations (e.g., Oracle to Oracle) and heterogeneous migrations (e.g., Oracle to Amazon Aurora).

>Understanding these database services and their specific use cases helps you select the right database solution for your application, ensuring optimal performance, scalability, and cost-efficiency.


## Networking
AWS provides a range of networking services to connect, secure, and manage your cloud infrastructure. These services help you build and scale your applications with high availability and security.

### Cloud-Native Networking Services
Cloud-native networking services are designed to work seamlessly within the AWS environment, providing secure, scalable, and high-performance networking capabilities.

- **VPC (Virtual Private Cloud)**: Enables you to launch AWS resources in a logically isolated virtual network that you define.
- **Internet Gateway**: A horizontally scaled, redundant, and highly available VPC component that allows communication between instances in your VPC and the internet.
- **Route Tables**: Contains a set of rules, called routes, that are used to determine where network traffic is directed.
- **NACL (Network Access Control List)**: Provides a stateless firewall for controlling traffic in and out of one or more subnets.
- **Region**: A physical location around the world where AWS clusters data centers.
- **AZ (Availability Zone)**: One or more discrete data centers with redundant power, networking, and connectivity in an AWS Region.
- **Subnet**: A range of IP addresses in your VPC where you can place AWS resources.
- **Security Group**: Acts as a virtual firewall for your instance to control inbound and outbound traffic.

### Enterprise/Hybrid Networking Services
Enterprise and hybrid networking services enable secure and reliable connectivity between your on-premises data centers and the AWS cloud, supporting hybrid cloud architectures.

- **AWS Virtual Private Network (VPN)**: Establishes a secure connection between your on-premises network and your AWS VPC.
- **DirectConnect**: Provides a dedicated network connection from your premises to AWS, improving performance and security.
- **PrivateLinks**: Enables you to access services hosted on AWS in a highly available and scalable manner, keeping your network traffic within the AWS network.

### VPC & Subnets
Amazon VPC allows you to provision a logically isolated section of the AWS cloud where you can launch AWS resources in a virtual network. Subnets divide the VPC into smaller network segments, improving management and security.

### Security Groups vs NACLs
Security Groups and Network Access Control Lists (NACLs) both provide network security controls, but they function differently. Security Groups are stateful, managing the traffic for instances, while NACLs are stateless, managing the traffic for subnets.

### AWS CloudFront
AWS CloudFront is a fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency and high transfer speeds. It integrates with other AWS services to provide a robust solution for content delivery.

>Understanding these networking services helps you design, deploy, and manage your applications in the AWS cloud effectively, ensuring security, performance, and scalability.


## EC2
Amazon Elastic Compute Cloud (EC2) provides scalable computing capacity in the AWS cloud, allowing you to launch virtual servers as needed. Understanding EC2 is crucial for managing your compute resources effectively.

### EC2 Instance Families
EC2 instance families are grouped by their capabilities, optimized for different use cases:

- **General Purpose**: Balanced compute, memory, and networking resources (e.g., t3, m5).
- **Compute Optimized**: High compute-to-memory ratio (e.g., c5).
- **Memory Optimized**: High memory-to-compute ratio (e.g., r5, x1).
- **Storage Optimized**: High, sequential read and write access to large data sets (e.g., i3).
- **Accelerated Computing**: Use hardware accelerators, or co-processors, to perform functions such as floating-point number calculations, graphics processing, or data pattern matching (e.g., p3, g4).

### EC2 Instance Types
EC2 instance types within each family offer different combinations of CPU, memory, storage, and networking capacity, allowing you to choose the optimal configuration for your application needs.

### Dedicated Host vs Dedicated Instances
- **Dedicated Host**: Physical server fully dedicated to your use, providing visibility and control over the underlying hardware, useful for licensing and compliance requirements.
- **Dedicated Instances**: EC2 instances that run on hardware dedicated to a single customer, offering similar isolation but without the visibility into the underlying hardware.

### EC2 Tenancy
EC2 tenancy defines how instances are run on hardware:

- **Shared Tenancy**: Instances run on shared hardware; default option with no additional cost.
- **Dedicated Tenancy**: Instances run on hardware dedicated to a single customer, providing physical isolation.
- **Host Tenancy**: Similar to dedicated tenancy, but provides visibility into the underlying hardware for compliance and licensing purposes.

>Understanding these EC2 concepts helps you optimize your compute resources for performance, cost, and compliance requirements.


## EC2 Pricing Models
AWS offers several pricing models for EC2 instances to provide flexibility and cost efficiency, catering to different use cases and budget requirements.

### On-Demand
On-Demand instances let you pay for compute capacity by the hour or second, with no long-term commitments. This model is ideal for applications with short-term, spiky, or unpredictable workloads that cannot be interrupted.

### Reserved (Reserved Instances)
Reserved Instances (RIs) provide a significant discount compared to On-Demand pricing in exchange for a one- or three-year commitment. This model is best for applications with steady-state or predictable usage.

### RI (Reserved Instances) Attributes
- **Instance Type**: Specific EC2 instance type (e.g., t3.medium).
- **Platform**: Operating system (e.g., Linux, Windows).
- **Tenancy**: Shared or dedicated.
- **Term**: One or three years.
- **Payment Option**: All upfront, partial upfront, or no upfront.

### Regional & Zonal RI
- **Regional RI**: Provides a discount on usage in any Availability Zone within a specified region.
- **Zonal RI**: Provides a capacity reservation in a specific Availability Zone.

### RI Limits
Reserved Instances are subject to purchase limits based on the region and the instance type, which can be increased by contacting AWS support if necessary.

### Capacity Reservations
Capacity Reservations ensure you have access to EC2 capacity when you need it, in a specific Availability Zone, for any duration. You pay for the reserved capacity, regardless of whether you use it.

### Standard vs Convertible RI
- **Standard RI**: Provides the highest discount but can only be modified to change Availability Zone, instance size (within the same family), and network type.
- **Convertible RI**: Offers a lower discount but allows you to change the instance type, operating system, and tenancy during the term.

### RI Marketplace
The RI Marketplace allows you to sell your unused Standard Reserved Instances to other AWS customers, providing flexibility if your computing needs change.

### Spot
Spot Instances allow you to bid on unused EC2 capacity at a significantly lower price than On-Demand instances. Ideal for fault-tolerant and flexible applications that can handle interruptions.

### AWS Batch
AWS Batch enables you to run batch computing workloads on the AWS Cloud, dynamically provisioning the optimal quantity and type of compute resources based on the volume and specific resource requirements of the jobs submitted.

### Dedicated
Dedicated Instances run on hardware dedicated to a single customer, offering physical isolation. This model is suitable for workloads requiring a dedicated server for compliance or licensing purposes.

### Savings Plan
Savings Plans offer significant savings over On-Demand pricing in exchange for a commitment to a consistent amount of usage (measured in $/hour) for a one- or three-year term, providing flexibility to use any EC2 instance type.

>Understanding these EC2 pricing models helps you choose the most cost-effective option for your workloads, ensuring efficient resource utilization and cost management.

	
## Identity

### Zero-Trust Model
The Zero-Trust Model is a security concept centered around the belief that organizations should not automatically trust anything inside or outside its perimeters and must verify anything and everything trying to connect to its systems before granting access.

### Zero-Trust on AWS
AWS implements Zero-Trust through a combination of services that provide comprehensive monitoring, threat detection, and investigation.

- **AWS CloudTrail**: Enables governance, compliance, and operational and risk auditing of your AWS account.
- **Amazon GuardDuty**: A threat detection service that continuously monitors for malicious activity and unauthorized behavior.
- **Amazon Detective**: Analyzes and visualizes security data to help you conduct faster and more efficient investigations.

### Zero-Trust on AWS with Third Parties
AWS can integrate with third-party identity and access management solutions to enhance the Zero-Trust Model.

- **Azure Active Directory, Google BeyondCorp, JumpCloud**: Third-party identity providers that can be integrated with AWS Single Sign-On (SSO) to provide seamless access to AWS resources.

### Directory Services
AWS Directory Service offers multiple ways to use Microsoft Active Directory with other AWS services. You can choose from AWS Managed Microsoft AD, AD Connector, or Simple AD.

### Active Directory
Active Directory (AD) is a directory service developed by Microsoft for Windows domain networks, which is also supported by AWS through AWS Managed Microsoft AD.

### Identity Providers
Identity Providers (IdPs) are services that provide authentication and authorization to applications and services by verifying user identities.

### Single-Sign-On
Single-Sign-On (SSO) allows users to authenticate once and gain access to multiple applications and services without re-entering credentials.

### LDAP
Lightweight Directory Access Protocol (LDAP) is an open, vendor-neutral application protocol for accessing and maintaining distributed directory information services over an IP network.

### Multi-Factor Authentication
Multi-Factor Authentication (MFA) adds an extra layer of security by requiring users to provide two or more verification factors to gain access to a resource.

### Security Keys
Security keys are hardware devices used for authenticating a user by providing a physical token for login, enhancing security through MFA.

### AWS IAM
AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely.

- **Policies**: Documents that define permissions for actions on AWS resources.
- **Permissions**: Rules that define what actions users, groups, and roles can perform on AWS resources.
- **Users**: Individual IAM users that you create in your AWS account.
- **Groups**: Collections of IAM users, which can be assigned permissions collectively.
- **Roles**: IAM roles that AWS services or applications can assume to access AWS resources.

### Anatomy of an IAM Policy
IAM policies define permissions and consist of the following elements:

- **Version**: Specifies the policy language version.
- **Statement**: Container for individual permissions.
- **Sid**: Optional identifier for the policy statement.
- **Effect**: Specifies whether the statement results in an allow or deny.
- **Action**: List of actions the policy allows or denies.
- **Principal**: Specifies the user, account, service, or other entity that is allowed or denied access.
- **Resource**: Specifies the AWS resource to which the actions apply.
- **Condition**: Specifies the conditions under which the policy grants permission.

### Principle of Least Privilege
The principle of least privilege involves granting users only the permissions they need to perform their job functions.

- **JEA (Just Enough Administration)**: Limits administrative privileges.
- **JIT (Just In Time)**: Grants temporary access to resources as needed.

### AWS Account Root User
The root user has full access to all AWS services and resources in the account. Some administrative tasks can only be performed by the root user:

- Change your account settings
- Close your AWS account
- Change or cancel your AWS Support plan

### AWS SSO
AWS Single Sign-On (SSO) allows you to centrally manage access to multiple AWS accounts and business applications, providing users with a single sign-on experience.


## Application Integration
AWS provides various services for integrating applications, ensuring seamless communication and data flow between different systems and components.

### Queuing & SQS
Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. It is designed for scenarios where messages do not need to be processed in real-time.

### Streaming and Kinesis
Amazon Kinesis is a platform on AWS to collect, process, and analyze real-time, streaming data, enabling you to get timely insights and react quickly to new information.

### PubSub & SNS

Amazon Simple Notification Service (SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. It follows the Publisher => Event Bus => Subscriber model, where messages are published to a topic and delivered to multiple subscribers.

### API Gateway & Amazon API Gateway

Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. It acts as a "front door" for applications to access data, business logic, or functionality from backend services.

### State Machines & AWS Step Functions

AWS Step Functions is a serverless orchestration service that lets you combine AWS Lambda functions and other AWS services to build and run scalable applications. It uses state machines to define workflows that trigger actions in response to events.

### Event Bus & AWS EventBridge

Amazon EventBridge is a serverless event bus service that makes it easy to connect applications using data from your own applications, integrated software-as-a-service (SaaS) applications, and AWS services.

- **Event Bus**: Acts as a channel for transmitting events from producers to consumers.
- **Producers**: Generate events and send them to the event bus.
- **Events**: Pieces of data that indicate state changes or updates.
- **Partner Sources**: External services that can send events to EventBridge.
- **Rules**: Define how events are routed to targets.
- **Targets**: Resources that process events, such as Lambda functions, Step Functions, or SQS queues.

### Application Integration Services

AWS offers a range of services to facilitate application integration:

- **SNS**: Simple Notification Service for message delivery.
- **SQS**: Simple Queue Service for message queuing.
- **Step Functions**: For orchestrating workflows.
- **EventBridge**: For event-driven architectures.
- **Kinesis**: For real-time data streaming.
- **Amazon MQ**: Managed message broker service for Apache ActiveMQ and RabbitMQ.
- **MKS**: Managed Kafka service for real-time data streaming.
- **API Gateway**: For creating, deploying, and managing APIs.
- **AppSync**: A managed service for building GraphQL APIs, enabling you to query and manipulate data from multiple sources.

Understanding these application integration services helps you design robust, scalable, and efficient architectures that facilitate seamless communication between different parts of your applications.


## Containers
### VMs vs Containers
### Microservices?
### Kubernetes
### Docker
### Podman, Buildah and Skopeo
### Container Services
   Primary services;
      ECS
      AWS  Fargate
      EKS
      AWS Lambd
   Provisionning and Deployment
      EB
      App Runner
      AWS Copilot CLI
   SUpporting Services
      ECR
      X-Ray
      Step Functions

## Governance
### Organizations & Accounts
   AWS Organizations
   Root Account User
   Organization Units
   Serice Control Policies
### AWS Control Tower
   Landing Zone
   Account Factory
   Guardrails
### AWS Config 
### AWS Quick Starts
### Tagging
### Resource Groups
### Business Centric Services
   Amazon Connect
   WorkSpaces
   WorkDocs
   Chime
   WOrkMail
   Pinpoint (Exam)
   Simple Email Service (SES) (Exam)
   QuickSight (Exam)






## Provisioning
### Provisioning Services
   EB
   OpsWorks
   CloudFormation
   QuickStarts
   AWS Marketplace
   Amplify
   App Runner
   Copilot
   CodeStar
   CDK
 ### AWS Elastic Beanstalk
	
## Serverless
### Serverless Services
   DynamoDB
   S3
   ECS Fargate
   AWS Lambda
   Set Functions
   Aurora Serverless
### What is Serverless
   Highly elastic and scalable, available, durable,
   Secure by default
   Scale-to-Zero
   Pay-for-Value

## Windows on AWS	
### AWS License Manager
   BYOL

## Logging
   CloudTrail
   CloudWatch
   AWS X-Ray
### AWS CloudTrail
### CloudWatch Alarm
### Anatomy of an Alarm
### Log Events
### Log Insights
### CloudWatch Metrics

## ML AI BigData
### Intro to ML & AI
### AI & ML Services
### BigData & Analytics Services
### Amazon QuickSight	
### ML & AI Services - Extended
   Amazon Bedrock
   Amazon CodeWhisper
### Generative AI
### ML & DL Frameworks and Tools
   Apache MXNet
   PyTorch
   TensoorFlow
   + Keras
   Apache Spark
   + SparkML
   Chainer

   Hugging Face
### Apache MXNet
### Intel?
   x86 & ARM
### Intel Xeon Scalable & Intel Gaudi
### GPU
### CUDA

## AWS Well Architected Framework
### General Definitions
### On Architecture
   On-Premise Enterprise (Centralized team) vs AWS (Distributed teams) 
### Amazon Leadership Principles
### General Design Principles
   Stop guessing your capacity needs
   Test systmes at production scale
   Automate to make architectural experimentation easier
   Allow for evolutionary architectures
   Drive architectures using data
   Improve through game days
### Anatomy of a Pillar
   Dedihgn Principles
   Definition
   BEst Practices
   Resources
### Operational Excellence
   Perform operations as code
   Make frequent, small, recersible changes
   Refine operartions procedures frequently
   Anticipate failure
   Learn from all operational failures
### Security
   Implement a strong identity foundation
   Enable traceability
   Apply security at all layers
   Automate security best practices
   Protect data in transit and at rest
   Keep people away from data
   Prepare for security events
### Reliability
   Automatically recover from failure
   Test recovery procedures
   Scale horizontally to invrease aggreagate system availability
   Stop guessing capacity
   Manage change in automation
### Performance Efficiency
   Democratize advanced technologies
   Go global in minutes
   Use serverless architectures
   Experiment more often
   Consider mechanical sympathy
### Cost Optimisation
   Implement Cloud Financial Management
   Adopt a consumption model
   Measure overall efficiency
   Stop spendinm money on undifferentiated heavy lifting
   Analyze and attribute expenditure 
### AWS Well-Architected-Tool	
### AWS Architecture Center

## TCO and Migration
### Total Cost of Ownership
### CAPEX vs OPEX
### Shifting-IT Personnel
### AWS Pricing Calculator
### Migration Evaluator
### VM Import Export
### Database Migration Service
### Cloud Adoption Framework

##  Billing and Pricing
### AWS Free Services
   IAM
   Amazon VPC
   Auto Scaling
   *CloudFormation*
   Elastic Beanstalk
   ...
### AWS Support Plans (IMPORTANT)
   Basic
   Developer
   Business 
   Enterprise
### TAM - Techinical Account Manager
### AWS Marketplace
### Consolidated Billing
### Consolidated Billing - Volume Discounts
### AWS Trusted Advisor
### SLAs
   SLA, SLI and SLO
### Service Health Dashboard
### AWS Personal Health Dashboard
### AWS Abuse
### AWS Free Tier
### AWS Credits
### AWS Partner Network
### AWS Budgets
### AWS Budget Reports
### AWS Cost & Usage Reports
### Cost Allocation Tags
### Billing Alarms
### AWS Cost Explorer
### Programmatiic Pricing APIs
