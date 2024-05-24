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

>Understanding these application integration services helps you design robust, scalable, and efficient architectures that facilitate seamless communication between different parts of your applications.


## Containers

### VMs vs Containers
Virtual Machines (VMs) run entire operating systems along with applications on top of a hypervisor, providing complete isolation but with higher overhead. Containers share the host OS kernel and run isolated processes, offering lightweight and efficient resource usage.

### Microservices
Microservices is an architectural style that structures an application as a collection of small, autonomous services modeled around a business domain. Each service runs in its own process and communicates with other services via HTTP APIs or messaging.

### Kubernetes
Kubernetes is an open-source system for automating deployment, scaling, and management of containerized applications. It groups containers into logical units for easy management and discovery.

### Docker
Docker is a platform that uses OS-level virtualization to deliver software in packages called containers. Containers bundle an application with all its dependencies, ensuring consistency across multiple environments.

### Podman, Buildah, and Skopeo
- **Podman**: A daemonless container engine for developing, managing, and running OCI containers on Linux.
- **Buildah**: A tool that facilitates building Open Container Initiative (OCI) container images.
- **Skopeo**: A command-line utility that performs various operations on container images and image repositories.

### Container Services

#### Primary Services
- **ECS (Elastic Container Service)**: A fully managed container orchestration service that supports Docker containers.
- **AWS Fargate**: A serverless compute engine for containers that works with ECS and EKS, removing the need to manage servers.
- **EKS (Elastic Kubernetes Service)**: A managed service that makes it easy to run Kubernetes on AWS.
- **AWS Lambda**: Serverless compute service that runs your code in response to events, managing the compute resources required automatically.

#### Provisioning and Deployment
- **Elastic Beanstalk (EB)**: An easy-to-use service for deploying and scaling web applications and services, automatically handling capacity provisioning, load balancing, and scaling.
- **App Runner**: A fully managed service that makes it easy to quickly deploy containerized web applications and APIs.
- **AWS Copilot CLI**: A command-line tool that simplifies building, releasing, and operating production-ready containerized applications on Amazon ECS and AWS Fargate.

#### Supporting Services
- **ECR (Elastic Container Registry)**: A fully managed Docker container registry that makes it easy to store, manage, and deploy container images.
- **X-Ray**: A service that helps with debugging and analyzing the performance of distributed applications, including those using containers.
- **Step Functions**: A serverless orchestration service that lets you coordinate multiple AWS services into serverless workflows.

Understanding these container services and tools helps you effectively manage, deploy, and scale containerized applications in the AWS cloud.


## Governance

### Organizations & Accounts
AWS provides a range of tools and services to help manage and govern your AWS environment effectively.

#### AWS Organizations
AWS Organizations allows you to centrally manage and govern multiple AWS accounts, enabling you to automate account creation, apply policies, and manage billing.

#### Root Account User
The Root Account User is the primary account holder and has complete access to all AWS services and resources. It is recommended to use this account sparingly and to enable Multi-Factor Authentication (MFA).

#### Organization Units
Organization Units (OUs) are logical groupings of AWS accounts within an organization that allow you to apply policies and manage accounts collectively.

#### Service Control Policies (SCPs)
Service Control Policies (SCPs) are a type of organization policy that you can use to manage permissions in your organization. SCPs help ensure that your accounts stay within your organization's access control guidelines.

### AWS Control Tower
AWS Control Tower offers a simple way to set up and govern a new, secure, multi-account AWS environment based on AWS best practices.

#### Landing Zone

A Landing Zone is a well-architected, multi-account AWS environment that is scalable and secure. AWS Control Tower automates the setup of your Landing Zone.

#### Account Factory

Account Factory is a feature in AWS Control Tower that provides a standardized method to provision new AWS accounts based on your organization's best practices and guardrails.

#### Guardrails

Guardrails are pre-configured governance rules for security, compliance, and operations that AWS Control Tower applies to your AWS environment.

### AWS Config

AWS Config is a service that enables you to assess, audit, and evaluate the configurations of your AWS resources. It continuously monitors and records your AWS resource configurations and allows automated compliance checks.

### AWS Quick Starts

AWS Quick Starts are automated reference deployments built by AWS solutions architects and AWS partners. They help you deploy popular technologies on AWS following best practices.

### Tagging

Tagging allows you to categorize AWS resources in different ways, such as by purpose, owner, or environment. Tags are key-value pairs that you can use to manage, identify, and organize resources.

### Resource Groups

Resource Groups enable you to manage and automate tasks on large numbers of AWS resources at once. They can be used to group resources that share one or more tags.

### Business Centric Services

AWS provides various services tailored to business needs, improving productivity and communication.

