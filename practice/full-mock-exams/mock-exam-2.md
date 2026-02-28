# Full Mock Exam 2 (65 Questions)

## Q1
A company wants to stop purchasing servers every 4 years and instead pay only for resources consumed each month. Which cloud economics model is this?

A. Capital expenditure model  
B. Consumption-based OPEX model  
C. Hardware depreciation model  
D. Dedicated host subscription model  

## Q2
A platform is designed to handle annual growth from 1,000 to 100,000 users over time. Which concept is primarily being described?

A. Elasticity  
B. Scalability  
C. Durability  
D. Fault isolation  

## Q3
A global application needs low-latency content delivery close to users in multiple countries. Which AWS service is most appropriate?

A. AWS Direct Connect  
B. Amazon CloudFront  
C. Amazon VPC  
D. AWS Config  

## Q4
An enterprise redesigns an existing app into microservices and serverless components during migration. Which strategy is this?

A. Rehost  
B. Replatform  
C. Refactor  
D. Repurchase  

## Q5
A company keeps a legacy system on-premises for regulatory reasons while migrating other workloads. Which migration decision is this?

A. Retire  
B. Retain  
C. Rehost  
D. Replatform  

## Q6
In AWS CAF, which perspective focuses on defining business outcomes and value realization?

A. Security  
B. Operations  
C. Business  
D. Platform  

## Q7
Which AWS Well-Architected pillar focuses on identity, traceability, and data protection?

A. Security  
B. Reliability  
C. Operational Excellence  
D. Performance Efficiency  

## Q8
An organization chooses managed services to reduce operational overhead and resource waste. Which Well-Architected pillar is most directly improved?

A. Sustainability  
B. Reliability  
C. Governance  
D. Performance  

## Q9
Which design improves workload availability when one data center in a Region fails?

A. Multi-AZ architecture  
B. Multi-account architecture  
C. Dedicated host purchasing  
D. Spot-only compute  

## Q10
A team migrates to AWS and changes the database engine to a managed service but keeps core application design. Which strategy is this?

A. Refactor  
B. Replatform  
C. Rehost  
D. Retire  

## Q11
Which statement best describes cloud economies of scale?

A. Each customer negotiates hardware costs independently  
B. AWS spreads costs across large aggregate demand to reduce unit cost  
C. Costs increase as more customers join AWS  
D. Only large enterprises can benefit  

## Q12
Who is responsible for deciding and configuring encryption settings for customer data in AWS services?

A. AWS only  
B. Customer  
C. Third-party auditor  
D. AWS Support  

## Q13
Who handles infrastructure and managed database engine patching for Amazon RDS?

A. Customer  
B. AWS  
C. Shared equally at all layers  
D. AWS Marketplace seller  

## Q14
A team creates and tears down development environments in minutes for rapid testing. Which cloud advantage is this?

A. Agility  
B. Dedicated tenancy  
C. Fixed asset utilization  
D. Capacity lock-in  

## Q15
Which cloud trait is shown when resources are provisioned by users without opening IT procurement tickets?

A. Shared fate  
B. On-demand self-service  
C. Long-term reservation  
D. Host affinity  

## Q16
An EC2 workload needs access to DynamoDB without embedding static credentials in code. What is the best approach?

A. Store root credentials in environment variables  
B. Attach an IAM role to the EC2 instance  
C. Use account password authentication  
D. Use a Network ACL  

## Q17
Which service issues temporary security credentials when assuming an IAM role?

A. AWS Artifact  
B. AWS STS  
C. AWS Config  
D. AWS WAF  

## Q18
Which control helps prevent accidental public exposure of Amazon S3 data at scale?

A. S3 Transfer Acceleration  
B. S3 Block Public Access  
C. S3 Intelligent-Tiering  
D. S3 Object Lambda  

## Q19
Which security action should be enabled for privileged IAM users in addition to strong passwords?

A. Use long-term access keys only  
B. Disable policy evaluation  
C. Multi-factor authentication (MFA)  
D. Reuse shared credentials  

## Q20
Which service is best for determining which principal made a specific API call?

A. Amazon CloudWatch  
B. AWS CloudTrail  
C. AWS Trusted Advisor  
D. Amazon Macie  

## Q21
A team needs to trigger alarms based on memory or CPU thresholds. Which service should they use?

A. AWS CloudTrail  
B. Amazon CloudWatch  
C. AWS Artifact  
D. AWS Organizations  

