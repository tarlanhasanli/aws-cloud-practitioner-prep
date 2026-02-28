# Security and Identity Cheat Sheet

## AWS Identity and Access Management (IAM)
### What it is
Service for authentication and authorization in AWS.

### When to use it (exam scenarios)
- Define least-privilege permissions for users, roles, and workloads.
- Grant temporary access via roles.

### Key features and limitations
- IAM users, groups, roles, and policies.
- Supports MFA and access key management.
- Root user should be used rarely and protected strongly.

### Common comparisons
- `IAM user vs IAM role`: user for long-term identity; role for temporary or assumed access.
- `Authentication vs authorization`: proving identity vs granting permissions.

### Exam keywords
`least privilege`, `MFA`, `role assumption`, `policy`

## AWS Organizations and Service Control Policies (SCPs)
### What it is
Multi-account governance and consolidated billing service.

### When to use it (exam scenarios)
- Centralized governance across many AWS accounts.
- Enforce guardrails with SCPs.

### Key features and limitations
- Consolidated billing and organizational units (OUs).
- SCPs set maximum permission boundaries; they do not directly grant permissions.

### Common comparisons
- `IAM policy vs SCP`: IAM grants/denies within account; SCP limits what accounts can do.

### Exam keywords
`multi-account`, `consolidated billing`, `OU`, `guardrails`

## AWS Shield and AWS WAF
### What it is
Protection services for network/application attack patterns.

### When to use it (exam scenarios)
- Shield for DDoS protection.
- AWS WAF for filtering web exploits like SQL injection and XSS.

### Key features and limitations
- Shield Standard provides baseline DDoS protection automatically.
- AWS WAF uses web ACL rules and integrates with CloudFront/ALB/API Gateway.

### Common comparisons
- `AWS Shield vs AWS WAF`: volumetric DDoS vs application-layer filtering.

### Exam keywords
`DDoS`, `SQL injection`, `XSS`, `web ACL`

## Amazon GuardDuty, Amazon Inspector, and Amazon Macie
### What it is
Managed detection services for threat intelligence, vulnerabilities, and sensitive data discovery.

### When to use it (exam scenarios)
- GuardDuty for suspicious activity detection in accounts/workloads.
- Inspector for vulnerability findings on compute/container images.
- Macie for sensitive data discovery/protection in Amazon S3.

### Key features and limitations
- GuardDuty uses logs/events with ML and threat intelligence.
- Inspector focuses on vulnerability posture.
- Macie focuses on S3 data sensitivity/classification.

### Common comparisons
- `GuardDuty vs Inspector`: threat detection behavior vs vulnerability assessment.
- `Macie vs GuardDuty`: data sensitivity in S3 vs account/workload threat events.

### Exam keywords
`threat detection`, `vulnerability`, `sensitive data`, `S3 data discovery`

## AWS Artifact and AWS Key Management Service (AWS KMS)
### What it is
- AWS Artifact: on-demand compliance reports and agreements.
- AWS KMS: managed encryption key service.

### When to use it (exam scenarios)
- Artifact when auditors ask for SOC/ISO/PCI reports.
- KMS when encryption key management and auditability are required.

### Key features and limitations
- Artifact is document access, not active monitoring.
- KMS integrates with many AWS services for encryption at rest.

### Common comparisons
- `AWS Artifact vs AWS Config`: reports/compliance docs vs resource configuration tracking.

### Exam keywords
`compliance report`, `SOC`, `PCI`, `encryption keys`

## Fast Comparison Table
| Comparison | Choose A When | Choose B When |
|---|---|---|
| IAM Role vs IAM User | Need temporary or workload access (Role) | Need long-term identity (User) |
| AWS Shield vs AWS WAF | Need DDoS protection (Shield) | Need application-layer filtering (AWS WAF) |
| GuardDuty vs Inspector | Need threat detection (GuardDuty) | Need vulnerability findings (Inspector) |
| Macie vs AWS Config | Need S3 sensitive data discovery (Macie) | Need resource configuration history/compliance (AWS Config) |
| IAM Policy vs SCP | Grant/deny account identity permissions (IAM Policy) | Set max permission boundaries at org level (SCP) |
