# Threat-Intelligence---lumma-stealer

# Lumma Stealer Threat Intelligence Project

### Targeted Threat Research on Lumma Stealer with a Focus on relating it to the Bahamas

This repository contains the full threat intelligence analysis I conducted on Lumma Stealer, an active info stealer malware strain. The project originated from a real-life incident response case and expanded into a regional deep dive into how Lumma affects sectors in the Bahamas.

---

##  Report Overview

The report includes:
- A full technical breakdown of Lumma Stealer's capabilities and TTPs
- MITRE ATT&CK mapping and infrastructure patterns
- IOC collection from [ThreatFox](https://threatfox.abuse.ch)
- VirusTotal hash enrichment and C2 profiling
- Dashboard development for visual IOC tracking
- Actionable detection and hunting recommendations
- End-user awareness and defense tips


---

##  Tools and Tech Stack

- `Python 3.10+`
- `Flask` (for dashboard integration)
- `ThreatFox API (abuse.ch)`
- `VirusTotal API`
- `AbuseIPDB API`
- `pandas`, `requests`, `dotenv`

---

##  Key Findings

- Lumma is actively abusing `.cfd`, `.click`, and `.top` TLDs
- Numerous fake banking domains observed targeting Caribbean IP ranges
- C2 infrastructure exhibits rapid rotation and evasive behavior

---


[Threat Intel - Lumma.pdf](https://github.com/user-attachments/files/19624776/Threat.Intel.-.Lumma.pdf)
