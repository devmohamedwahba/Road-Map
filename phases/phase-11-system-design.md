# 📌 Phase 11 — System Design (Ongoing)

## 📈 Scalability

### Horizontal Scaling
- [ ] Stateless services
- [ ] Load balancing algorithms (round-robin, least connections, consistent hashing)
- [ ] Session management (sticky sessions vs external store)
- [ ] Auto-scaling policies (CPU, memory, custom metrics)
- [ ] Database read replicas

### Caching
- [ ] Cache layers (browser, CDN, application, database)
- [ ] Cache invalidation strategies
- [ ] Cache-aside vs write-through vs write-behind
- [ ] Distributed caching (Redis Cluster)
- [ ] Cache stampede prevention
- [ ] CDN (CloudFront, Cloudflare)

### Data Partitioning
- [ ] Horizontal partitioning (sharding)
- [ ] Vertical partitioning
- [ ] Sharding strategies (range, hash, directory)
- [ ] Consistent hashing
- [ ] Rebalancing
- [ ] Cross-shard queries

### Asynchronous Processing
- [ ] Message queues for decoupling
- [ ] Event-driven architecture
- [ ] CQRS (separate read/write)
- [ ] Materialized views
- [ ] Change Data Capture

---

## 🛡️ Reliability & Availability

### CAP Theorem
- [ ] Consistency vs Availability vs Partition Tolerance
- [ ] CP systems (HBase, MongoDB with strong consistency)
- [ ] AP systems (Cassandra, DynamoDB)
- [ ] PACELC theorem (extends CAP)

### Consistency Models
- [ ] Strong consistency
- [ ] Eventual consistency
- [ ] Causal consistency
- [ ] Read-your-writes
- [ ] Linearizability

### Fault Tolerance
- [ ] Redundancy (active-active, active-passive)
- [ ] Failover mechanisms
- [ ] Health checks and heartbeats
- [ ] Circuit breakers
- [ ] Bulkheads
- [ ] Graceful degradation
- [ ] Chaos engineering basics

### High Availability
- [ ] SLA (99.9%, 99.99%, 99.999%)
- [ ] Multi-AZ deployments
- [ ] Multi-region architecture
- [ ] Disaster recovery (RPO, RTO)
- [ ] Backup strategies

---

## 🧩 Key Components

### Databases
- [ ] SQL vs NoSQL decision framework
- [ ] When to use PostgreSQL, MongoDB, Cassandra, DynamoDB
- [ ] Database indexing strategies
- [ ] Connection pooling
- [ ] Read replicas and write scaling

### Search
- [ ] Elasticsearch / OpenSearch
- [ ] Inverted index
- [ ] Full-text search design
- [ ] Search ranking and relevance

### Storage
- [ ] Object storage (S3)
- [ ] Block storage (EBS)
- [ ] File storage (EFS)
- [ ] Blob storage patterns
- [ ] Data lake basics

### Networking
- [ ] DNS resolution
- [ ] TCP/UDP
- [ ] HTTP/2, HTTP/3
- [ ] WebSockets vs SSE vs long polling
- [ ] API Gateway patterns
- [ ] Rate limiting algorithms (token bucket, sliding window)

### Security
- [ ] Authentication (OAuth2, OIDC, SAML)
- [ ] Authorization (RBAC, ABAC)
- [ ] Encryption (at rest, in transit)
- [ ] API security
- [ ] DDoS protection

---

## 💡 System Design Practice

### Design Exercises
- [ ] URL Shortener (TinyURL)
- [ ] Paste Bin
- [ ] Rate Limiter
- [ ] Notification System
- [ ] Chat System (WhatsApp)
- [ ] Social Media Feed (Twitter/Instagram)
- [ ] Ride Sharing (Uber)
- [ ] Video Streaming (YouTube/Netflix)
- [ ] File Storage (Google Drive/Dropbox)
- [ ] Search Engine
- [ ] E-commerce (Amazon)
- [ ] Payment System (Stripe)
- [ ] Distributed Cache
- [ ] Task Scheduler
- [ ] Metrics/Monitoring System

### Framework for Answering
- [ ] Clarify requirements (functional + non-functional)
- [ ] Estimate scale (QPS, storage, bandwidth)
- [ ] High-level design (components diagram)
- [ ] Deep dive into components
- [ ] Identify bottlenecks
- [ ] Discuss tradeoffs
- [ ] Address failure scenarios
