# AWS-Certified-Cloud-Practitioner-CLF-C01
AWS Certified Cloud Practitioner CLF-C01

-----------------------------------------

AWS Budgets allows you to provide notifications against targets. We recommend configuring notifications on both increases and decreases, and in both cost and usage for workloads.
-----------------------------------------

Amazon Relational Database Service (RDS), Amazon Redshift, and Amazon ElastiCache provide a managed database service. Amazon Athena, Amazon Elastic Map Reduce (EMR), and Amazon Elasticsearch provide a managed analytics service
-----------------------------------------

Serverless or Application-level Services: You can use serverless or application-level services such as AWS Lambda, Amazon Simple Queue Service (Amazon SQS), Amazon Simple Notification Service (Amazon SNS), and Amazon Simple Email Service (Amazon SES).
-----------------------------------------

Compute Savings Plans are the most flexible and provide a discount of up to 66%. They automatically apply across Availability Zones, instance size, instance family, operating system, tenancy, Region, and compute service
-----------------------------------------

AWS Trusted Advisor
five categories: cost optimization; security; fault tolerance; performance; and service limits.

Amazon CloudFront is a fast content delivery network (CDN)
1- Accelerate static website content delivery.
2- Live & on-demand video streaming.
3- Security.
4- Customizable content delivery with Lambda@Edge.
-----------------------------------------

Under the shared responsibility model, AWS is responsible for the hardware and software that run AWS services. This includes patching the infrastructure software and configuring infrastructure devices. 
As a customer, you are responsible for implementing best practices for data encryption, patching guest operating system and applications, identity and access management, and network & firewall configurations.


The customer is responsible for securing their network by configuring Security Groups, Network Access control Lists (NACLs), and Routing Tables. The customer is also responsible for setting a password policy on their AWS account that specifies the complexity and mandatory rotation periods for their IAM users' passwords.

** Patch Management
** Configuration Management
** Awareness & Training

Amazon DynamoDB is a fast and flexible NoSQL database service for all applications that need consistent, single-digit millisecond latency at any scale. It is a fully managed cloud database and supports both document and key-value store models. Its flexible data model, reliable performance, and automatic scaling of throughput capacity, makes it a great fit for mobile, web, gaming, ad tech, IoT, and many other applications.

-----------------------------------------

AWS Database Migration Service (DMS) helps you migrate databases to AWS easily and securely. The source database remains fully operational during the migration, minimizing downtime to applications that rely on the database. The AWS Database Migration Service can migrate your data to and from most widely used commercial and open-source databases. The service supports homogeneous migrations such as Oracle to Oracle, as well as heterogeneous migrations between different database platforms, such as Oracle to Amazon Aurora or Microsoft SQL Server to MySQL. It also allows you to stream data to Amazon Redshift from any of the supported sources including Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle, SAP ASE, and SQL Server, enabling consolidation and easy analysis of data in the petabyte-scale data warehouse. AWS Database Migration Service can also be used for continuous data replication with high availability.   

-----------------------------------------

Amazon Aurora is a MySQL and PostgreSQL compatible relational database built for the cloud, that combines the performance and availability of high-end commercial databases with the simplicity and cost-effectiveness of open source databases. Aurora is up to five times faster than standard MySQL databases and three times faster than standard PostgreSQL databases. It provides the security, availability, and reliability of commercial-grade databases at 1/10th the cost. Aurora is fully managed by Amazon Relational Database Service (RDS), which automates time-consuming administration tasks like hardware provisioning, database setup, patching, and backups.
-----------------------------------------

EC2 instance pricing varies depending on many variables:
- The buying option (On-demand, Reserved, Spot, Dedicated)
- Selected AMI
- Selected instance type
- Region
- Data Transfer in/out
- Storage capacity.   

-----------------------------------------
Horizontal Scaling:
Scaling horizontally takes place through an increase in the number of resources (e.g., adding more hard drives to a storage array or adding more servers to support an application). This is a great way to build Internet-scale applications that leverage the elasticity of cloud computing.

-----------------------------------------

