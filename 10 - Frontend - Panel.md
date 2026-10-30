---
tipo: modulo-frontend
modulo: panel
estado: implementado
grupo_tecnico: frontend
tags:
  - grupo/frontend
  - grupo/contrato
  - estado/implementado
  - modulo/panel
---

# Frontend - Panel

## Responsabilidad

Presentar saldo, resumen mensual, gráficos e indicadores financieros.

## Consume

Contrato de dashboard y sesión Bearer. El cliente presenta agregados recibidos; no recalcula reglas financieras.

## Código relacionado

- `fintrackFrontend/src/features/dashboard/`

## Documentación de entrega

- Spec: `fintrackFrontend/docs/specs/001-panel/spec.md`
- Plan: `fintrackFrontend/docs/specs/001-panel/plan.md`
- Tareas: `fintrackFrontend/docs/specs/001-panel/tasks.md`
- Arquitectura: `fintrackFrontend/docs/architecture.md`

## Pendientes de evidencia

Confirmar integración real con la API y aislamiento por usuario.

