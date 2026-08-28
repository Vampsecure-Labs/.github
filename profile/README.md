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

[![Tools](https://img.shields.io/badge/tools-27%20open%20source-dc143c?style=flat-square&logo=github)](https://github.com/vampsecure-labs)
[![Python](https://img.shields.io/badge/python-3.8%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/license-MIT-22c55e?style=flat-square)](LICENSE)
[![Focus](https://img.shields.io/badge/focus-Red%20%26%20Blue%20Team-7c3aed?style=flat-square)](https://github.com/vampsecure-labs)

*Professional-grade security tooling for authorized penetration testing, vulnerability research and defensive operations.*<br>
*Herramientas de seguridad profesionales para pruebas de intrusión autorizadas, investigación de vulnerabilidades y operaciones defensivas.*

</div>

---

## 🛠 Toolkit

<table>
<thead>
<tr>
<th width="240">Tool</th>
<th width="80">Category</th>
<th>Description / Descripción</th>
<th width="130">Findings</th>
</tr>
</thead>
<tbody>

<!-- ── RECON / ASM ─────────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🔍 RECONNAISSANCE &amp; ATTACK SURFACE · RECONOCIMIENTO &amp; SUPERFICIE DE ATAQUE</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-passive-recon"><b>vamp-passive-recon</b></a></td>
<td><code>RECON</code></td>
<td>Passive ASM — DNS, WHOIS, certificate transparency, GitHub dorks, Shodan OSINT, tech fingerprinting<br><sub>ASM pasivo — DNS, WHOIS, transparencia de certificados, dorks GitHub, OSINT Shodan, fingerprinting tecnológico</sub></td>
<td><code>RECON-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-easm"><b>vamp-easm</b></a> ⚡</td>
<td><code>ASM</code></td>
<td>Continuous EASM with daily diff tracking — subdomain discovery, async port scan, TLS cert monitoring, SQLite history, webhook alerts on new assets or cert changes<br><sub>EASM continuo con seguimiento diario de cambios — descubrimiento de subdominios, escaneo de puertos async, monitorización de certificados TLS, historial SQLite, alertas webhook ante nuevos activos o cambios de cert</sub></td>
<td><code>EASM-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-shodan-hunt"><b>vamp-shodan-hunt</b></a> ⚡</td>
<td><code>OSINT</code></td>
<td>Shodan OSINT exposure hunter — 4 modes: <b>CVE-exposed hosts</b>, product enumeration, org attack surface, raw query. Global exposure count, geo/org distribution, SHOD findings. No Shodan SDK required<br><sub>Cazador OSINT de exposición en Shodan — 4 modos: <b>hosts con CVE indexado</b>, enumeración de productos, superficie de ataque de org, consulta raw. Recuento global, distribución geo/org, hallazgos SHOD. Sin SDK de Shodan</sub></td>
<td><code>SHOD-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-subdomain-takeover"><b>vamp-subdomain-takeover</b></a></td>
<td><code>RECON</code></td>
<td>Subdomain takeover detector — CNAME dangling, service fingerprinting, 40+ provider signatures<br><sub>Detector de subdomain takeover — CNAME colgantes, fingerprinting de servicios, 40+ firmas de proveedores</sub></td>
<td><code>SDT-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-cloud-enum"><b>vamp-cloud-enum</b></a></td>
<td><code>CLOUD</code></td>
<td>Async public bucket/blob finder — S3, Azure Blob, GCP Storage. 462+ candidate names per target<br><sub>Buscador async de buckets/blobs públicos — S3, Azure Blob, GCP Storage. 462+ nombres candidatos por objetivo</sub></td>
<td><code>CLOUD-NNN</code></td>
</tr>

<!-- ── VULNERABILITY INTELLIGENCE ─────────────────────────────── -->
<tr><td colspan="4"><sub><b>🔬 VULNERABILITY INTELLIGENCE · INTELIGENCIA DE VULNERABILIDADES</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-cve-oracle"><b>vamp-cve-oracle</b></a></td>
<td><code>VULN</code></td>
<td>RBVM engine — NVD + CISA KEV + EPSS scoring + <b>Shodan global exposure count</b> per CVE, asset inventory, CVE-CPE correlation<br><sub>Motor RBVM — NVD + CISA KEV + EPSS + <b>recuento de exposición global Shodan</b> por CVE, inventario de activos, correlación CVE-CPE</sub></td>
<td><code>RBVM-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-forticheck"><b>vamp-forticheck</b></a></td>
<td><code>VULN</code></td>
<td>Multi-vendor edge device scanner — FortiOS, F5 BIG-IP, Palo Alto, Cisco ASA with live CVE probes + <b>Shodan pre-scan discovery</b> per vendor<br><sub>Escáner multi-vendor de dispositivos de borde — FortiOS, F5 BIG-IP, Palo Alto, Cisco ASA con sondas CVE en vivo + <b>descubrimiento Shodan pre-escaneo</b> por vendor</sub></td>
<td><code>FTC-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-ssl-audit"><b>vamp-ssl-audit</b></a></td>
<td><code>CRYPTO</code></td>
<td>TLS/SSL auditor with SSLabs-style grading — protocol versions, cipher suites, cert chain, HSTS<br><sub>Auditor TLS/SSL con calificación estilo SSLabs — versiones de protocolo, suites de cifrado, cadena de certificados, HSTS</sub></td>
<td><code>SSL-NNN</code></td>
</tr>

<!-- ── WEB / API ───────────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🌐 WEB &amp; API SECURITY · SEGURIDAD WEB &amp; API</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-http-audit"><b>vamp-http-audit</b></a></td>
<td><code>WEB</code></td>
<td>HTTP security auditor — security headers, CORS, CSP, clickjacking, open redirect, GraphQL introspection<br><sub>Auditor de seguridad HTTP — cabeceras de seguridad, CORS, CSP, clickjacking, redirección abierta, introspección GraphQL</sub></td>
<td><code>HTTP-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-wp2shell-audit"><b>vamp-wp2shell-audit</b></a></td>
<td><code>WEB</code></td>
<td>CMS security scanner — WordPress, Joomla &amp; Drupal plugin/theme enumeration, known exploits<br><sub>Escáner de seguridad CMS — WordPress, Joomla &amp; Drupal, enumeración de plugins/temas, exploits conocidos</sub></td>
<td><code>WP-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-jwt-audit"><b>vamp-jwt-audit</b></a></td>
<td><code>WEB</code></td>
<td>JWT token auditor — alg:none, weak secrets (300K wordlist), JWKS confusion, claim tampering<br><sub>Auditor de tokens JWT — alg:none, secretos débiles (wordlist 300K), confusión JWKS, manipulación de claims</sub></td>
<td><code>JWT-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-graphql-audit"><b>vamp-graphql-audit</b></a> ⚡</td>
<td><code>WEB</code></td>
<td>GraphQL DAST — introspection detection, BOLA/IDOR fuzzing, alias DoS, injection (SQLi/SSTI/XSS), subscription abuse. Standalone CLI, no Burp required<br><sub>DAST GraphQL — detección de introspección, fuzzing BOLA/IDOR, DoS por alias, inyección (SQLi/SSTI/XSS), abuso de suscripciones. CLI independiente, sin Burp</sub></td>
<td><code>GQL-NNN</code></td>
</tr>

<!-- ── INFRASTRUCTURE ─────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🏗 INFRASTRUCTURE &amp; CONTAINERS · INFRAESTRUCTURA &amp; CONTENEDORES</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-docker-audit"><b>vamp-docker-audit</b></a></td>
<td><code>INFRA</code></td>
<td>Docker daemon security auditor — socket exposure, privileged containers, secret ENV vars, network misconfig<br><sub>Auditor de seguridad Docker — exposición de socket, contenedores privilegiados, secretos en ENV, mala configuración de red</sub></td>
<td><code>DOCK-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-k8s-audit"><b>vamp-k8s-audit</b></a></td>
<td><code>INFRA</code></td>
<td>Kubernetes security auditor — RBAC, privileged pods, network policies, secrets management, image risks<br><sub>Auditor de seguridad Kubernetes — RBAC, pods privilegiados, políticas de red, gestión de secretos, riesgos de imagen</sub></td>
<td><code>K8S-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-arp-sentinel"><b>vamp-arp-sentinel</b></a></td>
<td><code>NETWORK</code></td>
<td>ARP spoofing &amp; MITM detector — passive monitoring, gateway verification, alert on anomalies<br><sub>Detector de ARP spoofing y MITM — monitorización pasiva, verificación de gateway, alertas ante anomalías</sub></td>
<td><code>ARP-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-icmp-shadow"><b>vamp-icmp-shadow</b></a></td>
<td><code>NETWORK</code></td>
<td>ICMP covert channel lab — exfiltration simulation, tunnel detection, firewall bypass probes<br><sub>Lab de canal encubierto ICMP — simulación de exfiltración, detección de túneles, sondas de bypass de cortafuegos</sub></td>
<td><code>SEC-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-gcp-audit"><b>vamp-gcp-audit</b></a> ⚡</td>
<td><code>CLOUD</code></td>
<td>GCP offensive auditor — IAM/SA key age, GCS public buckets, GKE legacy ABAC, Cloud Functions secret env vars, open firewall rules, incomplete audit logging. No Google SDK required<br><sub>Auditor ofensivo GCP — antigüedad de claves IAM/SA, buckets GCS públicos, ABAC heredado GKE, secretos en Cloud Functions, reglas de firewall abiertas, logging de auditoría incompleto. Sin SDK de Google</sub></td>
<td><code>GCP-NNN</code></td>
</tr>

<!-- ── SECRETS / CODE ─────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🔑 SECRETS &amp; CODE SECURITY · SECRETOS &amp; SEGURIDAD DE CÓDIGO</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-secrets-scanner"><b>vamp-secrets-scanner</b></a></td>
<td><code>SAST</code></td>
<td>Secrets &amp; sensitive data scanner — git history, 80+ patterns, CI/CD pre-commit hook, SARIF output<br><sub>Escáner de secretos y datos sensibles — historial git, 80+ patrones, hook pre-commit CI/CD, salida SARIF</sub></td>
<td><code>SEC-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-entropy-watch"><b>vamp-entropy-watch</b></a></td>
<td><code>SAST</code></td>
<td>Entropy-based ransomware &amp; exfil detector — file system monitoring, Shannon entropy analysis<br><sub>Detector de ransomware y exfiltración por entropía — monitorización del sistema de archivos, análisis de entropía Shannon</sub></td>
<td><code>ENT-NNN</code></td>
</tr>

<!-- ── EMERGING / NEW ─────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>⚡ EMERGING THREAT COVERAGE · COBERTURA DE AMENAZAS EMERGENTES</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-llm-probe"><b>vamp-llm-probe</b></a></td>
<td><code>AI SEC</code></td>
<td>LLM endpoint auditor — 6 phases: recon, injection, jailbreak, extraction, access controls + <b>Phase 6 bilingual dataset red team</b> (666+30 jailbreaks · 210+50 injection vectors · 390 forbidden questions · <b>EN+ES native detection</b>)<br><sub>Auditor de endpoints LLM — 6 fases: reconocimiento, inyección, jailbreak, extracción, controles + <b>Fase 6 red team bilingüe</b> (666+30 jailbreaks · 210+50 vectores de inyección · 390 preguntas prohibidas · <b>detección nativa EN+ES</b>)</sub></td>
<td><code>LLM-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-mcp-audit"><b>vamp-mcp-audit</b></a> ⚡</td>
<td><code>AI SEC</code></td>
<td>MCP tool poisoning auditor — 17 injection regexes + <b>50 real-world payload dataset</b>, privilege escalation, data exfiltration, OWASP Agentic Top 10. First OSS tool for MCP security (200K+ vulnerable instances)<br><sub>Auditor de envenenamiento de herramientas MCP — 17 regex de inyección + <b>dataset de 50 payloads reales</b>, escalada de privilegios, exfiltración de datos, OWASP Agentic Top 10. Primera herramienta OSS para seguridad MCP (200K+ instancias vulnerables)</sub></td>
<td><code>MCP-NNN</code></td>
</tr>

<!-- ── EMAIL ─────────────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>📧 EMAIL SECURITY · SEGURIDAD DE EMAIL</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-mail-audit"><b>vamp-mail-audit</b></a></td>
<td><code>EMAIL</code></td>
<td>Email security auditor — SPF, DKIM (RSA key length), DMARC policy, open relay, STARTTLS enforcement<br><sub>Auditor de seguridad email — SPF, DKIM (longitud de clave RSA), política DMARC, relay abierto, cumplimiento STARTTLS</sub></td>
<td><code>MAIL-NNN</code></td>
</tr>

<!-- ── LOGS / SIEM ─────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>📊 LOGS &amp; FORENSICS · LOGS &amp; ANÁLISIS FORENSE</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-log-analyzer"><b>vamp-log-analyzer</b></a></td>
<td><code>FORENSIC</code></td>
<td>Forensic log analyzer — 25 MITRE ATT&amp;CK detectors, cross-source correlation (web/Linux/DB), STIX 2.1 export, chain-of-custody ZIP, behavioral baseline, stdlib-only<br><sub>Analizador forense de logs — 25 detectores MITRE ATT&amp;CK, correlación multi-fuente (web/Linux/BD), exportación STIX 2.1, ZIP de cadena de custodia, baseline de comportamiento, solo stdlib</sub></td>
<td><code>FORA-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-log-hunter"><b>vamp-log-hunter</b></a></td>
<td><code>SIEM</code></td>
<td>IoC detector for server logs — SQLi, XSS, path traversal, webshells, brute force, scanner fingerprints<br><sub>Detector de IoC en logs de servidor — SQLi, XSS, path traversal, webshells, fuerza bruta, fingerprints de escáner</sub></td>
<td><code>LOG-NNN</code></td>
</tr>

<!-- ── REPORTING / ORCHESTRATION ──────────────────────────── -->
<tr><td colspan="4"><sub><b>🎯 REPORTING &amp; ORCHESTRATION · INFORMES &amp; ORQUESTACIÓN</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-penreport"><b>vamp-penreport</b></a></td>
<td><code>REPORT</code></td>
<td>Professional pentest report aggregator — consolidates all VSL JSON outputs into client-ready HTML/PDF<br><sub>Agregador de informes de pentest profesional — consolida todos los outputs JSON de VSL en un informe HTML/PDF listo para el cliente</sub></td>
<td>aggregator</td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-orchestrator"><b>vamp-orchestrator</b></a></td>
<td><code>META</code></td>
<td>Meta-tool chaining 16 VSL scanners — parallel execution, unified findings, MITRE ATT&amp;CK mapping, risk score 0-100<br><sub>Meta-herramienta que encadena 16 escáneres VSL — ejecución paralela, hallazgos unificados, mapeo MITRE ATT&amp;CK, puntuación de riesgo 0-100</sub></td>
<td>aggregator</td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-shellcode-lab"><b>vamp-shellcode-lab</b></a></td>
<td><code>RED</code></td>
<td>ARM64 shellcode research lab — macOS/Linux shellcode generation, encoding, analysis (authorized use)<br><sub>Lab de investigación de shellcode ARM64 — generación, codificación y análisis de shellcode macOS/Linux (uso autorizado)</sub></td>
<td><code>SEC-NNN</code></td>
</tr>

</tbody>
</table>

---

## ⚡ Quick Start / Inicio rápido

```bash
# Clone any tool / Clonar cualquier herramienta
git clone https://github.com/Vampsecure-Labs/vamp-passive-recon
cd vamp-passive-recon && pip install -r requirements.txt

# Run an audit / Ejecutar una auditoría
python3 vamp_passive_recon.py --target example.com --report-html recon.html

# Continuous attack surface monitoring / Monitorización continua de superficie de ataque
git clone https://github.com/Vampsecure-Labs/vamp-easm
cd vamp-easm && pip install -r requirements.txt
python3 vamp_easm.py scan --target example.com --alert-webhook $SLACK_WEBHOOK

# Orchestrate multiple tools in parallel / Orquestar múltiples herramientas en paralelo
git clone https://github.com/Vampsecure-Labs/vamp-orchestrator
python3 vamp_orchestrator.py --targets example.com --report-html full_audit.html

# Consolidate all results into an executive report / Consolidar resultados en informe ejecutivo
git clone https://github.com/Vampsecure-Labs/vamp-penreport
python3 vamp_penreport.py *.json --client "Acme Corp" --report-html executive_report.html
```

---

## 🔄 CI/CD Integration / Integración CI/CD

Every tool exits with **standardized exit codes** for pipeline automation.<br>
Todas las herramientas usan **códigos de salida estandarizados** para automatización de pipelines.

| Exit Code | Meaning / Significado |
|-----------|----------------------|
| `0` | No findings above LOW severity / Sin hallazgos por encima de severidad BAJA |
| `1` | HIGH severity findings detected / Hallazgos de severidad ALTA detectados |
| `2` | CRITICAL severity findings — pipeline should fail / Hallazgos CRÍTICOS — el pipeline debe fallar |

```yaml
# GitHub Actions / Forgejo CI example
- name: Secret scan
  run: python3 vamp_secrets_scanner.py --path . --output secrets.json
  continue-on-error: false  # exit 2 = CRITICAL = pipeline fails

# Daily EASM cron / Cron EASM diario
- name: Attack surface diff
  run: python3 vamp_easm.py scan --target $TARGET --alert-webhook $SLACK_WEBHOOK
```

---

## 📐 Unified Report Format / Formato de informe unificado

All tools produce a **consistent JSON schema** for interoperability.<br>
Todas las herramientas generan un **esquema JSON consistente** para interoperabilidad.

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

Use **[vamp-penreport](https://github.com/Vampsecure-Labs/vamp-penreport)** to aggregate outputs from multiple tools into a single client-ready report.<br>
Usa **[vamp-penreport](https://github.com/Vampsecure-Labs/vamp-penreport)** para agregar los resultados de múltiples herramientas en un único informe listo para el cliente.

---

<div align="center">

**© VampSecure Studios — VampSecure Labs Security Research Division**

*All tools are released for authorized security testing only.*<br>
*Todas las herramientas se publican exclusivamente para pruebas de seguridad autorizadas.*

*Usage against systems without explicit written permission is prohibited.*<br>
*El uso contra sistemas sin permiso escrito explícito está prohibido.*

</div>
