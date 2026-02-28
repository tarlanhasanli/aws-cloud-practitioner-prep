# AWS Cloud Adoption Framework (AWS CAF)

## Purpose
AWS CAF helps organizations plan and execute cloud transformation with business, people, and technical alignment.

## 6 Perspectives
| Perspective | Focus | Who Cares (Typical Roles) | Exam Keywords |
|---|---|---|---|
| Business | Business outcomes, value realization | CIO, business executives, finance leaders | `business value`, `outcomes`, `ROI` |
| People | Skills, culture, change management | HR, L&D, transformation leads, engineering managers | `training`, `change management`, `cloud skills` |
| Governance | Risk, compliance, policy, portfolio control | Compliance officers, risk, finance, PMO | `controls`, `risk`, `compliance`, `policy` |
| Platform | Foundational cloud architecture and engineering | Cloud architects, platform engineers, network teams | `landing zone`, `architecture`, `migration platform` |
| Security | Identity, detection, protection, resilience | Security architects, SecOps, CISO org | `identity`, `threat detection`, `security controls` |
| Operations | Run, monitor, and support cloud workloads | IT ops, SRE, incident response, support teams | `monitoring`, `incident`, `operations` |

## Transformation Phases
| Phase | Goal | Typical Outputs |
|---|---|---|
| Envision | Align stakeholders on business case and direction | Vision, target outcomes, initial roadmap |
| Align | Build capability and operating model alignment | Skills plans, governance model, prioritized initiatives |
| Launch | Deliver pilots and first production workloads | MVP workloads, landing zone, initial guardrails |
| Scale | Expand and optimize across the organization | Broad migration, optimized operations, continuous improvement |

## How CAF Appears on CLF-C02
- At CLF level, CAF is usually tested as **which perspective best fits a scenario**.
- Most questions are keyword-driven and role-focused rather than implementation detail.

## Scenario Cues
- "Need executive business justification" -> **Business perspective**
- "Need training and org readiness" -> **People perspective**
- "Need policy/compliance guardrails" -> **Governance perspective**
- "Need secure, scalable technical foundation" -> **Platform + Security perspectives**
- "Need to run and support workloads reliably" -> **Operations perspective**

## Common Confusions
| Confusion | Quick Decision Rule |
|---|---|
| Governance vs Security | Governance sets policy/risk oversight; Security implements protection controls |
| Business vs People | Business is value/outcomes; People is skills and org change |
| Platform vs Operations | Platform builds cloud foundation; Operations runs day-2 workload lifecycle |
