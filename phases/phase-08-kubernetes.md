# 📌 Phase 8 — Kubernetes (2 Months)

## ☸️ Core Concepts

### Architecture
- [ ] Control plane (API server, etcd, scheduler, controller manager)
- [ ] Worker nodes (kubelet, kube-proxy, container runtime)
- [ ] Cluster networking model
- [ ] kubectl basics and context switching

### Workloads
- [ ] Pods (single and multi-container)
- [ ] Init containers
- [ ] Sidecar containers
- [ ] Deployments (rolling updates, rollbacks)
- [ ] ReplicaSets
- [ ] StatefulSets (databases, ordered deployment)
- [ ] DaemonSets (per-node workloads)
- [ ] Jobs and CronJobs
- [ ] Pod lifecycle and restart policies

### Configuration
- [ ] ConfigMaps (environment variables, files)
- [ ] Secrets (opaque, TLS, docker-registry)
- [ ] Environment variables from ConfigMaps/Secrets
- [ ] Resource requests and limits (CPU, memory)
- [ ] LimitRanges and ResourceQuotas
- [ ] Pod security contexts
- [ ] Pod Disruption Budgets

### Networking
- [ ] Services (ClusterIP, NodePort, LoadBalancer, ExternalName)
- [ ] Ingress controllers (nginx, traefik)
- [ ] Ingress rules and TLS
- [ ] Network Policies (pod-to-pod firewalling)
- [ ] DNS in Kubernetes (CoreDNS)
- [ ] Service mesh basics (Istio/Linkerd overview)

### Storage
- [ ] Volumes (emptyDir, hostPath)
- [ ] PersistentVolumes (PV)
- [ ] PersistentVolumeClaims (PVC)
- [ ] StorageClasses
- [ ] Dynamic provisioning
- [ ] Volume snapshots

---

## 🔧 Operations

### Scaling
- [ ] Horizontal Pod Autoscaler (HPA)
- [ ] Vertical Pod Autoscaler (VPA)
- [ ] Cluster Autoscaler
- [ ] Custom metrics scaling

### Observability
- [ ] kubectl logs, describe, exec, port-forward
- [ ] Prometheus + Grafana on Kubernetes
- [ ] Liveness, readiness, and startup probes
- [ ] Events and troubleshooting
- [ ] kube-state-metrics

### Helm
- [ ] Chart structure
- [ ] values.yaml and overrides
- [ ] Template syntax
- [ ] Chart repositories
- [ ] Helm hooks
- [ ] Creating custom charts
- [ ] Helmfile (managing multiple charts)

### Security
- [ ] RBAC (Roles, ClusterRoles, Bindings)
- [ ] ServiceAccounts
- [ ] Pod Security Standards (restricted, baseline)
- [ ] Network policies for isolation
- [ ] Image pull secrets
- [ ] Secrets encryption at rest

### GitOps
- [ ] ArgoCD or Flux basics
- [ ] Declarative vs imperative management
- [ ] Sync policies
- [ ] Application sets

---

## 🚀 Phase 8 Project

- [ ] **Deploy Django + PostgreSQL + Redis on Kubernetes** — Deployments, Services, ConfigMaps, Secrets, PVCs, Ingress, HPA, Helm chart

---

## 📖 Resources

- **Docs:** [Kubernetes Official Docs](https://kubernetes.io/docs/)
- **Course:** [TechWorld with Nana — Kubernetes Tutorial](https://www.youtube.com/@TechWorldwithNana)
- **Course:** [KodeKloud — CKAD prep](https://kodekloud.com/)
- **Practice:** [killer.sh](https://killer.sh/) — CKAD exam simulator
- **Practice:** [Play with Kubernetes](https://labs.play-with-k8s.com/)
- **Book:** Kubernetes in Action — Marko Lukša
- **Tool:** [k9s](https://k9scli.io/) — terminal UI for Kubernetes
