# Hi there, I'm Pluscase Madoya 👋

Software Engineer specializing in Backend Systems, Distributed Architecture, and DevSecOps Automation.

---

### 🛠️ Tech Stack & Tooling

- **Backend & Core:** Node.js, Express.js, REST APIs, WebSockets (Socket.IO)
- **Data & Caching:** Redis, PostgreSQL, In-Memory Stores
- **DevOps & Containers:** Docker, Docker Compose, Linux, Git, GitHub Actions CI/CD
- **Security & DevSecOps:** Shift-left security pipelines, Gitleaks, Aqua Security Trivy, Least-privilege containerization

---

### 📌 Featured Projects

#### 🖥️ [net-health-dash](https://github.com/pluss192/net-health-dash)
A containerized, real-time IT infrastructure and network telemetry health dashboard.
- **Telemetry Streaming:** Pushes latency and host CPU/RAM metrics over WebSockets every 3 seconds.
- **Data Visualization:** Rolling multi-line latency metrics powered by Recharts.
- **Tech Stack:** Node.js, Express, Socket.IO, React 18, Tailwind CSS, Docker Compose.

#### 🛡️ [sentinel-rate-limiter](https://github.com/pluss192/sentinel-rate-limiter)
A distributed API Gateway and sliding-window rate-limiting engine designed to safeguard microservices from traffic spikes and brute-force attempts.
- **Sliding Window Log:** Atomic Redis pipeline tracking (`ZREMRANGEBYSCORE`, `ZCARD`, `ZADD`).
- **Fail-Open Resilience:** High-availability fallback design ensuring uninterrupted service.
- **Tech Stack:** Node.js, Express, Redis 7, Docker, GitHub Actions CI.

#### 🔒 [vault-guardian-ci](https://github.com/pluss192/vault-guardian-ci)
An automated DevSecOps continuous integration pipeline providing shift-left security enforcement.
- **Vulnerability & Secret Auditing:** Zero-trust pipeline integrating Gitleaks for secret detection and Aqua Security Trivy for container image scanning.
- **Hardened Deployment:** Multi-stage Docker build utilizing non-root runtime privilege separation.
- **Tech Stack:** Docker, GitHub Actions, Aqua Trivy, Gitleaks, Node.js.

---

### 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pluss192&show_icons=true&theme=tokyonight&hide_border=true" alt="pluss192 GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pluss192&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>
