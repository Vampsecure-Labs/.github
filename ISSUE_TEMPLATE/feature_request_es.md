---
name: "Solicitud de funcionalidad (ES)"
about: Propón una nueva capacidad o mejora para alguna herramienta VSL
title: '[FEAT] <nombre-herramienta>: <descripción breve>'
labels: enhancement
assignees: ''
---

## Herramienta

<!-- ¿Qué herramienta debería mejorarse? Si es una herramienta nueva, escribe "nueva herramienta". -->

## Comportamiento actual / limitación

<!-- ¿Qué no puedes hacer hoy, o qué funciona mal? -->

## Comportamiento propuesto

<!-- ¿Qué debería hacer la herramienta en su lugar? Sé lo más específico posible. -->

## Caso de uso

<!-- Describe un escenario real de auditoría donde esto sería útil. -->

```bash
# Ejemplo del comando o flujo de trabajo que te gustaría ejecutar
python3 vamp_<herramienta>.py --nuevo-flag ...
```

## Salida esperada / sección del informe

<!-- ¿Cómo debería verse la salida JSON o el informe HTML? Pega un ejemplo si puedes. -->

## Impacto en el schema VSL

<!-- ¿Añade nuevos campos al JSON de findings? ¿Afecta a la salida de vamp-penreport? -->
- [ ] Nuevos campos en `findings[]`
- [ ] Nueva clave a nivel raíz en la salida
- [ ] Cambios en la integración con vamp-penreport / vamp-orchestrator
- [ ] Sin cambios de schema

## ¿Dispuesto a contribuir?

- [ ] Puedo enviar un pull request con esta funcionalidad
- [ ] Puedo ayudar a probar una implementación
- [ ] Solo estoy haciendo una sugerencia

---

> Todas las herramientas VSL deben producir salida JSON estándar (array `findings[]`) compatible con `vamp-orchestrator` y `vamp-penreport`. Ten esto en cuenta al proponer nuevas herramientas o campos de salida.
