<div align="center">

# VampSecure Labs

**Professional open-source security auditing toolkit**  
*by [VampSecure Studios](https://vampsecurestudios.com) · Security Research Division*

[![Tools](https://img.shields.io/badge/tools-18-8B0000?style=flat-square)](https://github.com/orgs/vampsecure-labs/repositories)
[![Language](https://img.shields.io/badge/language-Python%203.10%2B-blue?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![Platform](https://img.shields.io/badge/platform-linux%20%7C%20macos-lightgrey?style=flat-square)](https://github.com/vampsecure-labs)

</div>

---

## Toolkit Overview

18 standalone CLI tools for professional penetration testing and security auditing. Each tool exports **Rich console output**, **JSON**, **HTML** and a **client PDF report** (VSL unified format). All tools chain together via [vamp-orchestrator](https://github.com/vampsecure-labs/vamp-orchestrator).

### Reconnaissance & Attack Surface

| Tool | Description |
|------|-------------|
| [vamp-passive-recon](https://github.com/vampsecure-labs/vamp-passive-recon) | Passive recon + ASM — 8 OSINT sources, Shodan, cert history |
| [vamp-subdomain-takeover](https://github.com/vampsecure-labs/vamp-subdomain-takeover) | Subdomain takeover scanner — 30+ fingerprinted services |
| [vamp-cloud-enum](https://github.com/vampsecure-labs/vamp-cloud-enum) | Public bucket finder — AWS S3 / Azure Blob / GCP Storage |

### Vulnerability Intelligence

| Tool | Description |
|------|-------------|
| [vamp-cve-oracle](https://github.com/vampsecure-labs/vamp-cve-oracle) | CVE engine — NVD v2, EPSS, OTX, CISA KEV, RBVM risk score |
| [vamp-forticheck](https://github.com/vampsecure-labs/vamp-forticheck) | Multi-vendor edge scanner — FortiOS, PAN-OS, F5, Cisco, Check Point |

### Web & API Security

| Tool | Description |
|------|-------------|
| [vamp-http-audit](https://github.com/vampsecure-labs/vamp-http-audit) | HTTP security headers, CORS, cookies, GraphQL introspection |
| [vamp-ssl-audit](https://github.com/vampsecure-labs/vamp-ssl-audit) | TLS/SSL auditor with SSLabs-style grading (A+ → F) |
| [vamp-wp2shell-audit](https://github.com/vampsecure-labs/vamp-wp2shell-audit) | WordPress / Joomla / Drupal security scanner |
| [vamp-jwt-audit](https://github.com/vampsecure-labs/vamp-jwt-audit) | JWT auditor — alg=none, RS256→HS256 confusion, HMAC brute force |
| [vamp-mail-audit](https://github.com/vampsecure-labs/vamp-mail-audit) | Email security — SPF, DKIM, DMARC, STARTTLS, open relay |

### Secrets & Code

| Tool | Description |
|------|-------------|
| [vamp-secrets-scanner](https://github.com/vampsecure-labs/vamp-secrets-scanner) | Static secret scanner — 77 patterns, SARIF, git history, CI hooks |
| [vamp-entropy-watch](https://github.com/vampsecure-labs/vamp-entropy-watch) | Ransomware detector via Shannon entropy monitoring |

### Infrastructure & Containers

| Tool | Description |
|------|-------------|
| [vamp-docker-audit](https://github.com/vampsecure-labs/vamp-docker-audit) | Docker security — privileged containers, ENV secrets, socket exposure |
| [vamp-arp-sentinel](https://github.com/vampsecure-labs/vamp-arp-sentinel) | ARP spoofing detector + PoC lab (Scapy + Rich Live) |

### Log Analysis & Threat Hunting

| Tool | Description |
|------|-------------|
| [vamp-log-hunter](https://github.com/vampsecure-labs/vamp-log-hunter) | IoC detection in nginx / auth / syslog — brute force, SQLi, webshells |

### Red Team Labs

| Tool | Description |
|------|-------------|
| [vamp-icmp-shadow](https://github.com/vampsecure-labs/vamp-icmp-shadow) | ICMP covert channel — XOR+Base64 chunked (authorized environments only) |
| [vamp-shellcode-lab](https://github.com/vampsecure-labs/vamp-shellcode-lab) | ARM64 shellcode lab — mmap RWX, direct syscalls, native execution |

### Orchestration

| Tool | Description |
|------|-------------|
| [vamp-orchestrator](https://github.com/vampsecure-labs/vamp-orchestrator) | Meta-tool — chains all VSL tools, risk score 0–100, unified report |

---

## Quick Start

```bash
# Clone any tool
git clone https://github.com/vampsecure-labs/vamp-passive-recon.git
cd vamp-passive-recon && pip install -r requirements.txt

# Run a scan
python vamp_passive_recon.py -d target.com --json results.json

# Or run everything at once
git clone https://github.com/vampsecure-labs/vamp-orchestrator.git
cd vamp-orchestrator
python vamp_orchestrator.py -d target.com --report-pdf engagement.pdf
```

## CI/CD Integration

All tools exit `2` on CRITICAL findings, `1` on HIGH, `0` on clean — designed to gate pipelines.

```yaml
- name: Secret scan
  run: python vamp_secrets_scanner.py . --sarif results.sarif
  continue-on-error: false
```

---

> **For authorized security testing only.**  
> © VampSecure Studios — VampSecure Labs Security Research Division
