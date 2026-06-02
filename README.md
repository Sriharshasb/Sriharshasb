# Hi there, I'm Sriharsha 👋

### 🚀 Senior Infrastructure Engineer specializing in System Reliability, Data Durability, and Automated Observability

With 12+ years of enterprise experience ensuring data durability, business continuity, and disaster recovery orchestration for high-availability environments, I specialize in engineering reliable infrastructure platforms. I bridge the gap between enterprise data planes (Dell PPDM, Data Domain, Virtualization) and modern cloud-native observability stacks.

- 📍 Based in Auckland, New Zealand
- 💼 Actively open to Senior Infrastructure / SRE / Platform Engineering roles
- ✉️ Connect with me on [LinkedIn](https://www.linkedin.com/in/sriharsha-sabbarapu-5719b4175/) or via email at [sriharshasb@gmail.com]

---

## 🛠️ Tech Stack & Capabilities


| Domain | Tools & Technologies |
| :--- | :--- |
| **Observability & Telemetry** | Prometheus, Grafana, Alertmanager, OpenTelemetry |
| **Automation & Scripting** | Python (REST APIs, custom exporters), Bash, Git |
| **Infrastructure & Storage** | Dell PPDM, Data Domain, PowerProtect, VMware ESXi, Linux/Windows Server |
| **SRE Methodologies** | SLA/SLO/SLI Tracking, Incident Response, Toil Reduction, Chaos/DR Testing |

---

## 🔬 Featured Engineering & Automation Projects

### 📡 [Dell PPDM Prometheus Exporter]
*An automated telemetry bridge designed to eliminate manual infrastructure checkouts (Toil) and enforce unified observability across enterprise data protection planes.*
- **The Core Problem:** Dell PPDM lacks a native Prometheus metrics endpoint, creating an isolated infrastructure silo that separates backup compliance from core platform monitoring.
- **The Engineering Solution:** Developed a stateless Python microservice that handles authentication dynamically via secure environment variables, leverages server-side pagination via OData query filters to maintain a flat memory footprint, and exposes a high-utility metrics stream (`:8000/metrics`) to a Prometheus TSDB.
- **The Reliability Impact:** Enabled centralized Grafana dashboarding for storage saturation trend lines and real-time Slack alerting via Alertmanager for silent SLA breaches (stuck jobs), significantly reducing MTTR.

---

## 📊 The SRE Mindset: Engineering for High Availability

I don't just run tools; I design for system reliability:
- **From Backup Windows to SLOs:** I treat data protection windows as strict Service Level Objectives, measuring system durability as a primary platform reliability indicator.
- **From Manual Triage to Toil Reduction:** If an infrastructure failure requires repetitive manual intervention, I automate the metrics collection, alerting pathway, or remediation playbook.
- **From Disaster Recovery to Chaos Engineering:** My years orchestrating full-site bare-metal restores mean I approach complex software systems with a "design for failure" mentality.

---

### 📈 GitHub Statistics
![Sriharsha's GitHub Stats](https://vercel.app)
