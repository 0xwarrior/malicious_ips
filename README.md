
<div align="center">

```
  ╔██████╗ ██╗  ██╗    ██╗    ██╗ █████╗ ██████╗ ██████╗ ██╗ ██████╗ ██████╗ 
  ██╔═══██╗╚██╗██╔╝    ██║    ██║██╔══██╗██╔══██╗██╔══██╗██║██╔═══██╗██╔══██╗
  ██║   ██║ ╚███╔╝     ██║ █╗ ██║███████║██████╔╝██████╔╝██║██║   ██║██████╔╝
  ██║   ██║ ██╔██╗     ██║███╗██║██╔══██║██╔══██╗██╔══██╗██║██║   ██║██╔══██╗
  ╚██████╔╝██╔╝ ██╗    ╚███╔███╔╝██║  ██║██║  ██║██║  ██║██║╚██████╔╝██║  ██║
   ╚═════╝ ╚═╝  ╚═╝     ╚══╝╚══╝ ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝ ╚═════╝ ╚═╝  ╚═╝
```

### `// THREAT INTELLIGENCE — HOSTILE IP REGISTRY`

![Status](https://img.shields.io/badge/STATUS-ACTIVE_MONITORING-red?style=flat-square&labelColor=0d0d0d&color=ff2222)
![Threat Level](https://img.shields.io/badge/THREAT_LEVEL-ELEVATED-orange?style=flat-square&labelColor=0d0d0d&color=ff6600)
![Environment](https://img.shields.io/badge/ENVIRONMENT-LAB%2FHONEYPOT-blue?style=flat-square&labelColor=0d0d0d&color=0077ff)
![License](https://img.shields.io/badge/LICENSE-USE_AT_OWN_RISK-gray?style=flat-square&labelColor=0d0d0d&color=444)

</div>

---

## ⚠ ADVISORY

> **This repository documents IP addresses observed conducting hostile activity — primarily reconnaissance, scanning, and probing — within a controlled lab environment.**  
> All entries represent **first-hand observations**. No guarantees are made regarding completeness or ongoing accuracy. **Verify independently before operationalizing.**

---

## 🕵 WHAT THIS IS

A personal threat intel feed seeded from **direct honeypot and lab observations**.  
Every IP in this list did something to earn its place here.

```
[OBSERVED BEHAVIORS]
├── Port scanning / service enumeration
├── Brute-force attempts (SSH, RDP, HTTP)
├── Vulnerability probing (CVE-targeted payloads)
├── Credential stuffing
└── C2 callback attempts
```

This is **not a curated third-party feed** — it's raw, first-hand signal.

---

## 🔗 COMPANION INTELLIGENCE SOURCES

Cross-reference with established blocklists for higher-confidence detections:

| Source | Description | Link |
|--------|-------------|------|
| 🔥 **Emerging Threats** | Community firewall blocklist — widely deployed, actively maintained | [emerging-Block-IPs.txt](https://rules.emergingthreats.net/fwrules/emerging-Block-IPs.txt) |
| 🌐 **FireHOL IP Lists** | Aggregated feeds from 400+ sources — categorized by behavior | [iplists.firehol.org](https://iplists.firehol.org/) |

---

## 🚨 USAGE RECOMMENDATIONS

```python
# BEFORE YOU ACT ON THIS DATA:
assert verify_independently(ip) == True
assert check_false_positive_rate() < threshold
assert understand_your_environment() == True
```

- ✅ Use as **enrichment context** in SIEM/SOAR workflows  
- ✅ Cross-reference with **VirusTotal, AbuseIPDB, OTX** before blocking  
- ✅ Suitable as **threat hunting seed data**  
- ⛔ Do **not** auto-block in production without validation  
- ⛔ Do **not** treat as authoritative intelligence without corroboration  

---

## 📡 CONTRIBUTING / REPORTING

Observed hostile behavior from an IP not on the list?  
Open an issue or PR with:

- **IP address**
- **Observed behavior** (what was it doing?)
- **Timestamp / timeframe**
- **Source context** (honeypot / prod / lab)

---

<div align="center">

```
[ ALL QUIET ON THE WIRE... FOR NOW ]
```

*Trust nothing. Verify everything. Log it all.*

</div>
