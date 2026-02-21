# Cloud Provider comparaison
## Cloud Resource Descriptions and Comparison Table

| #  | Description | AWS (Service Name) | Azure (Service Name) | Google Cloud (Service Name) |
|----|-------------|--------------------|----------------------|----------------------------|
| 1  | Scalable virtual machines | Amazon EC2 | Azure Virtual Machines | Compute Engine |
| 2  | Object storage | Amazon S3 | Azure Blob Storage | Cloud Storage |
| 3  | Managed relational database | Amazon RDS | Azure SQL Database | Cloud SQL |
| 4  | Serverless compute | AWS Lambda | Azure Functions | Cloud Functions |
| 5  | Virtual private network | Amazon VPC | Azure Virtual Network | Virtual Private Cloud |
| 6  | Content delivery network (CDN) | Amazon CloudFront | Azure CDN | Cloud CDN |
| 7  | Managed NoSQL database | Amazon DynamoDB | Azure Cosmos DB | Cloud Bigtable |
| 8  | Block storage | Amazon EBS | Azure Managed Disks | Persistent Disk |
| 9  | Managed Kubernetes service | Amazon EKS | Azure Kubernetes Service (AKS) | Google Kubernetes Engine (GKE) |
| 10 | Identity & key management | AWS IAM | Azure Active Directory | Cloud IAM |
| 11 | PaaS deployment platform | AWS Elastic Beanstalk | Azure App Service | App Engine |
| 12 | Monitoring & logging | Amazon CloudWatch | Azure Monitor | Cloud Monitoring |
| 13 | DNS service | Amazon Route 53 | Azure DNS | Cloud DNS |
| 14 | Load balancing | Elastic Load Balancing (ELB) | Azure Load Balancer | Cloud Load Balancing |
| 15 | Auto scaling | AWS Auto Scaling | Virtual Machine Scale Sets | Managed Instance Groups |
| 16 | Message queuing | Amazon SQS | Azure Service Bus | Cloud Pub/Sub |
| 17 | Real-time data streaming | Amazon Kinesis | Azure Event Hubs | Dataflow |
| 18 | Data warehouse | Amazon Redshift | Azure Synapse Analytics | BigQuery |
| 19 | Workflow orchestration | AWS Step Functions | Azure Logic Apps | Workflows |
| 20 | Data integration & migration | AWS Glue | Azure Data Factory | Data Fusion |
| 21 | Data catalog & governance | AWS Lake Formation | Microsoft Purview | Data Catalog |
| 22 | AI & ML services | Amazon SageMaker | Azure Machine Learning | Vertex AI |
| 23 | Infrastructure as Code | AWS CloudFormation | Azure Resource Manager (ARM) | Deployment Manager |
| 24 | CI/CD service | AWS CodePipeline | Azure DevOps | Cloud Build |
| 25 | Desktop as a Service (DaaS) | Amazon WorkSpaces | Azure Virtual Desktop | Google Cloud VMware Engine |
| 26 | Backup & disaster recovery | AWS Backup | Azure Backup | Backup and DR Service |
| 27 | Big data analytics platform | Amazon EMR | Azure HDInsight | Dataproc |
| 28 | File storage service | Amazon EFS | Azure Files | Filestore |
| 29 | Media processing & streaming | AWS Elemental MediaConvert | Azure Media Services | Transcoder API |
| 30 | Notification service | Amazon SNS | Azure Notification Hubs | Firebase Cloud Messaging |s

## Cloud Provider Comparison Report
AWS vs Microsoft Azure vs Google Cloud

### 1. INTRODUCTION
This report analyzes the key similarities, differences, unique capabilities, 
and naming conventions of equivalent services across the three major cloud 
providers: Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

### 2. KEY SIMILARITIES

2.1 Compute Services
All three providers offer scalable virtual machine services:
- AWS: Amazon EC2
- Azure: Azure Virtual Machines
- GCP: Compute Engine

Common Features:
- Auto-scaling
- Multiple instance types
- Global regions
- Linux and Windows support
- Pay-as-you-go pricing models

------------------------------------------------------------

2.2 Storage Services
Each provider offers:
- Object storage (S3 / Blob Storage / Cloud Storage)
- Block storage (EBS / Managed Disks / Persistent Disk)
- File storage (EFS / Azure Files / Filestore)

Common Features:
- High durability
- Encryption at rest and in transit
- Lifecycle management
- Multiple storage tiers

------------------------------------------------------------

2.3 Databases
All providers support:
- Managed relational databases
- Managed NoSQL databases
- Data warehouse solutions

Common Features:
- Automated backups
- Replication
- Scaling capabilities
- High availability options

------------------------------------------------------------

2.4 Containers & Kubernetes
Each provider offers a managed Kubernetes service:
- AWS: EKS
- Azure: AKS
- GCP: GKE

Common Features:
- Cluster auto-scaling
- Managed control plane
- Monitoring integration
- Rolling updates

------------------------------------------------------------

2.5 Serverless & Event-Driven Services
- AWS Lambda
- Azure Functions
- Cloud Functions

Common Features:
- Pay-per-execution
- Automatic scaling
- No server management
============================================================
### 3. KEY DIFFERENCES
3.1 Ecosystem Integration
AWS:
- Largest service catalog
- Mature and broad ecosystem

Azure:
- Strong integration with Microsoft enterprise tools
- Excellent hybrid cloud support

Google Cloud:
- Strong Kubernetes foundation
- Advanced analytics and AI integration

------------------------------------------------------------

3.2 Database Philosophy
AWS:
- DynamoDB optimized for high-scale key-value workloads

Azure:
- Cosmos DB supports multi-model databases

GCP:
- Bigtable optimized for large-scale analytics
- Clear separation between transactional and analytical systems

------------------------------------------------------------

3.3 Networking Design
AWS:
- Highly customizable VPC networking

Azure:
- Strong enterprise identity integration

GCP:
- Global VPC architecture
- Simplified multi-region networking

------------------------------------------------------------

3.4 AI & Machine Learning
AWS:
- Broad range of AI services

Azure:
- Strong enterprise AI integration
- OpenAI partnerships

GCP:
- Strong analytics-to-AI pipeline
- Advanced ML infrastructure

============================================================
### 4. UNIQUE STRENGTHS

AWS:
- Largest global infrastructure footprint
- Deep service customization
- Strong marketplace ecosystem

Azure:
- Enterprise-friendly
- Strong hybrid cloud capabilities
- Seamless Microsoft product integration

Google Cloud:
- Kubernetes-native architecture
- BigQuery serverless analytics
- Global networking simplicity

============================================================
### 5. NAMING CONVENTION DIFFERENCES

AWS:
- Acronym-heavy (EC2, S3, RDS)
- Marketing-driven names

Azure:
- Descriptive names
- Often includes "Azure" in service names

Google Cloud:
- Functional and simplified naming
- Frequently uses "Cloud" prefix

