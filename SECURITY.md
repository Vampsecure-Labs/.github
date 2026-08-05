# Security Policy / Política de Seguridad

---

## English

### Supported Tools

| Tool | Status |
|------|--------|
| vamp-orchestrator | ✅ Active |
| vamp-penreport | ✅ Active |
| vamp-log-analyzer | ✅ Active |
| vamp-passive-recon | ✅ Active |
| vamp-ssl-audit | ✅ Active |
| vamp-http-audit | ✅ Active |
| vamp-secrets-scanner | ✅ Active |
| vamp-docker-audit | ✅ Active |
| vamp-k8s-audit | ✅ Active |
| vamp-entropy-watch | ✅ Active |
| vamp-subdomain-takeover | ✅ Active |
| vamp-jwt-audit | ✅ Active |
| vamp-mail-audit | ✅ Active |
| vamp-forticheck | ✅ Active |
| vamp-cve-oracle | ✅ Active |
| vamp-cloud-enum | ✅ Active |
| vamp-llm-probe | ✅ Active |
| vamp-wp2shell-audit | ✅ Active |
| vamp-arp-sentinel | ✅ Active |
| vamp-icmp-shadow | ✅ Active |
| vamp-shellcode-lab | ✅ Active |

### Reporting a Vulnerability

**Do not open a public issue for security vulnerabilities.**

If you find a vulnerability in any VampSecure Labs tool — code execution, credential exposure, unsafe defaults, or any behavior that could harm users running these tools — please report it privately:

**Email:** contact@vampsecurestudios.com  
**Subject:** `[VSL-SEC] <tool-name> — <brief description>`

Include in your report:
- Tool name and version (`python3 <tool>.py --version`)
- Python version and OS
- A minimal reproduction case
- Impact assessment (what an attacker could achieve)

### Response Timeline

| Milestone | Target |
|-----------|--------|
| Acknowledgement | 72 hours |
| Triage and severity assessment | 7 days |
| Fix or mitigation | 30 days (critical), 90 days (others) |
| Public disclosure | After fix is released |

We follow a coordinated disclosure model. Reporters who identify valid vulnerabilities will be credited in the release notes unless anonymity is requested.

### Scope

**In scope:**
- Logic bugs that produce false negatives (missed vulnerabilities)
- Code execution vulnerabilities in the tools themselves
- Hardcoded credentials or secrets in source code
- Unsafe default behavior (e.g. running without scope validation)

**Out of scope:**
- Vulnerabilities in third-party dependencies (report to upstream)
- Findings from running the tools against unauthorized targets
- Theoretical vulnerabilities without a proof of concept

### Legal

VampSecure Labs tools are designed for authorized security assessments only. Using these tools against systems you do not own or have explicit written permission to test is illegal and outside the scope of this security policy.

---

## Español

### Herramientas soportadas

| Herramienta | Estado |
|-------------|--------|
| vamp-orchestrator | ✅ Activa |
| vamp-penreport | ✅ Activa |
| vamp-log-analyzer | ✅ Activa |
| vamp-passive-recon | ✅ Activa |
| vamp-ssl-audit | ✅ Activa |
| vamp-http-audit | ✅ Activa |
| vamp-secrets-scanner | ✅ Activa |
| vamp-docker-audit | ✅ Activa |
| vamp-k8s-audit | ✅ Activa |
| vamp-entropy-watch | ✅ Activa |
| vamp-subdomain-takeover | ✅ Activa |
| vamp-jwt-audit | ✅ Activa |
| vamp-mail-audit | ✅ Activa |
| vamp-forticheck | ✅ Activa |
| vamp-cve-oracle | ✅ Activa |
| vamp-cloud-enum | ✅ Activa |
| vamp-llm-probe | ✅ Activa |
| vamp-wp2shell-audit | ✅ Activa |
| vamp-arp-sentinel | ✅ Activa |
| vamp-icmp-shadow | ✅ Activa |
| vamp-shellcode-lab | ✅ Activa |

### Notificación de vulnerabilidades

**No abras un issue público para vulnerabilidades de seguridad.**

Si encuentras una vulnerabilidad en alguna herramienta de VampSecure Labs — ejecución de código, exposición de credenciales, comportamientos inseguros por defecto, o cualquier comportamiento que pueda perjudicar a los usuarios — repórtala de forma privada:

**Email:** contact@vampsecurestudios.com  
**Asunto:** `[VSL-SEC] <nombre-herramienta> — <descripción breve>`

Incluye en tu reporte:
- Nombre y versión de la herramienta (`python3 <tool>.py --version`)
- Versión de Python y sistema operativo
- Un caso de reproducción mínimo
- Evaluación del impacto (qué podría conseguir un atacante)

### Plazos de respuesta

| Hito | Objetivo |
|------|----------|
| Acuse de recibo | 72 horas |
| Triaje y evaluación de severidad | 7 días |
| Corrección o mitigación | 30 días (crítico), 90 días (otros) |
| Divulgación pública | Tras publicar la corrección |

Seguimos un modelo de divulgación coordinada. Los reporteros que identifiquen vulnerabilidades válidas serán mencionados en las notas de la versión, salvo que soliciten anonimato.

### Alcance

**En alcance:**
- Bugs lógicos que producen falsos negativos (vulnerabilidades no detectadas)
- Vulnerabilidades de ejecución de código en las propias herramientas
- Credenciales o secretos hardcodeados en el código fuente
- Comportamiento inseguro por defecto (p.ej. ejecución sin validación de scope)

**Fuera de alcance:**
- Vulnerabilidades en dependencias de terceros (repórtalas al proyecto correspondiente)
- Hallazgos obtenidos ejecutando las herramientas contra objetivos no autorizados
- Vulnerabilidades teóricas sin prueba de concepto

### Aviso legal

Las herramientas de VampSecure Labs están diseñadas exclusivamente para auditorías de seguridad autorizadas. Utilizarlas contra sistemas que no sean de tu propiedad o para los que no tengas permiso escrito explícito es ilegal y queda fuera del ámbito de esta política de seguridad.

---

© VampSecure Studios — VampSecure Labs Security Research Division
