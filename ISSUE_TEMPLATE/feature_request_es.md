---
name: "Solicitud de funcionalidad (ES)"
about: Propón una nueva capacidad o mejora para alguna herramienta VSL
title: '[FEAT] <nombre-herramienta>: <descripción breve>'
labels: enhancement
assignees: ''
---

## Herramienta

<!-- ¿Qué herramienta mejorarías? Si es una herramienta nueva, escribe "nueva herramienta". -->

## Qué no puedes hacer hoy

<!-- ¿Qué falta, o qué funciona mal? -->

## Lo que propones

<!-- ¿Qué debería hacer la herramienta? Cuanto más concreto, mejor. -->

## Caso de uso real

<!-- Describe una situación de auditoría donde esto te vendría bien. -->

```bash
# Ejemplo del comando que te gustaría poder ejecutar
python3 vamp_<herramienta>.py --nuevo-flag ...
```

## Cómo debería verse la salida

<!-- ¿Cómo quedaría el JSON o el informe HTML? Pega un ejemplo si puedes. -->

## ¿Cambia el formato de salida VSL?

<!-- ¿Añade nuevos campos al JSON de findings? ¿Afecta a vamp-penreport? -->
- [ ] Nuevos campos en `findings[]`
- [ ] Nueva clave a nivel raíz en la salida
- [ ] Cambia la integración con vamp-penreport / vamp-orchestrator
- [ ] No cambia nada del formato

## ¿Te animas a contribuir?

- [ ] Puedo programarlo y abrir un PR
- [ ] Puedo ayudar con las pruebas
- [ ] Solo es una idea, sin más

---

> Recuerda que todas las herramientas VSL generan JSON estándar compatible con `vamp-orchestrator` y `vamp-penreport`. Tenlo en cuenta si propones nuevos campos o una herramienta nueva.
