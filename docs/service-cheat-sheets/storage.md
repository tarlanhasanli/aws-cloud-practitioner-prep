# Storage Cheat Sheet

## Amazon S3
### What it is
Object storage built for durability, scalability, and broad integration across AWS services.

### When to use it (exam scenarios)
- Static website assets, backups, logs, media, and data lakes.
- Unknown or growing data volumes requiring high durability.
- Lifecycle tiering and archival requirements.

### Key features and limitations
- Multiple storage classes (Standard, Intelligent-Tiering, Standard-IA, One Zone-IA, Glacier tiers).
- Versioning, lifecycle policies, replication, encryption, bucket policies.
- Object storage, not block storage for boot volumes.

### Common comparisons
- `S3 vs EBS`: S3 for object storage, EBS for EC2 block volumes.
- `S3 Standard-IA vs One Zone-IA`: One Zone-IA is cheaper but single AZ.
- `S3 Glacier Instant Retrieval vs Deep Archive`: faster retrieval vs lowest-cost archive.

### Exam keywords
`11 9s durability`, `object storage`, `lifecycle`, `archive`, `bucket`

## Amazon EBS
### What it is
Persistent block storage volumes for Amazon EC2 instances.

### When to use it (exam scenarios)
- Boot volume or low-latency block storage for a single EC2 instance.
- Database/app workloads requiring consistent IOPS patterns.

### Key features and limitations
- Volume types: gp3/gp2, io1/io2, st1, sc1.
- Snapshots stored in Amazon S3.
- A volume is typically attached to one instance at a time (with limited exceptions).

### Common comparisons
- `EBS vs Instance Store`: EBS persists, instance store is ephemeral.
- `EBS vs EFS`: EBS is block/single-instance focus; EFS is shared file storage.

### Exam keywords
`block storage`, `EC2 volume`, `low-latency`, `snapshot`

## Amazon EFS
### What it is
Managed elastic NFS file system for Linux workloads.

### When to use it (exam scenarios)
- Multiple EC2 instances need shared concurrent file access.
- Content management, analytics, and shared application data.

### Key features and limitations
- Regional and multi-AZ design.
- Automatically scales file system size.
- Typically higher cost than S3 for equivalent data volume.

### Common comparisons
- `EFS vs EBS`: EFS is shared file system; EBS is single-instance block.
- `EFS vs Amazon FSx`: EFS for NFS Linux; FSx for specific file systems (Windows/Lustre/NetApp/OpenZFS).

### Exam keywords
`shared file`, `NFS`, `multiple EC2`, `elastic file system`

## Amazon S3 Glacier Storage Classes
### What it is
Low-cost archival tiers within Amazon S3 for infrequently accessed data.

### When to use it (exam scenarios)
- Compliance retention and long-term backups.
- Data rarely accessed but must be retained cheaply.

### Key features and limitations
- Retrieval speed and minimum storage duration vary by tier.
- Deep Archive offers the lowest cost with slowest retrieval.

### Common comparisons
- `Glacier Flexible Retrieval vs Deep Archive`: faster retrieval vs cheaper long-term storage.

### Exam keywords
`archive`, `long-term retention`, `compliance`, `infrequent retrieval`

## AWS Storage Gateway
### What it is
Hybrid service connecting on-premises environments to AWS storage.

### When to use it (exam scenarios)
- You need to extend on-prem backup/archive into AWS.
- Migration requires hybrid access patterns.

### Key features and limitations
- File, volume, and tape gateway modes.
- Requires local gateway deployment.

### Common comparisons
- `Storage Gateway vs AWS DataSync`: Gateway for ongoing hybrid access, DataSync for data transfer/migration workflows.

### Exam keywords
`hybrid`, `on-premises`, `virtual tape`, `bridge to AWS storage`

## Fast Comparison Table
| Comparison | Choose A When | Choose B When |
|---|---|---|
| S3 vs EBS | Need scalable object storage (S3) | Need block storage for EC2 (EBS) |
| EBS vs EFS | One instance, block-level performance (EBS) | Shared file access across instances (EFS) |
| S3 Standard vs S3 Glacier tiers | Frequent or immediate access (Standard) | Rare access and lower storage cost (Glacier tiers) |
| Storage Gateway vs DataSync | Ongoing hybrid integration (Storage Gateway) | Managed transfer/migration jobs (DataSync) |
