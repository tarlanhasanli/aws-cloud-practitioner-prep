# Monitoring and Governance Cheat Sheet

## Amazon CloudWatch
### What it is
Monitoring and observability service for metrics, logs, alarms, and dashboards.

### When to use it (exam scenarios)
- Monitor resource/application health.
- Trigger alerts and automated responses to thresholds/events.

### Key features and limitations
- Metrics, logs, alarms, events, dashboards.
- Near-real-time operational visibility.

### Common comparisons
- `Amazon CloudWatch vs AWS CloudTrail`: telemetry/monitoring vs API audit logging.

### Exam keywords
`metrics`, `alarms`, `dashboards`, `operational monitoring`

## AWS CloudTrail
### What it is
Audit trail of API and management activity in an AWS account.

### When to use it (exam scenarios)
- Investigate who did what and when.
- Meet governance and audit requirements.

### Key features and limitations
- Records API activity across services and accounts.
- Primarily for auditing, not metrics graphing.

### Common comparisons
- `AWS CloudTrail vs Amazon CloudWatch`: governance audit vs monitoring and alerting.

### Exam keywords
`API calls`, `audit trail`, `governance`, `forensics`

## AWS Config
### What it is
Service for tracking resource configuration changes and evaluating compliance.

### When to use it (exam scenarios)
- You need historical config state and compliance rules.
- Detect drift from required configuration baselines.

### Key features and limitations
- Configuration timeline and compliance status.
- Rule-based evaluation; does not replace vulnerability scanners.

### Common comparisons
- `AWS Config vs AWS CloudTrail`: state/config tracking vs API event logging.

### Exam keywords
`configuration history`, `compliance rule`, `resource drift`

## AWS Trusted Advisor
### What it is
Recommendations for cost optimization, performance, security, fault tolerance, and service limits.

### When to use it (exam scenarios)
- Identify idle resources, exposure risks, and quota concerns.

### Key features and limitations
- Category-based checks with action guidance.
- Feature depth varies by support plan.

### Common comparisons
- `Trusted Advisor vs Compute Optimizer`: broad account best-practice checks vs machine learning rightsizing for compute.

### Exam keywords
`best practices`, `service limits`, `cost savings`, `recommendations`

## AWS CloudFormation and AWS Control Tower
### What it is
- AWS CloudFormation: infrastructure as code templates.
- AWS Control Tower: landing zone and multi-account governance setup.

### When to use it (exam scenarios)
- Use CloudFormation for repeatable stack deployment.
- Use Control Tower for governed multi-account environments.

### Key features and limitations
- CloudFormation standardizes provisioning.
- Control Tower orchestrates baseline controls and account setup.

### Common comparisons
- `CloudFormation vs Manual console changes`: repeatability and consistency vs ad hoc manual operations.

### Exam keywords
`infrastructure as code`, `landing zone`, `account governance`

## Fast Comparison Table
| Comparison | Choose A When | Choose B When |
|---|---|---|
| Amazon CloudWatch vs AWS CloudTrail | Need metrics/log alarms (CloudWatch) | Need API activity audit (CloudTrail) |
| AWS CloudTrail vs AWS Config | Need event history of API calls (CloudTrail) | Need resource configuration timeline/compliance (AWS Config) |
| Trusted Advisor vs Compute Optimizer | Need broad account checks (Trusted Advisor) | Need compute rightsizing insights (Compute Optimizer) |
| CloudFormation vs Elastic Beanstalk | Need infrastructure templates (CloudFormation) | Need app platform deployment automation (Beanstalk) |
