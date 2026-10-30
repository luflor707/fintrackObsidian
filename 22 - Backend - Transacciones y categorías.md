---
tipo: modulo-backend
modulo: transactions-categories
estado: implementado
grupo_tecnico: backend
tags:
  - grupo/backend
  - grupo/contrato
  - estado/implementado
  - modulo/transacciones
---

# Backend - Transacciones y categorías

## Responsabilidad

Operaciones sobre movimientos y categorías propios, incluyendo listas y paginación.

## Código relacionado

- `fintrackBackend/src/modules/transactions/`

## Documentación

- Spec: `fintrackBackend/docs/specs/003-transactions-categories/spec.md`
- Contrato: `fintrackBackend/docs/openapi/transactions.v1.json`

## Regla

La propiedad del usuario y los importes decimales deben resolverse en la API, no en la interfaz.

