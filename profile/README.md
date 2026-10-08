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

[![Tools](https://img.shields.io/badge/tools-44%20open%20source-dc143c?style=flat-square&logo=github)](https://github.com/Vampsecure-Labs)
[![Python](https://img.shields.io/badge/python-3.9%2B-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![License](https://img.shields.io/badge/license-AGPL--3.0-22c55e?style=flat-square)](LICENSE)
[![PyPI](https://img.shields.io/badge/PyPI-published-orange?style=flat-square&logo=pypi)](https://pypi.org/user/VampSecureLabs/)
[![Homebrew](https://img.shields.io/badge/Homebrew-tap-brown?style=flat-square&logo=homebrew)](https://github.com/Vampsecure-Labs/homebrew-labs)

*Professional-grade security tooling for authorized penetration testing, vulnerability research and defensive operations.*<br>
*Herramientas de seguridad profesionales para pruebas de intrusión autorizadas, investigación de vulnerabilidades y operaciones defensivas.*

</div>

---

## 🛠 Toolkit

<table>
<thead>
<tr>
<th width="240">Tool</th>
<th width="80">Version</th>
<th>Description / Descripción</th>
</tr>
</thead>
<tbody>

<!-- ── RECON / ASM ─────────────────────────────────────────────── -->
<tr><td colspan="3"><sub><b>🔍 RECONNAISSANCE & ATTACK SURFACE · RECONOCIMIENTO & SUPERFICIE DE ATAQUE</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-passive-recon"><b>vamp-passive-recon</b></a></td>
<td><code>v1.3.0</code></td>
<td>Passive ASM — DNS, WHOIS, certificate transparency, GitHub dorks, Shodan OSINT, tech fingerprinting<br><sub>ASM pasivo — DNS, WHOIS, transparencia de certificados, dorks GitHub, OSINT Shodan, fingerprinting tecnológico</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-easm"><b>vamp-easm</b></a></td>
<td><code>v1.6</code></td>
<td>Continuous EASM — subdomain discovery, async port scan, TLS cert monitoring, Shodan+Censys enrichment, Shodan Monitor integration (<code>monitor --setup/--check</code>)<br><sub>EASM continuo — subdominios, puertos async, TLS, enriquecimiento Shodan+Censys, alertas Shodan Monitor persistentes</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-shodan-hunt"><b>vamp-shodan-hunt</b></a></td>
<td><code>v1.2</code></td>
<td>Shodan OSINT exposure hunter — CVE-exposed hosts, product enumeration, org attack surface, raw query. No Shodan SDK required<br><sub>Cazador OSINT de exposición en Shodan — hosts con CVE, enumeración de productos, superficie de ataque de org. Sin SDK</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-subdomain-takeover"><b>vamp-subdomain-takeover</b></a></td>
<td><code>v1.3</code></td>
<td>Subdomain takeover detector — CNAME dangling, 40+ provider fingerprints, <code>--monitor</code> continuous DNS polling<br><sub>Detector de subdomain takeover — CNAME colgantes, 40+ firmas de proveedores, <code>--monitor</code> polling DNS continuo</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-cloud-enum"><b>vamp-cloud-enum</b></a></td>
<td><code>v1.3</code></td>
<td>Async cloud storage & serverless scanner — S3/Azure/GCS buckets + GCP/AWS/Azure Cloud Functions exposure detection (<code>--check-functions</code>)<br><sub>Escáner async de almacenamiento cloud y serverless — buckets + Cloud Functions. No SDK requerido</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-ad-recon"><b>vamp-ad-recon</b></a></td>
<td><code>v1.2</code></td>
<td>Active Directory security auditor — Kerberoasting, AS-REP Roasting, ACL abuse, BloodHound-compatible output, agentless LDAP<br><sub>Auditor de seguridad Active Directory — Kerberoasting, AS-REP, abuso de ACL, salida compatible con BloodHound</sub></td>
</tr>

<!-- ── THREAT INTELLIGENCE ────────────────────────────────────── -->
<tr><td colspan="3"><sub><b>🕵️ THREAT INTELLIGENCE · INTELIGENCIA DE AMENAZAS</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-darkweb-intel"><b>vamp-darkweb-intel</b></a></td>
<td><code>v1.1.0</code></td>
<td>Darkweb & threat intelligence CLI — multi-source IOC lookup, automatic correlation, breach checks + <code>--monitor</code> persistent daemon<br><sub>CLI de inteligencia de amenazas y darkweb — IOC multi-fuente, correlación automática, filtraciones + daemon de vigilancia</sub></td>
</tr>

<!-- ── VULNERABILITY INTELLIGENCE ─────────────────────────────── -->
<tr><td colspan="3"><sub><b>🔬 VULNERABILITY INTELLIGENCE · INTELIGENCIA DE VULNERABILIDADES</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-cve-oracle"><b>vamp-cve-oracle</b></a></td>
<td><code>v3.2</code></td>
<td>RBVM engine — NVD + CISA KEV + EPSS scoring + Shodan global exposure count per CVE, asset inventory, CVE-CPE correlation<br><sub>Motor RBVM — NVD + CISA KEV + EPSS + recuento de exposición global Shodan por CVE, inventario de activos</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-forticheck"><b>vamp-forticheck</b></a></td>
<td><code>v2.1</code></td>
<td>Multi-vendor edge device scanner — FortiOS, F5 BIG-IP, Palo Alto, Cisco ASA with live CVE probes + Shodan pre-scan discovery<br><sub>Escáner multi-vendor de dispositivos de borde — FortiOS, F5 BIG-IP, Palo Alto, Cisco ASA con sondas CVE en vivo</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-ssl-audit"><b>vamp-ssl-audit</b></a></td>
<td><code>v1.7.0</code></td>
<td>TLS/SSL auditor — SSLabs-style grading (A+…F), cipher suites, cert chain, HSTS, OCSP stapling, <code>--delta</code> diff scan, multi-format export (HTML/JSON/Markdown/CSV/PDF), importable package<br><sub>Auditor TLS/SSL con calificación estilo SSLabs, <code>--delta</code> diff entre escaneos, paquete importable</sub></td>
</tr>

<!-- ── WEB / API ───────────────────────────────────────────────── -->
<tr><td colspan="3"><sub><b>🌐 WEB & API SECURITY · SEGURIDAD WEB & API</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-http-audit"><b>vamp-http-audit</b></a></td>
<td><code>v1.3.0</code></td>
<td>HTTP security headers & CORS auditor — CSP, HSTS, X-Frame-Options, Referrer-Policy, Permissions-Policy<br><sub>Auditor de cabeceras de seguridad HTTP y CORS — CSP, HSTS, X-Frame-Options, Referrer-Policy</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-graphql-audit"><b>vamp-graphql-audit</b></a></td>
<td><code>v1.4.0</code></td>
<td>GraphQL DAST auditor — introspection, BOLA/IDOR, alias abuse, APQ persisted queries, nested DoS detection<br><sub>Auditor DAST GraphQL — introspección, BOLA/IDOR, alias abuse, APQ, DoS anidado</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-wp2shell-audit"><b>vamp-wp2shell-audit</b></a></td>
<td><code>v1.2</code></td>
<td>WordPress/Joomla/Drupal security auditor — 40+ CVEs, plugin enumeration, xmlrpc abuse, WPScan API integration<br><sub>Auditor de seguridad WordPress/Joomla/Drupal — 40+ CVEs, enumeración de plugins, xmlrpc, API WPScan</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-waf-bypass"><b>vamp-waf-bypass</b></a></td>
<td><code>v1.1.0</code></td>
<td>WAF evasion tester — WAF fingerprinting, 15 bypass techniques (SQLi/XSS/LFI encoded), <code>--watch N</code> daemon mode, 56 tests<br><sub>Tester de evasión WAF — fingerprinting, 15 técnicas (SQLi/XSS/LFI codificados), daemon mode, 56 tests</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-oauth-audit"><b>vamp-oauth-audit</b></a></td>
<td><code>v1.1</code></td>
<td>OAuth 2.0 & OIDC security auditor — auth code injection, PKCE bypass (CVE-2025-4144), scope creep, .well-known misconfiguration<br><sub>Auditor de seguridad OAuth 2.0 y OIDC — inyección de código auth, bypass PKCE, scope creep, .well-known</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-jwt-audit"><b>vamp-jwt-audit</b></a></td>
<td><code>v1.4.0</code></td>
<td>JWT security auditor — alg=none, RS256→HS256 confusion, brute-force HMAC, kid injection, JWKS spoofing, OAuth flow audit. Importable package<br><sub>Auditor JWT — alg=none, confusión RS256/HS256, brute-force HMAC, kid injection, JWKS spoofing. Paquete importable</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-api-probe"><b>vamp-api-probe</b></a></td>
<td><code>v1.0</code></td>
<td>REST API DAST scanner — BOLA, BFLA, mass assignment, rate-limiting bypass, OWASP API Top 10, OpenAPI spec ingestion<br><sub>Escáner DAST REST — BOLA, BFLA, mass assignment, bypass de rate-limiting, OWASP API Top 10</sub></td>
</tr>

<!-- ── CLOUD & IAC ─────────────────────────────────────────────── -->
<tr><td colspan="3"><sub><b>☁️ CLOUD, IaC & CONTAINERS · CLOUD, IaC & CONTENEDORES</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-aws-audit"><b>vamp-aws-audit</b></a></td>
<td><code>v1.0.0</code></td>
<td>AWS security auditor — 71 CIS AWS Level 1 controls across 8 modules (IAM/S3/EC2/CloudTrail/RDS/KMS/GuardDuty/Config), SigV4 without boto3<br><sub>Auditor AWS — 71 controles CIS Level 1, 8 módulos (IAM/S3/EC2/CloudTrail/RDS/KMS/GuardDuty/Config), sin boto3</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-azure-audit"><b>vamp-azure-audit</b></a></td>
<td><code>v1.1</code></td>
<td>Microsoft Azure security auditor — RBAC, Storage ACL, Key Vault, App Service, NSG, AKS, Entra ID, Defender for Cloud<br><sub>Auditor Azure — RBAC, Storage ACL, Key Vault, App Service, NSG, AKS, Entra ID, Defender for Cloud</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-gcp-audit"><b>vamp-gcp-audit</b></a></td>
<td><code>v1.3</code></td>
<td>Google Cloud Platform security auditor — Service Accounts, GCS ACL, GKE, Cloud Run, BigQuery, Artifact Registry, Workload Identity<br><sub>Auditor GCP — Service Accounts, GCS ACL, GKE, Cloud Run, BigQuery, Artifact Registry, Workload Identity</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-iac-audit"><b>vamp-iac-audit</b></a></td>
<td><code>v2.5.0</code></td>
<td>IaC static security auditor — <b>264 checks</b> across 6 formats: Terraform, CloudFormation, Helm, Ansible, Pulumi, <b>AWS SAM/CDK</b>. YAML-driven extensible rules engine (9 rule files). CIS + MITRE ATT&CK mappings. AWS, Azure, GCP<br><sub>Auditor estático IaC — 264 checks, 6 formatos, motor YAML extensible. Brecha vs Checkov ~3.8x</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-k8s-audit"><b>vamp-k8s-audit</b></a></td>
<td><code>v3.0.0</code></td>
<td>Kubernetes security auditor — RBAC, pods, network, <b>CIS Benchmark YAML engine</b> (44 checks), kube-bench wrapper, <code>--control-plane</code> flags check, <code>--delta</code> diff scan, importable package<br><sub>Auditor Kubernetes — motor YAML CIS, kube-bench, control plane, diff scan, paquete importable</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-docker-audit"><b>vamp-docker-audit</b></a></td>
<td><code>v1.5.0</code></td>
<td>Docker security auditor — CIS Docker Benchmark, CycloneDX SBOM generation, secrets in env vars, layer secrets, <code>--delta</code> diff scan, importable package<br><sub>Auditor Docker — CIS Benchmark, SBOM CycloneDX, secretos en capas/env, diff scan, paquete importable</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-mobile-audit"><b>vamp-mobile-audit</b></a></td>
<td><code>v1.0.0</code></td>
<td>Mobile security static auditor — OWASP MASVS 2.0 checks for APK and IPA files, hardcoded secrets, SSL pinning, exported components<br><sub>Auditor estático mobile — OWASP MASVS 2.0, APK e IPA, secretos hardcodeados, SSL pinning, componentes exportados</sub></td>
</tr>

<!-- ── DevSec & Supply Chain ──────────────────────────────────── -->
<tr><td colspan="3"><sub><b>🔒 DevSec & SUPPLY CHAIN · SEGURIDAD DEL DESARROLLO</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-secrets-scanner"><b>vamp-secrets-scanner</b></a></td>
<td><code>v3.0.0</code></td>
<td>Static secrets & credentials scanner — <b>271 patterns</b> across 9 YAML rule files (cloud, AI APIs, CI/CD, SaaS, auth, payments, hardware/web3/gaming/enterprise), git history, Docker, K8s, SARIF, <code>--delta</code>, <code>--watch N</code> daemon, importable package<br><sub>Escáner de secretos — 271 patrones, 9 ficheros YAML, historial git, Docker, K8s, SARIF, diff, daemon. Paquete importable</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-supply-chain"><b>vamp-supply-chain</b></a></td>
<td><code>v1.1</code></td>
<td>Supply chain security scanner — SBOM CycloneDX/SPDX, CVE checks via OSV.dev, typosquatting detection, SAST↔CVE cross-reference<br><sub>Escáner de cadena de suministro — SBOM CycloneDX/SPDX, CVE OSV.dev, typosquatting, cruce SAST↔CVE</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-ci-audit"><b>vamp-ci-audit</b></a></td>
<td><code>v1.0</code></td>
<td>CI/CD pipeline security auditor — GitHub Actions, GitLab CI, Forgejo Actions: expression injection, SHA pinning, GITHUB_TOKEN permissions, fork access<br><sub>Auditor de pipelines CI/CD — expresion injection, SHA pin, permisos GITHUB_TOKEN, acceso desde forks</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-compliance-check"><b>vamp-compliance-check</b></a></td>
<td><code>v1.1</code></td>
<td>Static multi-framework compliance auditor — ENS RD 311/2022, NIS2, ISO 27001, DORA, GDPR. Spanish/European focus, gap analysis report<br><sub>Auditor de cumplimiento multi-marco — ENS, NIS2, ISO 27001, DORA, GDPR. Enfoque español/europeo</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-entropy-watch"><b>vamp-entropy-watch</b></a></td>
<td><code>v2.2</code></td>
<td>Entropy-based ransomware & exfil detector — file system monitoring, Shannon entropy analysis, 80+ known ransomware extensions<br><sub>Detector de ransomware y exfiltración por entropía — monitorización FS, entropía Shannon, 80+ extensiones</sub></td>
</tr>

<!-- ── ENDPOINT & HOST ─────────────────────────────────────────── -->
<tr><td colspan="3"><sub><b>🖥️ ENDPOINT & HOST SECURITY · SEGURIDAD DE ENDPOINTS</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-host-audit"><b>vamp-host-audit</b></a></td>
<td><code>v1.15.0</code></td>
<td>Multiplatform host hardening auditor — <b>272 checks</b>: Linux, macOS, Windows. ENS RD 311/2022 + CCN-STIC 808, NIS2, ISO 27001, DORA. SSH remote audit, YAML profiles, <code>--delta</code> diff<br><sub>Auditor de hardening multiplataforma — 272 checks Linux/macOS/Windows, ENS+CCN-STIC 808, NIS2, DORA, auditoría SSH remota</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-windows-audit"><b>vamp-windows-audit</b></a></td>
<td><code>v1.1.0</code></td>
<td>Windows post-compromise security auditor — 15 CIS checks, agentless (WinRM/PowerShell), <code>--baseline</code> delta scan with NEW/RECURRING/RESOLVED badges, HTML report, 74 tests<br><sub>Auditor Windows sin agente — 15 checks CIS, delta scan NEW/RECURRING/RESOLVED, informe HTML</sub></td>
</tr>

<!-- ── EMERGING / AI SEC ───────────────────────────────────────── -->
<tr><td colspan="3"><sub><b>⚡ EMERGING THREAT COVERAGE · COBERTURA DE AMENAZAS EMERGENTES</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-llm-probe"><b>vamp-llm-probe</b></a></td>
<td><code>v1.8.0</code></td>
<td>LLM security auditor — prompt injection, jailbreak, ASCII smuggling, RAG injection, model extraction. Bilingual EN+ES (666+210+390 payload dataset). <code>--watch N</code> daemon, importable package<br><sub>Auditor de seguridad LLM — inyección, jailbreak, smuggling ASCII, RAG, extracción de modelos. Bilingüe EN+ES</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-llm-payloads"><b>vamp-llm-payloads</b></a></td>
<td><i>dataset</i></td>
<td>Adversarial datasets for LLM red teaming — 666 jailbreaks EN, 210 injection vectors, 390 forbidden questions (companion to vamp-llm-probe)<br><sub>Datasets adversariales para red team LLM — jailbreaks, inyección, preguntas prohibidas (complemento de vamp-llm-probe)</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-mcp-audit"><b>vamp-mcp-audit</b></a></td>
<td><code>v2.3</code></td>
<td>MCP server security auditor — tool poisoning, 17 injection regexes + 50 payload dataset, OWASP Agentic Top 10, <code>--monitor</code> continuous polling, VS Code config audit. First OSS MCP security tool<br><sub>Auditor de seguridad MCP — envenenamiento de herramientas, OWASP Agentic Top 10, polling continuo. Primera herramienta OSS para MCP</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-rag-audit"><b>vamp-rag-audit</b></a></td>
<td><code>v1.0</code></td>
<td>RAG & agentic AI security auditor — indirect prompt injection, context poisoning, Unicode Tags smuggling, query injection, OWASP LLM Top 10<br><sub>Auditor de seguridad RAG y IA agéntica — inyección indirecta, context poisoning, Unicode Tags, OWASP LLM Top 10</sub></td>
</tr>

<!-- ── EMAIL ─────────────────────────────────────────────────── -->
<tr><td colspan="3"><sub><b>📧 EMAIL SECURITY · SEGURIDAD DE EMAIL</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-mail-audit"><b>vamp-mail-audit</b></a></td>
<td><code>v1.2.0</code></td>
<td>Email security auditor — SPF, DKIM (RSA key length), DMARC policy, BIMI, MTA-STS, SMTP open relay detection. Importable package<br><sub>Auditor de seguridad email — SPF, DKIM, DMARC, BIMI, MTA-STS, relay abierto. Paquete importable</sub></td>
</tr>

<!-- ── LOGS / FORENSICS ───────────────────────────────────────── -->
<tr><td colspan="3"><sub><b>📊 LOGS & FORENSICS · LOGS & ANÁLISIS FORENSE</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-log-analyzer"><b>vamp-log-analyzer</b></a></td>
<td><code>v2.4.0</code></td>
<td>Forensic log analyzer — 25 MITRE ATT&CK detectors, cross-source correlation, STIX 2.1 export, Sigma rules YAML, chain-of-custody ZIP, <code>--watch-wazuh-api</code>. Importable package<br><sub>Analizador forense de logs — 25 detectores MITRE ATT&CK, correlación multi-fuente, STIX 2.1, Sigma, cadena de custodia</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-log-hunter"><b>vamp-log-hunter</b></a></td>
<td><code>v1.3</code></td>
<td>IoC detector for server logs — <code>--fast-mode</code> triage (&lt;5s), SQLi/XSS/webshells/brute force detection. Distinct from vamp-log-analyzer (forensic)<br><sub>Detector de IoC en logs — triage <code>--fast-mode</code> &lt;5s, SQLi/XSS/webshells/fuerza bruta. Diferente de vamp-log-analyzer</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-forensic-query"><b>vamp-forensic-query</b></a></td>
<td><code>v1.3</code></td>
<td>Forensic SQL/log query engine — CSV/XLSX ingestion, DNI/email/IP pattern search, evidence ZIP signed, streaming SQLite >500MB<br><sub>Motor de consulta forense — ingestión CSV/XLSX, búsqueda DNI/email/IP, ZIP de evidencia firmado, SQLite streaming >500MB</sub></td>
</tr>

<!-- ── REPORTING / ORCHESTRATION ──────────────────────────────── -->
<tr><td colspan="3"><sub><b>🎯 REPORTING & ORCHESTRATION · INFORMES & ORQUESTACIÓN</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-penreport"><b>vamp-penreport</b></a></td>
<td><code>v2.7.0</code></td>
<td>Professional pentest report aggregator — all VSL JSON → client HTML/PDF, CVSS 3.1, Jira/DefectDojo export, GPG-signed PDF, ENS RD 311/2022 checklist. Importable package<br><sub>Agregador de informes pentest — JSON VSL → HTML/PDF, CVSS 3.1, Jira/DefectDojo, PDF firmado GPG, checklist ENS</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-orchestrator"><b>vamp-orchestrator</b></a></td>
<td><code>v2.5</code></td>
<td>Meta-tool chaining 22 VSL scanners — parallel execution, YAML pipelines, unified risk score, MITRE ATT&CK mapping, Telegram notifications. Playbooks: <code>devops_audit</code> / <code>cloud_posture</code> / <code>endpoint_hardening</code><br><sub>Meta-herramienta que encadena 22 escáneres VSL — ejecución paralela, pipelines YAML, puntuación unificada, Telegram</sub></td>
</tr>

<!-- ── LAB / RESEARCH ─────────────────────────────────────────── -->
<tr><td colspan="3"><sub><b>🔬 RESEARCH LAB · LABORATORIO DE INVESTIGACIÓN</b></sub></td></tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-arp-sentinel"><b>vamp-arp-sentinel</b></a></td>
<td><code>v2.2</code></td>
<td>ARP/IPv6 NDP spoofing detector + active PoC — Scapy-based passive+active detection for Blue Team / Red Team training<br><sub>Detector de ARP spoofing + PoC activo — Scapy, detección pasiva+activa para Blue Team / Red Team</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-icmp-shadow"><b>vamp-icmp-shadow</b></a></td>
<td><code>v1.3</code></td>
<td>ICMP covert channel lab for Blue Team / Red Team training — educational PoC, authorized use only<br><sub>Laboratorio de canal encubierto ICMP para formación Blue/Red Team — PoC educativo, solo uso autorizado</sub></td>
</tr>

<tr>
<td><a href="https://github.com/Vampsecure-Labs/vamp-shellcode-lab"><b>vamp-shellcode-lab</b></a></td>
<td><code>v1.0.0</code></td>
<td>ARM64 shellcode research lab — macOS/Linux shellcode generation, encoding, analysis. Authorized use only<br><sub>Lab de investigación de shellcode ARM64 — generación, codificación y análisis. Solo uso autorizado</sub></td>
</tr>

</tbody>
</table>

---

## ⚡ Quick Start / Inicio rápido

```bash
# Install via PyPI / Instalar vía PyPI
pip install vamp-ssl-audit vamp-secrets-scanner vamp-iac-audit vamp-k8s-audit

# Install via Homebrew / Instalar vía Homebrew
brew tap vampsecure-labs/labs
brew install vamp-ssl-audit vamp-iac-audit vamp-secrets-scanner

# Scan IaC for misconfigurations / Escanear IaC
vamp-iac-audit scan --path ./infra --json results.json

# Scan for secrets in git history / Escanear secretos en historial git
vamp-secrets-scanner . --git-history --sarif findings.sarif

# TLS audit / Auditoría TLS
vamp-ssl-audit example.com --html report.html

# Kubernetes security audit / Auditoría de seguridad Kubernetes
vamp-k8s-audit --all --delta last_scan.json

# Orchestrate multiple tools / Orquestar múltiples herramientas
python3 vamp_orchestrator.py --targets example.com --playbook devops_audit --report-html audit.html
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
# GitHub Actions / Forgejo CI
- name: IaC security scan
  run: vamp-iac-audit scan --path ./infra --json iac.json
  continue-on-error: false  # exit 2 = CRITICAL = pipeline fails

- name: Secrets scan
  run: vamp-secrets-scanner . --git-history --sarif secrets.sarif
```

---

## 📐 Unified Report Format / Formato de informe unificado

All tools produce a **consistent JSON schema** for interoperability.<br>
Todas las herramientas generan un **esquema JSON consistente** para interoperabilidad.

```json
{
  "tool": "vamp-iac-audit",
  "version": "2.5.0",
  "target": "./infra",
  "timestamp": "2026-10-08T12:00:00Z",
  "findings": [
    {
      "id": "IAC-CDK-Y-001",
      "severity": "CRITICAL",
      "title": "Lambda Function URL without authentication (AuthType: NONE)",
      "description": "...",
      "remediation": "...",
      "mitre_attack": "T1190"
    }
  ],
  "summary": { "total": 1, "critical": 1, "high": 0, "medium": 0, "low": 0 }
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
