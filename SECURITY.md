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

If you find a vulnerability in any VampSecure Labs tool — code execution, credential exposure, unsafe defaults, or any behavior that could harm people running these tools — please reach out privately:

**Email:** contact@vampsecurestudios.com  
**Subject:** `[VSL-SEC] <tool-name> — <brief description>`

It helps to include:
- Tool name and version (`python3 <tool>.py --version`)
- Python version and OS
- A minimal way to reproduce it
- What an attacker could actually do with this

### Response Timeline

| Milestone | Target |
|-----------|--------|
| We confirm we received it | 72 hours |
| We assess severity | 7 days |
| Fix or workaround | 30 days (critical), 90 days (others) |
| Public disclosure | After the fix is out |

We work through coordinated disclosure. Anyone who finds a real vulnerability gets credited in the release notes — just let us know if you'd rather stay anonymous.

### Scope

**We want to hear about:**
- Logic bugs that produce false negatives (missed vulnerabilities)
- Code execution vulnerabilities in the tools themselves
- Hardcoded credentials or secrets in source code
- Unsafe default behavior (e.g. running without scope validation)

**Out of scope:**
- Vulnerabilities in third-party dependencies (please report those upstream)
- Findings from running the tools against targets you don't own
- Theoretical issues without a working proof of concept

### Legal

VampSecure Labs tools are for authorized security assessments only. Using them against systems you don't own or haven't been explicitly permitted to test is illegal — and outside the scope of this policy.

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

### Cómo avisarnos de un problema de seguridad

**No abras un issue público si has encontrado un fallo de seguridad.**

Si encuentras algo en alguna herramienta de VampSecure Labs — ejecución de código arbitrario, credenciales expuestas, comportamientos inseguros por defecto, o cualquier cosa que pueda perjudicar a quien usa las herramientas — escríbenos en privado:

**Email:** contact@vampsecurestudios.com  
**Asunto:** `[VSL-SEC] <nombre-herramienta> — <descripción breve>`

Nos ayuda mucho si incluyes:
- Nombre y versión de la herramienta (`python3 <tool>.py --version`)
- Versión de Python y sistema operativo
- Cómo reproducirlo (cuanto más concreto, mejor)
- Qué daño podría causar si alguien lo aprovecha

### Cuándo respondemos

| Qué | En cuánto tiempo |
|-----|-----------------|
| Confirmamos que lo hemos recibido | 72 horas |
| Lo analizamos y valoramos su gravedad | 7 días |
| Publicamos un arreglo o solución temporal | 30 días (crítico), 90 días (otros) |
| Lo hacemos público | Cuando el arreglo ya está disponible |

Gestionamos los avisos de forma coordinada. Si encuentras algo real, te mencionamos en las notas de la versión — dinos si prefieres que no aparezca tu nombre.

### Qué cubrimos

**Esto sí nos interesa:**
- Bugs lógicos que hacen que la herramienta no detecte vulnerabilidades que debería detectar
- Vulnerabilidades de ejecución de código en las propias herramientas
- Credenciales o secretos escritos directamente en el código fuente
- Comportamientos inseguros por defecto (p.ej. ejecutarse sin validar el scope)

**Esto no entra:**
- Fallos en librerías de terceros (eso hay que reportarlo al proyecto que las mantiene)
- Resultados de usar las herramientas contra objetivos sin permiso
- Problemas teóricos sin demostración práctica

### Uso responsable

Nuestras herramientas son para auditorías con permiso expreso. Usarlas contra sistemas que no son tuyos o para los que no tienes autorización por escrito es ilegal — y queda fuera del alcance de esta política.

---

© VampSecure Studios — VampSecure Labs Security Research Division