- **Amazon Connect**: A cloud-based contact center service that makes it easy to set up and manage a customer contact center.
- **WorkSpaces**: A fully managed, secure Desktop-as-a-Service (DaaS) solution to provision desktops for users.
- **WorkDocs**: A secure enterprise document storage and sharing service.
- **Chime**: A communications service that allows you to meet, chat, and place business calls inside and outside your organization.
- **WorkMail**: A secure, managed business email and calendar service.
- **Pinpoint**: A flexible and scalable outbound and inbound marketing communications service. *
- **Simple Email Service (SES)**: A cloud-based email sending service designed to help digital marketers and application developers send marketing, notification, and transactional emails. *
- **QuickSight**: A business analytics service that makes it easy to deliver insights to everyone in your organization. *

Understanding these governance and business-centric services helps you manage and optimize your AWS environment effectively while enhancing productivity and compliance.








## Provisioning

AWS offers a variety of services to help you provision and manage your cloud infrastructure efficiently.

### Provisioning Services

#### Elastic Beanstalk (EB)

AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services. It automatically handles the deployment, from capacity provisioning, load balancing, and auto-scaling to application health monitoring.

#### OpsWorks

AWS OpsWorks is a configuration management service that provides managed instances of Chef and Puppet. It helps you automate how servers are configured, deployed, and managed across your EC2 instances or on-premises compute environments.

#### CloudFormation

AWS CloudFormation provides a common language for you to describe and provision all the infrastructure resources in your cloud environment. It allows you to use a simple text file to model and provision all the resources needed for your applications across all regions and accounts.

#### QuickStarts

AWS QuickStarts are automated reference deployments that help you rapidly deploy fully functional and scalable IT solutions and environments on the AWS Cloud, following AWS best practices.

#### AWS Marketplace

AWS Marketplace is a digital catalog that lists software and services you can buy and deploy to your AWS environment. It simplifies software procurement and deployment for popular software solutions.

#### Amplify

AWS Amplify is a set of tools and services that enables front-end web and mobile developers to build scalable full-stack applications, powered by AWS. It includes a development framework and managed services.

#### App Runner

AWS App Runner is a fully managed service that makes it easy for developers to quickly deploy containerized web applications and APIs at scale, without managing the underlying infrastructure.

#### Copilot

AWS Copilot CLI is a command-line tool that simplifies building, releasing, and operating production-ready containerized applications on Amazon ECS and AWS Fargate.

#### CodeStar

AWS CodeStar enables you to quickly develop, build, and deploy applications on AWS. It provides a unified user interface, enabling you to manage your software development activities in one place.

#### CDK (Cloud Development Kit)

AWS Cloud Development Kit (CDK) is an open-source software development framework to define your cloud application resources using familiar programming languages. It allows you to model and provision cloud infrastructure using code.

### AWS Elastic Beanstalk

AWS Elastic Beanstalk is a platform as a service (PaaS) that simplifies the deployment and management of applications in the AWS Cloud. With Elastic Beanstalk, you can quickly deploy, manage, and scale applications without worrying about the underlying infrastructure.

- **Deployment**: Supports multiple deployment options and allows rolling updates to minimize downtime.
- **Management**: Automatically manages the infrastructure, scaling, and load balancing.
- **Monitoring**: Provides health monitoring and detailed metrics to ensure your application runs smoothly.
- **Customization**: Allows customization of the environment and integration with other AWS services.

Understanding these provisioning services helps you automate and streamline your deployment processes, ensuring efficient and scalable application management on AWS.

	
## Serverless

### Serverless Services

- **DynamoDB**: A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability.
- **S3**: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.
- **ECS Fargate**: A serverless compute engine for containers that works with Amazon ECS, allowing you to run containers without managing servers.
- **AWS Lambda**: A compute service that lets you run code without provisioning or managing servers, automatically scaling based on the number of requests.
- **Step Functions**: A serverless orchestration service that lets you coordinate multiple AWS services into serverless workflows.
- **Aurora Serverless**: An on-demand, auto-scaling configuration for Amazon Aurora, automatically adjusting database capacity based on application demand.

### What is Serverless

Serverless computing allows you to build and run applications and services without thinking about servers. It provides:

- **Highly elastic and scalable**: Automatically adjusts resources to meet the demands of your applications.
- **Available and durable**: Ensures high availability and fault tolerance by default.
- **Secure by default**: Incorporates AWS's built-in security features, simplifying the protection of your data and applications.
- **Scale-to-Zero**: Automatically scales down to zero when not in use, reducing costs.
- **Pay-for-Value**: Charges you only for the compute time you consume, resulting in cost savings.

## Windows on AWS

### AWS License Manager

AWS License Manager simplifies the management of software licenses from vendors such as Microsoft, helping you manage licenses efficiently and remain compliant.

- **BYOL (Bring Your Own License)**: Allows you to use your existing software licenses on AWS, leveraging your current investments while benefiting from the scalability and flexibility of the cloud.

Understanding serverless services and managing Windows licenses on AWS helps you leverage cloud resources efficiently, ensuring cost-effective and scalable application deployment.




