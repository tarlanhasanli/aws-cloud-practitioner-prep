# Full Mock Exam 1 (65 Questions)

## Q1
A startup wants to launch quickly without buying physical servers. Which cloud financial model benefit is most relevant?

A. Fixed annual pricing  
B. Trade CAPEX for OPEX  
C. Dedicated tenancy  
D. Upfront reservation  

## Q2
An online retailer sees large and unpredictable traffic spikes during promotions. Which cloud concept best addresses this?

A. Elasticity  
B. Data sovereignty  
C. Dedicated hosts  
D. Manual scaling only  

## Q3
A critical app must remain available if one Availability Zone fails. Which design is best?

A. Single AZ with larger instances  
B. Multi-AZ deployment  
C. One Region only, one subnet  
D. Reserved pricing model  

## Q4
A company migrates an application to AWS with no major code changes. Which migration strategy is this?

A. Refactor  
B. Replatform  
C. Rehost  
D. Retire  

## Q5
A business decides to stop using its old CRM and adopt a SaaS CRM platform. Which migration strategy applies?

A. Rehost  
B. Repurchase  
C. Relocate  
D. Refactor  

## Q6
Which AWS Well-Architected pillar focuses on automatic recovery and fault tolerance?

A. Security  
B. Reliability  
C. Sustainability  
D. Cost Optimization  

## Q7
In AWS CAF, which perspective is focused on risk, policy, and compliance alignment?

A. People  
B. Governance  
C. Operations  
D. Business  

## Q8
A dev team can create complete test environments in minutes and delete them after use. Which cloud advantage is shown?

A. Hardware ownership  
B. Agility and on-demand self-service  
C. Long procurement cycles  
D. Manual datacenter scaling  

## Q9
A company requires continuity if an entire Region goes offline. What architecture is required?

A. Multi-AZ only  
B. Multi-Region  
C. Single VPC with more subnets  
D. Single NAT gateway  

## Q10
Who is responsible for patching the guest operating system on Amazon EC2?

A. AWS  
B. Customer  
C. Shared equally always  
D. AWS Support  

## Q11
Which cloud benefit allows teams to focus more on product features rather than running infrastructure?

A. Data residency  
B. Reduced undifferentiated heavy lifting  
C. Contract lock-in  
D. Fixed capacity planning  

## Q12
Which term means a system can increase capacity to handle higher demand?

A. Encryption  
B. Scalability  
C. Durability  
D. Traceability  

## Q13
A company uses a CDN to cache content globally closer to end users. Which AWS service is most likely used?

A. Amazon Route 53  
B. Amazon CloudFront  
C. Amazon VPC  
D. AWS Direct Connect  

## Q14
A team moves to AWS and makes limited optimizations such as moving to a managed database, but does not redesign the app. Which strategy is this?

A. Replatform  
B. Refactor  
C. Rehost  
D. Retain  

## Q15
Which pricing principle means customers pay only for consumed resources?

A. Fixed monthly fee  
B. Consumption-based pricing  
C. Datacenter amortization  
D. Enterprise-only discounts  

## Q16
Which account security action is strongly recommended for the AWS root user?

A. Create API keys for automation  
B. Enable MFA  
C. Share credentials with admins  
D. Use root for daily operations  

## Q17
An auditor asks who modified a security group yesterday. Which service should be checked?

A. Amazon CloudWatch  
B. AWS CloudTrail  
C. AWS Config  
D. AWS Budgets  

## Q18
A compliance team needs AWS SOC and PCI reports. Which service provides them?

A. AWS Artifact  
B. AWS Config  
C. Amazon Inspector  
D. AWS Shield  

## Q19
A web app must block SQL injection attempts. Which service should be used?

A. AWS Shield  
B. AWS WAF  
C. Amazon GuardDuty  
D. AWS CloudTrail  

## Q20
A company wants managed protection against DDoS attacks. Which service is the direct fit?

A. Amazon Macie  
B. AWS Shield  
C. AWS Config  
D. Amazon Inspector  

## Q21
Which service discovers sensitive data (for example PII) stored in Amazon S3?

A. Amazon Macie  
B. Amazon GuardDuty  
C. AWS Artifact  
D. AWS WAF  

## Q22
Which service analyzes account/workload activity to detect suspicious behavior and threats?

