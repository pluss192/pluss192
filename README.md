### 📌 Featured Projects

#### 🖥️ [net-health-dash](https://github.com/pluss192/net-health-dash)
A containerized, real-time IT infrastructure and network health dashboard.
- **Telemetry Streaming:** Pushes latency and CPU/RAM metrics over WebSockets every 3 seconds.
- **Data Visualization:** Rolling multi-line latency graphs using Recharts.
- **Architecture:** Node.js/Express, Socket.IO, React 18, Tailwind CSS, Docker Compose.

#### 🛡️ [sentinel-rate-limiter](https://github.com/pluss192/sentinel-rate-limiter)
Distributed API Gateway & Rate-Limiting Engine built to protect microservices against brute-force attacks and traffic spikes.
- **Sliding Window Log:** Atomic Redis pipeline tracking (`ZREMRANGEBYSCORE`, `ZCARD`, `ZADD`).
- **Fail-Open Resilience:** High-availability fallback design maintaining service uptime.
- **Deployment:** Fully dockerized with automated GitHub Actions CI testing.