## Logging

AWS provides several services to monitor and log the activities and performance of your AWS resources, ensuring operational health and compliance.

### AWS CloudTrail

AWS CloudTrail enables governance, compliance, and operational and risk auditing of your AWS account. It logs API calls and other actions taken by users, roles, or AWS services, providing detailed event history.

### CloudWatch

Amazon CloudWatch monitors your AWS resources and applications in real-time, collecting and tracking metrics, collecting and monitoring log files, and setting alarms.

### AWS X-Ray

AWS X-Ray helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture. It provides an end-to-end view of requests as they travel through your application.

### AWS CloudTrail

AWS CloudTrail logs all API calls made on your account, enabling you to track changes, troubleshoot issues, and ensure compliance with security and operational practices. It records information such as the identity of the API caller, the time of the API call, the source IP address, and the request parameters.

### CloudWatch Alarm

CloudWatch Alarms monitor CloudWatch metrics and send notifications or automatically make changes to the resources you are monitoring based on rules you define. This helps ensure your applications run smoothly and meet performance targets.

### Anatomy of an Alarm

A CloudWatch Alarm consists of:

- **Metric**: The data point being monitored (e.g., CPU utilization).
- **Threshold**: The value that triggers the alarm (e.g., CPU usage exceeds 80%).
- **Period**: The length of time over which the metric is evaluated.
- **Evaluation Periods**: The number of periods over which data is compared to the specified threshold.
- **Actions**: The response triggered by the alarm, such as sending notifications or auto-scaling actions.

### Log Events

Log events in CloudWatch Logs represent discrete entries that describe a specific occurrence, such as an error message or a transaction record, within an application or system.

### Log Insights

CloudWatch Logs Insights is an interactive query service that helps you analyze and visualize log data. It enables you to quickly gain insights from your logs to troubleshoot operational problems or conduct security analysis.

### CloudWatch Metrics

CloudWatch Metrics are fundamental data points about the performance of your systems and applications, automatically collected from various AWS services and custom sources. Metrics can be used to set alarms, generate reports, and monitor application health and performance.

Understanding these logging services and their components helps you maintain operational health, ensure compliance, and optimize the performance of your AWS resources.


## ML, AI, and Big Data

### Intro to ML & AI

Machine Learning (ML) and Artificial Intelligence (AI) involve using algorithms and statistical models to enable computers to perform tasks without explicit instructions. ML focuses on developing systems that can learn and improve from experience, while AI aims to create systems capable of performing tasks that typically require human intelligence.

### AI & ML Services

AWS provides a suite of AI and ML services that enable developers to build, train, and deploy machine learning models quickly and efficiently. These services are designed to help you create intelligent applications that can analyze data, recognize patterns, and make predictions.

### Big Data & Analytics Services

AWS offers a range of Big Data and Analytics services to help you process and analyze large volumes of data. These services provide the tools needed to collect, store, process, and visualize data, enabling you to gain valuable insights and make data-driven decisions.

### Amazon QuickSight

Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud. It allows you to create and publish interactive dashboards that include ML insights.

### ML & AI Services - Extended

- **Amazon Bedrock**: A fully managed service for building, training, and deploying ML models at scale.
- **Amazon CodeWhisperer**: An AI-powered code companion that helps developers write code faster by providing code recommendations based on the context of the code being written.

### Generative AI

Generative AI refers to a category of AI algorithms that generate new data based on existing data. This includes applications like text generation, image creation, and music composition.

### ML & DL Frameworks and Tools

AWS supports various machine learning (ML) and deep learning (DL) frameworks and tools to help you build and deploy your models.

- **Apache MXNet**: An open-source deep learning framework that allows you to define, train, and deploy deep neural networks.
- **PyTorch**: An open-source machine learning library based on the Torch library, used for applications such as computer vision and natural language processing.
- **TensorFlow + Keras**: An end-to-end open-source platform for machine learning, including Keras, a high-level neural networks API written in Python.
- **Apache Spark + SparkML**: A unified analytics engine for big data processing, with built-in modules for streaming, SQL, machine learning, and graph processing.
- **Chainer**: A flexible and intuitive deep learning framework, designed for researchers and developers.
- **Hugging Face**: An open-source library that provides tools for natural language processing, including pre-trained models and tokenizers.

### Apache MXNet

Apache MXNet is an open-source deep learning framework designed to train and deploy deep neural networks at scale. It supports both symbolic and imperative programming, making it flexible and efficient for a wide range of deep learning applications.

### Intel

### x86 & ARM

Intel provides processors based on different architectures:

- **x86**: A family of instruction set architectures based on the Intel 8086 CPU. Widely used in desktops, laptops, and servers.
- **ARM**: A family of reduced instruction set computing (RISC) architectures. Known for energy efficiency, widely used in mobile devices, embedded systems, and increasingly in cloud environments.

### Intel Xeon Scalable & Intel Gaudi

