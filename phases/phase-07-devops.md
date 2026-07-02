# 📌 Phase 7 — DevOps (2 Months)

## 🐳 Docker

### Fundamentals
- [ ] Images vs containers
- [ ] Dockerfile instructions (FROM, RUN, COPY, CMD, ENTRYPOINT)
- [ ] Build context and .dockerignore
- [ ] Layers and caching
- [ ] Multi-stage builds (reduce image size)
- [ ] Image tagging and versioning

### Networking
- [ ] Bridge networks
- [ ] Host networking
- [ ] Custom networks
- [ ] Container-to-container communication
- [ ] Port mapping

### Volumes & Storage
- [ ] Named volumes
- [ ] Bind mounts
- [ ] tmpfs mounts
- [ ] Volume drivers

### Docker Compose
- [ ] Service definitions
- [ ] Environment variables and .env files
- [ ] Depends_on and health checks
- [ ] Volume sharing between services
- [ ] Profiles (dev vs test vs prod)
- [ ] Override files (docker-compose.override.yml)

### Best Practices
- [ ] Non-root users in containers
- [ ] Minimal base images (alpine, distroless, slim)
- [ ] Security scanning (trivy, docker scout)
- [ ] Resource limits (memory, CPU)
- [ ] Logging drivers
- [ ] Health checks

---

## 🔄 CI/CD

### GitHub Actions
- [ ] Workflow syntax (on, jobs, steps)
- [ ] Triggers (push, pull_request, schedule, workflow_dispatch)
- [ ] Matrix builds
- [ ] Secrets and environment variables
- [ ] Caching (pip, node_modules, docker layers)
- [ ] Artifacts (upload/download)
- [ ] Reusable workflows
- [ ] Custom actions

### Pipeline Design
- [ ] Lint → Test → Build → Deploy
- [ ] Branch strategy (trunk-based, GitFlow)
- [ ] Pull request checks
- [ ] Automated versioning (semantic-release)
- [ ] Blue/green deployments
- [ ] Canary deployments
- [ ] Rollback strategies
- [ ] Environment promotion (dev → staging → prod)

### Additional CI/CD Tools
- [ ] Pre-commit hooks
- [ ] Dependabot / Renovate (dependency updates)
- [ ] Code coverage enforcement
- [ ] SAST (static security analysis)

---

## 📊 Monitoring & Observability

### The Three Pillars
- [ ] Metrics (what happened)
- [ ] Logs (why it happened)
- [ ] Traces (where it happened)

### Prometheus
- [ ] Metrics types (counter, gauge, histogram, summary)
- [ ] PromQL (query language)
- [ ] Exporters (node, postgres, redis, custom)
- [ ] Service discovery
- [ ] Alert rules
- [ ] Recording rules

### Grafana
- [ ] Dashboard creation
- [ ] Panels and visualizations
- [ ] Variables and templating
- [ ] Alerting
- [ ] Data sources (Prometheus, Loki, PostgreSQL)

### Loki (Log Aggregation)
- [ ] Log collection with Promtail
- [ ] LogQL (query language)
- [ ] Labels and streams
- [ ] Integration with Grafana

### OpenTelemetry
- [ ] Instrumentation (auto vs manual)
- [ ] Traces, spans, and context propagation
- [ ] Exporters (Jaeger, Zipkin, OTLP)
- [ ] Metrics collection
- [ ] Baggage and attributes

### Alerting
- [ ] Alert design (severity, routing, silencing)
- [ ] PagerDuty / OpsGenie integration
- [ ] Runbooks
- [ ] SLOs and error budgets

---

## 🚀 Phase 7 Project

- [ ] **Production CI/CD Pipeline** — GitHub Actions, Docker, automated tests, deployment to AWS, Prometheus + Grafana monitoring

---

## 📖 Resources

- **Docs:** [Docker Official Docs](https://docs.docker.com/)
- **Docs:** [GitHub Actions Docs](https://docs.github.com/en/actions)
- **Docs:** [Prometheus Docs](https://prometheus.io/docs/)
- **Course:** [TechWorld with Nana YouTube](https://www.youtube.com/@TechWorldwithNana) — Docker, CI/CD, DevOps
- **Book:** The Phoenix Project (DevOps culture)
- **Practice:** [Play with Docker](https://labs.play-with-docker.com/) — free online Docker lab
