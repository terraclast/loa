# 📁 Personal File Server & Infrastructure Project

This project documents the setup and management of a self-hosted file server used for remote access to personal archives, study material, and automation tools. Built entirely on open-source tools and administered via Linux, this project reflects a strong focus on self-reliance, security, and DevOps discipline.

---

## 🌐 Project Purpose

- Create a reliable, remotely accessible storage system for personal use.
- Reinforce knowledge in Linux system administration, scripting, security hardening, and monitoring.
- Serve as a practical DevOps/IT operations portfolio project.
- Implement automation for maintenance, alerts, and observability.

---

## 🧰 Technology Stack (Abstracted)

The system is based on:

- A virtualized Linux host
- Open-source file synchronization platform
- Secure reverse proxy with TLS support
- Fail2Ban for brute-force mitigation
- Lightweight monitoring & metrics solution
- Cron-driven automation
- Git for version control

> **Note:** Specific technologies and network details are omitted for security purposes. Only non-sensitive source code and notes are shared in this repository.

---

## 🔐 Security Highlights

- Remote root access disabled
- Strong firewall rules and port controls
- Enforced HTTPS with certificate automation
- System update automation
- Monitoring and alerting integrated for key services
- Auth rate-limiting and ban policies configured

---

## ⚙️ Automation & Maintenance

- System updates run weekly via cron.
- Log monitoring and basic metrics are exposed to a local dashboard.
- IP address changes are detected and logged.
- Maintenance windows are configured to reduce user-facing impact.

---

## 📓 Lessons and Value

This system has already been tested under live conditions and has proven resilient through:

- Version upgrades
- System reconfiguration
- Storage allocation failures
- Application errors and recovery scenarios

Through these challenges, I’ve strengthened skills in:

- Linux troubleshooting and recovery
- Secure service exposure
- Resource monitoring
- Update/upgrade workflows
- Real-world debugging under pressure

---

## 🚧 Ongoing Work

- Integrate automated backup workflows
- Expand dashboards with custom visualizations
- Refactor monitoring configuration for modularity
- Add logging aggregation and alert routing

---

## 📘 About This Repo

This repository contains:

- Scripts and automation helpers (sanitized)
- Logs of major infrastructure events (sanitized)
- Configuration and upgrade documentation
- Incident response summaries

Sensitive information has been intentionally omitted or abstracted to ensure privacy and reduce attack surface.

---

## 🤝 Contributing / Feedback

This project is not accepting contributions at this time. However, feedback, learning resources, and constructive questions are always welcome via the GitHub Issues section.

