## Cloud Computing 
- Cloud computing is the delivery of I.T services such as servers, storage, databases, networking, software, analytics, and intelligence over the internet where users 
can rent or lease these resources from cloud service providers such as AWS,Azure,GCP etc.

## Benefits of AWS
- Scalable-organizations can scale up or down based on demand or workload and accomodate any workload.
- Flexibilty and a variety of services-AWS has many services like computing power, storage, databases which allows users to choose specific services that meet their specifications or requirements.
- Global reach- through use of availability zones located in various regions,AWS global infrastructure enables users to deploy applications and services close to their end-users, reducing latency and improving performance
- Security-AWS has various security features like identity and access management, encryption, monitoring etc that enables user to build robust and secure applications
- Reliability and High Availability-multiple AZ(Availability Zones) within regions ensures applications remain available even in the instance of hardware failures or any other issue
- Cost-Efficiency: AWS follows a pay-as-you-go pricing model, where users pay only for the resources they consume and thus there is no need for upfront capital expenditure.
- Elasticity and Auto-Scaling: AWS allows users to automatically scale resources based on demand. Auto-scaling features enable the adjustment of computing capacity to maintain performance during peak times while minimizing costs during periods of lower demand.
- Global Content Delivery: AWS offers content delivery services like Amazon CloudFront, enabling the delivery of content, including videos and web pages, with low latency and high transfer speeds to users around the world


## Differences between on-demand delivery and cloud deployments
- On-demand delivery and cloud deployments are related concepts but refer to different aspects of cloud computing

## On-Demand Delivery
- The ability to access and consume computing resources or services as needed, without the need for long-term commitments or upfront investments.

## Cloud deployment
 Cloud deployment refers to the hosting and running of applications, services, or infrastructure on cloud computing platforms rather than on traditional on-premises servers or data centers

 ## Service models
- Infrastructure as a Service (IaaS): Deploying virtual machines, storage, and networking components in the cloud.
- Platform as a Service (PaaS): Developing and deploying applications without dealing with the underlying infrastructure.
- Software as a Service (SaaS): Accessing software applications over the internet on a subscription basis


## Pay as you go model
- In this model, customers are billed based on their actual usage of resources or services, rather than making upfront payments or committing to a fixed subscription fees 

## Deployment models
- Public Cloud: Easily accessible to the general public.
- Private Cloud (On-Premises): Accessible within an organisation.
- Hybrid Cloud: Combination of public and private cloud.
- Community Cloud: It shares the infrastructure between several organisations from a specific community.

## On premises vs cloud
- To differentiate between running workloads on-premises and in the cloud, consider a scenario in which developers must deploy a new application feature. Before they deploy, the team wants to test the feature in a separate quality assurance (QA) environment that has the same configurations as production. In an on-premises solution, an additional environment requires you to buy and install hardware, connect the necessary cabling, provision power, install operating systems, and more. 

In contrast, by running your application in the cloud, you can replicate an entire production environment in a matter of minutes or even seconds. Instead of physically installing hardware and connecting cabling, the solution is managed over the internet.

## AWS
- Amazon Web Services (AWS) is a leading cloud computing platform provided by Amazon.com,offering a wide range of cloud-based computing resources and services globally.

## AWS Global infrastructure
- AWS operates an extensive global network of data centers, known as Availability Zones, and Points of Presence (PoPs) strategically positioned worldwide. This network is designed to deliver cloud services with low-latency, high-speed, and fault-tolerant capabilities.

## Availability zones(AZ)
- A data center or a collection of data centers within an AWS region whose purpose of is to provide fault tolerance and high availability for applications and services hosted on AWS

## Regions
- AWS Regions are geographical areas consisting of multiple Availability Zones,AWS operates regions all over the world, including North America, Europe, Asia, and more.

## Edge locations
- Edge Locations are smaller AWS data centers strategically distributed around the world. These locations are used for content delivery and caching, reducing latency for end users


## Key points about AWS Availability Zones
- Isolation and Redundancy;each Availability Zone is isolated from the others, both in terms of physical infrastructure and electrical distribution,this is designed to minimize the impact of failures and ensure that a problem in one Availability Zone does not affect others.

- Geographic Distribution;Availability Zones are typically located in separate geographic areas within a region to minimise risk of natural disasters

- Highly Connected;Availability Zones within a region are connected with low-latency, high-throughput networking, allowing for fast and reliable communication between them.

- Scalability;users can use multiple Availability Zones to scale their applications horizontally, distributing workloads across different zones to handle increased traffic or demand.

- Resilience and Redundancy;multiple AZs allows users to design and deploy applications that are resilient to failures. By distributing application components across different Availability Zones, organizations can achieve redundancy and ensure continuous availability even if one zone experiences issues.

- Data Replication;customers can use AZs to implement data replication strategies. For example, they can use AWS services like Amazon RDS (Relational Database Service) with multi-AZ deployment for automatic failover and improved database availability.


## AWS tools
AWS provides a variety of tools and services to help users manage and optimize their cloud resources

-   AWS Management Console:
        The AWS Management Console is a web-based user interface that allows users to access and manage their AWS resources. 

-   AWS Command Line Interface (AWS CLI):
        AWS CLI is a command-line tool that enables users to interact with AWS services using text commands.

-   AWS Software Development Kits (SDKs):
        AWS offers SDKs for various programming languages, including Python, Java, JavaScript, .NET, and more. These SDKs help developers integrate AWS services into their applications.

-   AWS CloudFormation:
        CloudFormation allows users to define and provision AWS infrastructure as code. It uses templates to describe the resources and their configurations, enabling automated and repeatable deployments.

-   AWS Elastic Beanstalk:
        Elastic Beanstalk is a fully managed service that makes it easy to deploy and run applications in multiple languages. It handles capacity provisioning, load balancing, auto-scaling, and application health monitoring.

-    AWS Lambda:
        Lambda is a serverless computing service that allows users to run code without provisioning or managing servers. It automatically scales based on the incoming traffic.

-    AWS Identity and Access Management (IAM):
        IAM is used for managing access to AWS services and resources securely. It allows users to create and manage AWS users and groups, assign permissions, and set up roles.

-    Amazon S3 (Simple Storage Service):
        S3 is a scalable object storage service that allows users to store and retrieve any amount of data. It is commonly used for backup, archiving, and serving static web content.

-   Amazon RDS (Relational Database Service):
        RDS is a managed database service that supports various database engines, including MySQL, PostgreSQL, Oracle, and SQL Server. It simplifies database administration tasks.

-   Amazon EC2 (Elastic Compute Cloud):
        EC2 provides resizable compute capacity in the cloud. Users can launch virtual servers (instances) based on their specific needs.

-   Amazon VPC (Virtual Private Cloud):
        VPC enables users to create isolated networks within the AWS cloud. It provides control over the virtual networking environment, including IP address ranges, subnets, and route tables.

-   Amazon CloudFront:
        CloudFront is a content delivery network (CDN) service that accelerates the delivery of content to users worldwide. It distributes content from edge locations for low-latency access.

-   AWS CloudWatch:
        CloudWatch provides monitoring and observability for AWS resources. It collects and tracks metrics, monitors log files, and sets alarms.

-   AWS Trusted Advisor:
        Trusted Advisor provides best practices and recommendations for optimizing AWS resources in areas such as cost, performance, security, and fault tolerance.