# 📌 Phase 5 — Background Processing (1–2 Months)

## 📨 Celery

### Fundamentals
- [ ] Celery architecture (broker, worker, result backend)
- [ ] Task definition and registration
- [ ] Calling tasks (delay, apply_async)
- [ ] Task results and states
- [ ] Task signatures (chain, group, chord)

### Task Configuration
- [ ] Retry logic (max_retries, countdown, exponential backoff)
- [ ] Task timeouts (soft_time_limit, time_limit)
- [ ] Task priorities
- [ ] Task routing to specific queues
- [ ] Rate limiting per task

### Scheduling
- [ ] Celery Beat (periodic tasks)
- [ ] Crontab schedules
- [ ] Solar schedules
- [ ] Dynamic scheduling
- [ ] Database-backed schedules (django-celery-beat)

### Monitoring & Debugging
- [ ] Flower (web monitoring)
- [ ] Celery events
- [ ] Task logging
- [ ] Dead letter queues
- [ ] Handling task failures gracefully

### Best Practices
- [ ] Idempotent tasks
- [ ] Small atomic tasks vs large tasks
- [ ] Avoiding database state in tasks
- [ ] Task serialization (JSON vs pickle)
- [ ] Prefetch multiplier tuning
- [ ] Worker concurrency (prefork vs eventlet vs gevent)

---

## 🐇 RabbitMQ

### Core Concepts
- [ ] AMQP protocol basics
- [ ] Connections and channels
- [ ] Exchanges (direct, fanout, topic, headers)
- [ ] Queues (durable, exclusive, auto-delete)
- [ ] Bindings and routing keys
- [ ] Message acknowledgment (ack, nack, reject)

### Patterns
- [ ] Work queues (competing consumers)
- [ ] Publish/Subscribe (fanout)
- [ ] Routing (direct exchange)
- [ ] Topics (pattern matching)
- [ ] RPC over RabbitMQ
- [ ] Dead letter exchanges (DLX)
- [ ] Message TTL
- [ ] Priority queues

### Operations
- [ ] Management UI
- [ ] Virtual hosts
- [ ] User permissions
- [ ] Clustering
- [ ] Mirrored queues (high availability)
- [ ] Shovel (cross-cluster replication)
- [ ] Monitoring and alerting

---

## 🚀 Phase 5 Project

- [ ] **Email/Notification Processing Service** — Celery workers, RabbitMQ, retry logic, priority queues, rate limiting, monitoring with Flower

---

## 📖 Resources

- **Docs:** [Celery Official Docs](https://docs.celeryq.dev/)
- **Docs:** [RabbitMQ Tutorials](https://www.rabbitmq.com/tutorials) — official step-by-step
- **Course:** [TestDriven.io — Django + Celery](https://testdriven.io/)
- **YouTube:** [Pretty Printed](https://www.youtube.com/@prettyprinted) — Celery tutorials
- **Book:** RabbitMQ in Action (Manning)