A. AWS CloudTrail  
B. Amazon GuardDuty  
C. AWS Config  
D. AWS KMS  

## Q23
A team needs vulnerability findings for compute workloads. Which service is best?

A. Amazon Inspector  
B. Amazon Route 53  
C. AWS Shield  
D. AWS Organizations  

## Q24
Which service can evaluate whether resources comply with a rule like "EBS volumes must be encrypted"?

A. AWS Config  
B. AWS Artifact  
C. Amazon CloudWatch  
D. AWS STS  

## Q25
Which AWS feature sets maximum permission boundaries across accounts in an organization?

A. IAM user policies  
B. Resource tags  
C. Service Control Policies (SCPs)  
D. Security groups  

## Q26
A developer in Account A needs temporary access to resources in Account B. Which is best practice?

A. Share root account credentials  
B. Assume an IAM role using AWS STS  
C. Create long-term keys in Account B and email them  
D. Use a Network ACL  

## Q27
Which statement about security groups is correct?

A. They are stateless and subnet-level  
B. They are stateful and instance-level  
C. They support explicit deny rules  
D. They replace IAM authorization  

## Q28
If an IAM policy explicitly denies an action, what is the result?

A. Action allowed if another policy allows it  
B. Action denied  
C. Action depends on Region  
D. Action requires AWS Support approval  

## Q29
Who secures the physical AWS data centers under shared responsibility?

A. Customer  
B. AWS  
C. Customer and AWS equally by contract  
D. AWS Partner Network vendors  

## Q30
Who is responsible for configuring Amazon S3 bucket permissions?

A. AWS  
B. Customer  
C. AWS Support  
D. Third-party assessor  

## Q31
Which service is used to create and manage encryption keys?

A. AWS KMS  
B. AWS Artifact  
C. AWS Config  
D. Amazon SNS  

## Q32
Which service provides consolidated billing for multiple AWS accounts?

A. AWS Organizations  
B. AWS CloudFormation  
C. AWS IAM  
D. AWS Direct Connect  

## Q33
A security team needs centralized AWS WAF policy management across many accounts. Which service helps?

A. AWS Firewall Manager  
B. AWS CloudTrail  
C. Amazon GuardDuty  
D. AWS Billing Conductor  

## Q34
A team needs alerts when CPU utilization exceeds 80%. Which service should trigger the alarm?

A. AWS CloudTrail  
B. Amazon CloudWatch  
C. AWS Artifact  
D. AWS Config  

## Q35
Which IAM approach follows security best practice?

A. Grant AdministratorAccess to all users  
B. Share one IAM user among developers  
C. Grant least privilege permissions  
D. Use only the root user  

## Q36
Which service should be used for full operating-system-level control of virtual machines?

A. AWS Lambda  
B. Amazon ECS  
C. Amazon EC2  
D. Amazon EventBridge  

## Q37
Which service is best for running code in response to an S3 object upload event?

A. Amazon EC2  
B. AWS Lambda  
C. AWS Direct Connect  
D. Amazon RDS  

## Q38
A platform team requires Kubernetes APIs and tooling. Which AWS compute service should they choose?

A. Amazon ECS  
B. Amazon EKS  
C. AWS Elastic Beanstalk  
D. AWS Batch  

## Q39
An application needs a durable queue to decouple producers and consumers. Which service is best?

A. Amazon SNS  
B. Amazon SQS  
C. Amazon EFS  
D. AWS Step Functions  

## Q40
A service must push notifications to multiple subscribers simultaneously. Which service is best?

A. Amazon SNS  
B. Amazon SQS  
C. AWS WAF  
D. Amazon EC2 Auto Scaling  

## Q41
Which service acts as an event bus for routing events to targets?

A. Amazon EventBridge  
B. Amazon Kinesis Video Streams  
C. AWS CloudFormation  
D. Amazon EBS  

## Q42
A company needs a managed relational database with automated backups. Which service fits?

A. Amazon DynamoDB  
B. Amazon RDS  
C. Amazon S3  
D. Amazon Redshift Spectrum  

## Q43
Which managed database is best for high-scale key-value workloads?

A. Amazon RDS  
B. Amazon DynamoDB  
C. Amazon Aurora Serverless v2  
D. Amazon Redshift  