- **Intel Xeon Scalable**: A line of high-performance processors designed for data centers, supporting a wide range of workloads from AI and analytics to cloud and networking.
- **Intel Gaudi**: AI training processors designed to deliver high performance and efficiency for deep learning workloads.

### GPU

Graphics Processing Units (GPUs) are specialized processors designed to accelerate the rendering of images and video. In ML and AI, GPUs are used to accelerate the training and inference of deep learning models, significantly reducing the time required to process large datasets.

### CUDA

CUDA (Compute Unified Device Architecture) is a parallel computing platform and application programming interface (API) model created by NVIDIA. It allows developers to use NVIDIA GPUs for general purpose processing, enabling significant performance improvements in compute-intensive tasks such as deep learning and scientific computing.

Understanding these services and tools helps you leverage AWS's capabilities to build, deploy, and scale ML and AI applications, and process and analyze big data efficiently.





## AWS Well-Architected Framework

### General Definitions

The AWS Well-Architected Framework helps cloud architects build secure, high-performing, resilient, and efficient infrastructure for their applications. It provides a consistent approach to evaluate architectures and implement scalable designs.

### On Architecture

- **On-Premise Enterprise (Centralized team)**: Traditionally, on-premise architectures are managed by centralized teams responsible for all aspects of the IT infrastructure.
- **AWS (Distributed teams)**: In the AWS environment, architecture responsibilities are distributed across teams, promoting agility and innovation.

### Amazon Leadership Principles

Amazon's Leadership Principles guide the culture and decision-making process within the organization, emphasizing customer obsession, ownership, inventiveness, and long-term thinking.

### General Design Principles

- **Stop guessing your capacity needs**: Automatically scale capacity up or down as needed.
- **Test systems at production scale**: Perform testing in production environments to understand system behavior.
- **Automate to make architectural experimentation easier**: Use automation to speed up experimentation and innovation.
- **Allow for evolutionary architectures**: Design systems that can evolve over time.
- **Drive architectures using data**: Make informed decisions based on data analysis.
- **Improve through game days**: Simulate real-world scenarios to test and improve system reliability and performance.

### Anatomy of a Pillar

Each pillar of the Well-Architected Framework includes:

- **Design Principles**: Guidelines to improve your architecture.
- **Definition**: Explanation of the pillar's scope.
- **Best Practices**: Recommendations for achieving the pillar's goals.
- **Resources**: Additional materials and tools to help implement best practices.

### Operational Excellence

- **Perform operations as code**: Define operations procedures as code to standardize and automate tasks.
- **Make frequent, small, reversible changes**: Reduce risk and improve agility by deploying small changes frequently.
- **Refine operations procedures frequently**: Continuously improve procedures to adapt to evolving needs.
- **Anticipate failure**: Design systems that anticipate and tolerate failures.
- **Learn from all operational failures**: Use failures as learning opportunities to improve system resilience.

### Security

- **Implement a strong identity foundation**: Use AWS IAM to manage user access securely.
- **Enable traceability**: Monitor and log all actions to maintain visibility and control.
- **Apply security at all layers**: Implement security measures across all layers of your architecture.
- **Automate security best practices**: Use automation to enforce security policies consistently.
- **Protect data in transit and at rest**: Encrypt data to protect it from unauthorized access.
- **Keep people away from data**: Minimize direct access to data by using automated tools.
- **Prepare for security events**: Develop incident response plans and practice them regularly.

### Reliability

- **Automatically recover from failure**: Implement mechanisms to detect and recover from failures.
- **Test recovery procedures**: Regularly test your recovery processes to ensure they work as expected.
- **Scale horizontally to increase aggregate system availability**: Distribute workloads across multiple resources to improve availability.
- **Stop guessing capacity**: Use auto-scaling to match capacity with demand.
- **Manage change with automation**: Use automated tools to manage and deploy changes.

### Performance Efficiency

- **Democratize advanced technologies**: Make advanced technologies accessible to all teams.
- **Go global in minutes**: Use AWS global infrastructure to deploy applications quickly around the world.
- **Use serverless architectures**: Leverage serverless computing to build scalable and cost-effective applications.
- **Experiment more often**: Encourage innovation through rapid experimentation.
- **Consider mechanical sympathy**: Understand how your workload interacts with the underlying infrastructure.

### Cost Optimization

- **Implement Cloud Financial Management**: Manage and optimize cloud spending.
- **Adopt a consumption model**: Pay only for the resources you use.
- **Measure overall efficiency**: Continuously monitor and improve resource usage.
- **Stop spending money on undifferentiated heavy lifting**: Focus on tasks that add value to your business.
- **Analyze and attribute expenditure**: Track and allocate costs to understand spending patterns.

### AWS Well-Architected Tool

The AWS Well-Architected Tool helps you review and improve your cloud architectures. It provides insights and recommendations based on the Well-Architected Framework.

