# Pricing and Support Cheat Sheet

## EC2 and Compute Pricing Models

## On-Demand Instances
### What it is
Pay for compute capacity by the second (or hour, depending on service), with no long-term commitment.

### When to use it (exam scenarios)
- Unpredictable workloads, short-term projects, or initial deployments.

### Key features and limitations
- Flexible and simple.
- Usually highest unit price.

### Exam keywords
`no commitment`, `flexibility`, `short-term`

## Reserved Instances and Savings Plans
### What it is
Commitment-based pricing models that reduce cost for steady usage.

### When to use it (exam scenarios)
- Predictable long-term workloads (1 or 3 years).

### Key features and limitations
- Reserved Instances are more specific to instance attributes.
- Savings Plans are generally more flexible across usage patterns.

### Common comparisons
- `Reserved Instances vs Savings Plans`: specificity vs flexibility.

### Exam keywords
`1-year`, `3-year`, `steady-state`, `commitment discount`

## Spot Instances
### What it is
Spare AWS capacity at deep discounts, with potential interruption.

### When to use it (exam scenarios)
- Fault-tolerant, interruptible workloads like batch processing.

### Key features and limitations
- Lowest cost potential.
- Can be reclaimed by AWS with short notice.

### Common comparisons
- `Spot vs On-Demand`: lowest cost with interruption risk vs highest flexibility.

### Exam keywords
`interruptible`, `batch`, `cost-sensitive`

## Cost Management Services
| Service | Primary Purpose | Exam Cue |
|---|---|---|
| AWS Cost Explorer | Visualize and analyze historical cost and usage | `cost trends`, `forecasting` |
| AWS Budgets | Set budget thresholds and alerts | `budget alert`, `notify` |
| Cost Anomaly Detection | Detect unusual spend patterns | `unexpected spike` |
| AWS Pricing Calculator | Estimate architecture costs before deployment | `estimate monthly bill` |
| AWS Billing Conductor | Customize billing views/rates across groups | `internal chargeback/showback` |

## AWS Support Plans
| Plan | Typical Use | Response / Features |
|---|---|---|
| Basic | Learning and account/billing basics | No technical support, docs and forums |
| Developer | Dev/test workloads | Business-hours guidance, lower urgency SLAs |
| Business | Production workloads | 24x7 technical support, faster response, Trusted Advisor full checks |
| Enterprise On-Ramp / Enterprise | Mission-critical org-scale operations | Fastest response and architectural guidance; Enterprise includes TAM |

## Common Comparisons
| Comparison | Choose A When | Choose B When |
|---|---|---|
| Savings Plans vs Reserved Instances | Need flexibility across compute usage (Savings Plans) | Need instance-specific reservation strategy (Reserved Instances) |
| Spot vs On-Demand | Workload tolerates interruptions (Spot) | Workload cannot be interrupted (On-Demand) |
| AWS Cost Explorer vs AWS Budgets | Need spend analysis/forecast views (Cost Explorer) | Need proactive threshold alerts (Budgets) |
| Business vs Enterprise support | Need production support with strong SLA (Business) | Need TAM and highest enterprise support depth (Enterprise) |

## Exam Keywords
`pay-as-you-go`, `commitment discount`, `forecast`, `budget alert`, `TAM`, `cost optimization`
