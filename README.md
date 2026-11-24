<div align="center">
  <img src="./banner.png" alt="Sardor Obidov — Developer Banner" width="100%" />
</div>

<br/>

# Sardor Obidov

**Backend & Systems Engineer · Linux Infrastructure · Python**

I design and operate backend services, REST APIs, self-hosted platforms, and automated Linux infrastructure with a focus on reliability, low overhead, and operational simplicity.

Good systems engineering goes beyond application code. It requires understanding how workloads behave from the kernel and network stack up to the service layer, handling failure modes gracefully, and keeping production environments predictable.

## Production Systems

### [obidovdev](https://obidovdev.uz) — Personal Platform & Lab
Central engineering hub and deployment showcase hosting production projects, infrastructure experiments, and technical notes.

### Email OTP Authentication Service (`api-otp`)
Standalone authentication microservice built with Django REST Framework, providing one-time password generation, request throttling, and stateless verification across services.

### [Ob-Havo/Dev](https://github.com/obidovdev/weather) — Trilingual Weather PWA
Lightweight Progressive Web App built with Flask and deployed on Ubuntu Linux behind Cloudflare, Caddy, and Gunicorn under persistent `systemd` process supervision.

### Course Attendance & Management Platform
Backend web system structured around normalized relational schemas, role-based access control, and consistent attendance state tracking.

## AI & Automation Services

### [obidovAI](https://ai.obidovdev.uz) — Multi-User AI Assistant & Automation Service
Publicly accessible Telegram-integrated AI service backed by self-hosted Ollama models (`qwen3`, `qwen2.5`).

Architected with persistent session memory, controlled tool execution, and guardrails to support multi-user access safely—combining low-cost local inference with dependable remote orchestration.

## Tech Stack

**Languages**
- Python, SQL, Bash

**Backend Engineering**
- Django, Django REST Framework, Flask
- REST APIs, OTP Authentication, Telegram Bot API

**Infrastructure & Operations**
- Linux (Ubuntu), `systemd`, Gunicorn
- Caddy, Cloudflare DNS & Edge Routing
- Git, `uv`, SSH, Linux Networking & Kernel Troubleshooting

**AI & Automation**
- Self-Hosted LLM Inference (Ollama: `qwen3`, `qwen2.5`)
- Multi-User Bot Orchestration & Automated Workflows

## Engineering Focus

- Building clean, maintainable backend architectures and microservices
- Running self-hosted Linux workloads with `systemd`, Caddy, and automated recovery
- Operating shared AI services with clear boundaries, resource controls, and uptime discipline
- Tuning Linux environments for continuous availability and low operational toil
- Applying practical security hygiene to APIs, ingress, and host configurations

## Privacy, Access & Signal-to-Noise

Not every repository needs to be public, and not every endpoint should be open without guardrails.

In production systems, unthrottled exposure creates noise, contention, and unnecessary risk. Reliable infrastructure relies on explicit access boundaries, rate limits, and clean interfaces—exposing only what is intentional, monitored, and ready for real traffic.

**I apply the same discipline to my engineering work and focus.**

Experimental prototypes, internal configs, and unfinished work stay private until proven solid. What lives here is deliberate, tested, and built to stay up.

## Connect

- **Portfolio:** [obidovdev.uz](https://obidovdev.uz)
- **Telegram:** [@srdpy](https://t.me/srdpy)
- **GitHub:** [@obidovdev](https://github.com/obidovdev)

---

*Clean architecture. Intentional engineering. Reliable systems.*