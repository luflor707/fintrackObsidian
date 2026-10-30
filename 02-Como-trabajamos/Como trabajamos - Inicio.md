---
tipo: brain
area: como-trabajamos
color: cyan
estado: activo
tags:
  - grupo/proceso
---

# 🔄 Cómo trabajamos

> [!workflow] Propósito
> Convertir una necesidad en una entrega verificable, con decisiones pequeñas y evidencia real.

🗺️ Canvas visual: [[Como trabajamos.canvas]]

## Ruta SDD

```text
Inventariar → Especificar → Revisar → Planificar → Dividir → Ejecutar → Auditar
```

## Grupos

| Grupo | Pregunta | Resultado | Color |
|---|---|---|---|
| SDD | ¿Qué existe y qué se quiere cambiar? | Spec y evidencia | Cian |
| Calidad | ¿Cómo sabemos que funciona? | Checks registrados | Cian |
| Git | ¿Cómo aislamos y entregamos? | Rama, merge o push explícito | Cian |
| Decisiones | ¿Por qué elegimos esto? | Registro de decisión | Cian |

## Reglas

- Describir primero lo que existe; después especificar el cambio.
- No reimplementar capacidades existentes por ceremonia.
- Una tarea autorizada, un alcance acotado y una comprobación pertinente.
- “Existe un test” no equivale a “el test pasó”.
- Un merge local no es un push.

## Etiquetas de certeza

`OBSERVADO` · `RECOMENDACIÓN` · `DEPENDENCIA EXTERNA` · `[NO VERIFICADO]`

## Ciclo mínimo

| Paso | Salida verificable |
|---|---|
| Inventariar | Capacidades, exclusiones y SHA |
| Especificar | QUÉ/POR QUÉ y RF EARS |
| Revisar | Ambigüedades, contradicciones y límites |
| Planificar | Módulos, contratos, datos y tests |
| Dividir | Tareas de 20–30 minutos |
| Ejecutar | Cambio acotado y checks |
| Auditar | Cobertura, fallos y veredicto |