Vertical Scaling:
Scaling vertically takes place through an increase in the specifications of an individual resource (e.g., upgrading a server with a larger hard drive, adding more memory, or provisioning a faster CPU). On Amazon EC2, this can easily be achieved by stopping an instance and resizing it to an instance type that has more RAM, CPU, I/O,or networking capabilities. This way of scaling can eventually hit a limit and it is not always a cost efficient or highly available approach. However, it is very easy to implement and can be sufficient for many use cases especially as a short term solution.
-----------------------------------------

The Well-Architected Framework identifies a set of general design principles to facilitate good design in the cloud:

1- Stop guessing your capacity needs: Eliminate guessing about your infrastructure capacity needs. When you make a capacity decision before you deploy a system, you might end up sitting on expensive idle resources or dealing with the performance implications of limited capacity. With cloud computing, these problems can go away. You can use as much or as little capacity as you need, and scale up and down automatically.

2- Test systems at production scale: In the cloud, you can create a production-scale test environment on demand, complete your testing, and then decommission the resources. Because you only pay for the test environment when it's running, you can simulate your live environment for a fraction of the cost of testing on premises.

3- Automate to make architectural experimentation easier: Automation allows you to create and replicate your systems at low cost and avoid the expense of manual effort. You can track changes to your automation, audit the impact, and revert to previous parameters when necessary.

4- Allow for evolutionary architectures: Allow for evolutionary architectures. In a traditional environment, architectural decisions are often implemented as static, one-time events, with a few major versions of a system during its lifetime. As a business and its context continue to change, these initial decisions might hinder the system's ability to deliver changing business requirements. In the cloud, the capability to automate and test on demand lowers the risk of impact from design changes. This allows systems to evolve over time so that businesses can take advantage of innovations as a standard practice.

5- Drive architectures using data: In the cloud you can collect data on how your architectural choices affect the behavior of your workload. This lets you make fact-based decisions on how to improve your workload. Your cloud infrastructure is code, so you can use that data to inform your architecture choices and improvements over time.

6- Improve through game days: Test how your architecture and processes perform by regularly scheduling game days to simulate events in production. This will help you understand where improvements can be made and can help develop organizational experience in dealing with events.

-----------------------------------------

For Enterprise-level customers, a TAM (Technical Account Manager) provides technical expertise for the full range of AWS services and obtains a detailed understanding of your use case and technology architecture. TAMs work with AWS Solution Architects to help you launch new projects and give best practices recommendations throughout the implementation life cycle. Your TAM is the primary point of contact for ongoing support needs, and you have a direct telephone line to your TAM.
-----------------------------------------

Amazon Aurora is a MySQL and PostgreSQL-compatible relational database built for the cloud. Amazon Aurora combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases. It delivers up to five times the throughput of standard MySQL and up to three times the throughput of standard PostgreSQL. Amazon Aurora is designed to be compatible with MySQL and with PostgreSQL, so that existing applications and tools can run without requiring modification. It is available through Amazon Relational Database Service (RDS), freeing you from time-consuming administrative tasks such as provisioning, patching, backup, recovery, failure detection, and repair.

-----------------------------------------

The AWS Abuse team can assist you when AWS resources are being used to engage in the following types of abusive behavior:     

I. Spam: You are receiving unwanted emails from an AWS-owned IP address, or AWS resources are being used to spam websites or forums.

II. Port scanning: Your logs show that one or more AWS-owned IP addresses are sending packets to multiple ports on your server, and you believe this is an attempt to discover unsecured ports.

III. Denial of service attacks (DOS): Your logs show that one or more AWS-owned IP addresses are being used to flood ports on your resources with packets, and you believe this is an attempt to overwhelm or crash your server or software running on your server.    

IV. Intrusion attempts: Your logs show that one or more AWS-owned IP addresses are being used to attempt to log in to your resources.

V. Hosting objectionable or copyrighted content: You have evidence that AWS resources are being used to host or distribute illegal content or distribute copyrighted content without the consent of the copyright holder.

VI. Distributing malware: You have evidence that AWS resources are being used to distribute software that was knowingly created to compromise or cause harm to computers or machines on which it is installed.
-----------------------------------------

