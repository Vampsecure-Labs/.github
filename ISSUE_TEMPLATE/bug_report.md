---
name: Bug report
about: Something is not working correctly in one of the VSL tools
title: '[BUG] <tool-name>: <brief description>'
labels: bug
assignees: ''
---

## Tool

<!-- Which tool is affected? -->
- [ ] vamp-orchestrator
- [ ] vamp-penreport
- [ ] vamp-log-analyzer
- [ ] vamp-passive-recon
- [ ] vamp-ssl-audit
- [ ] vamp-http-audit
- [ ] vamp-secrets-scanner
- [ ] vamp-docker-audit
- [ ] vamp-k8s-audit
- [ ] vamp-entropy-watch
- [ ] vamp-subdomain-takeover
- [ ] vamp-jwt-audit
- [ ] vamp-mail-audit
- [ ] vamp-forticheck
- [ ] vamp-cve-oracle
- [ ] vamp-cloud-enum
- [ ] vamp-llm-probe
- [ ] vamp-wp2shell-audit
- [ ] Other: ___

## Environment

```
Tool version: (output of --version or grep VERSION= <tool>.py)
Python version: (python3 --version)
OS: (uname -a or Windows version)
```

## Command

<!-- Paste the exact command, sanitizing any sensitive targets or credentials -->

```bash
python3 vamp_<tool>.py ...
```

## Expected behavior

<!-- What should happen? -->

## Actual behavior

<!-- What actually happens? -->

## Error output / stack trace

```
Paste full error output here
```

## Steps to reproduce

1.
2.
3.

## Additional context

<!-- Any relevant configuration, target type, network setup, etc. -->

---

> ⚠️ If this is a security vulnerability in the tool itself, do not open a public issue. See [SECURITY.md](../SECURITY.md) for private disclosure instructions.
