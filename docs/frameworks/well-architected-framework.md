# AWS Well-Architected Framework (All 6 Pillars)

## Why It Matters for CLF-C02
Questions often ask for the **best architectural choice** based on reliability, security, cost, or performance tradeoffs.

## 1) Operational Excellence
### Design principles
- Perform operations as code
- Make frequent, small, reversible changes
- Refine procedures frequently
- Anticipate failure and learn from operations

### Common exam cues
`automate operations`, `runbooks`, `continuous improvement`, `post-incident review`

## 2) Security
### Design principles
- Implement strong identity foundation
- Enable traceability
- Apply security at all layers
- Protect data in transit and at rest
- Keep people away from data
- Prepare for security events

### Common exam cues
`least privilege`, `MFA`, `encryption`, `audit trail`, `incident response`

## 3) Reliability
### Design principles
- Automatically recover from failure
- Test recovery procedures
- Scale horizontally to increase resilience
- Stop guessing capacity
- Manage change via automation

### Common exam cues
`Multi-AZ`, `fault tolerance`, `self-healing`, `automatic failover`

## 4) Performance Efficiency
### Design principles
- Democratize advanced technologies
- Go global in minutes
- Use serverless architectures
- Experiment often
- Match supply to demand

### Common exam cues
`right-size`, `serverless`, `global users`, `performance bottleneck`

## 5) Cost Optimization
### Design principles
- Implement cloud financial management
- Adopt consumption model
- Measure overall efficiency
- Stop spending on undifferentiated heavy lifting
- Analyze and attribute expenditure

### Common exam cues
`pay-as-you-go`, `rightsizing`, `Savings Plans`, `cost visibility`

## 6) Sustainability
### Design principles
- Understand impact
- Establish sustainability goals
- Maximize utilization
- Anticipate and adopt efficient hardware/software
- Use managed services
- Reduce downstream impact

### Common exam cues
`reduce energy footprint`, `improve utilization`, `managed services`

## Pillar-to-Service Hints
| Pillar | Typical CLF Service Signals |
|---|---|
| Operational Excellence | AWS CloudFormation, Amazon CloudWatch, AWS Systems Manager |
| Security | IAM, AWS CloudTrail, AWS KMS, AWS WAF, AWS Shield |
| Reliability | Elastic Load Balancing, Auto Scaling, Multi-AZ deployments |
| Performance Efficiency | Amazon CloudFront, AWS Lambda, right instance families |
| Cost Optimization | AWS Cost Explorer, Compute Optimizer, Savings Plans |
| Sustainability | Serverless and managed services, right-sizing, efficient architectures |

## Fast Decision Cues
- If the question says "recover automatically" -> **Reliability**
- If it says "trace user activity" -> **Security** (traceability)
- If it says "reduce waste/spend" -> **Cost Optimization**
- If it says "improve deployment/operations process" -> **Operational Excellence**