## Q22
Which service tracks resource configuration drift and evaluates compliance rules?

A. Amazon GuardDuty  
B. AWS Config  
C. Amazon SNS  
D. AWS Direct Connect  

## Q23
Where can auditors download AWS compliance reports and certifications?

A. AWS Artifact  
B. Amazon Inspector  
C. AWS Shield  
D. AWS Budgets  

## Q24
A company asks for native managed DDoS protection for internet-facing resources. Which service is correct?

A. AWS WAF  
B. AWS Shield  
C. Amazon Macie  
D. AWS Config  

## Q25
A web team needs rule-based filtering for malicious HTTP request patterns such as XSS. Which service is best?

A. AWS WAF  
B. Amazon GuardDuty  
C. AWS Artifact  
D. Amazon Inspector  

## Q26
Which service detects suspicious account activity using threat intelligence and machine learning?

A. Amazon GuardDuty  
B. AWS CloudFormation  
C. AWS Cost Explorer  
D. Amazon Route 53  

## Q27
Which service scans workloads for vulnerabilities and unintended network exposure?

A. Amazon Inspector  
B. AWS KMS  
C. AWS Shield  
D. AWS Budgets  

## Q28
Which service discovers and classifies sensitive data in Amazon S3?

A. Amazon Macie  
B. AWS Config  
C. AWS CloudTrail  
D. AWS STS  

## Q29
What is the main purpose of Service Control Policies in AWS Organizations?

A. Grant permissions directly to users  
B. Set maximum permission boundaries for member accounts  
C. Encrypt data at rest  
D. Configure subnet route tables  

## Q30
What is the effect of an explicit deny in IAM policy evaluation?

A. Ignored if a broader allow exists  
B. Overrides all allows  
C. Evaluated only in us-east-1  
D. Requires support case confirmation  

## Q31
Which service enables centralized account management and consolidated billing?

A. AWS Organizations  
B. AWS Identity and Access Management (IAM)  
C. Amazon VPC  
D. AWS CloudTrail  

## Q32
Which service manages encryption keys for AWS-integrated encryption?

A. AWS KMS  
B. Amazon CloudFront  
C. AWS WAF  
D. Amazon SQS  

## Q33
Which network security control is stateless and can explicitly allow or deny traffic at subnet level?

A. Security group  
B. Network ACL  
C. IAM role  
D. Route table  

## Q34
Which service helps enforce centralized WAF and Shield policies across multiple accounts?

A. AWS Firewall Manager  
B. AWS Artifact  
C. AWS Cost Explorer  
D. Amazon Macie  

## Q35
A security engineer wants to identify external access granted to resources from outside the account. Which IAM-related service helps with this analysis?

A. IAM Access Analyzer  
B. AWS Budgets  
C. Amazon CloudWatch Synthetics  
D. AWS Pricing Calculator  

## Q36
A legacy application requires custom kernel modules and full OS control. Which compute service should be used?

A. AWS Lambda  
B. Amazon EC2  
C. AWS Fargate  
D. Amazon S3  

## Q37
A team wants to run containers without managing EC2 worker nodes. Which option best fits?

A. Amazon ECS on EC2 only  
B. AWS Fargate  
C. Amazon EKS managed node groups only  
D. Amazon RDS  

## Q38
A team wants AWS-native container orchestration without Kubernetes complexity. Which service should they choose?

A. Amazon ECS  
B. Amazon EKS  
C. AWS Lambda  
D. AWS Batch  

## Q39
Which service is a managed Kubernetes control plane on AWS?

A. Amazon ECS  
B. Amazon EKS  
C. Elastic Load Balancing  
D. AWS Fargate  

## Q40
Which service helps deploy web applications quickly while AWS handles much of the underlying environment management?

A. AWS Elastic Beanstalk  
B. Amazon EC2 Auto Scaling  
C. AWS CloudTrail  
D. AWS KMS  

## Q41
Which load balancer supports content-based routing for HTTP/HTTPS requests?

A. Network Load Balancer  
B. Application Load Balancer  
C. Gateway Load Balancer  
D. Route 53 only  

## Q42
Which feature automatically adds or removes EC2 instances based on demand and policies?

A. AWS CloudFormation  
B. Auto Scaling  
C. Amazon SQS  
D. AWS Artifact  

## Q43
Which storage option is persistent block storage attached to EC2?

A. Amazon S3  
B. Amazon EBS  
C. Amazon EFS  
D. AWS Storage Gateway  

