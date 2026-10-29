# Eleven Book

## Regla prioritaria — Guardar solo después de la aprobación del usuario

Un resumen se guarda en este repositorio **únicamente después de que el usuario lo haya escuchado y dé su aprobación explícita tanto al resumen como a sus puntos clave**. Esa aprobación autoriza a guardar la versión aprobada, sin pedir una segunda confirmación.

- Preparar y entregar primero el archivo `.md` completo, con los puntos clave al final, para que el usuario pueda escucharlo y revisarlo.
- No interpretar la entrega, el silencio, «ya lo escuché», una solicitud de cambios ni un «ok» referido a otra acción como aprobación para guardarlo. Un «ok» cuenta cuando su contexto deja claro que aprueba el resumen y los puntos clave y autoriza su guardado.
- Si el usuario pide correcciones, entregar la versión corregida y esperar su aprobación antes de guardarla. Una aprobación previa no autoriza a guardar una versión posteriormente modificada.
- Después de esa aprobación, guardar el mismo archivo completo en `libros/<autor-en-slug>/<titulo-en-slug>/resumen.md`. Usar nombres de carpeta en minúsculas, sin tildes y con guiones; una carpeta propia por libro. Conservar el título y el autor completos dentro del Markdown. Si ya existe una carpeta para esa misma obra, reutilizarla y actualizar el archivo correspondiente sin crear duplicados.
- Mantener en el README un índice de los libros guardados, con título, autor y enlace relativo a cada resumen aprobado.
- Guardar solo el resumen y sus puntos clave aprobados. No subir los archivos originales del libro ni capítulos íntegros como parte de este flujo.
- Esta regla no aprueba automáticamente ningún resumen existente ni autoriza su guardado retroactivo.

Instrucciones para preparar libros aportados como fuentes en ChatGPT y escucharlos en **ElevenReader**, usando archivos Markdown descargables.

El repositorio contiene **dos procedimientos independientes**:

- **[Capítulos íntegros](REGLAS.md)**: convertir, a pedido, el texto completo de un capítulo en un archivo `.md`, sin resumir, reescribir ni comentar.
- **[Resúmenes de libros completos](RESUMENES.md)**: condensar todos los capítulos de un libro de no ficción en **un solo `.md`**, con un resumen narrativo corto y fiel y una sección final obligatoria de **puntos clave en bullets**, para escuchar y decidir si vale la pena leer el original.

## Fuente de verdad

Los asistentes deben empezar por [AGENTS.md](AGENTS.md), que indica qué procedimiento corresponde a cada pedido.

## Uso

1. Incorporar el libro como fuente al proyecto de ChatGPT (PDF, EPUB u otro formato legible).
2. Elegir la tarea:
   - «Capítulo 1» para recibir el texto íntegro de ese capítulo.
   - «Haceme un resumen de todos los capítulos para ElevenReader» para recibir **un solo archivo con el resumen completo y los puntos clave al final, en bullets**.
3. Descargar el archivo `.md` e importarlo en ElevenReader.
4. Escuchar y revisar el resumen y los puntos clave. Solo después de aprobar explícitamente ambos se guarda la versión aprobada en la carpeta del libro y se agrega al índice.

Si hay varios libros entre las fuentes, utilizar el indicado por el usuario o el contexto inequívoco; preguntar solamente si es imposible identificarlo.

## Alcance y privacidad

Este repositorio guarda **instrucciones y resúmenes expresamente aprobados por el usuario después de escucharlos y revisar sus puntos clave**. Los archivos se entregan primero en la conversación; su entrega no autoriza su guardado en GitHub. No se suben libros originales ni capítulos íntegros como parte del archivo de resúmenes.

Ambos procedimientos son aplicables a cualquier libro. El modo de capítulos íntegros preserva la redacción original; el modo de resúmenes sintetiza ideas y argumentos sin agregar análisis crítico.

## Libros aprobados

- [La victoria final de Dios: una defensa filosófica comparativa del universalismo](libros/john-kronen-y-eric-reitan/la-victoria-final-de-dios/resumen.md) — John Kronen y Eric Reitan.
- [Todo estará bien: exploraciones sobre el universalismo y la teología cristiana, de Orígenes a Moltmann](libros/gregory-macdonald/todo-estara-bien/resumen.md) — Gregory MacDonald, editor.
- [Sus puertas nunca se cerrarán: el infierno, la esperanza y la Nueva Jerusalén](libros/bradley-jersak/sus-puertas-nunca-se-cerraran/resumen.md) — Bradley Jersak.
- [Que todos se salven: cielo, infierno y salvación universal](libros/david-bentley-hart/que-todos-se-salven/resumen.md) — David Bentley Hart.
