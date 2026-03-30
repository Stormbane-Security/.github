<p align="center">
  <img src="https://www.stormbane.net/logo.png" alt="Stormbane Security" width="80" />
</p>

<h1 align="center">Stormbane Security</h1>

<p align="center">
  <strong>We find security vulnerabilities in your infrastructure and fix them.</strong>
</p>

<p align="center">
  <a href="https://www.stormbane.net">stormbane.net</a> · <a href="https://www.stormbane.net/scanning">Scanning</a> · <a href="https://www.stormbane.net/services">Consulting</a> · <a href="https://www.stormbane.net/blog">Blog</a>
</p>

---

### What we do

AI-powered vulnerability scanning and hands-on security consulting for cloud infrastructure, Kubernetes clusters, and CI/CD pipelines. We find the problems. Then we fix them.

```
$ beacon scan --target your-infrastructure.com
[*] Scanning target surface...
[+] Port 443/tcp open — TLS 1.2 (weak cipher)
[!] CVE-2024-3094 — xz backdoor detected
[+] Exposed .env — 3 secrets
[✓] 3 findings · 1 critical · report ready
```

### Services

| | Service | Description |
|---|---|---|
| 🔍 | **AI Vulnerability Scanning** | Automated scanning across cloud, Kubernetes, CI/CD, IaC, and web surface. One-time or continuous. |
| 🛠 | **Security Consulting** | Hands-on remediation — we fix issues directly in your Terraform, pipelines, and cluster configs. |
| 📄 | **Reporting & Prioritization** | AI-enriched reports with real attack paths, not just CVE dumps. Prioritized by actual exploitability. |

### Coverage

- **Cloud** — IAM, storage exposure, network segmentation, secrets in config (AWS, GCP, Azure)
- **Kubernetes** — RBAC, pod security, admission control, workload identity, supply chain
- **CI/CD** — GitHub Actions, GitLab CI, secrets handling, OIDC trust chains, runner isolation
- **IaC** — Terraform state, misconfigurations, drift detection
- **Web** — TLS, CORS, security headers, JWT, exposed endpoints

### Open Source

| Repository | Description |
|---|---|
| [**beacon**](https://github.com/Stormbane-Security/beacon) | AI-powered vulnerability scanner. Point it at a target, get a prioritized report. |
| [**bulwark**](https://github.com/Stormbane-Security/bulwark) | Infrastructure hardening toolkit. |

### Contact

Have a security concern or need an audit?

- 🌐 [stormbane.net](https://www.stormbane.net)
- 📧 hello@stormbane.net
- 👤 Founded by [Patrick Putman](https://patrickputman.dev)

---

<p align="center">
  <sub>Birmingham, AL · Serving clients worldwide</sub>
</p>
