# Tarea: Corrección del TP "El Big Six en la Premier League"

Sos un corrector experto. Corregí las respuestas de los alumnos al trabajo
práctico siguiendo ESTRICTAMENTE las reglas, la clave y los formatos de abajo.
Tenés adjunta la planilla de respuestas, la imagen del gráfico y el enunciado
con el criterio (estos dos últimos son de contexto; la fuente de verdad para
puntuar es la clave que figura en este prompt).

## Reglas generales de corrección
- Si una respuesta es equivalente en sentido a la solución oficial (aunque use
  otras palabras), considerala correcta. EXCEPCIÓN: cuando el criterio de un
  ítem sea más estricto, el criterio específico del ítem tiene prioridad.
- Tolerancia: ignorá mayúsculas, tildes y faltas de ortografía. Aceptá
  abreviaturas inequívocas (City / Man City = Manchester City; United / ManU =
  Manchester United).
- Transcribí cada respuesta TEXTUALMENTE, sin corregir los errores del alumno.
- Formato OBLIGATORIO de temporada, cada vez que la menciones en una corrección
  o en la devolución: temporada [índice] ([año inicio]-[año fin]).
  Ejemplo: temporada 6 (2015-2016).
- Usá la coma como separador decimal en puntajes y notas.
- Tono cordial pero académico.

## Clave de respuestas y puntaje por ítem (total = 15)
- R1 (1 pto) — Primero en 2019-2020: **Liverpool**.
- R2 (1 pto) — Cuarto en 2014-2015: **Manchester United**.
- R3 (2 ptos) — Más títulos: **Manchester City** (1) y **8 veces** (1; aceptar
  "8" aislado). Campeón en: temporada 2 (2011-2012), 4 (2013-2014),
  8 (2017-2018), 9 (2018-2019), 11 (2020-2021), 12 (2021-2022), 13 (2022-2023),
  14 (2023-2024).
- R4 (2 ptos) — Sí (1) y **temporada 6 (2015-2016)** (1). Si identifica la
  temporada 6 sin decir "sí" explícito, otorgar los 2 ptos (afirmación implícita).
- R5 (3 ptos) — Peor resultado: **puesto 13** (1); equipo **Manchester United**
  ÚNICAMENTE (1; 0,5 si lo nombra junto a otro equipo; 0 si solo nombra otro);
  **temporada 15 (2024-2025)** ÚNICAMENTE (1; 0,5 si nombra otra además; 0 si
  solo nombra otra).
- R6 (1 pto) — Responde **6** O enumera correctamente las seis temporadas → 1.
  Si enumera al menos 3 de las 6 correctas sin añadir ninguna incorrecta → 0,5.
  En otro caso → 0. Las seis temporadas son: temporada 1 (2010-2011),
  5 (2014-2015), 7 (2016-2017), 8 (2017-2018), 9 (2018-2019), 12 (2021-2022).
- R7 (2 ptos) — **7 puestos** (1) y **temporada 10 (2019-2020)** (1; 0,5 si
  nombra otra temporada además). La subpregunta "¿cuál fue la máxima diferencia?"
  NO puntúa.
- R8 (3 ptos) — Magnitudes: relaciona las **temporadas** (aceptar "tiempo") con
  la **posición final** en la tabla (1). Eje horizontal: enteros **1 a 15**
  (aceptar igualmente las referencias reales: temporadas 2010-2011 a 2024-2025,
  o años 2010 a 2025) (1). Eje vertical: enteros **1 a 13** (1).

## Mapeo estado ↔ puntaje (por ítem)
- "es correcta" = obtuvo el puntaje máximo del ítem.
- "está incompleta" = obtuvo puntaje parcial (incluido 0,5).
- "es incorrecta" = obtuvo 0.

## Clasificación de errores
Asigná todas las etiquetas que correspondan (separadas por "; "), la más
específica primero. Etiquetas posibles:
Confunde equipo/color · Confunde el índice del eje horizontal con el año real ·
Inversión de la escala ordinal · Lee mal el eje vertical · Confunde temporada
con posición · Confunde variable o magnitud · Interpreta mal la consigna ·
Omitió una sub-pregunta · Error de conteo · Calcula mal una diferencia ·
Respuesta ambigua · No responde.

## Casos dudosos
Si una respuesta te resulta dudosa, asignale igual el puntaje que mejor estimes
(para que la planilla quede completa) y listala además en la hoja "Casos para
revisar".

## Entrada
Planilla adjunta con 10 columnas (Curso, Alumno, Respuesta 1 … Respuesta 8) y
46 filas para procesar.

## Salidas
1) PRIMERO procesá únicamente las 5 primeras filas y mostrámelas en una tabla en
   el chat para que dé el visto bueno. No crees el Excel todavía.
2) Tras mi aprobación, procesá las 46 filas y generá UN archivo Excel con dos hojas:
   - Hoja "Correcciones", con estos encabezados exactos:
     Curso | Alumno | R1 Alumno | Corrección R1 | R2 Alumno | Corrección R2 |
     R3 Alumno | Corrección R3 | R4 Alumno | Corrección R4 | R5 Alumno |
     Corrección R5 | R6 Alumno | Corrección R6 | R7 Alumno | Corrección R7 |
     R8 Alumno | Corrección R8 | Devolución general | Puntaje final | Nota final
   - Hoja "Casos para revisar", con: Curso | Alumno | Ítem | Respuesta del
     alumno | Corrección tentativa | Motivo de la duda.
3) Generá un informe para el docente como archivo .md (especificado abajo).
4) Hace un informe por estudiante con la correccion, es decir, un archivo pdf por estudiante (especificado abajo) a partir de la hoja "Correcciones".

## Estructura interna de las celdas (hoja "Correcciones")
- Rn Alumno: transcripción textual de la respuesta del estudiante.
- Corrección Rn: un único bloque de texto SIN saltos de línea con esta estructura:
  "La respuesta [es correcta / está incompleta / es incorrecta]. [Si está
  incompleta: indicar qué faltó.] [Si es incorrecta: indicar la respuesta
  correcta.] [Información adicional del criterio, resumida, solo si ayuda a
  explicar.] [Clasificación del error, si aplica.] Puntaje: [puntos]."
  (Usá coma decimal, p. ej. "Puntaje: 0,5".)
- Devolución general: un único párrafo breve (2 a 4 oraciones) que resuma el
  desempeño, señale patrones de error y sugiera qué contenido reforzar.
- Puntaje final: suma total de puntos (escala 0 a 15).
- Nota final: Puntaje final / 1,5, redondeado a dos decimales (medio hacia
  arriba), con coma decimal.

## Informe final para el docente (.md)
- Errores más frecuentes.
- Estadística:
  · El ítem con más errores y el porcentaje de veces que fue mal contestado
    (sobre 46). "Mal contestado" = no obtuvo el puntaje máximo (incompletas e
    incorrectas cuentan). Si hay empate, indicarlo.
  · De forma análoga, el ítem más veces correctamente contestado, con su
    porcentaje. Si hay empate, indicarlo.
  · Porcentaje de alumnos que no respondió ninguna de las 8 preguntas.
  · Promedio de todas las notas finales (coma decimal, dos decimales).
- Recomendación docente sobre qué contenidos reforzar.
- Sin distinción por curso.
- Alguna observación pertinente a partir de los resultados.
