# Common CLF-C02 Trick Questions (and Fast Decision Rules)

## 1) Amazon CloudWatch vs AWS CloudTrail vs AWS Config
- Confusion: "monitoring", "logging", and "compliance" overlap.
- Fast rule:
  - Need metrics/alarms/dashboards -> **Amazon CloudWatch**
  - Need API audit history (who did what) -> **AWS CloudTrail**
  - Need resource configuration timeline/compliance -> **AWS Config**

## 2) AWS WAF vs AWS Shield
- Confusion: both are security protections.
- Fast rule:
  - Need DDoS protection -> **AWS Shield**
  - Need SQL injection/XSS filtering -> **AWS WAF**

## 3) Security Group vs Network ACL
- Confusion: both filter traffic in VPC.
- Fast rule:
  - Instance-level, stateful, allow rules -> **Security Group**
  - Subnet-level, stateless, allow/deny -> **Network ACL**

## 4) Amazon RDS Multi-AZ vs Read Replica
- Confusion: both involve additional DB instances.
- Fast rule:
  - High availability/failover -> **Multi-AZ**
  - Read scaling/reporting -> **Read Replica**

## 5) Reserved Instances vs Savings Plans
- Confusion: both are commitment discounts.
- Fast rule:
  - Want broader flexibility across usage -> **Savings Plans**
  - Comfortable with more instance-specific commitment -> **Reserved Instances**

## 6) Spot Instances vs On-Demand
- Confusion: both run same workloads.
- Fast rule:
  - Interruptible, fault-tolerant workload -> **Spot**
  - Cannot tolerate interruption -> **On-Demand**

## 7) Amazon EBS vs Amazon EFS vs Amazon S3
- Confusion: all are storage.
- Fast rule:
  - Block storage for EC2 -> **EBS**
  - Shared file storage for many instances -> **EFS**
  - Scalable object storage -> **S3**

## 8) VPN vs AWS Direct Connect
- Confusion: both connect on-prem to AWS.
- Fast rule:
  - Quick encrypted connection over internet -> **VPN**
  - Dedicated private predictable link -> **Direct Connect**

## 9) IAM Policy vs SCP
- Confusion: both are policies.
- Fast rule:
  - Grant/deny identity permissions in account -> **IAM Policy**
  - Set max allowed actions across accounts in org -> **SCP**

## 10) AWS Artifact vs AWS Trusted Advisor
- Confusion: both appear in compliance/cost discussions.
- Fast rule:
  - Need compliance documents/reports -> **AWS Artifact**
  - Need best-practice recommendations -> **AWS Trusted Advisor**
