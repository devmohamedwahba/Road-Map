# 📌 Phase 9 — Distributed Systems (2–3 Months)

> 🗓️ **Start:** April 22, 2028  
> 🗓️ **End:** July 22, 2028

## 🌐 Microservices Architecture

### Design Principles
- [ ] Monolith vs microservices (when to split)
- [ ] Service boundaries (bounded contexts from DDD)
- [ ] Single responsibility per service
- [ ] Database per service
- [ ] Shared nothing architecture
- [ ] API contracts and versioning
- [ ] Backward compatibility

### Communication Patterns
- [ ] Synchronous (REST, gRPC)
- [ ] Asynchronous (message queues, events)
- [ ] Request/Reply
- [ ] Event-driven (fire and forget)
- [ ] Choreography vs orchestration
- [ ] Service mesh (sidecar proxy)

### Data Management
- [ ] Eventual consistency
- [ ] Saga pattern (orchestration vs choreography)
- [ ] Two-phase commit (2PC) — and why to avoid it
- [ ] Outbox pattern
- [ ] Change Data Capture (CDC)
- [ ] CQRS in distributed context

---

## 🔥 Apache Kafka

### Core Concepts
- [ ] Topics and partitions
- [ ] Producers and consumers
- [ ] Consumer groups
- [ ] Offsets and commits
- [ ] Brokers and clusters
- [ ] Zookeeper / KRaft

### Patterns
- [ ] Event streaming
- [ ] Event sourcing with Kafka
- [ ] Log compaction
- [ ] Exactly-once semantics
- [ ] Dead letter topics
- [ ] Schema registry (Avro, Protobuf)
- [ ] Kafka Connect (source and sink connectors)
- [ ] Kafka Streams basics

### Operations
- [ ] Topic configuration (partitions, replication)
- [ ] Consumer lag monitoring
- [ ] Retention policies
- [ ] Performance tuning

---

## 🔌 gRPC

### Fundamentals
- [ ] Protocol Buffers (protobuf) syntax
- [ ] Service definitions
- [ ] Unary RPC
- [ ] Server streaming
- [ ] Client streaming
- [ ] Bidirectional streaming
- [ ] Error handling and status codes
- [ ] Interceptors (middleware)
- [ ] gRPC vs REST (when to use which)

---

## 🛡️ Resilience Patterns

### Fault Tolerance
- [ ] Circuit Breaker (closed → open → half-open)
- [ ] Retry with exponential backoff
- [ ] Timeout patterns
- [ ] Bulkhead (isolation)
- [ ] Fallback strategies
- [ ] Health checks and heartbeats

### Consistency
- [ ] Idempotency keys
- [ ] Distributed transactions
- [ ] Conflict resolution (last-write-wins, CRDTs)
- [ ] Consensus algorithms (Raft overview)
- [ ] Leader election

### API Gateway
- [ ] Request routing
- [ ] Authentication/authorization
- [ ] Rate limiting
- [ ] Load balancing
- [ ] Request aggregation
- [ ] Circuit breaking at gateway level
- [ ] Kong / AWS API Gateway / Traefik

### Observability in Distributed Systems
- [ ] Distributed tracing (correlation IDs)
- [ ] Centralized logging
- [ ] Service dependency maps
- [ ] SLIs, SLOs, SLAs
- [ ] Error budgets

---

## 🚀 Phase 9 Project

- [ ] **Microservices E-commerce** — 3+ services, Kafka events, gRPC between services, API Gateway, Saga pattern, distributed tracing

---

## 📖 Resources

- **Book:** Designing Data-Intensive Applications — Martin Kleppmann (chapters 4-12)
- **Book:** Building Microservices — Sam Newman
- **Docs:** [Kafka Official Docs](https://kafka.apache.org/documentation/)
- **Docs:** [gRPC Official Docs](https://grpc.io/docs/)
- **Course:** [Hussein Nasser YouTube](https://www.youtube.com/@haboringuy) — distributed systems, Kafka, gRPC
- **Course:** [Martin Fowler's articles](https://martinfowler.com/) — patterns, event sourcing, CQRS
