# SAA-C03
Certification prep
Sure! Here are comprehensive notes for preparing for the AWS Certified Solutions Architect – Associate (SAA-C03) exam, covering key tools and important points:
---
# AWS Certified Solutions Architect – Associate (SAA-C03) Preparation Notes
## 1. **AWS Global Infrastructure**
**Regions**: Geographically isolated areas that contain multiple Availability Zones.
**Availability Zones (AZs)**: Data centers within a region, isolated from failures in other AZs.
**Edge Locations**: Locations for content delivery, typically used by Amazon CloudFront.
## 2. **Compute Services**
**EC2 (Elastic Compute Cloud)**:
Types of instances: General Purpose, Compute Optimized, Memory Optimized, Storage Optimized, Accelerated Computing.
Key features: Auto Scaling, Elastic Load Balancing, EBS (Elastic Block Store).
Pricing models: On-Demand, Reserved, Spot Instances, Savings Plans.
**Lambda**: Serverless compute service. Key concepts: Functions, Event sources, Execution role.
**Elastic Beanstalk**: Easy-to-use service for deploying and scaling web applications.
**ECS (Elastic Container Service)** and **EKS (Elastic Kubernetes Service)**: Container management services.
## 3. **Storage Services**
**S3 (Simple Storage Service)**:
Storage classes: Standard, Intelligent-Tiering, Standard-IA, One Zone-IA, Glacier, Glacier Deep Archive.
Key features: Versioning, Lifecycle policies, Cross-region replication, S3 Transfer Acceleration.
**EBS (Elastic Block Store)**: Persistent block storage for EC2 instances.
Types: General Purpose (SSD), Provisioned IOPS (SSD), Throughput Optimized (HDD), Cold (HDD).
**EFS (Elastic File System)**: Scalable file storage for use with EC2.
**Glacier**: Low-cost archival storage.
**Storage Gateway**: Hybrid cloud storage service.
## 4. **Database Services**
**RDS (Relational Database Service)**:
Supported engines: Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle, Microsoft SQL Server.
Key features: Multi-AZ deployments, Read replicas, Automated backups, Snapshots.
**DynamoDB**: NoSQL database service.
Key features: On-demand and provisioned capacity, Global tables, DynamoDB Streams, TTL.
**Redshift**: Data warehousing service.
**ElastiCache**: In-memory caching service.
Engines: Redis, Memcached.
**Neptune**: Graph database service.
## 5. **Networking & Content Delivery**
**VPC (Virtual Private Cloud)**:
Components: Subnets, Route Tables, Internet Gateway, NAT Gateway, Security Groups, Network ACLs.
Peering connections, VPC endpoints, VPC Flow Logs.
**Route 53**: DNS and domain name registration.
Routing policies: Simple, Weighted, Latency-based, Failover, Geolocation, Geoproximity, Multi-value answer.
**CloudFront**: Content delivery network (CDN) service.
Concepts: Distributions, Edge locations, Origins, Behaviors.
**Direct Connect**: Dedicated network connection to AWS.
**VPN (Virtual Private Network)**: Securely connect on-premises networks to AWS.
## 6. **Security, Identity, & Compliance**
**IAM (Identity and Access Management)**:
Components: Users, Groups, Roles, Policies.
Concepts: MFA (Multi-Factor Authentication), IAM Best Practices.
**Cognito**: User authentication and management for web and mobile apps.
**KMS (Key Management Service)**: Manage encryption keys.
**CloudHSM**: Hardware-based key storage.
**AWS Shield**: DDoS protection.
**WAF (Web Application Firewall)**: Protect web applications from common web exploits.
**Artifact**: On-demand access to AWS security and compliance reports.
## 7. **Management & Governance**
**CloudWatch**: Monitoring and observability service.
Components: Metrics, Alarms, Logs, Events, Dashboards.
**CloudTrail**: Track user activity and API usage.
**Config**: AWS resource inventory, configuration history, and configuration change notifications.
**Systems Manager**: Manage AWS resources and on-premises servers.
Key features: Automation, Session Manager, Parameter Store, Patch Manager.
**Trusted Advisor**: Best practices checks and recommendations.
## 8. **Analytics**
**Athena**: Query data in S3 using SQL.
**EMR (Elastic MapReduce)**: Big data processing using Hadoop, Spark, etc.
**Kinesis**: Real-time data streaming and processing.
Components: Kinesis Data Streams, Kinesis Data Firehose, Kinesis Data Analytics.
**QuickSight**: Business intelligence and analytics.
**Data Pipeline**: Data workflow orchestration.
## 9. **Migration & Transfer**
**DMS (Database Migration Service)**: Migrate databases to AWS.
**Snowball**: Petabyte-scale data transport solution.
**Migration Hub**: Track application migrations to AWS.
## 10. **Developer Tools**
**CodeCommit**: Managed source control service.
**CodeBuild**: Build and test code.
**CodeDeploy**: Automated code deployment.
**CodePipeline**: Continuous integration and continuous delivery (CI/CD) service.
**Cloud9**: Cloud-based IDE.
## 11. **Machine Learning**
**SageMaker**: Build, train, and deploy machine learning models.
**Rekognition**: Image and video analysis.
**Comprehend**: Natural language processing (NLP).
**Lex**: Build conversational interfaces using voice and text.
**Polly**: Text-to-speech service.
## Important Points to Remember
**Security Best Practices**: Regularly review IAM policies, enable MFA, use encryption, monitor using CloudWatch and CloudTrail.
**Cost Management**: Use the AWS Pricing Calculator, enable Cost Explorer, set up budgets and alerts, leverage Reserved Instances and Savings Plans.
**High Availability & Disaster Recovery**: Utilize Multi-AZ deployments, automated backups, snapshots, and cross-region replication.
**Networking**: Understand VPC design, subnetting, security groups, and NACLs.
**Automation**: Leverage CloudFormation and Systems Manager for infrastructure as code and automated management.
**Compliance**: Familiarize yourself with AWS compliance programs and services like Artifact, Shield, and WAF.
---







