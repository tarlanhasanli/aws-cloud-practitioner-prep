# Keywords to Answers (CLF-C02)

Use this as a rapid association table before practice tests.

## Keyword -> Service Mapping
| Keyword / Phrase | Most Likely Answer |
|---|---|
| `DDoS protection` | AWS Shield |
| `SQL injection` | AWS WAF |
| `XSS filtering` | AWS WAF |
| `API call history` | AWS CloudTrail |
| `metrics and alarms` | Amazon CloudWatch |
| `configuration history` | AWS Config |
| `compliance reports (SOC/PCI/ISO)` | AWS Artifact |
| `temporary credentials` | AWS Security Token Service (AWS STS) |
| `least privilege access` | IAM policies and roles |
| `multi-account governance` | AWS Organizations |
| `permission boundary across org` | Service Control Policies (SCPs) |
| `threat detection` | Amazon GuardDuty |
| `sensitive data in S3` | Amazon Macie |
| `vulnerability scanning` | Amazon Inspector |
| `manage encryption keys` | AWS KMS |
| `serverless compute` | AWS Lambda |
| `virtual machines` | Amazon EC2 |
| `managed Kubernetes` | Amazon EKS |
| `AWS-native container orchestration` | Amazon ECS |
| `shared queue / decouple services` | Amazon SQS |
| `pub/sub fan-out` | Amazon SNS |
| `event bus` | Amazon EventBridge |
| `orchestration of steps` | AWS Step Functions |
| `object storage` | Amazon S3 |
| `block storage for EC2` | Amazon EBS |
| `shared file storage` | Amazon EFS |
| `relational managed database` | Amazon RDS |
| `NoSQL key-value at scale` | Amazon DynamoDB |
| `DNS service` | Amazon Route 53 |
| `CDN and edge caching` | Amazon CloudFront |
| `isolated network` | Amazon VPC |
| `private subnet outbound internet` | NAT Gateway |
| `on-prem encrypted tunnel` | Site-to-Site VPN |
| `dedicated private connectivity` | AWS Direct Connect |
| `infrastructure as code` | AWS CloudFormation |
| `cost analysis and trends` | AWS Cost Explorer |
| `budget alerts` | AWS Budgets |
| `unexpected spend spike` | Cost Anomaly Detection |
| `rightsizing recommendation` | AWS Compute Optimizer |
| `best-practice checks` | AWS Trusted Advisor |
| `discount with commitment` | Savings Plans / Reserved Instances |
| `interruptible discounted compute` | Spot Instances |
| `technical account manager` | Enterprise Support |

## Quick Scenario Examples

### Scenario 1
A team needs a complete record of who deleted an IAM policy yesterday.
- Best answer: **AWS CloudTrail**
- Why: AWS CloudTrail captures API management activity for auditing and forensics.

### Scenario 2
A company must block SQL injection attempts on a public web app.
- Best answer: **AWS WAF**
- Why: WAF inspects and filters Layer 7 web requests using rules.

### Scenario 3
A startup wants lowest-cost compute for fault-tolerant nightly batch jobs.
- Best answer: **Spot Instances**
- Why: Spot offers deep discounts with interruption risk that batch jobs can tolerate.

### Scenario 4
An application needs a shared Linux file system mounted by multiple EC2 instances.
- Best answer: **Amazon EFS**
- Why: EFS is a managed, shared NFS file system.

### Scenario 5
Leadership asks for current month spend trends and forecasted AWS cost.
- Best answer: **AWS Cost Explorer**
- Why: Cost Explorer provides usage/spend visualization and forecasting.
