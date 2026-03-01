# AWS Certified Cloud Practitioner (CLF-C02) Study Repository

A structured, exam-focused study resource for the **AWS Certified Cloud Practitioner (CLF-C02)** exam.

## Official Resources (Start Here)
- Certification page: https://aws.amazon.com/certification/certified-cloud-practitioner/
- Official learning plan: https://skillbuilder.aws/learning-plan/8UUCEZGNX4/exam-prep-plan-aws-certified-cloud-practitioner-clfc02--english/1J2VTQSGU2
- Course: https://skillbuilder.aws/learn/94T2BEN85A/aws-cloud-practitioner-essentials/8D79F3AVR7

## Quick Links
- [Recommended Study Order](#recommended-study-order)
- [Repository Map](#repository-map)
- [What CLF-C02 Usually Tests](#what-clf-c02-usually-tests)
- [Study Strategy](#study-strategy)

## Recommended Study Order
1. Read [Exam Domains](docs/exam-domains.md)
2. Follow [Study Plan (7/14/21 Days)](docs/study-plan.md)
3. Learn service fundamentals in [`docs/service-cheat-sheets/`](docs/service-cheat-sheets/compute.md)
4. Review frameworks in [`docs/frameworks/`](docs/frameworks/shared-responsibility-model.md)
5. Drill memory with [`docs/quick-recall/`](docs/quick-recall/keywords-to-answers.md)
6. Practice by domain in [`practice/questions-by-domain/`](practice/questions-by-domain/domain-1-cloud-concepts.md)
7. Take full mocks in [`practice/full-mock-exams/`](practice/full-mock-exams/mock-exam-1.md)
8. Review mistakes using [`practice/answer-keys/`](practice/answer-keys/domain-1-cloud-concepts-key.md)

## Repository Map

### Core docs
- [Exam Domains and Repo Mapping](docs/exam-domains.md)
- [Study Plan (7/14/21 Days)](docs/study-plan.md)

### Service cheat sheets
- [Compute (includes EC2 instance families)](docs/service-cheat-sheets/compute.md)
- [Storage](docs/service-cheat-sheets/storage.md)
- [Networking](docs/service-cheat-sheets/networking.md)
- [Security and Identity](docs/service-cheat-sheets/security-identity.md)
- [Monitoring and Governance](docs/service-cheat-sheets/monitoring-governance.md)
- [Pricing and Support](docs/service-cheat-sheets/pricing-support.md)

### Frameworks
- [Shared Responsibility Model](docs/frameworks/shared-responsibility-model.md)
- [AWS Well-Architected Framework](docs/frameworks/well-architected-framework.md)
- [AWS Cloud Adoption Framework (CAF)](docs/frameworks/aws-caf.md)

### Quick recall
- [Must-Know Services by Domain](docs/quick-recall/must-know-services.md)
- [Common Trick Questions](docs/quick-recall/common-trick-questions.md)
- [Keywords to Answers](docs/quick-recall/keywords-to-answers.md)

### Practice
- [Practice README](practice/README.md)
- [Questions by Domain](practice/questions-by-domain/domain-1-cloud-concepts.md)
- [Full Mock Exams](practice/full-mock-exams/mock-exam-1.md)
- [Answer Keys](practice/answer-keys/domain-1-cloud-concepts-key.md)

## What CLF-C02 Usually Tests
- Cloud value proposition (agility, elasticity, CAPEX vs OPEX)
- Shared responsibility boundaries
- Core service recognition by use case
- Security controls and governance basics
- Cost and pricing model decisions
- Billing/support tools and cost optimization behavior

## Study Strategy
- Focus on **service purpose + keyword cues**, not low-level implementation details.
- Practice decision comparisons heavily: `Amazon CloudWatch vs AWS CloudTrail vs AWS Config`, `RDS vs DynamoDB`, `AWS WAF vs AWS Shield`.
- Use answer keys to identify patterns in wrong answers and revisit the matching docs.
