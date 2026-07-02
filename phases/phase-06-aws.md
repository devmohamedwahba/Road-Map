# 📌 Phase 6 — Cloud / AWS (1–2 Months)

## ☁️ AWS Fundamentals

### Identity & Access
- [ ] IAM Users, Groups, Roles
- [ ] IAM Policies (JSON structure)
- [ ] Least privilege principle
- [ ] Service roles
- [ ] Cross-account access
- [ ] MFA and security best practices
- [ ] AWS Organizations and SCPs

### Networking
- [ ] VPC (Virtual Private Cloud)
- [ ] Subnets (public vs private)
- [ ] Internet Gateway
- [ ] NAT Gateway
- [ ] Route tables
- [ ] Security Groups (stateful)
- [ ] Network ACLs (stateless)
- [ ] VPC Peering
- [ ] VPC Endpoints (Gateway & Interface)
- [ ] Elastic IPs

### Compute
- [ ] EC2 instance types and sizing
- [ ] AMIs (Amazon Machine Images)
- [ ] Key pairs and SSH access
- [ ] User data scripts
- [ ] Auto Scaling Groups
- [ ] Launch Templates
- [ ] Spot instances vs On-Demand vs Reserved
- [ ] Elastic Load Balancer (ALB, NLB)
- [ ] Target groups and health checks

---

## 🗄️ AWS Storage & Database

### S3
- [ ] Buckets, objects, keys
- [ ] Storage classes (Standard, IA, Glacier)
- [ ] Bucket policies and ACLs
- [ ] Pre-signed URLs
- [ ] Lifecycle rules
- [ ] Versioning
- [ ] Event notifications
- [ ] Static website hosting
- [ ] Cross-region replication

### RDS
- [ ] Supported engines (PostgreSQL, MySQL)
- [ ] Multi-AZ deployments
- [ ] Read replicas
- [ ] Automated backups and snapshots
- [ ] Parameter groups
- [ ] Performance Insights
- [ ] RDS Proxy (connection pooling)

---

## ⚙️ AWS Application Services

### Lambda
- [ ] Function creation and deployment
- [ ] Triggers and event sources
- [ ] Cold starts and optimization
- [ ] Layers
- [ ] Environment variables
- [ ] Concurrency (reserved, provisioned)
- [ ] Lambda with API Gateway
- [ ] Lambda with SQS/SNS

### Messaging & Events
- [ ] SNS (Simple Notification Service) — fan-out
- [ ] SQS (Simple Queue Service) — decoupling
- [ ] SQS FIFO vs Standard
- [ ] Dead letter queues
- [ ] EventBridge (event bus, rules, targets)
- [ ] EventBridge Scheduler

### API Gateway
- [ ] REST API vs HTTP API
- [ ] Routes and integrations
- [ ] Request/response transformations
- [ ] Authorizers (Lambda, Cognito, JWT)
- [ ] Throttling and quotas
- [ ] Stages and deployments
- [ ] Custom domain names

### Secrets & Configuration
- [ ] Secrets Manager (rotation, access)
- [ ] Systems Manager Parameter Store
- [ ] When to use Secrets Manager vs Parameter Store

### Monitoring
- [ ] CloudWatch Logs
- [ ] CloudWatch Metrics
- [ ] CloudWatch Alarms
- [ ] X-Ray (distributed tracing)
- [ ] CloudTrail (audit logging)

---

## 📦 Containers on AWS

### ECR (Elastic Container Registry)
- [ ] Creating repositories
- [ ] Pushing/pulling images
- [ ] Image scanning
- [ ] Lifecycle policies

### ECS (Elastic Container Service)
- [ ] Task definitions
- [ ] Services
- [ ] Fargate vs EC2 launch type
- [ ] Service discovery
- [ ] Auto scaling
- [ ] Load balancer integration
- [ ] Secrets injection
- [ ] Logging configuration

---

## 🏗️ Infrastructure as Code

### Terraform (or CloudFormation)
- [ ] Provider configuration
- [ ] Resources and data sources
- [ ] Variables and outputs
- [ ] State management (remote state, locking)
- [ ] Modules (reusable infrastructure)
- [ ] Workspaces (environments)
- [ ] Import existing resources
- [ ] Plan → Apply workflow

---

## 🚀 Phase 6 Project

- [ ] **Deploy Production API** — VPC, ALB, ECS Fargate, RDS, S3, Secrets Manager, CloudWatch, Terraform
