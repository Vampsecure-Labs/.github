<div align="center">

```
██╗   ██╗ █████╗ ███╗   ███╗██████╗ ███████╗███████╗ ██████╗██╗   ██╗██████╗ ███████╗
██║   ██║██╔══██╗████╗ ████║██╔══██╗██╔════╝██╔════╝██╔════╝██║   ██║██╔══██╗██╔════╝
██║   ██║███████║██╔████╔██║██████╔╝███████╗█████╗  ██║     ██║   ██║██████╔╝█████╗  
╚██╗ ██╔╝██╔══██║██║╚██╔╝██║██╔═══╝ ╚════██║██╔══╝  ██║     ██║   ██║██╔══██╗██╔══╝  
 ╚████╔╝ ██║  ██║██║ ╚═╝ ██║██║     ███████║███████╗╚██████╗╚██████╔╝██║  ██║███████╗
  ╚═══╝  ╚═╝  ╚═╝╚═╝     ╚═╝╚═╝     ╚══════╝╚══════╝ ╚═════╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝
                                   L A B S
```

### Security Research Division — VampSecure Studios

[![Tools](https://img.shields.io/badge/tools-22%20open%20source-dc143c?style=flat-square&logo=github)](https://github.com/vampsecure-labs)
[![Python](https://img.shields.io/badge/python-3.8%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](LICENSE)
[![Focus](https://img.shields.io/badge/focus-Red%20%26%20Blue%20Team-7c3aed?style=flat-square)](https://github.com/vampsecure-labs)

*Professional-grade security tooling for authorized penetration testing, vulnerability research and defensive operations.*

</div>

---

## 🛠 Toolkit

<table>
<thead>
<tr>
<th width="240">Tool</th>
<th width="80">Category</th>
<th>Description</th>
<th width="130">Findings</th>
</tr>
</thead>
<tbody>

<!-- ── RECON / ASM ─────────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🔍 RECONNAISSANCE & ATTACK SURFACE</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-passive-recon"><b>vamp-passive-recon</b></a></td>
<td><code>RECON</code></td>
<td>Passive ASM — DNS, WHOIS, certificate transparency, GitHub dorks, Shodan OSINT, tech fingerprinting</td>
<td><code>RECON-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-subdomain-takeover"><b>vamp-subdomain-takeover</b></a></td>
<td><code>RECON</code></td>
<td>Subdomain takeover detector — CNAME dangling, service fingerprinting, 40+ provider signatures</td>
<td><code>SDT-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-cloud-enum"><b>vamp-cloud-enum</b></a></td>
<td><code>CLOUD</code></td>
<td>Async public bucket/blob finder — S3, Azure Blob, GCP Storage. 462+ candidate names per target</td>
<td><code>CLOUD-NNN</code></td>
</tr>

<!-- ── VULNERABILITY INTELLIGENCE ─────────────────────────────── -->
<tr><td colspan="4"><sub><b>🔬 VULNERABILITY INTELLIGENCE</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-cve-oracle"><b>vamp-cve-oracle</b></a></td>
<td><code>VULN</code></td>
<td>RBVM engine — NVD + CISA KEV + EPSS scoring, asset inventory, CVE-CPE correlation</td>
<td><code>RBVM-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-forticheck"><b>vamp-forticheck</b></a></td>
<td><code>VULN</code></td>
<td>Multi-vendor edge device scanner — FortiOS, F5 BIG-IP, Palo Alto, Cisco ASA with live CVE probes</td>
<td><code>FTC-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-ssl-audit"><b>vamp-ssl-audit</b></a></td>
<td><code>CRYPTO</code></td>
<td>TLS/SSL auditor with SSLabs-style grading — protocol versions, cipher suites, cert chain, HSTS</td>
<td><code>SSL-NNN</code></td>
</tr>

<!-- ── WEB / API ───────────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🌐 WEB & API SECURITY</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-http-audit"><b>vamp-http-audit</b></a></td>
<td><code>WEB</code></td>
<td>HTTP security auditor — security headers, CORS, CSP, clickjacking, open redirect, GraphQL introspection</td>
<td><code>HTTP-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-wp2shell-audit"><b>vamp-wp2shell-audit</b></a></td>
<td><code>WEB</code></td>
<td>CMS security scanner — WordPress, Joomla & Drupal plugin/theme enumeration, known exploits</td>
<td><code>WP-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-jwt-audit"><b>vamp-jwt-audit</b></a></td>
<td><code>WEB</code></td>
<td>JWT token auditor — alg:none, weak secrets (300K wordlist), JWKS confusion, claim tampering</td>
<td><code>JWT-NNN</code></td>
</tr>

<!-- ── INFRASTRUCTURE ─────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🏗 INFRASTRUCTURE & CONTAINERS</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-docker-audit"><b>vamp-docker-audit</b></a></td>
<td><code>INFRA</code></td>
<td>Docker daemon security auditor — socket exposure, privileged containers, secret ENV vars, network misconfig</td>
<td><code>DOCK-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-k8s-audit"><b>vamp-k8s-audit</b></a></td>
<td><code>INFRA</code></td>
<td>Kubernetes security auditor — RBAC, privileged pods, network policies, secrets management, image risks</td>
<td><code>K8S-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-arp-sentinel"><b>vamp-arp-sentinel</b></a></td>
<td><code>NETWORK</code></td>
<td>ARP spoofing & MITM detector — passive monitoring, gateway verification, alert on anomalies</td>
<td><code>ARP-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-icmp-shadow"><b>vamp-icmp-shadow</b></a></td>
<td><code>NETWORK</code></td>
<td>ICMP covert channel lab — exfiltration simulation, tunnel detection, firewall bypass probes</td>
<td><code>SEC-NNN</code></td>
</tr>

<!-- ── SECRETS / CODE ─────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🔑 SECRETS & CODE SECURITY</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-secrets-scanner"><b>vamp-secrets-scanner</b></a></td>
<td><code>SAST</code></td>
<td>Secrets & sensitive data scanner — git history, 80+ patterns, CI/CD pre-commit hook, SARIF output</td>
<td><code>SEC-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-entropy-watch"><b>vamp-entropy-watch</b></a></td>
<td><code>SAST</code></td>
<td>Entropy-based ransomware & exfil detector — file system monitoring, Shannon entropy analysis</td>
<td><code>ENT-NNN</code></td>
</tr>

<!-- ── EMERGING / NEW ─────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>⚡ EMERGING THREAT COVERAGE</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-llm-probe"><b>vamp-llm-probe</b></a></td>
<td><code>AI SEC</code></td>
<td>LLM endpoint security auditor — prompt injection, jailbreak probes, data extraction, rate limit testing</td>
<td><code>LLM-NNN</code></td>
</tr>

<!-- ── EMAIL ─────────────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>📧 EMAIL SECURITY</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-mail-audit"><b>vamp-mail-audit</b></a></td>
<td><code>EMAIL</code></td>
<td>Email security auditor — SPF, DKIM (RSA key length), DMARC policy, open relay, STARTTLS enforcement</td>
<td><code>MAIL-NNN</code></td>
</tr>

<!-- ── LOGS / SIEM ─────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>📊 LOGS & FORENSICS</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-log-analyzer"><b>vamp-log-analyzer</b></a></td>
<td><code>FORENSIC</code></td>
<td>Forensic log analyzer — 25 MITRE ATT&CK detectors, cross-source correlation (web/Linux/DB), STIX 2.1 export, chain-of-custody ZIP, behavioral baseline, stdlib-only</td>
<td><code>FORA-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-log-hunter"><b>vamp-log-hunter</b></a></td>
<td><code>SIEM</code></td>
<td>IoC detector for server logs — SQLi, XSS, path traversal, webshells, brute force, scanner fingerprints</td>
<td><code>LOG-NNN</code></td>
</tr>

<!-- ── REPORTING / ORCHESTRATION ──────────────────────────── -->
<tr><td colspan="4"><sub><b>🎯 REPORTING & ORCHESTRATION</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-penreport"><b>vamp-penreport</b></a></td>
<td><code>REPORT</code></td>
<td>Professional pentest report aggregator — consolidates all VSL JSON outputs into client-ready HTML/PDF</td>
<td>aggregator</td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-orchestrator"><b>vamp-orchestrator</b></a></td>
<td><code>META</code></td>
<td>Meta-tool chaining 12 VSL scanners — parallel execution, unified findings, risk score 0-100</td>
<td>aggregator</td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-shellcode-lab"><b>vamp-shellcode-lab</b></a></td>
<td><code>RED</code></td>
<td>ARM64 shellcode research lab — macOS/Linux shellcode generation, encoding, analysis (authorized use)</td>
<td><code>SEC-NNN</code></td>
</tr>

</tbody>
</table>

---

## ⚡ Quick Start

```bash
# Clone any tool
git clone https://github.com/Vampsecure-Labs/vamp-passive-recon
cd vamp-passive-recon && pip install -r requirements.txt

# Run an audit
python3 vamp_passive_recon.py --target example.com --report-html recon.html

# Orchestrate multiple tools in parallel
git clone https://github.com/Vampsecure-Labs/vamp-orchestrator
python3 vamp_orchestrator.py --targets example.com --report-html full_audit.html

# Consolidate all results into an executive report
git clone https://github.com/Vampsecure-Labs/vamp-penreport
python3 vamp_penreport.py *.json --client "Acme Corp" --report-html executive_report.html
```

---

## 🔄 CI/CD Integration

Every tool exits with **standardized exit codes** for pipeline automation:

| Exit Code | Meaning |
|-----------|---------|
| `0` | No findings above LOW severity |
| `1` | HIGH severity findings detected |
| `2` | CRITICAL severity findings — pipeline should fail |

```yaml
# GitHub Actions / Forgejo CI example
- name: Secret scan
  run: python3 vamp_secrets_scanner.py --path . --output secrets.json
  continue-on-error: false  # exit 2 = CRITICAL = pipeline fails
```

---

## 📐 Unified Report Format

All tools produce a **consistent JSON schema** for interoperability:

```json
{
  "tool": "vamp-http-audit",
  "version": "2.0",
  "target": "https://example.com",
  "timestamp": "2026-08-03T12:00:00Z",
  "findings": [
    {
      "id": "HTTP-001",
      "severity": "HIGH",
      "title": "Missing Content-Security-Policy header",
      "description": "...",
      "evidence": "...",
      "remediation": "..."
    }
  ],
  "summary": { "total": 1, "critical": 0, "high": 1, "medium": 0, "low": 0 }
}
```

Use **[vamp-penreport](https://github.com/Vampsecure-Labs/vamp-penreport)** to aggregate outputs from multiple tools into a single client-ready report.

---

<div align="center">

**© VampSecure Studios — VampSecure Labs Security Research Division**

*All tools are released for authorized security testing only.*
*Usage against systems without explicit written permission is prohibited.*

</div>
