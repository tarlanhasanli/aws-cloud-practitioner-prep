# Domain 2 Answer Key: Security and Compliance

| Q# | Answer | Explanation |
|---|---|---|
| 1 | B | MFA adds a second factor and is strongly recommended for root. |
| 2 | C | Least privilege means granting only the permissions needed. |
| 3 | B | EC2 roles provide temporary credentials without hardcoded keys. |
| 4 | B | AWS CloudTrail records API and account activity for auditing. |
| 5 | A | AWS Config tracks resource configuration changes over time. |
| 6 | A | AWS Artifact provides compliance reports and agreements. |
| 7 | B | AWS Shield is the DDoS protection service. |
| 8 | B | AWS WAF filters malicious web requests like SQL injection/XSS. |
| 9 | A | GuardDuty is managed threat detection using logs/intelligence. |
| 10 | A | Macie discovers and helps protect sensitive data in S3. |
| 11 | B | Inspector identifies vulnerabilities and exposure in workloads. |
| 12 | C | SCPs define maximum permissions across organization accounts. |
| 13 | A | AWS Organizations provides account governance and consolidated billing. |
| 14 | A | AWS KMS is the managed key service for encryption workflows. |
| 15 | B | Customers control data classification and access choices. |
| 16 | B | AWS secures physical facilities and core infrastructure. |
| 17 | B | Security groups are stateful and applied at instance/ENI level. |
| 18 | C | IAM roles + MFA align with AWS identity best practices. |
| 19 | B | Cross-account role assumption with STS is the standard pattern. |
| 20 | B | S3 Block Public Access prevents broad accidental public exposure. |
| 21 | B | AWS CloudTrail is the primary source for "who did what" API actions. |
| 22 | B | Explicit deny always overrides allows in IAM evaluation. |
| 23 | A | Config rules can evaluate compliance posture continuously. |
| 24 | A | Firewall Manager centralizes WAF and security policy management. |
| 25 | B | GuardDuty detects unusual and potentially malicious behavior patterns. |

## Review Notes
- If you miss Q4/Q5/Q21/Q23, revisit `AWS CloudTrail vs Amazon CloudWatch vs AWS Config`.
- If you miss Q7/Q8/Q24, revisit the `AWS Shield/WAF/Firewall Manager` boundary.
