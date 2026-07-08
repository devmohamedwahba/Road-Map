# 📌 Phase 4 — Database Mastery (2 Months)

> 🗓️ **Start:** May 22, 2027  
> 🗓️ **End:** July 22, 2027

## 🐘 PostgreSQL

### Schema Design & Modeling
- [ ] Entity-Relationship diagrams
- [ ] Normalization (1NF, 2NF, 3NF, BCNF)
- [ ] When to denormalize (read performance vs write complexity)
- [ ] One-to-one, one-to-many, many-to-many relationships
- [ ] Polymorphic associations (and alternatives)
- [ ] Soft deletes vs hard deletes
- [ ] Audit columns (created_at, updated_at, created_by)
- [ ] UUID vs serial primary keys (tradeoffs)
- [ ] Migration strategy for evolving schemas (zero-downtime migrations)
- [ ] Schema versioning

### Core Concepts
- [ ] Data types (TEXT, INTEGER, NUMERIC, JSONB, ARRAY, UUID, TIMESTAMPTZ)
- [ ] Constraints (PRIMARY KEY, FOREIGN KEY, UNIQUE, CHECK, NOT NULL)
- [ ] Schemas and namespaces
- [ ] Sequences and identity columns

### Indexing
- [ ] B-Tree indexes (default)
- [ ] Hash indexes
- [ ] GIN indexes (full-text search, JSONB, arrays)
- [ ] GiST indexes (geometric, range types)
- [ ] Partial indexes (conditional)
- [ ] Composite indexes
- [ ] Expression indexes
- [ ] Covering indexes (INCLUDE)
- [ ] When NOT to index

### Query Optimization
- [ ] EXPLAIN and EXPLAIN ANALYZE
- [ ] Reading query plans (Seq Scan, Index Scan, Bitmap Scan)
- [ ] Join algorithms (Nested Loop, Hash Join, Merge Join)
- [ ] Cost estimation
- [ ] Query planner statistics
- [ ] Common Table Expressions (CTEs)
- [ ] Window functions (ROW_NUMBER, RANK, LAG, LEAD, SUM OVER)

### Advanced Features
- [ ] Partitioning (range, list, hash)
- [ ] Materialized Views
- [ ] JSONB operations and indexing
- [ ] Full-text search (tsvector, tsquery)
- [ ] Triggers and trigger functions
- [ ] Stored procedures and functions (PL/pgSQL)
- [ ] Row-level security (RLS)
- [ ] Advisory locks

### Replication & High Availability
- [ ] Streaming replication
- [ ] Logical replication
- [ ] Read replicas
- [ ] Failover strategies
- [ ] Connection pooling (PgBouncer)
- [ ] Vacuum and autovacuum
- [ ] pg_stat_statements (query analysis)

### Transactions
- [ ] ACID properties
- [ ] Isolation levels (Read Committed, Repeatable Read, Serializable)
- [ ] Deadlocks and how to avoid them
- [ ] Optimistic vs pessimistic locking
- [ ] SELECT FOR UPDATE

---

## ⚡ Redis

### Data Structures
- [ ] Strings (SET, GET, INCR, TTL)
- [ ] Lists (LPUSH, RPOP, LRANGE)
- [ ] Sets (SADD, SMEMBERS, SINTER, SUNION)
- [ ] Sorted Sets (ZADD, ZRANGE, ZRANK — leaderboards)
- [ ] Hashes (HSET, HGET, HGETALL)
- [ ] Streams (XADD, XREAD, consumer groups)
- [ ] HyperLogLog (cardinality estimation)
- [ ] Bitmaps

### Caching Patterns
- [ ] Cache-aside (lazy loading)
- [ ] Write-through
- [ ] Write-behind (write-back)
- [ ] Cache invalidation strategies
- [ ] TTL-based expiration
- [ ] Cache stampede prevention

### Advanced Use Cases
- [ ] Pub/Sub messaging
- [ ] Distributed locks (Redlock)
- [ ] Rate limiting (sliding window, token bucket)
- [ ] Session storage
- [ ] Job queues (simple)
- [ ] Real-time leaderboards
- [ ] Geospatial queries

### Operations
- [ ] Persistence (RDB snapshots, AOF)
- [ ] Redis Sentinel (high availability)
- [ ] Redis Cluster (horizontal scaling)
- [ ] Memory management and eviction policies
- [ ] Monitoring (INFO, MONITOR, redis-cli)
- [ ] Lua scripting

---

## 🚀 Phase 4 Project

- [ ] **Analytics Platform** — PostgreSQL (complex queries, materialized views), Redis (caching, real-time counters), query optimization

---

## 📖 Resources

- **Book:** Designing Data-Intensive Applications — Martin Kleppmann (chapters 1-3, 5-7)
- **Docs:** [PostgreSQL Official Docs](https://www.postgresql.org/docs/current/)
- **Docs:** [Redis Official Docs](https://redis.io/docs/)
- **Course:** [Hussein Nasser YouTube](https://www.youtube.com/@haboringuy) — database internals, indexing, replication
- **Practice:** [pgexercises.com](https://pgexercises.com/) — interactive SQL exercises
- **Tool:** [explain.dalibo.com](https://explain.dalibo.com/) — visualize PostgreSQL query plans