AWS Organizations has five main benefits:
1) Centrally manage access polices across multiple AWS accounts.
2) Automate AWS account creation and management.
3) Control access to AWS services.
4) Consolidate billing across multiple AWS accounts.
5) Configure AWS services across multiple accounts.

-----------------------------------------

The benefits of the AWS personal health dashboard include:

**A personalized View of Service Health: Personal Health Dashboard gives you a personalized view of the status of the AWS services that power your applications, enabling you to quickly see when AWS is experiencing issues that may impact you. For example, in the event of a lost EBS volume associated with one of your EC2 instances, you would gain quick visibility into the status of the specific service you are using, helping save precious time troubleshooting to determine root cause.

**Proactive Notifications: The dashboard also provides forward looking notifications, and you can set up alerts across multiple channels, including email and mobile notifications, so you receive timely and relevant information to help plan for scheduled changes that may affect you. In the event of AWS hardware maintenance activities that may impact one of your EC2 instances, for example, you would receive an alert with information to help you plan for, and proactively address any issues associated with the upcoming change.

**Detailed Troubleshooting Guidance: When you get an alert, it includes remediation details and specific guidance to enable you to take immediate action to address AWS events impacting your resources. For example, in the event of an AWS hardware failure impacting one of your EBS volumes, your alert would include a list of your affected resources, a recommendation to restore your volume, and links to the steps to help you restore it from a snapshot. This targeted and actionable information reduces the time needed to resolve issues.

-----------------------------------------

Amazon Glacier is an extremely low-cost storage service that provides secure, durable, and flexible storage for long-term data backup and archival. With Amazon Glacier, customers can reliably store their data for as little as $0.004 per gigabyte per month. Amazon Glacier enables customers to offload the administrative burdens of operating and scaling storage to AWS, so that they don’t have to worry about capacity planning, hardware provisioning, data replication, hardware failure detection and repair, or time-consuming hardware migrations.

Amazon Glacier is an extremely low-cost storage service optimized for infrequently used data or "cold data"

-----------------------------------------

Other managed services include: AWS Lambda, Amazon RDS, Amazon Redshift, Amazon CloudFront, and several other services.

-----------------------------------------

You should attempt to build as much automation as possible in both detecting and reacting to failure. You can use services like ELB and Amazon Route53 to configure health checks and mask failure by only routing traffic to healthy endpoints. In addition, Auto Scaling can be configured to automatically replace unhealthy nodes. You can also replace unhealthy nodes using the Amazon EC2 auto-recovery feature or services such as AWS OpsWorks and AWS Elastic Beanstalk. It won’t be possible to predict every possible failure scenario on day one. Make sure you collect enough logs and metrics to understand normal system behavior. After you understand that, you will be able to set up alarms that trigger automated response or manual intervention.
-----------------------------------------

The AWS Auto Scaling service itself is free to use, you only pay for the resources that Auto-scaling provisions on your behalf (e.g. scaling EC2 capacity up).

-----------------------------------------

Amazon S3 offers a range of storage classes designed for different use cases. These include S3 Standard for general-purpose storage of frequently accessed data; S3 Intelligent-Tiering for data with unknown or changing access patterns; S3 Standard-Infrequent Access (S3 Standard-IA) and S3 One Zone-Infrequent Access (S3 One Zone-IA) for long-lived, but less frequently accessed data; and Amazon S3 Glacier (S3 Glacier) and Amazon S3 Glacier Deep Archive (S3 Glacier Deep Archive) for long-term archive and digital preservation.

-----------------------------------------
AWS provides flexible infrastructure and services that help customers implement strong DDoS mitigations and create highly available application architectures that follow AWS Best Practices for DDoS Resiliency. These include services such as Amazon Route 53, Amazon CloudFront, Elastic Load Balancing, and AWS WAF to control and absorb traffic, and deflect unwanted requests. These services integrate with AWS Shield, a managed DDoS protection service that provides always-on detection and automatic inline mitigations to safeguard web applications running on AWS.

-----------------------------------------

