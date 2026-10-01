# Reglas del repositorio — TESIS

Este repositorio contiene la tesis. Estas reglas **sustituyen**, solo dentro de
`D:\Negocia.pe\TESIS`, a las reglas globales de documentacion del ecosistema
Negocia.pe.

## Boveda de documentacion de la tesis (unica fuente de verdad)

- La boveda Obsidian de este repo es **`D:\Negocia.pe\TESIS\docs`**.
- NO se usa la boveda `D:\Negocia.pe\appnegocialat\docs` ni el subagente
  `documentador-boveda` para este repo.
- Al iniciar trabajo, lee SOLO `docs/HOME.md`. Para el detalle de un capitulo,
  decision o componente, lee el `.md` exacto enlazado desde HOME.

## Documentacion automatica (OBLIGATORIO)

- **Todo lo que se cree, modifique, corrija o elimine** en este repo (capitulos,
  borradores, codigo, datos, experimentos, resultados, figuras, bibliografia,
  decisiones metodologicas, configuracion) debe quedar documentado en `docs/`.
- Al terminar cada tarea, invoca el subagente **`documentador-tesis`** en
  background (primero se entrega el trabajo al usuario, luego se documenta).
- En el prompt del subagente pasa siempre:
  - **QUE** cambio (resumen funcional/academico),
  - **DONDE** (rutas absolutas + lineas, secciones o nombres de funcion),
  - **POR QUE** (motivo o decision que lo origino).
  Sin esos tres datos no lo invoques.
- Excepciones (NO documentar): cambios puramente cosmeticos (typos, formato),
  archivos temporales/scratchpad, o si el usuario escribe `SIN DOCUMENTAR`.
- Al recibir su reporte, resume al usuario en UNA linea que `.md` se crearon o
  actualizaron.

## Integridad academica

- No inventar citas, autores, DOIs, datos ni resultados. Toda referencia debe
  existir en `docs/BIBLIOGRAFIA/` o ser aportada por el usuario.
- Si un dato no esta documentado, preguntar antes de asumirlo.
