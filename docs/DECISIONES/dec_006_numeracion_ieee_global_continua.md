---
tipo: decision
id: dec_006
fecha: 2026-10-19
estado: aceptada
tags: [decision, citas, ieee, numeracion]
related: [dec_003_estilo_citas_ieee, referencias_globales_ieee, referencias_capitulo_i, referencias_capitulo_ii, referencias_capitulo_iii]
---

# DEC-006 — Numeracion IEEE global continua

## Contexto
Tras [[dec_003_estilo_citas_ieee]], los Capitulos II y III se generaron con numeracion IEEE independiente por capitulo (cada uno reiniciaba en [1]). El usuario pidio que las fuentes nuevas continuaran desde el ultimo numero del Capitulo I ([27] a [28]) y confirmo actualizar los documentos.

## Alternativas consideradas
1. Numeracion independiente por capitulo (reinicia en [1]).
2. Numeracion global continua en toda la tesis.

## Decision
Opcion 2. Cap. I conserva [1]-[27]; las fuentes nuevas continuan por orden de primera aparicion: [28] INEI 2026, [29] Ley 29733, [30] PRODUCE 2025, [31] Lavanda Reyes et al., [32] Lopez Leonardo y Lozada Tiglla, [33] Naciones Unidas 2015, [34] Bravo Maruri et al. Las fuentes reutilizadas usan el mismo numero que en el Cap. I. Citas multiples en orden ascendente. Cada capitulo lista al final solo las fuentes que cita, ordenadas por numero global (la lista no es consecutiva). Cap. II cita 23 fuentes y Cap. III 16.

## Justificacion
Solicitud explicita del usuario; un numero = una fuente en toda la tesis evita ambiguedad al consolidar el documento final. Verificado por script (segun el coordinador): mismo texto de referencia por numero en los tres capitulos y todas las citas del cuerpo presentes en la lista. El texto de los capitulos no cambio, solo los numeros.

## Consecuencias / impacto en la tesis
- Maestra en [[referencias_globales_ieee]]; nuevas fuentes continuan desde [35].
- Regenerados `Capitulo II - Problema y justificacion.docx` y `Capitulo III - Objetivos, preguntas e hipotesis.docx`; Cap. I sin cambios.
- Si se agrega o retira una fuente del Cap. I, hay que revisar los numeros de los capitulos siguientes.
- Complementa (no reemplaza) a dec_003.
