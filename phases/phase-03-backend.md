# 📌 Phase 3 — Modern Backend (2–3 Months)

## ⚡ FastAPI

### HTTP & Networking Fundamentals (prerequisite)
- [ ] HTTP request/response lifecycle
- [ ] HTTP methods semantics (GET is safe, PUT is idempotent, POST is not)
- [ ] Status codes (2xx, 3xx, 4xx, 5xx) — know the common ones by heart
- [ ] Headers (Content-Type, Authorization, Cache-Control, ETag)
- [ ] Cookies and sessions
- [ ] CORS — what it is, preflight requests, why browsers enforce it
- [ ] TLS/HTTPS handshake (conceptual)
- [ ] DNS resolution flow
- [ ] TCP three-way handshake (conceptual)
- [ ] HTTP/1.1 vs HTTP/2 vs HTTP/3 differences
- [ ] Keep-alive connections and connection pooling
- [ ] Content negotiation

### Fundamentals
- [ ] Project structure and organization
- [ ] Path parameters and query parameters
- [ ] Request body (Pydantic models)
- [ ] Response models and status codes
- [ ] Path operation decorators (GET, POST, PUT, DELETE, PATCH)

### Dependency Injection
- [ ] Basic dependencies
- [ ] Sub-dependencies
- [ ] Dependencies with yield (resource cleanup)
- [ ] Class-based dependencies
- [ ] Global dependencies
- [ ] Overriding dependencies in tests

### Middleware
- [ ] CORS middleware
- [ ] Custom middleware (timing, logging, request ID)
- [ ] Exception handlers
- [ ] Request/response interceptors

### Authentication & Security
- [ ] OAuth2 with Password flow
- [ ] JWT tokens (access + refresh)
- [ ] Token expiration and rotation
- [ ] Role-based access control (RBAC)
- [ ] API key authentication
- [ ] Rate limiting
- [ ] HTTPS and security headers

### Advanced Features
- [ ] Background tasks
- [ ] WebSockets
- [ ] Server-Sent Events (SSE)
- [ ] File uploads/downloads
- [ ] Streaming responses
- [ ] Lifespan events (startup/shutdown)
- [ ] Custom APIRouter
- [ ] Versioning strategies

### Database Integration
- [ ] SQLAlchemy async (asyncpg)
- [ ] Alembic migrations
- [ ] Repository pattern with FastAPI
- [ ] Connection pooling
- [ ] Transaction management

### API Design
- [ ] RESTful conventions
- [ ] Pagination (cursor-based vs offset)
- [ ] Filtering and sorting
- [ ] Error response format
- [ ] OpenAPI documentation customization
- [ ] API versioning

---

## 🎯 Django Advanced

### ORM Deep Dive
- [ ] QuerySet API (select_related, prefetch_related)
- [ ] Custom managers and querysets
- [ ] Q objects and complex lookups
- [ ] F expressions and annotations
- [ ] Aggregation (Sum, Count, Avg, Max)
- [ ] Subqueries
- [ ] Raw SQL when needed
- [ ] Database functions

### Signals
- [ ] pre_save, post_save
- [ ] pre_delete, post_delete
- [ ] m2m_changed
- [ ] request_started, request_finished
- [ ] Custom signals
- [ ] When to use signals vs overriding save()

### Middleware
- [ ] Request/response cycle
- [ ] Custom middleware classes
- [ ] Middleware ordering matters
- [ ] Async middleware

### Custom Management Commands
- [ ] Command structure
- [ ] Arguments and options
- [ ] Colored output
- [ ] Scheduling with cron/celery

### Performance Optimization
- [ ] N+1 query problem
- [ ] Database indexing from Django
- [ ] Caching (per-view, template fragment, low-level)
- [ ] Django Debug Toolbar
- [ ] Query optimization with EXPLAIN
- [ ] Lazy loading vs eager loading
- [ ] Pagination

### Django REST Framework (DRF)
- [ ] Serializers (ModelSerializer, custom)
- [ ] ViewSets and Routers
- [ ] Permissions
- [ ] Throttling
- [ ] Filtering (django-filter)
- [ ] Nested serializers
- [ ] Custom actions

---

## 🚀 Phase 3 Projects

- [ ] **Enterprise REST API** — FastAPI, JWT auth, RBAC, PostgreSQL, pagination, rate limiting
- [ ] **Django Admin Dashboard** — custom admin, optimized queries, caching

---

## 📖 Resources

- **Docs:** [FastAPI Official Docs](https://fastapi.tiangolo.com/) — one of the best documentation sites in Python
- **Docs:** [Django Official Docs](https://docs.djangoproject.com/)
- **Docs:** [DRF Official Docs](https://www.django-rest-framework.org/)
- **Course:** [TestDriven.io FastAPI tutorials](https://testdriven.io/)
- **Book:** Two Scoops of Django
- **YouTube:** [Bug Bytes](https://www.youtube.com/@bugbytes3923) — Django & FastAPI tutorials
