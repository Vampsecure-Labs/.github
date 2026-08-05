---
name: "Informe de error (ES)"
about: Algo no funciona correctamente en alguna de las herramientas VSL
title: '[BUG] <nombre-herramienta>: <descripción breve>'
labels: bug
assignees: ''
---

## Herramienta

<!-- ¿Qué herramienta está afectada? -->
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
- [ ] Otra: ___

## Entorno

```
Versión de la herramienta: (salida de --version o grep VERSION= <tool>.py)
Versión de Python: (python3 --version)
Sistema operativo: (uname -a o versión de Windows)
```

## Comando ejecutado

<!-- Pega el comando exacto, quitando objetivos o credenciales reales -->

```bash
python3 vamp_<herramienta>.py ...
```

## Qué esperabas que pasara

<!-- ¿Qué debería ocurrir? -->

## Qué pasó en realidad

<!-- ¿Qué ocurre en realidad? -->

## Error completo

```
Pega aquí el error completo
```

## Pasos para reproducirlo

1.
2.
3.

## ¿Algo más?

<!-- Configuración relevante, tipo de objetivo, entorno de red, etc. -->

---

> ⚠️ Si crees que has encontrado un fallo de seguridad en la propia herramienta, no lo publiques aquí. Escríbenos en privado siguiendo lo que explica [SECURITY.md](../SECURITY.md).