## Q44
Which Amazon RDS feature is used mainly to scale read traffic?

A. Multi-AZ deployment  
B. Read Replica  
C. Automatic minor version upgrade  
D. DB parameter groups  

## Q45
Which Amazon RDS option is mainly for high availability and failover?

A. Read Replica  
B. Multi-AZ deployment  
C. Database snapshots  
D. Provisioned IOPS  

## Q46
Which service provides a shared file system for multiple Linux EC2 instances?

A. Amazon EBS  
B. Amazon EFS  
C. Amazon S3 Glacier  
D. AWS Backup  

## Q47
Which storage service is typically used for EC2 root volumes?

A. Amazon S3  
B. Amazon EBS  
C. Amazon EFS  
D. AWS Storage Gateway  

## Q48
A company archives data for regulatory retention and rarely retrieves it. Which storage class is most suitable?

A. S3 Standard  
B. S3 Standard-IA  
C. S3 Glacier Deep Archive  
D. Amazon EBS st1  

## Q49
Which AWS service provides DNS management?

A. Amazon Route 53  
B. Amazon CloudFront  
C. AWS Transit Gateway  
D. AWS Global Accelerator only  

## Q50
Which service improves global delivery performance by caching content at edge locations?

A. Amazon CloudWatch  
B. Amazon CloudFront  
C. AWS Config  
D. Amazon VPC  

## Q51
A private subnet needs outbound internet access while remaining non-public. Which component is required?

A. Internet Gateway  
B. NAT Gateway  
C. VPC endpoint only  
D. Route 53 Resolver  

## Q52
Which service provides a dedicated private connection from on-premises to AWS?

A. Site-to-Site VPN  
B. AWS Direct Connect  
C. Amazon Route 53  
D. AWS Shield  

## Q53
Which connectivity option uses an encrypted tunnel over the public internet?

A. AWS Direct Connect  
B. Site-to-Site VPN  
C. VPC Peering  
D. Transit Gateway peering  

## Q54
Which load balancer supports host-based and path-based routing?

A. Network Load Balancer  
B. Application Load Balancer  
C. Gateway Load Balancer  
D. Classic Load Balancer only  

## Q55
Which load balancer is best for ultra-high performance TCP/UDP workloads?

A. Application Load Balancer  
B. Network Load Balancer  
C. Route 53 health checks  
D. CloudFront origin groups  

## Q56
Which service allows infrastructure provisioning from declarative templates?

A. AWS CloudFormation  
B. Amazon CloudWatch  
C. AWS CloudTrail  
D. AWS Budgets  

## Q57
Which service helps present virtual tape libraries for on-premises backup software while storing data in AWS?

A. AWS Storage Gateway  
B. Amazon EFS  
C. AWS Snowcone  
D. AWS Lambda  

## Q58
A new workload is unpredictable and the team wants maximum flexibility with no commitment. Which pricing option fits?

A. Reserved Instances  
B. Savings Plans  
C. On-Demand  
D. Dedicated Hosts  

## Q59
A steady workload runs continuously and the team wants lower cost with commitment flexibility. Which model is best?

A. Spot Instances  
B. Savings Plans  
C. On-Demand only  
D. Free Tier  

## Q60
Which pricing model offers the deepest discount for interruptible compute capacity?

A. On-Demand  
B. Spot Instances  
C. Dedicated Instances  
D. Savings Plans  

## Q61
Which AWS tool is best for visualizing historical spend and forecasting cost trends?

A. AWS Cost Explorer  
B. AWS Artifact  
C. Amazon GuardDuty  
D. AWS WAF  

## Q62
Which service should be configured for budget threshold and forecasted cost alerts?

A. AWS Budgets  
B. AWS Config  
C. Amazon CloudFront  
D. AWS KMS  

## Q63
Which AWS service identifies unusual or unexpected spend spikes?

A. AWS Trusted Advisor  
B. Cost Anomaly Detection  
C. AWS Organizations  
D. Amazon Inspector  

## Q64
Which support plan includes a Technical Account Manager?

A. Basic  
B. Developer  
C. Business  
D. Enterprise  

## Q65
Which minimum support plan unlocks full Trusted Advisor checks?

A. Basic  
B. Developer  
C. Business  
D. No paid plan is needed  
