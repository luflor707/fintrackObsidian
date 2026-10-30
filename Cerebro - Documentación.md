---
tipo: cerebro
nombre: documentacion
filtro_grafo: "tag:#grupo/documentacion OR tag:#grupo/contrato"
tags:
  - grupo/documentacion
  - cerebro/documentacion
---

# Cerebro de documentación

Responde **dónde vive cada verdad y cómo evitar que la documentación se quede atrás**.

## Núcleos

- [[05-Documentacion/Documentacion - Inicio]]
- [[00 - Mapa de FinanTrack]]
- [[Cerebro - Arquitectura]]

## División Frontend / Backend

### 🩷 Documentación frontend

- Código: `fintrackFrontend/src/features/`.
- Specs: `fintrackFrontend/docs/specs/`.
- Arquitectura e integración: `fintrackFrontend/docs/architecture.md` y `integration.md`.
- Evidencia: `fintrackFrontend/docs/sdd/verification.md`.

### 🔷 Documentación backend

- Código: `fintrackBackend/src/modules/`.
- Specs: `fintrackBackend/docs/specs/`.
- Contratos: `fintrackBackend/docs/openapi/`.
- Evidencia: `fintrackBackend/docs/sdd/coverage.md`.

### Puente entre ambos

Los contratos HTTP y sus pruebas son la documentación compartida. Si cambia una respuesta, actualizar frontend, backend, spec y evidencia.

## Jerarquía de fuentes

1. Código, contratos y pruebas actuales.
2. Specs, planes, tareas y matrices del repositorio.
3. Este vault como mapa y contexto.
4. Entregas históricas, marcadas como históricas.

## Regla de mantenimiento

Si cambia un módulo, actualizar su nota, la spec relacionada, el plan, la tarea, la matriz de evidencia y el índice cuando corresponda.

