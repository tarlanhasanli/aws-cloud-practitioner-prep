# Compute Cheat Sheet

## Amazon EC2
### What it is
Resizable virtual servers where you manage the operating system and instance-level configuration.

### When to use it (exam scenarios)
- You need full control of OS, runtime, and networking.
- The app needs custom software, legacy dependencies, or specific instance families.
- You need steady-state workloads with predictable capacity.

### Key features and limitations
- Supports many instance families (general purpose, compute, memory, storage, accelerated).
- Pricing: On-Demand, Savings Plans, Reserved Instances, Spot, Dedicated Hosts.
- Needs patching/maintenance by customer for OS and applications.

### Common comparisons
- `EC2 vs AWS Lambda`: EC2 for long-running/OS control, Lambda for event-driven serverless.
- `EC2 vs Elastic Beanstalk`: Beanstalk abstracts deployment/ops on top of EC2.

### Exam keywords
`full control`, `custom OS`, `long-running`, `lift-and-shift`, `instance family`

### EC2 instance families quick guide
| Family | Best for | Typical exam cues |
|---|---|---|
| General Purpose | Balanced compute/memory/networking | `balanced workload`, `general web app`, `dev/test` |
| Compute Optimized | CPU-intensive processing | `high CPU`, `batch processing`, `compute-heavy` |
| Memory Optimized | In-memory and memory-heavy apps | `large memory`, `in-memory database`, `real-time analytics` |
| Accelerated Computing | GPU/hardware acceleration | `ML training`, `GPU`, `video rendering` |
| Storage Optimized | High-throughput, high-IO local storage workloads | `high IOPS`, `low-latency local storage`, `large-scale logs` |

### Instance-family decision shortcut
- If the question says `balanced` with no clear bottleneck, start with **General Purpose**.
- If the bottleneck is CPU, use **Compute Optimized**.
- If the workload is memory-bound, use **Memory Optimized**.
- If it requires GPU or specialized accelerators, use **Accelerated Computing**.
- If it emphasizes very high storage throughput/IOPS, use **Storage Optimized**.

## AWS Lambda
### What it is
Serverless compute that runs code in response to events.

### When to use it (exam scenarios)
- Event-driven processing from Amazon S3, Amazon SNS, Amazon SQS, Amazon EventBridge.
- Short-lived APIs or automation tasks.
- Burst workloads where auto-scaling without server management is needed.

### Key features and limitations
- Pay per request and execution duration.
- Automatic scaling.
- Execution time and runtime constraints compared with EC2.

### Common comparisons
- `Lambda vs EC2`: Lambda for no server management; EC2 for full environment control.
- `Lambda vs AWS Fargate`: Lambda for functions/events; Fargate for container workloads.

### Exam keywords
`serverless`, `event-driven`, `no servers`, `pay per invocation`

## Amazon ECS and AWS Fargate
### What it is
Managed container orchestration with optional serverless container runtime (Fargate).

### When to use it (exam scenarios)
- You run containerized microservices on AWS.
- You want AWS-native orchestration without Kubernetes operations.
- You want to avoid managing container hosts (use Fargate).

### Key features and limitations
- ECS integrates tightly with IAM, Amazon CloudWatch, load balancers.
- Fargate removes EC2 node management.
- ECS is not Kubernetes; EKS is for Kubernetes standardization.

### Common comparisons
- `ECS vs EKS`: ECS is AWS-native and simpler; EKS is managed Kubernetes.
- `Fargate vs EC2 launch type`: Fargate simplifies ops; EC2 launch type offers more host control.

### Exam keywords
`containers`, `task`, `cluster`, `AWS-native orchestration`, `no host management`

## Amazon EKS
### What it is
Managed Kubernetes control plane on AWS.

### When to use it (exam scenarios)
- Teams already use Kubernetes tooling and ecosystem.
- Need portability across Kubernetes environments.

### Key features and limitations
- AWS manages Kubernetes control plane availability.
- Worker nodes still require planning (unless using Fargate profiles).
- More operational complexity than ECS for CLF-level use cases.

### Common comparisons
- `EKS vs ECS`: EKS for Kubernetes standard; ECS for simpler AWS-native container ops.

### Exam keywords
`Kubernetes`, `K8s`, `managed control plane`, `container portability`

## AWS Elastic Beanstalk
### What it is
Platform as a Service for deploying web applications with minimal infrastructure management.

### When to use it (exam scenarios)
- You want to deploy code quickly and let AWS provision load balancing and scaling resources.
- Teams want a managed app platform but not a full serverless refactor.

### Key features and limitations
- Supports common languages/platforms.
- Handles environment provisioning and updates.
- Less control than manual EC2 design.

### Common comparisons
- `Beanstalk vs EC2`: Beanstalk is more managed, EC2 is manual control.
- `Beanstalk vs Lambda`: Beanstalk for traditional web apps; Lambda for function-based apps.

### Exam keywords
`PaaS`, `deploy web app quickly`, `managed application platform`

## Elastic Load Balancing and Auto Scaling
### What it is
ELB distributes traffic; Auto Scaling adds/removes capacity automatically.

### When to use it (exam scenarios)
- Web application needs high availability across multiple Availability Zones.
- Traffic varies significantly across the day.

### Key features and limitations
- Application Load Balancer (Layer 7) for HTTP/HTTPS routing.
- Network Load Balancer (Layer 4) for high-performance TCP/UDP.
- Auto Scaling policies can be dynamic, scheduled, or predictive.

### Common comparisons
- `ALB vs NLB`: ALB for URL/path/host routing, NLB for low-latency network traffic.
- `Auto Scaling vs larger instance`: scale out for resilience, scale up for quick vertical growth.

### Exam keywords
`high availability`, `multi-AZ`, `traffic spikes`, `horizontal scaling`

## Fast Comparison Table
| Comparison | Choose A When | Choose B When |
|---|---|---|
| EC2 vs Lambda | Need OS control and long-running workload (EC2) | Event-driven serverless and minimal ops (Lambda) |
| ECS vs EKS | Want simpler AWS-native containers (ECS) | Need Kubernetes API/tooling (EKS) |
| Beanstalk vs EC2 | Want managed deployment platform (Beanstalk) | Need full infra control (EC2) |
| ALB vs NLB | Need HTTP routing features (ALB) | Need high-throughput TCP/UDP performance (NLB) |