### AWS Architecture Center

The AWS Architecture Center provides best practices, reference architectures, and blueprints to help you design and build your cloud applications.


## TCO and Migration

### Total Cost of Ownership (TCO)

Total Cost of Ownership (TCO) evaluates the cost of owning an IT infrastructure over its lifecycle, including hardware, software, maintenance, and labor. AWS provides tools to compare the cost of on-premises infrastructure with AWS cloud solutions, helping organizations understand potential savings.

### CAPEX vs OPEX

- **CAPEX (Capital Expenditure)**: Upfront costs for physical infrastructure, including hardware, software licenses, and installation. These are fixed, long-term investments.
- **OPEX (Operational Expenditure)**: Ongoing costs for running and maintaining infrastructure, including utility bills, maintenance, and subscription services. AWS enables a shift from CAPEX to OPEX by offering pay-as-you-go pricing models.

### Shifting IT Personnel

Migrating to the cloud allows organizations to shift IT personnel from maintenance tasks to more strategic roles, such as developing new applications and optimizing existing ones. This enhances productivity and innovation.

### AWS Pricing Calculator

The AWS Pricing Calculator helps you estimate the cost of AWS services for your specific use cases. It provides a detailed cost breakdown, allowing you to plan your budget effectively and compare costs with on-premises solutions.

### Migration Evaluator

Migration Evaluator (formerly TSO Logic) provides a data-driven assessment to build a business case for AWS cloud migration. It analyzes your on-premises infrastructure and calculates the potential savings and benefits of moving to AWS.

### VM Import/Export

VM Import/Export enables you to import virtual machine images from your existing environment to AWS and export them back to your on-premises environment. This facilitates seamless migration of workloads to and from the AWS cloud.

### Database Migration Service

AWS Database Migration Service (DMS) helps you migrate databases to AWS quickly and securely. The source database remains fully operational during the migration, minimizing downtime. DMS supports homogeneous migrations (e.g., Oracle to Oracle) and heterogeneous migrations (e.g., Oracle to Amazon Aurora).

### Cloud Adoption Framework

The AWS Cloud Adoption Framework (CAF) provides guidance and best practices to help organizations achieve successful cloud adoption. It outlines the necessary steps and strategies across six perspectives: Business, People, Governance, Platform, Security, and Operations.

Understanding TCO and migration services helps organizations plan and execute their move to the cloud efficiently, optimizing costs and enhancing their IT capabilities.





## Billing and Pricing

### AWS Free Services

AWS offers several services that are free to use, helping you manage and operate your AWS environment without incurring additional costs.

- **IAM (Identity and Access Management)**: Securely control access to AWS services and resources.
- **Amazon VPC (Virtual Private Cloud)**: Provision a logically isolated network within the AWS cloud.
- **Auto Scaling**: Automatically adjust the number of EC2 instances based on demand.
- **CloudFormation**: Create and manage AWS resources using templates.
- **Elastic Beanstalk**: Deploy and manage applications without worrying about the infrastructure.

### AWS Support Plans (IMPORTANT)

AWS offers multiple support plans to meet different needs:

- **Basic**: Free access to account and billing support, and access to AWS community forums.
- **Developer**: Basic support plus business hours access to Cloud Support Associates for technical support and guidance.
- **Business**: 24/7 access to Cloud Support Engineers, access to AWS Trusted Advisor, and more.
- **Enterprise**: All Business support features plus a Technical Account Manager (TAM), concierge support team, and more.

### TAM - Technical Account Manager

A Technical Account Manager (TAM) provides proactive guidance and advocacy, helping you design, architect, and optimize your AWS environment.

### AWS Marketplace

AWS Marketplace is a digital catalog with thousands of software listings from independent software vendors that make it easy to find, test, buy, and deploy software that runs on AWS.

### Consolidated Billing

Consolidated Billing allows you to combine multiple AWS accounts into a single billing entity, simplifying payment and tracking.

### Consolidated Billing - Volume Discounts

Consolidated Billing can help you achieve volume discounts by pooling usage across all accounts in the organization, maximizing savings.

### AWS Trusted Advisor

AWS Trusted Advisor provides real-time guidance to help you provision your resources following AWS best practices. It covers cost optimization, performance, security, fault tolerance, and service limits.

### SLAs

Service Level Agreements (SLAs) define the service commitments and guarantees provided by AWS:

- **SLA (Service Level Agreement)**: The overall agreement defining the service level.
- **SLI (Service Level Indicator)**: A specific metric used to measure service performance.
- **SLO (Service Level Objective)**: The target value or range for a service level indicator.

### Service Health Dashboard

The AWS Service Health Dashboard provides a comprehensive view of the health of AWS services across all regions, informing you of outages and disruptions.

### AWS Personal Health Dashboard

The AWS Personal Health Dashboard provides alerts and remediation guidance when AWS experiences events that may impact your AWS resources.