Snowball is a petabyte-scale data transport solution that uses devices designed to be secure to transfer large amounts of data into and out of the AWS Cloud. Using Snowball addresses common challenges with large-scale data transfers including high network costs, long transfer times, and security concerns. Customers today use Snowball to migrate analytics data, genomics data, video libraries, image repositories, backups, and to archive part of data center shutdowns, tape replacement or application migration projects. Transferring data with Snowball is simple, fast, more secure, and can be as little as one-fifth the cost of transferring data via high-speed Internet. 

-----------------------------------------
AWS X-Ray helps developers analyze and debug distributed applications in production or under development, such as those built using microservice architecture. With X-Ray, you can understand how your application and its underlying services are performing so you can identify and troubleshoot the root cause of performance issues and errors. X-Ray provides an end-to-end view of requests as they travel through your application, and shows a map of your application’s underlying components. You can use X-Ray to analyze both applications in development and in production, from simple three-tier applications to complex microservices applications consisting of thousands of services. 

-----------------------------------------

The Multi-AZ principle involves deploying an AWS resource in multiple Availability Zones to achieve high availability for that resource.

-----------------------------------------

DynamoDB automatically spreads the data and traffic for your tables over a sufficient number of servers to handle your throughput and storage requirements, while maintaining consistent and fast performance. All of your data is stored on solid-state disks (SSDs) and is automatically replicated across multiple Availability Zones in an AWS Region, providing built-in fault tolerance in the event of a server failure or Availability Zone outage.

-----------------------------------------

Amazon S3 provides durable infrastructure to store important data and is designed for durability of 99.999999999% of objects. Data in all Amazon S3 storage classes is redundantly stored across multiple Availability Zones (except S3 One Zone-IA).


-----------------------------------------
A security group acts as a virtual firewall for your instance to control inbound and outbound traffic. A Network Access Control List (NACL) acts as a firewall for controlling traffic in and out of one or more subnets. Therefore, if they are configured properly, they can protect your instances from DDoS attacks.

-----------------------------------------
AWS Snowmobile is an Exabyte-scale data transfer service used to move extremely large amounts of data to AWS. You can transfer up to 100 Petabytes (PB) per Snowmobile, a 45-foot long ruggedized shipping container, pulled by a semi-trailer truck. Snowmobile makes it easy to move massive volumes of data to the cloud, including video libraries, image repositories, or even a complete data center migration. At exabyte scale, transferring data with Snowmobile is more secure, fast and cost effective.

-----------------------------------------
AWS CloudTrail is a web service that records AWS API calls for your account and delivers log files to you. The recorded information includes the identity of the API caller, the time of the API call, the source IP address of the API caller, the request parameters, and the response elements returned by the AWS service.  With CloudTrail, you can get a history of AWS API calls for your account, including API calls made using the AWS Management Console, AWS SDKs, command line tools, and higher-level AWS services (such as AWS CloudFormation). The AWS API call history produced by CloudTrail enables security analysis, resource change tracking, and compliance auditing.

-----------------------------------------
AWS Professional Services created the AWS Cloud Adoption Framework (AWS CAF) to help organizations design and travel an accelerated path to successful cloud adoption. The guidance and best practices provided by the framework help you build a comprehensive approach to cloud computing across your organization, and throughout your IT lifecycle. Using the AWS CAF helps you realize measurable business benefits from cloud adoption faster and with less risk.

-----------------------------------------
Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Amazon EC2’s simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment. Amazon EC2 reduces the time required to obtain and boot new server instances to minutes, allowing you to quickly scale capacity, both up and down, as your computing requirements change. Amazon EC2 changes the economics of computing by allowing you to pay only for capacity that you actually use. Amazon EC2 provides developers the tools to build failure resilient applications and isolate them from common failure scenarios.

-----------------------------------------

You can control network traffic in AWS by configuring security groups, network access control lists, and route tables.

1- Security groups: Act as a firewall for associated Amazon EC2 instances, controlling both inbound and outbound traffic at the instance level.

2- Network access control lists (ACLs): Act as a firewall for associated subnets, controlling both inbound and outbound traffic at the subnet level.

3- Route Tables: A route table contains a set of rules, called routes, that are used to determine where network traffic is directed.

-----------------------------------------

