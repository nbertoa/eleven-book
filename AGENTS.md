# Instrucciones para asistentes — Eleven Book

## Regla prioritaria — Guardar solo después de la aprobación del usuario

Un resumen se guarda en este repositorio **únicamente después de que el usuario lo haya escuchado y dé su aprobación explícita tanto al resumen como a sus puntos clave**. Esa aprobación autoriza a guardar la versión aprobada, sin pedir una segunda confirmación.

- Preparar y entregar primero el archivo `.md` completo, con los puntos clave al final, para que el usuario pueda escucharlo y revisarlo.
- No interpretar la entrega, el silencio, «ya lo escuché», una solicitud de cambios ni un «ok» referido a otra acción como aprobación para guardarlo. Un «ok» cuenta cuando su contexto deja claro que aprueba el resumen y los puntos clave y autoriza su guardado.
- Si el usuario pide correcciones, entregar la versión corregida y esperar su aprobación antes de guardarla. Una aprobación previa no autoriza a guardar una versión posteriormente modificada.
- Después de esa aprobación, guardar el mismo archivo completo en `libros/<autor-en-slug>/<titulo-en-slug>/resumen.md`. Usar nombres de carpeta en minúsculas, sin tildes y con guiones; una carpeta propia por libro. Conservar el título y el autor completos dentro del Markdown. Si ya existe una carpeta para esa misma obra, reutilizarla y actualizar el archivo correspondiente sin crear duplicados.
- Mantener en el README un índice de los libros guardados, con título, autor y enlace relativo a cada resumen aprobado.
- Guardar solo el resumen y sus puntos clave aprobados. No subir los archivos originales del libro ni capítulos íntegros como parte de este flujo.
- Esta regla no aprueba automáticamente ningún resumen existente ni autoriza su guardado retroactivo.

Este repositorio es la fuente canónica de instrucciones para preparar textos de libros como archivos Markdown, destinados a **ElevenReader**.

Hay **dos modalidades diferentes**. Elegir la que corresponde al pedido sin confundirlas:

1. **Capítulo íntegro**: ante «Capítulo N», «Prepará el prólogo» o una petición de conversión fiel, aplicar [REGLAS.md](REGLAS.md). Entregar el capítulo completo, sin resúmenes ni reescritura.
2. **Resumen de libro completo**: ante «Resumí el libro», «Resumen de todos los capítulos» o una petición de audiolibro resumido, aplicar [RESUMENES.md](RESUMENES.md). Entregar **un único archivo .md** con síntesis narrativa de todos los capítulos y una sección final obligatoria `## Puntos clave` en bullets, sin crítica añadida.

## Prioridades compartidas

1. **Fidelidad a la fuente aportada por el usuario**: verificar contenido, capítulos y límites; no inferir pasajes desde títulos, memoria o fuentes secundarias.
2. **No inventar ni ocultar lagunas**: si parte de la fuente es inaccesible, indicarlo claramente.
3. **Texto apto para escuchar**: limpio, natural, sin formato que interrumpa la narración.
4. **Entregar un archivo .md real y descargable** acorde a la modalidad elegida.
5. **Guardar resúmenes solo con aprobación explícita** del usuario sobre el resumen y sus puntos clave, conforme a la regla prioritaria. No subir libros originales ni capítulos íntegros como parte de ese guardado.

Cuando el usuario identifique inequívocamente el libro entre las fuentes del proyecto, no volver a pedirlo. No alterar las reglas de un modo para satisfacer pedidos del otro.

Consultar [README.md](README.md) para el propósito y los ejemplos de uso.

## Libros destacados para leer completos

- La aprobación del resumen y sus puntos clave autoriza su guardado, pero no implica por sí sola una recomendación de lectura completa.
- Cuando el usuario destaque expresamente un libro como valioso para leer completo, marcar su entrada del índice del README con `★` y el texto `Lectura completa recomendada`.
- Mantener la leyenda de esa marca en el README. Un libro sin estrella no tiene una valoración negativa: simplemente no recibió esa distinción.
- Asignar o quitar la estrella solo por indicación del usuario. No extenderla automáticamente a otros libros ni modificar el texto aprobado del resumen para incorporar esta valoración.
