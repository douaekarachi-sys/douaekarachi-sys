<div align="center">

# Douae Karachi

**Cybersecurity Analyst — SOC · Threat Detection · Network & Application Security**

Rabat, Morocco · Cisco Certified Associate, Cyber Threat Management

[LinkedIn](https://www.linkedin.com/in/douae-karachi-2a93372b5/) ·
[Portfolio](https://cspjcts.pages.dev/) ·
[Email](mailto:douaekarachi@gmail.com)

</div>

---

I work toward SOC (Tier 1/2) roles, and I learn by building. The repositories
below aren't tutorials followed to the letter — they're environments I designed,
deployed, attacked, and debugged myself. Together they cover the ground a SOC
analyst actually stands on: network security, web-application defense, traffic
analysis, enterprise infrastructure, and the security-adjacent engineering
(data, DevSecOps, ML) that makes the rest make sense.

When something breaks, the fix and the error message end up in the README —
because that's where the real learning is.

---

## Selected work — Security

**[secure-network-architecture](https://github.com/douaekarachi-sys/secure-network-architecture)**
Multi-site hub-and-spoke design applying defense in depth: IT/OT separation via a
**one-way data diode**, mTLS DMZs with default-deny, encrypted IPSec tunnels, a
central SOC (SIEM/SOAR), and a NAC policy. Documented with validated diagrams.

**[dvwa-coraza-waf](https://github.com/douaekarachi-sys/dvwa-coraza-waf)**
Web attack/defense lab. The same SQL injection returns the **entire user table**
when sent directly — and gets a **403** through a Coraza WAF (OWASP CRS).
Measured A/B, with an automated test proving the block.

**[tcp-udp-sockets-wireshark](https://github.com/douaekarachi-sys/tcp-udp-sockets-wireshark)**
TCP vs UDP client/server in Python, analyzed at the packet level in Wireshark —
down to payload lengths matching the exact bytes on the wire.

**[enterprise-infrastructure-lab](https://github.com/douaekarachi-sys/enterprise-infrastructure-lab)**
Segmented enterprise network on PNETLab: pfSense perimeter, per-department VLANs,
Active Directory with **PowerShell** provisioning, Zimbra mail, centralized
DHCP/DNS, and a Kali node for testing.

**[reverse-proxy-lab](https://github.com/douaekarachi-sys/reverse-proxy-lab)**
Reverse proxy with path-based routing to backends on a **non-routable Docker
network** — the internal services are unreachable except through the proxy, which
also preserves the real client IP for logging.

**[VoxGuard](https://github.com/douaekarachi-sys/VoxGuard)**
Audio deepfakes from both sides: voice cloning (XTTS-v2) and detection (WavLM +
cosine similarity), framed by an explicit usage charter and ethics memo.

## Selected work — Engineering

**[bigdata-hadoop-spark-elasticsearch](https://github.com/douaekarachi-sys/bigdata-hadoop-spark-elasticsearch)**
The same computation implemented three ways — MapReduce, Spark and Elasticsearch
— to compare batch vs real-time, with a full ETL pipeline. (ELK is the backbone
of most SIEMs.)

**TruckFlow** — Spring Boot platform wired into a complete DevSecOps chain:
GitHub Actions CI + **SonarQube quality gate** → Jenkins CD → Argo CD GitOps →
Grafana/Prometheus.

**salleflow** — FastAPI booking system with three **isolated PostgreSQL schemas**,
least-privilege database roles, and a concurrency test against double-booking.

---

## Tools I've worked with

**Network & security** — pfSense · Suricata · Snort · Wireshark · Coraza WAF ·
OWASP CRS · Nmap
**Systems** — Linux · Windows Server · Active Directory · Docker
**Data & observability** — Elasticsearch · Kibana · Grafana · Prometheus ·
Hadoop · Spark
**Scripting** — Python · PowerShell · Bash
**CI/CD** — GitHub Actions · Jenkins · SonarQube · Argo CD

**Going deeper on** — Wazuh & Splunk (SIEM operations) · MITRE ATT&CK ·
threat hunting · CompTIA Security+ (in progress)

---

## Languages

French (native) · Arabic (native) · English (fluent)

<div align="center">

Open to SOC Analyst roles and freelance opportunities.

</div>
