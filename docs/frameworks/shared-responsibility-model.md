# AWS Shared Responsibility Model

## Core Rule
- **AWS** is responsible for **security OF the cloud**.
- **Customer** is responsible for **security IN the cloud**.

## AWS Responsibilities (Security OF the Cloud)
- Physical facilities and global infrastructure
- Hardware lifecycle and host OS/hypervisor layers
- Managed service control planes and foundational networking components

## Customer Responsibilities (Security IN the Cloud)
- Data classification and protection
- IAM configuration (users, roles, permissions, MFA)
- OS and application patching where customer controls compute
- Network controls (security groups, NACLs, routing choices)
- Encryption configuration and key usage decisions

## By Service Type: EC2 vs RDS vs S3
| Area | Amazon EC2 | Amazon RDS | Amazon S3 |
|---|---|---|---|
| Physical hosts/data centers | AWS | AWS | AWS |
| Host OS / hypervisor | AWS | AWS | AWS |
| Guest OS patching | Customer | AWS | AWS (service-managed) |
| Database engine patching | Customer (self-managed DB on EC2) | AWS (managed service) | AWS (not applicable) |
| Data encryption settings | Customer chooses/configures | Customer chooses/configures | Customer chooses/configures |
| IAM policies and access controls | Customer | Customer | Customer |
| Network controls (SG/NACL/VPC) | Customer | Customer | Customer (bucket policies + networking patterns) |
| Application security | Customer | Customer app usage | Customer app usage |

## Practical Exam Examples
- "Who patches OS on EC2?" -> **Customer**
- "Who patches database engine for Amazon RDS?" -> **AWS** (for managed service operations)
- "Who controls S3 bucket policy?" -> **Customer**
- "Who secures AWS data centers?" -> **AWS**

## Common Trap Patterns
| Trap | Correct Thinking |
|---|---|
| "AWS is managed, so AWS handles everything" | Managed service reduces ops scope, not data/access responsibility |
| "RDS means no security tasks for customer" | Customer still handles data, users, network access, encryption settings |
| "S3 breach means AWS failed security" | Most incidents are customer misconfiguration (public access/policy issues) |

## Exam Keywords
`security OF vs IN`, `managed service boundary`, `customer configuration`, `IAM`, `encryption`
