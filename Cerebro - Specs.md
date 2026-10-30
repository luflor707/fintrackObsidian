---
tipo: cerebro
nombre: specs
filtro_grafo: "tag:#grupo/specs OR tag:#estado/implementado OR tag:#estado/propuesto"
tags:
  - grupo/specs
  - cerebro/specs
---

# Cerebro de specs

Responde **qué debe hacer el producto, por qué y cómo se acepta**.

## Núcleos

- [[03-Specs/Specs - Inicio]]
- [[10 - Frontend - Panel]]
- [[20 - Backend - Auth y sesiones]]
- [[Cerebro - Documentación]]

## División Frontend / Backend

### 🩷 Specs frontend

| Capacidad | Documento |
|---|---|
| Panel | [[10 - Frontend - Panel]] |
| Movimientos | [[11 - Frontend - Movimientos]] |
| Presupuestos | [[12 - Frontend - Presupuestos]] |
| Informes | [[13 - Frontend - Informes]] |
| Metas | [[14 - Frontend - Metas]] |
| Usuarios y auth | [[15 - Frontend - Usuarios]] · [[17 - Frontend - Auth]] · [[18 - Frontend - Cuenta]] |
| Notificaciones | [[16 - Frontend - Notificaciones]] · propuesta |

### 🔷 Specs backend

| Capacidad | Documento |
|---|---|
| Auth y sesiones | [[20 - Backend - Auth y sesiones]] |
| Perfil | [[21 - Backend - Perfil]] |
| Transacciones | [[22 - Backend - Transacciones y categorías]] |
| Dashboard | [[23 - Backend - Dashboard]] |
| Presupuestos | [[24 - Backend - Presupuestos]] |
| Ahorros | [[25 - Backend - Ahorros]] |
| Reportes | [[26 - Backend - Reportes]] |
| Notificaciones | [[27 - Backend - Notificaciones]] · propuesta |

Cada spec frontend debe enlazar al contrato backend que consume; cada spec backend debe indicar qué consumidor soporta.

## Estructura de una spec

```text
Contexto → usuarios → historias → RF EARS → RNF → límites → fuera de alcance → evidencia
```

## Estado

- Capacidades 001–007 del backend: descritas con comportamiento observado.
- Notificaciones: propuesta, no tratar como implementada.
- Las specs no autorizan implementación sin una tarea encargada.

