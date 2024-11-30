# Cloud Platform Guide

<!-- Repository Badges -->
[![Last Updated](https://img.shields.io/badge/Last%20Updated-April%202024-blue)](https://github.com/yourusername/cloud-platform-guide)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)
[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](LICENSE)

<div align="center">

![Cloud Platform Comparison](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA4MDAgMjAwIj48cmVjdCB3aWR0aD0iODAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0iI2Y2ZjhmYSIvPjxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDUwLDYwKSI+PHBhdGggZD0iTSAwLDQwIEMgMCwxNy45IDE3LjksMCA0MCwwIEggMTQwIEMgMTYyLjEsMCAxODAsMTcuOSAxODAsNDAgQyAxODAsNjIuMSAxNjIuMSw4MCAxNDAsODAgSCA0MCBDIDE3LjksODAgMCw2Mi4xIDAsNDAiIGZpbGw9IiNGRjk5MDAiLz48cGF0aCBkPSJNIDIwMCw0MCBDIDIwMCwxNy45IDIxNy45LDAgMjQwLDAgSCAzNDAgQyAzNjIuMSwwIDM4MCwxNy45IDM4MCw0MCBDIDM4MCw2Mi4xIDM2Mi4xLDgwIDM0MCw4MCBIIDI0MCBDIDI3LjksODAgMjAwLDYyLjEgMjAwLDQwIiBmaWxsPSIjMDA4OUQ2Ii8+PHBhdGggZD0iTSA0MDAsNDAgQyA0MDAsMTcuOSA0MTcuOSwwIDQ0MCwwIEggNTQwIEMgNTYyLjEsMCA1ODAsMTcuOSA1ODAsNDAgQyA1ODAsNjIuMSA1NjIuMSw4MCA1NDAsODAgSCA0NDAgQyA0MTcuOSw4MCA0MDAsNjIuMSA0MDAsNDAiIGZpbGw9IiMzNEE4NTMiLz48cGF0aCBkPSJNIDYwMCw0MCBDIDYwMCwxNy45IDYxNy45LDAgNjQwLDAgSCA3NDAgQyA3NjIuMSwwIDc4MCwxNy45IDc4MCw0MCBDIDY4MCw2Mi4xIDc2Mi4xLDgwIDc0MCw4MCBIIDc0MCBDIDY5Ny45LDgwIDYwMCw2Mi4xIDYwMCw0MCIgZmlsbD0iI0M3NDYzNCIvPjwvZz48dGV4dCB4PSI0MDAiIHk9IjE4MCIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZm9udC1mYW1pbHk9IkFyaWFsLCBzYW5zLXNlcmlmIiBmb250LXNpemU9IjI0IiBmb250LXdlaWdodD0iYm9sZCIgZmlsbD0iIzI0MjkyZSI+Q2xvdWQgUGxhdGZvcm0gQ29tcGFyaXNvbiBHdWlkZTwvdGV4dD48L3N2Zz4=)

</div>

*A cross-reference guide for AWS, Azure, GCP, and OCI services*

📚 [Services](#service-comparison) | 
📊 [Market Position](#market-position-as-of-april-2024) | 
💡 [Differentiators](#key-differentiators) | 
🤝 [Contributing](CONTRIBUTING.md)

## Version History
| Version | Date | Changes |
|---------|------|---------|
| 1.0 | April 2024 | - Initial release with AWS, Azure, GCP, and OCI comparison |
|     |            | - Added market share data and key differentiators |
|     |            | - Included unique strengths for each platform |

## Disclaimer
This guide represents cloud services as of April 2024. Cloud providers continuously evolve their offerings. Please:
- Refer to official documentation for the most current information
- Check provider websites for latest service availability
- Consider this a reference point rather than current state
- Submit issues or pull requests for updates

## Market Position (as of April 2024)
- AWS: Market leader in public cloud, strongest enterprise presence
- Azure: Second largest provider, strong Microsoft ecosystem integration
- GCP: Growing rapidly, particularly strong in AI/ML and analytics
- OCI: Emerging provider, particularly strong for Oracle workloads

## Service Comparison

### Compute Services
| AWS | Azure | GCP | OCI | Description |
|-----|--------|-----|-----|-------------|
| EC2 | Virtual Machines | Compute Engine | Compute | Core IaaS computing |
| Elastic Beanstalk | App Service | App Engine | Container Engine | PaaS application hosting |
| Lambda | Azure Functions | Cloud Functions | Functions | Serverless computing |
| ECS | Container Instances | Cloud Run | Container Engine | Container orchestration |
| EKS | AKS | GKE | Container Engine for Kubernetes | Managed Kubernetes |
| Lightsail | App Service | Cloud Run | Compute | Simplified compute |
| EC2 Auto Scaling | VM Scale Sets | Instance Groups | Autoscaling | Auto-scaling service |
| EC2 Spot | Spot VMs | Preemptible VMs | Preemptible | Low-cost compute |
| Batch | Batch | Batch | Pipeline | Batch computing |
| Outposts | Azure Stack | Anthos | Dedicated Region | On-premises cloud |

### Storage Services
| AWS | Azure | GCP | OCI | Description |
|-----|--------|-----|-----|-------------|
| S3 | Blob Storage | Cloud Storage | Object Storage | Object storage |
| EBS | Managed Disks | Persistent Disk | Block Volume | Block storage |
| EFS | Azure Files | Filestore | File Storage | File storage |
| Storage Gateway | StorSimple | Storage Transfer | Storage Gateway | Hybrid storage |
| S3 Glacier | Archive Storage | Archive Storage | Archive Storage | Cold storage |
| Backup | Backup | Cloud Backup | Backup | Backup service |
| Snow Family | Data Box | Transfer Appliance | Data Transfer | Data transfer |
| FSx | NetApp Files | NetApp Cloud | File Storage | File system service |
| S3 One Zone | Cool Storage | Nearline Storage | Standard Storage | Infrequent access |

### Database Services
| AWS | Azure | GCP | OCI | Description |
|-----|--------|-----|-----|-------------|
| RDS | Azure SQL Database | Cloud SQL | Database | Managed RDBMS |
| DynamoDB | Cosmos DB | Firestore | NoSQL Database | NoSQL database |
| ElastiCache | Cache for Redis | Memorystore | Cache | In-memory cache |
| Redshift | Synapse Analytics | BigQuery | Data Warehouse | Data warehouse |
| Aurora | Azure SQL Database | Cloud Spanner | Database | Enterprise database |
| DocumentDB | Cosmos DB | Firestore | NoSQL Database | Document database |
| Neptune | Cosmos DB Graph | Not Available | Graph Studio | Graph database |
| Timestream | Time Series Insights | Not Available | Not Available | Time series database |
| Keyspaces | Table Storage | Bigtable | NoSQL Database | Wide column store |

### Networking Services
| AWS | Azure | GCP | OCI | Description |
|-----|--------|-----|-----|-------------|
| VPC | Virtual Network | VPC | Virtual Cloud Network | Private cloud network |
| Route 53 | Azure DNS | Cloud DNS | DNS | DNS service |
| CloudFront | CDN | Cloud CDN | CDN | Content delivery |
| Direct Connect | ExpressRoute | Cloud Interconnect | FastConnect | Dedicated connection |
| API Gateway | API Management | Cloud Endpoints | API Gateway | API management |
| ELB | Load Balancer | Cloud Load Balancing | Load Balancer | Load balancing |
| Transit Gateway | Virtual WAN | Cloud Router | DRG | Network hub |
| Global Accelerator | Front Door | Premium Tier | Not Available | Global routing |
| PrivateLink | Private Link | Private Service Connect | Service Gateway | Private connectivity |

### Security Services
| AWS | Azure | GCP | OCI | Description |
|-----|--------|-----|-----|-------------|
| IAM | Entra ID (formerly Azure AD) | Cloud IAM | Identity & Access | Identity management |
| KMS | Key Vault | Cloud KMS | Key Management | Key management |
| Shield | DDoS Protection | Cloud Armor | WAF | DDoS protection |
| WAF | WAF | Cloud Armor | WAF | Web app firewall |
| Security Hub | Security Center | Security Command | Cloud Guard | Security management |
| GuardDuty | Defender | Threat Detection | Cloud Guard | Threat detection |
| Macie | Information Protection | DLP API | Cloud Guard | Data protection |
| Certificate Manager | App Gateway | Certificate Authority | Certificates | Certificate service |

### AI and Machine Learning
| AWS | Azure | GCP | OCI | Description |
|-----|--------|-----|-----|-------------|
| SageMaker | Machine Learning | Vertex AI | AI Services | ML platform |
| Rekognition | Computer Vision | Vision AI | Vision | Image/video analysis |
| Comprehend | Text Analytics | Natural Language | Language | NLP service |
| Polly | Cognitive Speech | Text-to-Speech | Speech | Text-to-speech |
| Lex | Bot Service | Dialogflow | Digital Assistant | Chatbot platform |
| Forecast | Forecasting | Not Available | Not Available | Time series forecasting |
| Personalize | Personalizer | Recommendations AI | Not Available | Recommendations |
| Textract | Form Recognizer | Document AI | Vision | Document processing |

### Analytics Services
| AWS | Azure | GCP | OCI | Description |
|-----|--------|-----|-----|-------------|
| EMR | HDInsight | Dataproc | Data Flow | Managed Hadoop |
| Kinesis | Event Hubs | Pub/Sub | Streaming | Data streaming |
| Athena | Data Lake Analytics | BigQuery | Data Flow | Serverless queries |
| QuickSight | Power BI | Looker | Analytics Cloud | Business intelligence |
| Glue | Data Factory | Cloud Data Fusion | Data Integration | ETL service |
| Lake Formation | Data Lake Storage | Cloud Storage | Data Lake | Data lake service |
| OpenSearch | OpenSearch | Not Available | Search Service | Search & analytics |
| MSK | Event Hubs | Pub/Sub | Streaming | Managed Kafka |

### Management and Monitoring
| AWS | Azure | GCP | OCI | Description |
|-----|--------|-----|-----|-------------|
| CloudWatch | Monitor | Cloud Monitoring | Monitoring | Monitoring service |
| CloudTrail | Activity Log | Audit Logs | Audit | Audit logging |
| Systems Manager | Automation | Cloud Operations | Management Agent | Resource management |
| Organizations | Management Groups | Resource Manager | Compartments | Multi-account mgmt |
| CloudFormation | Resource Manager | Deployment Manager | Resource Manager | Infrastructure as code |
| Service Health | Service Health | Status Dashboard | Health Checks | Health monitoring |
| Trusted Advisor | Advisor | Security Health | Cloud Guard | Best practices |
| Control Tower | Landing Zones | Deployment Manager | Landing Zones | Account governance |

### Developer Tools
| AWS | Azure | GCP | OCI | Description |
|-----|--------|-----|-----|-------------|
| CodeCommit | DevOps | Cloud Source | DevOps | Source control |
| CodeBuild | Pipelines | Cloud Build | Build | CI/CD pipeline |
| CodeDeploy | DevOps | Cloud Deploy | Deployment | Application deployment |
| CodePipeline | DevOps | Cloud Build | DevOps | Delivery pipeline |
| Cloud9 | DevOps | Cloud Shell | Cloud Shell | IDE |
| X-Ray | Application Insights | Cloud Trace | Application Performance | Tracing |
| CodeArtifact | Artifacts | Artifact Registry | Container Registry | Artifact management |
| Cloud Development Kit | Developer CLI | Cloud Code | Resource Manager | Infrastructure SDK |

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