### AWS Abuse

AWS Abuse addresses issues related to the abusive use of AWS services, such as spam, port scanning, and denial of service (DoS) attacks.

### AWS Free Tier

The AWS Free Tier offers limited usage of AWS services for free, allowing you to explore and experiment with AWS services without incurring costs.

### AWS Credits

AWS Credits can be used to offset your AWS bill, making it more affordable to experiment with and use AWS services. Credits are often awarded through promotional programs, training, and events.

### AWS Partner Network

The AWS Partner Network (APN) is a global community of partners that leverages AWS to build solutions and services for customers. APN partners receive business, technical, marketing, and go-to-market support.

### AWS Budgets

AWS Budgets allows you to set custom cost and usage budgets and receive alerts when your usage exceeds your thresholds.

### AWS Budget Reports

AWS Budget Reports provide detailed insights into your cost and usage data, helping you track and manage your spending effectively.

### AWS Cost & Usage Reports

AWS Cost & Usage Reports offer the most comprehensive set of cost and usage data available, enabling you to analyze your spending in detail.

### Cost Allocation Tags

Cost Allocation Tags allow you to categorize and track your AWS costs by assigning tags to resources, making it easier to manage and allocate costs.

### Billing Alarms

Billing Alarms in Amazon CloudWatch alert you when your estimated charges exceed your predefined threshold, helping you manage and control your spending.

### AWS Cost Explorer

AWS Cost Explorer provides an easy-to-use interface to visualize, understand, and manage your AWS costs and usage over time.

### Programmatic Pricing APIs

AWS provides programmatic access to pricing information through APIs, allowing you to integrate cost management and optimization into your applications and workflows.

Understanding these billing and pricing tools helps you manage your AWS costs effectively, ensuring that you stay within budget and optimize your spending.



## Security

### Defense-In-Depth

Defense-in-Depth is a multi-layered security strategy that involves implementing multiple levels of security controls throughout an IT system. This approach ensures that if one layer fails, additional layers will continue to protect the system.

#### 7 Layers of Security

AWS employs a comprehensive, multi-layered approach to security, often referred to as the "7 layers of security." Each layer addresses specific aspects of security to protect your data and applications.

1. **Data**

   Data security involves protecting the integrity, confidentiality, and availability of data both at rest and in transit. Techniques include encryption, access controls, and data masking.

2. **Applications**

   Application security focuses on ensuring that applications are secure against threats. This includes practices such as secure coding, regular application security assessments, and using application-level firewalls.

3. **VM / Compute**

   Virtual Machine (VM) and Compute security involves securing the virtual machines and compute resources used to run applications. This includes using hardened OS images, applying security patches, and implementing proper identity and access management for compute resources.

4. **Networking**

   Network security encompasses measures to protect data during transmission and to secure network infrastructure. Techniques include the use of virtual private clouds (VPCs), subnets, routing controls, network access control lists (NACLs), and security groups.

5. **Perimeter**

   Perimeter security focuses on protecting the network perimeter through firewalls, intrusion detection systems (IDS), intrusion prevention systems (IPS), and DDoS protection services like AWS Shield.

6. **Policies & Access**

   Policies and access management involve defining and enforcing access policies to ensure that only authorized users and services can access resources. AWS Identity and Access Management (IAM), multi-factor authentication (MFA), and service control policies (SCPs) are key components.

7. **Physical Security**

   Physical security pertains to the protection of the physical infrastructure of data centers. AWS implements strict physical security measures, including controlled access, surveillance, and secure disposal of hardware, to safeguard against unauthorized physical access.


### CIA Triad

The CIA Triad is a fundamental concept in information security, focusing on three key principles:

- **Confidentiality**: Ensuring that information is accessible only to those authorized to access it.
- **Integrity**: Maintaining the accuracy and completeness of data.
- **Availability**: Ensuring that information and resources are available to authorized users when needed.

### Vulnerabilities

Vulnerabilities are weaknesses in a system that can be exploited by threats to gain unauthorized access to resources. Identifying and mitigating vulnerabilities is critical to maintaining a secure environment.

### Encryption

Encryption is the process of converting data into a coded form to prevent unauthorized access. AWS provides various encryption services to protect data at rest and in transit.

### Cyphers

Cyphers are algorithms used to perform encryption and decryption. Common cyphers include AES (Advanced Encryption Standard) and RSA (Rivest-Shamir-Adleman).

### Cryptographic Keys

Cryptographic keys are used in encryption and decryption processes. They come in two types: symmetric (same key for encryption and decryption) and asymmetric (different keys for encryption and decryption).

### Hashing & Salting

- **Hashing**: The process of converting data into a fixed-size string of characters, which is typically a hash code. Hashing is used for data integrity checks.
- **Salting**: Adding random data to a hash input to ensure that even identical inputs produce different hash outputs, enhancing security.

### Digital Signatures & Signing

