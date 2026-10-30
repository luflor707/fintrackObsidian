---
tipo: brain
area: documentacion
color: violet
estado: activo
tags:
  - grupo/documentacion
---

# 📚 Documentación

> [!documentation] Propósito
> Encontrar rápido la fuente correcta y mantenerla alineada con el código y la evidencia.

🗺️ Canvas visual: [[Documentacion.canvas]]

## Grupos

| Grupo | Responde | Fuente | Color |
|---|---|---|---|
| Producto | ¿Qué debe hacer? | Specs y criterios | Violeta |
| Técnica | ¿Cómo está construido? | Arquitectura y contratos | Violeta |
| Operación | ¿Cómo se ejecuta y verifica? | README, CI y checks | Violeta |
| Historial | ¿Qué ocurrió y cuándo? | Entregas y decisiones | Violeta |

## Jerarquía de fuentes

1. Código, contratos y pruebas actuales.
2. Specs, planes, tareas y matrices del repositorio.
3. Este vault como mapa y contexto compartido.
4. Documentos históricos, siempre marcados como históricos.

## Mapa rápido

| Necesidad | Ubicación |
|---|---|
| Constitución | `fintrackBackend/docs/constitution.md`, `fintrackFrontend/docs/constitution.md` |
| Flujo SDD | `docs/sdd/README.md` o `docs/sdd/workflow.md` |
| Inventario | `fintrackFrontend/docs/sdd/inventory.md` |
| Arquitectura | `docs/architecture.md` |
| Especificación | `docs/specs/NNN-tema/spec.md` |
| Plan técnico | `docs/specs/NNN-tema/plan.md` |
| Tareas | `docs/specs/NNN-tema/tasks.md` |
| Contratos HTTP | `docs/openapi/` o `contracts/` |
| Evidencia | `coverage.md` o `verification.md` |

## Regla de actualización

Si cambia el comportamiento, actualizar juntos spec, plan afectado, tarea, matriz e índice. Registrar SHA y fecha de auditoría.

## Checklist de cierre

- [ ] La documentación refleja el estado actual.
- [ ] Las propuestas están separadas de lo implementado.
- [ ] Los enlaces no apuntan a evidencia histórica como si fuera actual.
- [ ] Se registró el resultado real de los checks.

