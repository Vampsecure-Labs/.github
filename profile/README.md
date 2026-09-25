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

[![Tools](https://img.shields.io/badge/tools-31%20open%20source-dc143c?style=flat-square&logo=github)](https://github.com/vampsecure-labs)
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
<td>Continuous EASM — subdomain discovery, async port scan, TLS cert monitoring, Shodan + Censys enrichment. <b>v1.5</b>: Shodan Monitor integration — persistent alerts for automatic detection of new open ports &amp; CVEs on monitored IPs (<code>monitor --setup/--check</code>)<br><sub>EASM continuo — subdominios, puertos async, TLS, enriquecimiento Shodan+Censys. <b>v1.5</b>: integración Shodan Monitor — alertas persistentes para detección automática de nuevos puertos abiertos y CVEs en IPs monitorizadas (<code>monitor --setup/--check</code>)</sub></td>
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
<td>Subdomain takeover detector — CNAME dangling, 40+ provider fingerprints, <b>--monitor</b> continuous DNS polling<br><sub>Detector de subdomain takeover — CNAME colgantes, 40+ firmas de proveedores, <b>--monitor</b> polling DNS continuo</sub></td>
<td><code>SDT-NNN</code></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-cloud-enum"><b>vamp-cloud-enum</b></a></td>
<td><code>CLOUD</code></td>
<td>Async cloud storage &amp; serverless scanner — S3/Azure/GCS buckets + <b>GCP/AWS/Azure Cloud Functions</b> exposure detection (<code>--check-functions</code>)<br><sub>Escáner async de almacenamiento cloud y serverless — buckets S3/Azure/GCS + detección de exposición de <b>GCP/AWS/Azure Cloud Functions</b> (<code>--check-functions</code>)</sub></td>
<td><code>CLOUD-NNN</code></td>
</tr>

<!-- ── THREAT INTELLIGENCE ────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🕵️ THREAT INTELLIGENCE · INTELIGENCIA DE AMENAZAS</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-darkweb-intel"><b>vamp-darkweb-intel</b></a></td>
<td><code>OSINT</code></td>
<td>Darkweb &amp; threat intelligence CLI — multi-source IOC lookup, automatic correlation, breach checks + <b>--monitor</b> persistent daemon<br><sub>CLI de inteligencia de amenazas y darkweb — IOC multi-fuente, correlación automática, filtraciones + <b>--monitor</b> daemon de vigilancia continua</sub></td>
<td><code>DWI-NNN</code></td>
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
<td><a href="https://github.com/Vampsecure-Labs/vamp-oauth-audit"><b>vamp-oauth-audit</b></a></td>
<td><code>WEB</code></td>
<td>OAuth 2.0 and OIDC security flow auditor — PKCE, state validation, implicit flow abuse, open redirect, token analysis<br><sub>Auditor de flujos OAuth 2.0 y OIDC — validación PKCE y state, abuso de flujo implícito, redirección abierta, análisis de tokens</sub></td>
<td><code>OAUTH-NNN</code></td>
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
<td>ARP spoofing &amp; IPv6 NDP MITM detector — passive monitoring, gateway verification, <b>JSON output integrated with vamp-orchestrator</b><br><sub>Detector de ARP spoofing e IPv6 NDP MITM — monitorización pasiva, verificación de gateway, <b>salida JSON integrada con vamp-orchestrator</b></sub></td>
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

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-azure-audit"><b>vamp-azure-audit</b></a></td>
<td><code>CLOUD</code></td>
<td>Microsoft Azure security auditor — IAM, Storage, AKS, App Services, NSG, Key Vault, Defender. REST API only<br><sub>Auditor de seguridad Microsoft Azure — IAM, Storage, AKS, App Services, NSG, Key Vault, Defender. Solo REST API, sin SDK</sub></td>
<td><code>AZR-NNN</code></td>
</tr>

<!-- ── SECRETS / CODE ─────────────────────────────────────────── -->
<tr><td colspan="4"><sub><b>🔑 SECRETS &amp; CODE SECURITY · SECRETOS &amp; SEGURIDAD DE CÓDIGO</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-secrets-scanner"><b>vamp-secrets-scanner</b></a></td>
<td><code>SAST</code></td>
<td>Secrets &amp; sensitive data scanner — git history, 80+ patterns, Docker runtime, <b>Kubernetes Secrets (<code>--k8s</code>)</b>, CI/CD, SARIF<br><sub>Escáner de secretos y datos sensibles — historial git, 80+ patrones, runtime Docker, <b>Kubernetes Secrets (<code>--k8s</code>)</b>, CI/CD, SARIF</sub></td>
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
<td><a href="https://github.com/Vampsecure-Labs/vamp-llm-payloads"><b>vamp-llm-payloads</b></a></td>
<td><code>AI SEC</code></td>
<td>Adversarial datasets for LLM red teaming — prompt injection vectors, jailbreak sequences, forbidden question corpus (companion to vamp-llm-probe)<br><sub>Datasets adversariales para red team LLM — vectores de inyección de prompts, secuencias de jailbreak, corpus de preguntas prohibidas (complemento de vamp-llm-probe)</sub></td>
<td>dataset</td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-mcp-audit"><b>vamp-mcp-audit</b></a> ⚡</td>
<td><code>AI SEC</code></td>
<td>MCP tool poisoning auditor — 17 injection regexes + 50 payload dataset, OWASP Agentic Top 10, <b>--monitor</b> continuous server polling. First OSS MCP security tool (200K+ vulnerable instances)<br><sub>Auditor de envenenamiento de herramientas MCP — 17 regex + dataset 50 payloads, OWASP Agentic Top 10, <b>--monitor</b> polling continuo de servidores. Primera herramienta OSS para seguridad MCP (200K+ instancias vulnerables)</sub></td>
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
<td>IoC detector for server logs — <b>--fast-mode</b> triage (&lt;5s), SQLi/XSS/webshells/brute force; distinct from vamp-log-analyzer (forensic)<br><sub>Detector de IoC en logs — <b>--fast-mode</b> triage (&lt;5s), SQLi/XSS/webshells/fuerza bruta; diferenciado de vamp-log-analyzer (forense)</sub></td>
<td><code>LOG-NNN</code></td>
</tr>

<!-- ── REPORTING / ORCHESTRATION ──────────────────────────── -->
<tr><td colspan="4"><sub><b>🎯 REPORTING &amp; ORCHESTRATION · INFORMES &amp; ORQUESTACIÓN</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-penreport"><b>vamp-penreport</b></a></td>
<td><code>REPORT</code></td>
<td>Professional pentest report aggregator — all VSL JSON → client HTML/PDF, CVSS 3.1, Jira/Defect Dojo export, <b>custom PDF template (<code>--pdf-template</code>)</b><br><sub>Agregador de informes pentest — todos los JSON VSL → HTML/PDF cliente, CVSS 3.1, export Jira/Defect Dojo, <b>plantilla PDF personalizable (<code>--pdf-template</code>)</b></sub></td>
<td>aggregator</td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-orchestrator"><b>vamp-orchestrator</b></a></td>
<td><code>META</code></td>
<td>Meta-tool chaining 19 VSL scanners — parallel execution, unified risk score, MITRE ATT&amp;CK mapping, <b>Telegram notifications</b> on scan completion<br><sub>Meta-herramienta que encadena 19 escáneres VSL — ejecución paralela, puntuación de riesgo unificada, mapeo MITRE ATT&amp;CK, <b>notificaciones Telegram</b> al completar</sub></td>
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

# Continuous attack surface monitoring + Shodan Monitor alerts / EASM continuo + alertas Shodan Monitor
git clone https://github.com/Vampsecure-Labs/vamp-easm
cd vamp-easm && pip install -r requirements.txt
python3 vamp_easm.py scan --target example.com --shodan-key $SHODAN_KEY --alert-webhook $SLACK_WEBHOOK
python3 vamp_easm.py monitor --target example.com --shodan-key $SHODAN_KEY --setup  # activate persistent alerts
python3 vamp_easm.py monitor --target example.com --shodan-key $SHODAN_KEY --check  # check for new threats

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