## Q44
Which EC2 storage type is ephemeral and lost when the instance stops or terminates?

A. Amazon EBS  
B. Instance store  
C. Amazon EFS  
D. Amazon S3 Glacier  

## Q45
Which service provides shared managed file storage for Linux-based workloads?

A. Amazon EFS  
B. Amazon EBS  
C. Amazon S3  
D. AWS DataSync  

## Q46
Which service is object storage designed for durability and scale?

A. Amazon EBS  
B. Amazon S3  
C. Amazon EFS  
D. Amazon FSx for Lustre  

## Q47
Which Amazon S3 feature can automatically move objects to lower-cost storage classes over time?

A. Bucket ACLs  
B. Lifecycle policies  
C. Cross-account roles  
D. IAM permission boundaries  

## Q48
Which service is a managed relational database offering?

A. Amazon RDS  
B. Amazon DynamoDB  
C. Amazon S3  
D. Amazon SNS  

## Q49
Which service is best for key-value NoSQL workloads with very high request rates?

A. Amazon Redshift  
B. Amazon DynamoDB  
C. Amazon Aurora PostgreSQL  
D. Amazon RDS for Oracle  

## Q50
Which managed relational engine family is designed for high performance and MySQL/PostgreSQL compatibility?

A. Amazon Aurora  
B. Amazon DynamoDB  
C. Amazon Neptune  
D. Amazon DocumentDB  

## Q51
Which service is purpose-built for petabyte-scale analytics and data warehousing?

A. Amazon Redshift  
B. Amazon RDS  
C. Amazon DynamoDB  
D. Amazon ElastiCache  

## Q52
Which Route 53 capability directs traffic away from unhealthy endpoints?

A. Reserved pricing  
B. Health checks with failover routing  
C. Spot fleet rebalance  
D. IAM role chaining  

## Q53
Which statement about VPC peering is correct?

A. It supports automatic transitive routing across all peered VPCs  
B. It is non-transitive  
C. It replaces route tables  
D. It is only for on-premises connections  

## Q54
A company needs a central hub to connect many VPCs across accounts. Which service is most suitable?

A. VPC peering only  
B. AWS Transit Gateway  
C. Internet Gateway  
D. NAT Gateway  

## Q55
Which option provides dedicated private connectivity from a data center to AWS?

A. Site-to-Site VPN  
B. AWS Direct Connect  
C. VPC endpoint  
D. Internet Gateway  

## Q56
Which option provides encrypted hybrid connectivity over the public internet?

A. AWS Direct Connect  
B. Site-to-Site VPN  
C. Transit Gateway Connect only  
D. Route table propagation  

## Q57
Which service deploys and manages AWS infrastructure using templates?

A. AWS CloudFormation  
B. AWS CloudTrail  
C. Amazon CloudWatch  
D. AWS Shield  

## Q58
A workload runs sporadically and has uncertain future usage. Which pricing model should be chosen first?

A. On-Demand  
B. Reserved Instances  
C. Savings Plans  
D. Dedicated Hosts  

## Q59
A stable workload is expected to run for years on specific instance attributes. Which discount model is commonly considered?

A. Spot only  
B. Reserved Instances  
C. Free Tier  
D. On-Demand only  

## Q60
A team wants commitment discounts that can apply more flexibly across compute usage. Which option is best?

A. Savings Plans  
B. Dedicated Instances  
C. Spot blocks  
D. Capacity Reservations only  

## Q61
Which compute option may be interrupted by AWS but often has the lowest cost?

A. On-Demand  
B. Spot Instances  
C. Reserved Instances  
D. Dedicated Hosts  

## Q62
Which tool should be used to estimate cloud cost before building an architecture?

A. AWS Pricing Calculator  
B. AWS Budgets  
C. AWS Trusted Advisor  
D. AWS Config  

## Q63
Which tool can notify teams when actual or forecasted spend exceeds thresholds?

A. AWS Budgets  
B. AWS Artifact  
C. Amazon Macie  
D. AWS KMS  

## Q64
Which tool is best for detailed spend trend analysis and forecasting by service?

A. AWS Cost Explorer  
B. AWS Shield  
C. AWS WAF  
D. AWS CloudTrail  

## Q65
A production team needs 24x7 technical support with phone/chat access but does not require a TAM. Which support plan is the minimum fit?

A. Basic  
B. Developer  
C. Business  
D. Enterprise  
