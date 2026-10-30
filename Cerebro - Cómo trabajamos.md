---
tipo: cerebro
nombre: como-trabajamos
filtro_grafo: "tag:#grupo/proceso"
tags:
  - grupo/proceso
  - cerebro/como-trabajamos
---

# Cerebro de cómo trabajamos

Responde **cómo pasamos de una necesidad a una entrega comprobada**.

## Núcleos

- [[02-Como-trabajamos/Como trabajamos - Inicio]]
- [[Cerebro - Specs]]
- [[Cerebro - Desarrollo]]

## División Frontend / Backend

### 🩷 Flujo Frontend

Inventario de pantalla → spec de interacción → contrato consumido → implementación de feature → tests UI → evidencia.

### 🔷 Flujo Backend

Inventario de comportamiento → spec funcional → contrato/API → implementación de módulo → tests de servicio → evidencia.

El punto de coordinación entre ambos es el contrato; una capa no inventa el comportamiento de la otra.

## Ciclo SDD

```mermaid
flowchart LR
    subgraph FE["FRONTEND · MAGENTA"]
        FEA[Inventario UI] --> FEB[Spec UI] --> FEC[Feature + tests]
    end
    subgraph BE["BACKEND · AZUL"]
        BEA[Inventario API] --> BEB[Spec funcional] --> BEC[Módulo + tests]
    end
    FEC --> CONTRACT[Contrato]
    CONTRACT --> BEC
    FEC --> AUDIT[Auditar]
    BEC --> AUDIT
```

## Reglas

- Separar `OBSERVADO`, `RECOMENDACIÓN` y `DEPENDENCIA EXTERNA`.
- Ejecutar solo la tarea autorizada.
- Registrar comando, resultado, fecha y SHA.
- Un merge local no equivale a publicar.

