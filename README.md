# 🛡️ Bot Killer — Adaptive Web & Application-Layer Protection

> **⚡ Automated `Nginx` & `Apache` defense for portals, web apps, and streaming/STB platforms**  
> Combines temporary bans, rolling-window repeat-offender escalation to permanent bans, automated datacenter/VPN list enrichment, synchronized service reloads, `dry-run` safety, and a **live online dashboard** for real-time operational monitoring.

---

## 🎯 What It Protects Against

| 🛡️ Attack Vector | 🔍 Threat Behavior | ⚙️ How Bot Killer Responds |
| :--- | :--- | :--- |
| **🔐 Auth & STB Brute-Force** | Bursts of failed logins and repeated authentication/STB errors | Detects threshold spikes and applies rapid temporary blocks |
| **🔄 MAC Address Rotation** | Attackers rotating MAC addresses to bypass single-identifier blocks | Enforces source-level (`IP`) rules, rolling-window tracking, and permanent ban escalation at the web-server layer |
| **🤖 Bots & Scanners** | Automated path scanning, probes, and abusive request patterns | Modular detection blocks automated noise and reduces server resource strain |
| **🌐 Datacenter & VPN Floods** | High-frequency abuse originating from hosting/DC or VPN ranges | Enriches datacenter/VPN lists and speeds up filtering of high-risk sources |
| **🔁 Repeat Offenders** | Persistent violators returning after temporary bans expire | Tracks offense history across a rolling time window and escalates repeaters into permanent bans |

---

## 📊 Live Online Dashboard & Operational Workflow

* **📈 Real-Time Online Dashboard:** Monitor live operation, active bans, repeat offenders, permanent blocks, and DC/VPN activity at a glance—without relying solely on raw terminal logs.
* **🔄 Synchronized Service Reloads:** Every state change updates rule files for `Nginx` and `Apache` and triggers safe, synchronized service reloads.
* **🧪 Safe Rollout (`Dry-Run` & Tuning):** Test behavior safely before full enforcement and tune thresholds to match real portal, web, or streaming/STB traffic.
* **🧭 Clear Architectural Scope:** Built for HTTP/application and web-server defense and server load reduction. It complements—rather than replaces—upstream volumetric network-edge DDoS protection.

---

## 📦 Deployment, Tuning & Licensing

Whether you run a high-traffic portal, a streaming/STB platform, or a managed web environment, deployment can be tailored to your stack:

* **🚀 Standard Setup:** Core installation on `Nginx` / `Apache`, baseline configuration, and `dry-run` validation.
* **🎛️ Custom Setup & Tuning:** Full deployment tailored to your logs, traffic profile, attack vectors, and threshold tuning.
* **🤝 Licensing & Support:** Ongoing operational support, rule adjustments, and real-time monitoring guidance.

---

## 📩 Inquiries, Custom Setups & Licensing

Interested in deploying **Bot Killer** on your infrastructure, tuning thresholds for your traffic, or discussing licensing and support?  
Reach out directly via message or through your preferred contact channel with your web-server stack (`Nginx` / `Apache`) and main traffic challenges.