Digital signatures use cryptographic techniques to verify the authenticity and integrity of a message, software, or digital document. They ensure that the message has not been altered and confirm the sender's identity.

### In-Transit vs At-Rest Encryption

- **In-Transit Encryption**: Protects data as it moves between systems or over networks.
   - Transport Layer Security (TLS)
   - Secure Sockets Layers (SSL)
- **At-Rest Encryption**: Protects data stored on disks or other media.

### Compliance Programs

AWS compliance programs help customers meet regulatory and compliance requirements. AWS provides certifications and attestations for various standards, such as:
   - General Data Protection Regulation (GDPR)
   - International Organization for Standardization (ISO / International Electrotechnical Commission)
   - System and Organization Controls (SOC)
   - Payment Card INdustry Data Security Standard (PCI DSS)
   - Federal Information Processing Standard (FIPS) 140-2

### Pen Testing

Penetration Testing (Pen Testing) involves simulating cyber attacks on your system to identify and fix security vulnerabilities. AWS allows customers to perform Pen Testing on their AWS environments.

### AWS Artifact

AWS Artifact is a portal that provides on-demand access to AWS's security and compliance reports, such as SOC, PCI, and ISO certifications.

### AWS Inspector
Hardening refers to the process of securing a system by reducing its surface of vulnerability. Hardening is common for Virtual Machines where you run a collection of security checks known as a security benchmark

AWS Inspector is an automated security assessment service that runs a security benchmark against specific EC2 instances. It can perform *Network* and *Host* Assesments.

### DDoS

Distributed Denial of Service (DDoS) attacks aim to disrupt the normal traffic of a targeted server, service, or network by overwhelming it with a flood of internet traffic.

### AWS Shield

AWS Shield is a managed DDoS protection service that safeguards web applications running on AWS. It comes in two tiers: Standard (free) and Advanced (paid). 

Both plans integrate with AWS Web Application Fireqall (WAF)

### AWS GuardDuty

AWS GuardDuty is a *threat detection service* that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts and workloads. It uses ML to analyze CloudTrail Logs, VPC Flow Logs and DNS Logs.

### Amazon Macie

Amazon Macie is a fully managed data security and data privacy service that uses machine learning and pattern matching to discover, monitor *S3 data access* activity, and protect sensitive data in AWS. Macie works by using ML to analyze CloudTrail Logs.

### AWS VPN

AWS VPN enables a *secure* and **private tunnel** between your on-premises networks and your AWS environments through IPsec VPN connections.

**Internet Protocol Security (IPSec)** is a secure network protocol suit that authenticates and encrypts the packets of data to provide secure encrypted communication between two computers over and IP network. Used in virtual private networks (VPNs).

### AWS WAF (Web Application Firewall)

AWS WAF is a web application firewall that helps protect your web applications from common web exploits and vulnerabilities by allowing you to control the traffic that reaches your applications.
WAF can be attached to either **CloudFront** or and **Application Load Balancer (ALB)**. Protect applications from attackes covered in the *OWASP Top 10* most dangerous attacks.

### Hardware Security Module (HSM)

AWS CloudHSM provides managed hardware security modules that enable you to generate and use your own encryption keys on the AWS Cloud, complying with stringent security standards.

### AWS KMS (Key Management Service)

AWS KMS is a managed service that enables you to create and control the encryption keys used to encrypt your data, integrating with various AWS services for seamless encryption.

### CloudHSM

AWS CloudHSM is a cloud-based hardware security module (HSM) that allows you to manage your encryption keys using FIPS 140-2 Level 3 validated HSMs, providing high levels of security for cryptographic operations.

Understanding these security services and concepts helps you build a secure, compliant, and resilient AWS environment.


## Variation Study

### Know Your Initialisms

Understanding the various initialisms used in AWS services is crucial for distinguishing between them and knowing their specific functionalities.

| Initialism | Meaning                            | Initialism | Meaning                      | Initialism | Meaning                            |
|------------|------------------------------------|------------|------------------------------|------------|------------------------------------|
| IAM        | Identity and Access Management     | MQ         | Message Queue                | EBS        | Elastic Block Store                |
| S3         | Simple Storage Service             | ASG        | Auto Scaling Group           | EFS        | Elastic File System                |
| SWF        | Simple Workflow Service            | TAM        | Technical Account Manager    | EMR        | Elastic MapReduce                  |
| SNS        | Simple Notification Service        | ELB        | Elastic Load Balancer        | EB         | Elastic Beanstalk                  |
| SQS        | Simple Queue Service               | ALB        | Application Load Balancer    | ES         | Elasticsearch Service              |
| SES        | Simple Email Service               | NLB        | Network Load Balancer        | EKS        | Elastic Kubernetes Service         |
| SSM        | Systems Manager                    | GWLB       | Gateway Load Balancer        | MSK        | Managed Streaming for Kafka        |
| RDS        | Relational Database Service        | CLB        | Classic Load Balancer        | RAM        | Resource Access Manager            |
| VPC        | Virtual Private Cloud              | EC2        | Elastic Compute Cloud        | ACM        | AWS Certificate Manager            |
| CPN        | CloudFront                         | EC5        | Elastic Container Service    | PoLP       | Principle of Least Privilege       |
| CFN        | CloudFormation                     | ECR        | Elastic Container Registry   | IoT        | Internet of Things                 |
| WAF        | Web Application Firewall           |            |                              | RI         | Reserved Instance                  |