Amazon Simple Workflow Service (SWF) is a web service that makes it easy to coordinate work across distributed application components. Amazon SWF enables applications for a range of use cases, including media processing, web application back-ends, business process workflows, and analytics pipelines, to be designed as a coordination of tasks. Tasks represent invocations of various processing steps in an application which can be performed by executable code, web service calls, human actions, and scripts. The coordination of tasks involves managing execution dependencies, scheduling, and concurrency in accordance with the logical flow of the application. With Amazon SWF, developers get full control over implementing processing steps and coordinating the tasks that drive them, without worrying about underlying complexities such as tracking their progress and keeping their state.

-----------------------------------------

AWS also provides a fully managed security service called AWS Macie to help protect your sensitive data in Amazon S3. Amazon Macie uses machine learning to automatically discover, classify, and protect sensitive data in Amazon S3. Amazon Macie recognizes sensitive data such as personally identifiable information (PII) or intellectual property, and provides you with dashboards and alerts that give visibility into how this data is being accessed or moved. The fully managed service continuously monitors data access activity for anomalies, and generates detailed alerts when it detects risk of unauthorized access or inadvertent data leaks. Today, Amazon Macie is available to protect data stored in Amazon S3, with support for additional AWS data stores coming later this year.

-----------------------------------------
The AWS Software Development Kit (AWS SDK) can simplify using AWS services in your applications with an API tailored to your programming language or platform. Programming languages supported include Java, .NET, Node.js, PHP, Python, Ruby, Go, and C++.

-----------------------------------------
Amazon CloudWatch is the AWS service that allows you to monitor the usage of your AWS resources. CloudWatch collects metrics, and allows you to create alarms based on those metrics.  You can use CloudWatch to monitor your estimated AWS charges. When you enable the monitoring of estimated charges for your AWS account, the estimated charges are calculated and sent several times daily to CloudWatch as metric data. Billing metric data includes the estimated charges for every service in AWS that you use, in addition to the estimated overall total of your AWS charges. The alarm triggers when your account billing exceeds the threshold you specify.

-----------------------------------------

There are three main types of Budgets that Customers can create using the AWS Budgets service:

1- Cost Budgets:

AWS Cost Budgets gives customers the ability to set custom budgets that alert them when their costs exceed (or are forecasted to exceed) their budgeted amount.

2- Usage Budgets:

AWS Usage Budgets can alert customers when their usage exceeds (or is forecasted to exceed) the thresholds they define.

3- Reservation Budgets:

Customers can use the Reservation Budgets to set reservation utilization or coverage targets and receive alerts when their utilization drops below the threshold they define. This will help AWS customers track the utilization of their reserved instances and avoid over-spending on unused reservations.

-----------------------------------------

Shared Controls are controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives. In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services. Examples include:

** Patch Management – AWS is responsible for patching the underlying hosts and fixing flaws within the infrastructure, but customers are responsible for patching their guest OS and applications.

** Configuration Management – AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.

** Awareness & Training - AWS trains AWS employees, but a customer must train their own employees.

-----------------------------------------

AWS Application Discovery Service helps systems integrators quickly and reliably plan application migration projects by automatically identifying applications running in on-premises data centers, their associated dependencies, and their performance profiles. Planning data center migrations can involve thousands of workloads that are often deeply interdependent. Application discovery and dependency mapping are important early first steps in the migration process, but these tasks are difficult to perform at scale due to the lack of automated tools. AWS Application Discovery Service automatically collects configuration and usage data from servers, storage, and networking equipment to develop a list of applications, how they perform, and how they are interdependent. This information helps reduce the complexity and time in planning your cloud migration.

-----------------------------------------

An Amazon Machine Image (AMI) provides the information required to launch an instance, which is a virtual server in the cloud. You must specify an AMI when you launch an instance, and you can launch as many instances from the AMI as you need. You can also launch instances from as many different AMIs as you need.


