# 📌 Phase 14 — Application Security (Ongoing, deep-dive during Infra Track)

> 🗓️ **Start:** September 22, 2027 (deep-dive alongside Phase 6 – AWS & infra)  
> 🗓️ **End:** Ongoing — security is never "done"

> Security topics show up scattered across other phases (JWT, RBAC, IAM). This phase is the dedicated deep-dive so it isn't just an afterthought for a "Senior" title.

## 🔐 Fundamentals

- [ ] OWASP Top 10 (know each one, not just the name)
- [ ] Injection attacks (SQL injection, command injection) and parameterized queries
- [ ] Cross-Site Scripting (XSS) — stored, reflected, DOM-based
- [ ] Cross-Site Request Forgery (CSRF) and tokens
- [ ] Broken authentication patterns
- [ ] Security misconfiguration
- [ ] Sensitive data exposure
- [ ] Server-Side Request Forgery (SSRF)
- [ ] Insecure deserialization

## 🔑 AuthN / AuthZ

- [ ] Password hashing (bcrypt, argon2) — never roll your own
- [ ] Session vs token-based auth tradeoffs
- [ ] OAuth2 flows (authorization code, client credentials, PKCE)
- [ ] OIDC vs OAuth2
- [ ] Multi-factor authentication (MFA/TOTP)
- [ ] Least privilege and RBAC/ABAC in practice
- [ ] Secrets rotation policies

## 🧰 Secure Development Practices

- [ ] Input validation vs output encoding
- [ ] Dependency scanning (pip-audit, Snyk, Dependabot)
- [ ] Static Application Security Testing (SAST) in CI
- [ ] Secret scanning (gitleaks, trufflehog) — never commit secrets
- [ ] Container image scanning (trivy)
- [ ] Security headers (CSP, HSTS, X-Frame-Options)
- [ ] Rate limiting and brute-force protection
- [ ] Logging without leaking PII/secrets

## ☁️ Infrastructure Security

- [ ] Principle of least privilege for IAM
- [ ] Network segmentation (security groups, NACLs, private subnets)
- [ ] Encryption at rest and in transit (TLS everywhere)
- [ ] Secrets management (never in env files committed to git)
- [ ] Audit logging (CloudTrail equivalents)
- [ ] Incident response basics (what to do when a key leaks)

## 🚀 Practice

- [ ] Run OWASP ZAP or Burp Suite against one of your own projects
- [ ] Fix every finding from a dependency scan on an existing repo
- [ ] Add gitleaks + SAST to a CI pipeline
- [ ] Do a couple of rounds on a legal practice platform (PortSwigger Web Security Academy, TryHackMe) to see attacks first-hand

---

## 📖 Resources

- **Web:** [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- **Practice:** [PortSwigger Web Security Academy](https://portswigger.net/web-security) — free, hands-on labs
- **Practice:** [TryHackMe](https://tryhackme.com/) — guided security challenges
- **Tool:** [OWASP ZAP](https://www.zaproxy.org/) — free security scanner
- **Course:** [Hussein Nasser — Backend Security playlist](https://www.youtube.com/@haboringuy)
- **Docs:** [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/)
