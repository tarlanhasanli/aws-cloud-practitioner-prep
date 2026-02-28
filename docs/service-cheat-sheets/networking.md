# Networking Cheat Sheet

## Amazon VPC
### What it is
A logically isolated virtual network for AWS resources.

### When to use it (exam scenarios)
- You need subnet segmentation (public/private), route control, and network security boundaries.

### Key features and limitations
- Components: subnets, route tables, internet gateway, NAT gateway, security groups, NACLs.
- Regional construct spanning multiple Availability Zones.

### Common comparisons
- `Security Group vs NACL`: SG is stateful/instance-level, NACL is stateless/subnet-level.
- `Internet Gateway vs NAT Gateway`: IGW for inbound+outbound internet for public resources; NAT for outbound internet from private subnets.

### Exam keywords
`isolated network`, `public/private subnet`, `route table`, `NAT`

## Amazon Route 53
### What it is
Highly available DNS and domain registration service.

### When to use it (exam scenarios)
- You need DNS resolution and global traffic routing policies.

### Key features and limitations
- Routing policies: simple, weighted, latency, failover, geolocation.
- Health checks and DNS failover support.

### Common comparisons
- `Route 53 vs CloudFront`: Route 53 resolves DNS; CloudFront caches/distributes content.

### Exam keywords
`DNS`, `domain`, `routing policy`, `health check`

## Amazon CloudFront
### What it is
Global content delivery network (CDN) to reduce latency and improve content delivery performance.

### When to use it (exam scenarios)
- You serve static/dynamic content to global users.
- You need edge caching and DDoS posture improvement with AWS Shield integration.

### Key features and limitations
- Edge locations cache content closer to users.
- Works with Amazon S3, custom origins, and HTTPS.

### Common comparisons
- `CloudFront vs S3`: CloudFront distributes/caches; S3 stores objects.

### Exam keywords
`CDN`, `edge locations`, `low latency global delivery`

## Site-to-Site Connectivity: VPN and Direct Connect
### What it is
Connectivity choices from on-premises networks to AWS.

### When to use it (exam scenarios)
- VPN: faster setup, lower cost, encrypted internet path.
- Direct Connect: dedicated private connection with predictable performance.

### Key features and limitations
- VPN depends on internet conditions.
- Direct Connect has provisioning lead time and partner/location requirements.

### Common comparisons
- `VPN vs Direct Connect`: VPN for quick encrypted setup; Direct Connect for consistent private throughput.

### Exam keywords
`hybrid connectivity`, `private link`, `dedicated connection`, `encrypted tunnel`

## VPC Peering and Transit Gateway
### What it is
Options for connecting multiple VPCs.

### When to use it (exam scenarios)
- VPC Peering for simpler, point-to-point VPC links.
- Transit Gateway for many VPCs/accounts and hub-and-spoke at scale.

### Key features and limitations
- VPC peering is non-transitive.
- Transit Gateway simplifies many-to-many network management.

### Common comparisons
- `VPC Peering vs Transit Gateway`: peering for few connections, Transit Gateway for complex network topologies.

### Exam keywords
`hub-and-spoke`, `multi-account networking`, `non-transitive peering`

## Fast Comparison Table
| Comparison | Choose A When | Choose B When |
|---|---|---|
| Security Group vs NACL | Need stateful instance-level controls (Security Group) | Need stateless subnet-level filtering incl. deny rules (NACL) |
| IGW vs NAT Gateway | Public resources need internet access (IGW) | Private subnet needs outbound-only internet (NAT Gateway) |
| VPN vs Direct Connect | Need quick, internet-based encrypted link (VPN) | Need private dedicated, consistent connectivity (Direct Connect) |
| VPC Peering vs Transit Gateway | Few direct VPC links (Peering) | Many VPCs/accounts with centralized routing (Transit Gateway) |
