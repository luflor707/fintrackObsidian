---
tipo: modulo-backend
modulo: perfil
estado: implementado
grupo_tecnico: backend
tags:
  - grupo/backend
  - grupo/contrato
  - estado/implementado
  - modulo/perfil
---

# Backend - Perfil

## Responsabilidad

Consulta y edición del perfil propio, respetando la propiedad del usuario autenticado.

## Código relacionado

- `fintrackBackend/src/modules/users/`

## Documentación

- Spec: `fintrackBackend/docs/specs/002-user-profile/spec.md`
- Contrato: `fintrackBackend/docs/openapi/users.v1.json`

## Regla

Una cuenta no debe leer ni modificar el perfil de otra cuenta.

