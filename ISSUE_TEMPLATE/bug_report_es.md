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

<!-- Pega el comando exacto, eliminando objetivos o credenciales sensibles -->

```bash
python3 vamp_<herramienta>.py ...
```

## Comportamiento esperado

<!-- ¿Qué debería ocurrir? -->

## Comportamiento real

<!-- ¿Qué ocurre en realidad? -->

## Salida de error / traza

```
Pega aquí la salida de error completa
```

## Pasos para reproducir

1.
2.
3.

## Contexto adicional

<!-- Configuración relevante, tipo de objetivo, entorno de red, etc. -->

---

> ⚠️ Si se trata de una vulnerabilidad de seguridad en la propia herramienta, no abras un issue público. Consulta [SECURITY.md](../SECURITY.md) para instrucciones de notificación privada.