-----------------------------------------
To enable HTTPS connections to your website or application in AWS, you need an SSL/TLS server certificate. You can use a server certificate provided by AWS Certificate Manager (ACM) or one that you obtained from an external provider. You can use ACM or IAM to store and deploy server certificates. Use IAM as a certificate manager only when you must support HTTPS connections in a region that is not supported by ACM. IAM supports deploying server certificates in all regions, but you must obtain your certificate from an external provider for use with AWS. Amazon Route 53 is used to register domain names or use your own domain name to route your end users to Internet applications. Route 53 is not responsible for creating SSL certifications.

-----------------------------------------

Amazon Route 53 can be used for:

● Registering domain names

● ​DNS configuration and management

● Configuring health checks to route traffic only to healthy endpoints

● Managing global application traffic (cross-regions) through a variety of routing types.

-----------------------------------------

AWS Key Management Service (KMS) is a managed service that makes it easy for you to create and control the encryption keys used to encrypt your data, and uses FIPS 140-2 validated hardware security modules to protect the security of your keys. AWS Key Management Service is integrated with most other AWS services to help you protect the data you store with these services. AWS Key Management Service is also integrated with AWS CloudTrail to provide you with logs of all key usage to help meet your regulatory and compliance needs.

-----------------------------------------

AWS CloudHSM is a cloud-based hardware security module (HSM) that enables you to easily generate and use your own encryption keys on the AWS Cloud. With CloudHSM, you can manage your own encryption keys using FIPS 140-2 Level 3 validated HSMs. CloudHSM offers you the flexibility to integrate with your applications using industry-standard APIs, such as PKCS#11, Java Cryptography Extensions (JCE), and Microsoft CryptoNG (CNG) libraries

-----------------------------------------
In relation to Amazon RDS databases:

AWS is responsible for:

1- Managing the underlying infrastructure and foundation services.

2- Managing the operating system.

3- Database setup.

4- Patching and backups.

-----------------------------------------

The customer is still responsible for:

1- Protecting the data stored in databases (through encryption and IAM access control).

2- Managing the database settings that are specific to the application.

3- Building the relational schema.

4- Network traffic protection.

-----------------------------------------

S3 pricing is based on four factors:

1) Total amount of data (in GB) stored on S3
2) Storage class (S3 Standard, S3 Intelligent-Tiering, S3 Standard-Infrequent Access, S3 One Zone-IA, S3 Glacier, or S3 Glacier Deep Archive)
3) Amount of data transferred out of AWS from S3
4) Number of requests to S3

-----------------------------------------

Server-based services include: Amazon EC2, Amazon RDS, Amazon Redshift and Amazon EMR.

Serverless services include: AWS Lambda, AWS Fargate, Amazon SNS, Amazon SQS and Amazon DynamoDB.

-----------------------------------------
Amazon Connect is a cloud-based contact center solution. Amazon Connect makes it easy to set up and manage a customer contact center and provide reliable customer engagement at any scale. You can set up a contact center in just a few steps, add agents from anywhere, and start to engage with your customers right away. Amazon Connect provides rich metrics and real-time reporting that allow you to optimize contact routing. You can also resolve customer issues more efficiently by putting customers in touch with the right agents. Amazon Connect integrates with your existing systems and business applications to provide visibility and insight into all of your customer interactions.

-----------------------------------------

The question stated that the application is designed to recover quickly from failures, therefore it can handle any interruption may occur with the instance. Hence, we can use the Spot instances for this application. Spot instances provide a discount (up to 90%) off the On-Demand price.

-----------------------------------------

The Spot price is determined by long-term trends in supply and demand for EC2 spare capacity. If the Spot price exceeds the maximum price you specify for a given instance or if capacity is no longer available, your instance will automatically be interrupted.

Spot Instances are the most cost-effective choice if you are flexible about when your applications run and if your applications can be interrupted. For example, Spot Instances are well-suited for data analysis, batch jobs, background processing, and optional tasks. 

-----------------------------------------

Benefits of DynamoDB include:

1- Performance at scale:

DynamoDB supports some of the world’s largest scale applications by providing consistent, single-digit millisecond response times at any scale. You can build applications with virtually unlimited throughput and storage.

2- Serverless:

With DynamoDB, there are no servers to provision, patch, or manage and no software to install, maintain, or operate. DynamoDB automatically scales tables up and down to adjust for capacity and maintain performance.

