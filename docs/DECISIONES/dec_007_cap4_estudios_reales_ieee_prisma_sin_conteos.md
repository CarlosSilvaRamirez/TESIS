---
tipo: decision
id: dec_007
fecha: 2026-10-20
estado: aceptada
tags: [decision, capitulo_iv, prisma, integridad]
related: [capitulo_iv_revision_literatura, dec_003_estilo_citas_ieee, dec_006_numeracion_ieee_global_continua, referencias_capitulo_iv]
---

# DEC-007 — Cap. IV: estudios reales, IEEE y PRISMA sin conteos inventados

## Contexto
`Downloads/cap4.docx` (prompts 13-20) pide una matriz con "ejemplos simulados", verificacion de referencias en APA 7 y un flujo PRISMA. El repo prohibe inventar estudios o datos, y el usuario ya adopto IEEE ([[dec_003_estilo_citas_ieee]], [[dec_006_numeracion_ieee_global_continua]]).

## Alternativas consideradas
1. Seguir el prompt literalmente (estudios simulados, APA 7, conteos ilustrativos).
2. Estudios reales verificados, IEEE y flujo PRISMA con valores pendientes.

## Decision
Opcion 2:
- Matriz (4.4) con 15 estudios reales verificados; pais "No reportado" cuando el resumen no lo indica.
- Verificacion de referencias (4.8) cumplida en IEEE, no APA 7.
- Figura 1 PRISMA con n = __ para que el usuario complete tras ejecutar las busquedas.

## Justificacion
Regla de integridad academica del repo; decision previa del usuario de usar IEEE; los conteos solo existen tras ejecutar las ecuaciones de 4.1.

## Consecuencias / impacto en la tesis
- Pendiente del usuario: ejecutar busquedas y completar la Figura 1.
- Nueva fuente [35] solo en Cap. IV ([[referencias_capitulo_iv]]).
- Los 15 estudios de la matriz no equivalen aun a la muestra final de la revision.
