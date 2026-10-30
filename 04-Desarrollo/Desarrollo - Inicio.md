---
tipo: brain
area: desarrollo
color: emerald
estado: activo
tags:
  - grupo/desarrollo
---

# 🛠️ Desarrollo

> [!development] Propósito
> Llevar una spec desde una tarea pequeña hasta una entrega comprobada, sin perder el contexto.

🗺️ Canvas visual: [[Desarrollo.canvas]]

## Grupos

| Grupo | Contenido | Color |
|---|---|---|
| Roadmap | Orden de capacidades y dependencias | Verde esmeralda |
| Feature work | Una rama/worktree por feature | Verde esmeralda |
| Checks | Tests, lint, build y evidencia | Verde esmeralda |
| Pendientes | Trabajo no iniciado y dependencias | Verde esmeralda |

## Ciclo de una feature

1. Leer constitución, spec, plan y tareas.
2. Confirmar el contrato entre capas.
3. Crear o seleccionar worktree y rama de feature.
4. Escribir el test pertinente cuando cambia comportamiento.
5. Implementar una tarea.
6. Ejecutar checks de la capa afectada.
7. Actualizar evidencia y marcar la tarea solo si cumple “Hecho cuando”.
8. Revisar el diff y preparar integración.

## Checks por capa

| Capa | Comprobar |
|---|---|
| Frontend | Typecheck, lint, tests y build |
| Backend | Tests unitarios/API, lint y contrato |
| Integración | Sesión, autorización, datos y errores |
| Docs | Enlaces, IDs y estado de requisitos |

## Backlog inicial

- [ ] Confirmar integración real de sesión y autorización.
- [ ] Auditar cobertura RF por capacidad.
- [ ] Registrar casos límite de meses sin actividad en reportes.
- [ ] Cerrar contrato de notificaciones antes de implementarlas.

