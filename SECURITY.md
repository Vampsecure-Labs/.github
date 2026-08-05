# Security Policy

## Supported Tools

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

## Reporting a Vulnerability

**Do not open a public issue for security vulnerabilities.**

If you find a vulnerability in any VampSecure Labs tool — code execution, credential exposure, unsafe defaults, or any behavior that could harm users running these tools — please report it privately:

**Email:** security@vampsecurestudios.com  
**Subject:** `[VSL-SEC] <tool-name> — <brief description>`

Include in your report:
- Tool name and version (`python3 <tool>.py --version`)
- Python version and OS
- A minimal reproduction case
- Impact assessment (what an attacker could achieve)

## Response Timeline

| Milestone | Target |
|-----------|--------|
| Acknowledgement | 72 hours |
| Triage and severity assessment | 7 days |
| Fix or mitigation | 30 days (critical), 90 days (others) |
| Public disclosure | After fix is released |

We follow a coordinated disclosure model. Reporters who identify valid vulnerabilities will be credited in the release notes unless anonymity is requested.

## Scope

**In scope:**
- Logic bugs in tool output that produce false negatives (missed vulnerabilities)
- Code execution vulnerabilities in the tools themselves
- Hardcoded credentials or secrets in source code
- Unsafe default behavior (e.g. running without scope validation)

**Out of scope:**
- Vulnerabilities in third-party dependencies (report to upstream)
- Findings from running the tools against unauthorized targets
- Theoretical vulnerabilities without a proof of concept

## Legal

VampSecure Labs tools are designed for authorized security assessments only. Using these tools against systems you do not own or have explicit written permission to test is illegal and outside the scope of this security policy.

---

© VampSecure Studios — VampSecure Labs Security Research Division
