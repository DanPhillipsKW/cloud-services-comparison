# Cloud Platform Guide

<div align="center">

### Cloud Providers
[![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/)
[![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com/)
[![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com/)
[![OCI](https://img.shields.io/badge/OCI-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://cloud.oracle.com/)

### Document Info
[![Last Updated](https://img.shields.io/badge/Last%20Updated-April%202024-blue)](https://github.com/DanPhillipsKW/cloud-services-comparison)
[![Study Guide](https://img.shields.io/badge/Type-Study%20Guide-green)](https://github.com/DanPhillipsKW/cloud-services-comparison)
[![Reference](https://img.shields.io/badge/Type-Reference-yellow)](https://github.com/DanPhillipsKW/cloud-services-comparison)
[![Status](https://img.shields.io/badge/Status-Maintained-brightgreen.svg)](https://github.com/DanPhillipsKW/cloud-services-comparison)

### Repository
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](https://github.com/DanPhillipsKW/cloud-services-comparison/blob/main/CONTRIBUTING.md)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://github.com/DanPhillipsKW/cloud-services-comparison/blob/main/LICENSE)
[![Pull Requests](https://img.shields.io/badge/PRs-Welcome-blueviolet.svg)](https://github.com/DanPhillipsKW/cloud-services-comparison/blob/main/CONTRIBUTING.md)
[![Version](https://img.shields.io/badge/Version-1.0-orange.svg)](https://github.com/DanPhillipsKW/cloud-services-comparison/releases)

</div>

## Table of Contents
📚 [Services](#service-comparison) | 
📊 [Market Position](#market-position) | 
💡 [Differentiators](#key-differentiators) | 
🤝 [Contributing](https://github.com/DanPhillipsKW/cloud-services-comparison/blob/main/CONTRIBUTING.md)

## Version History

| Version | Date | Changes |
|:--------|:-----|:---------|
| 1.0 | April 2024 | - Initial release with AWS, Azure, GCP, and OCI comparison |
|     |            | - Added market share data and key differentiators |
|     |            | - Included unique strengths for each platform |

## Disclaimer
This guide represents cloud services as of April 2024. Cloud providers continuously evolve their offerings. Please:
- Refer to official documentation for the most current information
- Check provider websites for latest service availability
- Consider this a reference point rather than current state
- Submit issues or pull requests for updates

## Market Position
- AWS: Market leader in public cloud, strongest enterprise presence
- Azure: Second largest provider, strong Microsoft ecosystem integration
- GCP: Growing rapidly, particularly strong in AI/ML and analytics
- OCI: Emerging provider, particularly strong for Oracle workloads

## Service Comparison

### 1. Compute Services
| AWS | Azure | GCP | OCI | Description |
|:---------|:----------|:---------|:---------|:------------|
| EC2 | Virtual Machines | Compute Engine | Compute | Core IaaS computing service |
| Elastic Beanstalk | App Service | App Engine | Container Engine | Platform-as-a-Service application hosting |
| Lambda | Azure Functions | Cloud Functions | Functions | Serverless computing platform |
| ECS | Container Instances | Cloud Run | Container Engine | Managed container orchestration service |
| EKS | AKS | GKE | Container Engine for Kubernetes | Managed Kubernetes service |
| Lightsail | App Service | Cloud Run | Compute | Simplified compute platform |
| EC2 Auto Scaling | VM Scale Sets | Instance Groups | Autoscaling | Automated scaling service |
| EC2 Spot | Spot VMs | Preemptible VMs | Preemptible | Low-cost compute instances |
| Batch | Batch | Batch | Pipeline | Managed batch computing service |
| Outposts | Azure Stack | Anthos | Dedicated Region | On-premises cloud solution |

### 2. Storage Services
| AWS | Azure | GCP | OCI | Description |
|:---------|:----------|:---------|:---------|:------------|
| S3 | Blob Storage | Cloud Storage | Object Storage | Object storage service |
| EBS | Managed Disks | Persistent Disk | Block Volume | Block storage service |
| EFS | Azure Files | Filestore | File Storage | Managed file storage service |
| Storage Gateway | StorSimple | Storage Transfer | Storage Gateway | Hybrid storage solution |
| S3 Glacier | Archive Storage | Archive Storage | Archive Storage | Long-term cold storage service |
| Backup | Backup | Cloud Backup | Backup | Managed backup service |
| Snow Family | Data Box | Transfer Appliance | Data Transfer | Offline data transfer solution |
| FSx | NetApp Files | NetApp Cloud | File Storage | Enterprise file system service |
| S3 One Zone | Cool Storage | Nearline Storage | Standard Storage | Infrequent access storage tier |

### 3. Database Services
| AWS | Azure | GCP | OCI | Description |
|:---------|:----------|:---------|:---------|:------------|
| RDS | Azure SQL Database | Cloud SQL | Database | Managed relational database service |
| DynamoDB | Cosmos DB | Firestore | NoSQL Database | Managed NoSQL database service |
| ElastiCache | Cache for Redis | Memorystore | Cache | In-memory caching service |
| Redshift | Synapse Analytics | BigQuery | Data Warehouse | Enterprise data warehouse service |
| Aurora | Azure SQL Database | Cloud Spanner | Database | Enterprise-grade database service |
| DocumentDB | Cosmos DB | Firestore | NoSQL Database | Document database service |
| Neptune | Cosmos DB Graph | -- | Graph Studio | Graph database service |
| Timestream | Time Series Insights | -- | -- | Time series database service |
| Keyspaces | Table Storage | Bigtable | NoSQL Database | Wide column store service |

### 4. Networking Services
| AWS | Azure | GCP | OCI | Description |
|:---------|:----------|:---------|:---------|:------------|
| VPC | Virtual Network | VPC | Virtual Cloud Network | Private cloud network service |
| Route 53 | Azure DNS | Cloud DNS | DNS | Managed DNS service |
| CloudFront | CDN | Cloud CDN | CDN | Content delivery network service |
| Direct Connect | ExpressRoute | Cloud Interconnect | FastConnect | Dedicated connectivity service |
| API Gateway | API Management | Cloud Endpoints | API Gateway | API management service |
| ELB | Load Balancer | Cloud Load Balancing | Load Balancer | Load balancing service |
| Transit Gateway | Virtual WAN | Cloud Router | DRG | Network transit hub service |
| Global Accelerator | Front Door | Premium Tier | -- | Global routing service |
| PrivateLink | Private Link | Private Service Connect | Service Gateway | Private connectivity service |

### 5. Security Services
| AWS | Azure | GCP | OCI | Description |
|:---------|:----------|:---------|:---------|:------------|
| IAM | Entra ID | Cloud IAM | Identity & Access | Identity management service |
| KMS | Key Vault | Cloud KMS | Key Management | Encryption key management service |
| Shield | DDoS Protection | Cloud Armor | WAF | DDoS protection service |
| WAF | WAF | Cloud Armor | WAF | Web application firewall service |
| Security Hub | Security Center | Security Command | Cloud Guard | Security management service |
| GuardDuty | Defender | Threat Detection | Cloud Guard | Threat detection service |
| Macie | Information Protection | DLP API | Cloud Guard | Data protection service |
| Certificate Manager | App Gateway | Certificate Authority | Certificates | SSL/TLS certificate service |

### 6. AI and Machine Learning
| AWS | Azure | GCP | OCI | Description |
|:---------|:----------|:---------|:---------|:------------|
| SageMaker | Machine Learning | Vertex AI | AI Services | Machine learning platform service |
| Rekognition | Computer Vision | Vision AI | Vision | Image/video analysis service |
| Comprehend | Text Analytics | Natural Language | Language | Natural language processing service |
| Polly | Cognitive Speech | Text-to-Speech | Speech | Text-to-speech service |
| Lex | Bot Service | Dialogflow | Digital Assistant | Conversational AI service |
| Forecast | Forecasting | -- | -- | Time series forecasting service |
| Personalize | Personalizer | Recommendations AI | -- | Recommendation engine service |
| Textract | Form Recognizer | Document AI | Vision | Document processing service |

### 7. Analytics Services
| AWS | Azure | GCP | OCI | Description |
|:---------|:----------|:---------|:---------|:------------|
| EMR | HDInsight | Dataproc | Data Flow | Managed Hadoop service |
| Kinesis | Event Hubs | Pub/Sub | Streaming | Real-time streaming service |
| Athena | Data Lake Analytics | BigQuery | Data Flow | Serverless query service |
| QuickSight | Power BI | Looker | Analytics Cloud | Business intelligence service |
| Glue | Data Factory | Cloud Data Fusion | Data Integration | Data integration service |
| Lake Formation | Data Lake Storage | Cloud Storage | Data Lake | Data lake service |
| OpenSearch | OpenSearch | -- | Search Service | Search and analytics service |
| MSK | Event Hubs | Pub/Sub | Streaming | Managed Kafka service |

### 8. Management and Monitoring
| AWS | Azure | GCP | OCI | Description |
|:---------|:----------|:---------|:---------|:------------|
| CloudWatch | Monitor | Cloud Monitoring | Monitoring | Resource monitoring service |
| CloudTrail | Activity Log | Audit Logs | Audit | Audit logging service |
| Systems Manager | Automation | Cloud Operations | Management Agent | Resource management service |
| Organizations | Management Groups | Resource Manager | Compartments | Multi-account management service |
| CloudFormation | Resource Manager | Deployment Manager | Resource Manager | Infrastructure as code service |
| Service Health | Service Health | Status Dashboard | Health Checks | Service health monitoring |
| Trusted Advisor | Advisor | Security Health | Cloud Guard | Best practices analysis service |
| Control Tower | Landing Zones | Deployment Manager | Landing Zones | Account governance service |

### 9. Developer Tools
| AWS | Azure | GCP | OCI | Description |
|:---------|:----------|:---------|:---------|:------------|
| CodeCommit | DevOps | Cloud Source | DevOps | Source control service |
| CodeBuild | Pipelines | Cloud Build | Build | CI/CD build service |
| CodeDeploy | DevOps | Cloud Deploy | Deployment | Application deployment service |
| CodePipeline | DevOps | Cloud Build | DevOps | CI/CD pipeline service |
| Cloud9 | DevOps | Cloud Shell | Cloud Shell | Cloud IDE service |
| X-Ray | Application Insights | Cloud Trace | Application Performance | Application tracing service |
| CodeArtifact | Artifacts | Artifact Registry | Container Registry | Artifact management service |
| Cloud Development Kit | Developer CLI | Cloud Code | Resource Manager | Infrastructure SDK service |

## Key Differentiators

### AWS
- Largest service portfolio
- Most mature market presence
- Extensive global infrastructure
- Leading in serverless offerings
- Strongest container ecosystem
- Most availability zones

### Azure
- Deep Microsoft integration
- Strong hybrid capabilities
- Enterprise-focused with Entra ID integration
- Best .NET integration
- Strong government cloud presence
- Extensive compliance certifications

### GCP
- Leading AI/ML capabilities
- Open source friendly
- Superior network performance
- Best-in-class data analytics
- Strong Kubernetes heritage
- Global fiber network

### OCI
- Oracle workload optimization
- Predictable pricing
- Bare metal performance
- Strong enterprise SLAs
- Best Oracle Database performance
- Strong data sovereignty features

## Important Service Naming Notes
- Azure Active Directory (Azure AD) was rebranded to Microsoft Entra ID in 2023
- GCP was formerly known as Google Cloud Platform
- OCI was formerly known as Oracle Cloud Infrastructure
- AWS Elastic Container Service is abbreviated as ECS
- Azure Kubernetes Service is abbreviated as AKS
- Google Kubernetes Engine is abbreviated as GKE

---
*Remember to check official documentation for the most up-to-date information as cloud services evolve rapidly.*