3- Highly available:

Availability and fault tolerance are built in, eliminating the need to architect your applications for these capabilities.

-----------------------------------------

Dedicated Instances are Amazon EC2 instances that run in a virtual private cloud (VPC) on hardware that's dedicated to a single customer. Dedicated Instances that belong to different AWS accounts are physically isolated at the hardware level. In addition, Dedicated Instances that belong to AWS accounts that are linked to a single payer account are also physically isolated at the hardware level. However, Dedicated Instances may share hardware with other instances from the same AWS account that are not Dedicated Instances.


-----------------------------------------

Amazon Virtual Private Cloud (Amazon VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.

-----------------------------------------

Services Provide real-time auditing for compliance and vulnerabilities
- 
AWS Config, Amazon Inspector, and AWS Trusted Advisor


-----------------------------------------

AWS Serverless Services include:

Compute: AWS Lambda, AWS Fargate

Messaging: Amazon SNS, Amazon SQS

Database: Amazon DynamoDB, Amazon Aurora Serverless

Orchestration: AWS Step Functions

-----------------------------------------

With per-second billing in EC2 you pay for only what you use. It takes cost of unused minutes and seconds in an hour off of the bill, so you can focus on improving your applications instead of maximizing usage to the hour.

Per-second billing is available for instances launched in Amazon Linux or Ubuntu.

For other instances, including Windows, each partial instance-hour consumed will be billed as a full hour.

In this case, the customer will be charged for 2 hours, 5 minutes and 9 seconds for the Linux instance, and 5 hours for the Windows instance

-----------------------------------------

AWS Global Accelerator is a networking service that improves the availability and performance of the applications that you offer to your global users. Today, if you deliver applications to your global users over the public internet, your users might face inconsistent availability and performance as they traverse through multiple public networks to reach your application. These public networks can be congested and each hop can introduce availability and performance risk. AWS Global Accelerator uses the highly available and congestion-free AWS global network to direct internet traffic from your users to your applications on AWS, making your users’ experience more consistent. To improve the availability of your application, you must monitor the health of your application endpoints and route traffic only to healthy endpoints. AWS Global Accelerator improves application availability by continuously monitoring the health of your application endpoints and routing traffic to the closest healthy endpoints.

-----------------------------------------

Amazon DynamoDB Accelerator (DAX) is an in-memory cache for DynamoDB that delivers up to a 10x performance improvement – from milliseconds to microseconds – even at millions of requests per second.

-----------------------------------------

Know the details of the following (not an exhaustive list):

a. Fundamentals of AWS: IAM, S3, EC2, EBS, EFS, Redshift, RDS, DynamoDB, Auto Scaling

b. VPN, VPC, Transit Gateway, Internet Gateway, NAT Gateway

c. CloudFront, CloudFormation, CloudTrail, CloudWatch

d. AWS Security best practices such as IAM policies and KMS

e. What are Region and Availability Zone (AZ) restrictions for different AWS services: Single AZ, Multi-AZ, Single Region, Multi-Region


f. What AWS services are global: IAM, CloudFront, Amazon Route 53, WAF, Amazon Chime, DynamoDB, WorkDocs, WorkMail, WorkSpaces, WorkLink, Service Certificates

g. What AWS services are truly free: Security Groups, Auto Scaling, CloudFormation

h. What AWS services include a free tier for 12 months for new AWS customers: EC2, S3, RDS, CloudFront, DynamoDB*, Glacier*, Lambda*
*Does not automatically expire after 12 months

i. What AWS services are never free (need to pay to use)
WIREE — WAF, Inspector, Route 53, EBS volumes, ELB

j. What AWS services are serverless
AWS Serverless Services include:
Compute: AWS Lambda, AWS Fargate
Messaging: Amazon SNS, Amazon SQS
Database: Amazon DynamoDB, Amazon Aurora Serverless
Orchestration: AWS Step Functions


k. What AWS services scale automatically without intervention: S3, Lambda

l. Which data storage options have auto-backup:
REEDS — RDS, EFS, EBS, DynamoDB, Storage Gateway

-----------------------------------------



