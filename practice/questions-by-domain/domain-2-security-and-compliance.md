# Domain 2: Security and Compliance (25 Questions)

## Q1 [Easy]
What is the recommended way to add extra protection to the AWS account root user?

A. Create more access keys  
B. Enable multi-factor authentication (MFA)  
C. Share root password with administrators  
D. Use the root user for daily tasks  

## Q2 [Easy]
Which IAM principle grants only the permissions required to perform a task?

A. Full administrative access  
B. Separation of duties  
C. Least privilege  
D. Implicit allow  

## Q3 [Medium]
An Amazon EC2 application must access an Amazon S3 bucket without storing long-term credentials on the instance. What should be used?

A. IAM user access keys in code  
B. IAM role attached to the EC2 instance  
C. Root account credentials  
D. Security group rule  

## Q4 [Easy]
Which AWS service records API activity across an account for auditing?

A. Amazon CloudWatch  
B. AWS CloudTrail  
C. AWS Config  
D. Amazon Inspector  

## Q5 [Easy]
Which service provides a history of AWS resource configuration changes?

A. AWS Config  
B. AWS CloudTrail  
C. AWS Artifact  
D. AWS Shield  

## Q6 [Easy]
Which AWS service provides on-demand access to AWS compliance reports such as SOC and PCI documents?

A. AWS Artifact  
B. AWS WAF  
C. Amazon GuardDuty  
D. AWS IAM Identity Center  

## Q7 [Easy]
Which service is primarily designed to protect against distributed denial-of-service (DDoS) attacks?

A. AWS WAF  
B. AWS Shield  
C. Amazon Macie  
D. AWS Config  

## Q8 [Easy]
Which service helps block SQL injection attacks against a web application?

A. AWS Shield  
B. AWS WAF  
C. Amazon GuardDuty  
D. Amazon Inspector  

## Q9 [Medium]
Which service continuously monitors for suspicious account and workload activity using threat intelligence?

A. Amazon GuardDuty  
B. Amazon Macie  
C. AWS CloudHSM  
D. AWS Secrets Manager  

## Q10 [Medium]
A security team needs to discover sensitive data in Amazon S3 buckets. Which service should they use?

A. Amazon Macie  
B. Amazon GuardDuty  
C. Amazon Inspector  
D. AWS CloudTrail  

## Q11 [Medium]
Which service is used to identify software vulnerabilities in supported compute workloads?

A. AWS Config  
B. Amazon Inspector  
C. AWS Artifact  
D. AWS Shield  

## Q12 [Medium]
A company needs to apply permission guardrails across all AWS accounts in an organization. Which feature should be used?

A. IAM inline policies  
B. Bucket policies  
C. Service Control Policies (SCPs)  
D. Security groups  

## Q13 [Easy]
Which AWS service enables centralized governance and consolidated billing for multiple AWS accounts?

A. AWS Organizations  
B. AWS Config  
C. AWS CloudFormation  
D. AWS Systems Manager  

## Q14 [Easy]
Which service helps create and manage encryption keys used by AWS services?

A. AWS KMS  
B. AWS Artifact  
C. AWS Shield  
D. Amazon Detective  

## Q15 [Medium]
Under the shared responsibility model, who is responsible for data classification and access policy decisions?

A. AWS only  
B. Customer only  
C. AWS Support only  
D. Shared only for Lambda  

## Q16 [Easy]
Under the shared responsibility model, who is responsible for physical security of AWS data centers?

A. Customer  
B. AWS  
C. Third-party auditor  
D. Customer security team and AWS equally  

## Q17 [Medium]
Which statement correctly describes a security group?

A. Stateless and subnet-level  
B. Stateful and instance-level  
C. Supports deny rules explicitly  
D. Replaces IAM policies  

## Q18 [Medium]
Which is an IAM best practice?

A. Use root user access keys for automation  
B. Share one IAM user across the team  
C. Use roles and enable MFA where possible  
D. Attach AdministratorAccess to all users  

## Q19 [Medium]
A user in Account A needs temporary access to resources in Account B. Which AWS approach is most appropriate?

A. Share root credentials  
B. Use an IAM role with AWS STS  
C. Add user from Account A directly into Account B root  
D. Open inbound SSH from internet  

## Q20 [Medium]
Which Amazon S3 setting helps prevent accidental public exposure at account and bucket level?

A. S3 Object Lambda  
B. S3 Block Public Access  
C. S3 Transfer Acceleration  
D. S3 Batch Operations  

## Q21 [Medium]
A compliance auditor asks: "Which user deleted this IAM policy yesterday?" Which service should be checked first?

A. Amazon CloudWatch  
B. AWS CloudTrail  
C. AWS Config  
D. AWS Trusted Advisor  

## Q22 [Medium]
In IAM policy evaluation, what happens if one applicable policy has an explicit deny?

A. Access is allowed if another policy allows it  
B. Access is denied  
C. Access depends on AWS Region  
D. Access is deferred to AWS Support  

## Q23 [Medium]
Which service can evaluate resources against rules such as "EBS volumes must be encrypted"?

A. AWS Config  
B. AWS Artifact  
C. AWS CloudTrail  
D. Amazon GuardDuty  

## Q24 [Hard]
A security team wants centralized management of AWS WAF rules across multiple accounts in AWS Organizations. Which service helps with this?

A. AWS Firewall Manager  
B. AWS Artifact  
C. Amazon Macie  
D. AWS Budgets  

## Q25 [Hard]
An account shows unusual API calls from anomalous locations and suspicious behavior patterns. Which service is designed to detect this?

A. Amazon Inspector  
B. Amazon GuardDuty  
C. AWS IAM Access Analyzer  
D. AWS Config  
