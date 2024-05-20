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








### VMs, Containers & Serverless
   VMSs
      Amazon LightSail
   Containers
      Elastic Container Service (ECS)
      Elastic Container Registry (ECR)
      ECS Fargate
      Elastic Kubernetes Service (EKS)
   Serverless
      AWS Lambda  
### High Performace Compute (HPC)
#### Bottlerocket
#### AWS ParallelCluster
### Edge & Hybrid
   AWS Outposts
   AWS Wavelength
   VMWare Cloud on AWS
   AWS Local Zones
### Cost & Capacity Mgmt

## Storage Services
### Types of STorate Services
    Elastic Block Store (EBS) - Block
    AWS Elastic File System (EFS) - File
    Amazon Simple Storage Service (S3) - Object
### Intro to S3
### S3 Storage Classes
### AWS Snow Family
### Storage Services
   Simple Storage Service (S3)
   S3 Glacier
   Elastic Block Store (EBS)
   AWS Elastic File System (EFS)
   Storage Gateway
      Flie Gateway
      Volume Gateway
      Tape Gateway
   AWS Snow Family
   AWS Backup
   CloudEndure Disaster Recovery
   Amazon FSx
      SMB
      Lustre



## Databases
### Data Warehouses
### Key Value Store
### Document Database
### NoSQL Database Services
### Relational Database Services
### Other Database Services

## Networking
### Cloud-Native Networking Services
### Enterprise/Hybrid Networking Services
### VPC & Subnets
### Security Groups vs NACLs
### AWS CloudFront

## EC2
### EC2 Instance Families
### EC2 Instance Types
### Dedicated Host vs Dedicated Instances
### EC2 Tenancy
### Launch an EC2, SSH & Session Manager
### Launch an ASG (Auto Scaling Group)
### Launch an ALB (Application Load Balancer)
### EC2 Cleanup