### AWS Config vs AWS AppConfig

- **AWS Config**: A service that enables you to assess, audit, and evaluate the configurations of your AWS resources. It continuously monitors and records AWS resource configurations and allows automated compliance checks.
- **AWS AppConfig**: A service used to quickly deploy application configurations, allowing you to manage and deploy application configuration changes in a controlled and monitored way.

### SNS vs SQS

- **SNS (Simple Notification Service)**: A fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. It uses a publish/subscribe model to send messages to multiple subscribers. Generally used for sending **plain text emails**.
- **SQS (Simple Queue Service)**: A fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications. It uses a queuing model to send messages between distributed application components.

### SNS vs SES vs PinPoint vs Workmail

- **SNS (Simple Notification Service)**: Used for sending notifications, i.e. *Practical and Internal Emails*, to multiple subscribers via various protocols such as SMS, SQS, email, and HTTP/S. Generally used for sending **plain text emails**. Best example is billing alarms. 
Need to what are **Topics** and **Subcriptions**!
- **SES (Simple Email Service)**: A cloud-based email sending service designed for sending marketing, notification, and *Transactional Emails*, e.g. Signup. Reset Password, Invoices...
SES sends **html emails, , SNS cannot.
- **PinPoint**: A flexible and scalable outbound and inbound marketing communications service used for *Promotional Emails*. It enables targeted messaging across multiple channels including email, SMS, and push notifications.
- **WorkMail**: A secure, managed business email and calendar service. *Email Web Client* similar to Gmail and Outlook.

### Amazon Inspector vs AWS Trusted Advisor

- **Amazon Inspector**: An automated security assessment service that helps improve the security and compliance of applications deployed on AWS. It identifies vulnerabilities and deviations from best practices. Audits **a single EC2 instance** that you've selected.
- **AWS Trusted Advisor**: **Doesn't generate out a PDF** report. Gives a **holistic view** of recommendations accorss multiple services and best practices.

### Connect Named Services

Understanding AWS services with "Connect" in their name helps differentiate their purposes:

- **Amazon Connect**: A cloud-based contact center service that makes it easy to set up and manage a customer contact center.
- **Direct Connect**: A network service that provides a dedicated network connection from your premises to AWS, improving performance and security for data transfer.
- **Media Connect**: A service for transporting live video securely and reliably, allowing you to build mission-critical live video workflows with scalable, real-time video transport capabilities.


### Elastic Transcoder vs MediaConvert

- **Elastic Transcoder**: *The Old Way*. A cloud-based media transcoding service designed to convert media files from their source format into versions that will play back on devices like smartphones, tablets, and PCs.
- **AWS Elemental MediaConvert**: *The New Way*. A file-based video transcoding service with broadcast-grade features, designed for large-scale video processing workflows. *More robust* service that can perform various operations during transcoding.

### AWS Artifact vs Amazon Inspector

- **AWS Artifact**: Why should an enterprise trust AWS?
Generates a security report that's based on **global compliance frameworks**, such as SOC, PCI, and ISO certifications.
- **Amazon Inspector**: How do we know this EC2 instance is secure? Prove it?
An automated security assessment service that helps improve the security and compliance of applications deployed on AWS by identifying vulnerabilities and deviations from best practices.

### ELB Variants

Understanding the different types of Elastic Load Balancers (ELBs) helps you choose the right one for your use case:

- **ELB (Elastic Load Balancer)**: A general term for load balancing services provided by AWS.
   - **ALB (Application Load Balancer)**: Best suited for load balancing HTTP and HTTPS traffic, operating at the application layer (OSI model layer 7). Can attach WAF.
   - **NLB (Network Load Balancer)**: Best suited for load balancing TCP, UDP, and TLS traffic, operating at the transport layer (OSI model layer 4), capable of handling millions of requests per second while maintaining ultra-low latencies.
   - **GWLB (Gateway Load Balancer)**: A transparent network gateway that can deploy, scale, and manage third-party virtual appliances, operating at layer 3 (network layer) of the OSI model.
   - **CLB (Classic Load Balancer)**: The original AWS load balancer, supporting layer 3, 4 and layer 7 load balancing, intended for applications built within the EC2-Classic network. RETIRED!

Understanding these variations and differences between AWS services helps you select the appropriate tools for your specific needs, ensuring efficient and effective use of AWS resources.


