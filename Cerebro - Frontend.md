---
tipo: cerebro-capa
nombre: frontend
color: magenta
tags:
  - grupo/frontend
  - cerebro/frontend
---

# Cerebro Frontend

Este es el centro de todas las neuronas frontend. Todo lo que vive aquí pertenece a la experiencia, composición y consumo de contratos del cliente.

## Neuronas de módulo

- [[10 - Frontend - Panel]]
- [[11 - Frontend - Movimientos]]
- [[12 - Frontend - Presupuestos]]
- [[13 - Frontend - Informes]]
- [[14 - Frontend - Metas]]
- [[15 - Frontend - Usuarios]]
- [[16 - Frontend - Notificaciones]]
- [[17 - Frontend - Auth]]
- [[18 - Frontend - Cuenta]]

## Neuronas transversales

- [[Cerebro - Arquitectura]]
- [[Cerebro - Cómo trabajamos]]
- [[Cerebro - Specs]]
- [[Cerebro - Desarrollo]]
- [[Cerebro - Documentación]]

## Código

`fintrackFrontend/src/app/` · `fintrackFrontend/src/features/` · `fintrackFrontend/docs/`

```mermaid
flowchart LR
    BRAIN((CEREBRO\nFRONTEND))
    BRAIN --> PANEL[Panel]
    BRAIN --> TX[Movimientos]
    BRAIN --> BUD[Presupuestos]
    BRAIN --> REPORT[Informes]
    BRAIN --> GOALS[Metas]
    BRAIN --> AUTH[Auth + cuenta]
    BRAIN --> DOC[Specs + docs]
    classDef brain fill:#D81B60,color:#fff,stroke:#880E4F
    classDef neuron fill:#F8BBD0,color:#111,stroke:#D81B60
    class BRAIN brain
    class PANEL,TX,BUD,REPORT,GOALS,AUTH,DOC neuron
```

