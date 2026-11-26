What the Product Is
An automated web and application-layer traffic protection system (Nginx / Apache) built for portals as well as web, streaming, and STB platforms. It monitors abuse patterns in logs and traffic, applies temporary bans, tracks repeat offenses across a rolling time window, and automatically promotes persistent offenders to permanent bans.

Attacks and Threats It Protects Against

Authentication & Access Abuse (Brute-Force / Auth & STB Errors): Detects and blocks sources generating bursts of failed logins or authentication errors.

MAC Address Rotation & Identifier Evasion: When attackers rotate MAC addresses to bypass single-identifier blocks, source-level (IP) enforcement, rolling-window tracking, and permanent ban escalation stop abusive traffic at the web server layer.

Bots, Scanners & Abusive Requests: Identifies and blocks automated path scanning, suspicious probes, and repetitive request patterns that strain server resources.

Datacenter & VPN Traffic (DC / VPN Sources): Recognizes and enriches datacenter/VPN address lists to speed up filtering of high-risk sources.

Repeat Offenders: Tracks offense history over a defined time window and automatically escalates recurring violators into permanent ban rules, reducing manual intervention and server load.

How It Operates & Realistic Scope

Every state change—temporary bans, DC/VPN list additions, permanent bans, and ban expirations—updates rule files for Nginx and Apache and triggers synchronized service reloads, with dry-run support and threshold tuning tailored to the target environment.

Designed for application/HTTP and web-server protection and load reduction; it complements rather than replaces upstream volumetric network DDoS mitigation.
