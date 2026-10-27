# Reglas para capítulos en ElevenReader

## Resultado esperado

Ante el pedido de un capítulo, entregar **un archivo real `.md` descargable**, listo para importar a ElevenReader. El capítulo es el entregable; no sustituirlo por un resumen, una explicación, una muestra o texto pegado en el chat.

No procesar otros capítulos sin que se pidan.

## 1. Fuente y límites del capítulo

- Trabajar sobre el libro incluido como fuente en el proyecto o adjuntado por el usuario.
- Identificar correctamente dónde comienza y termina el capítulo, recurriendo al índice, encabezados y estructura real del documento.
- Mantener el **texto íntegro** del capítulo: párrafos, diálogos, citas, epígrafes, subtítulos y demás contenido sustantivo, en su orden original.
- No inventar ni completar palabras, fragmentos o páginas faltantes. Si el archivo de origen está truncado, ilegible o falta parte del capítulo, informar exactamente qué no se pudo recuperar.
- Si hay ambigüedad entre ediciones, traducciones o libros, respetar la fuente efectivamente proporcionada. No sustituirla por otra versión disponible en internet.

## 2. Fidelidad editorial

- **No resumir, parafrasear, reinterpretar, traducir ni agregar comentarios del asistente.**
- Conservar el idioma, el vocabulario, los nombres propios, el tono, las citas y la secuencia argumental del original.
- Se permite corregir errores de extracción evidentes comprobados contra la fuente (por ejemplo, palabras cortadas por saltos de línea, ligaduras mal interpretadas o caracteres extraños).
- No introducir correcciones estilísticas ni reformular frases para que «suenen mejor». Si una intervención puede modificar el significado, no hacerla.
- Si el usuario pide expresamente una traducción o adaptación, tratarla como una tarea diferente de esta conversión fiel.

## 3. Limpieza para lectura en voz alta

Eliminar los elementos que son artefactos del soporte, no del texto del libro:

- Números de página y encabezados o pies de página repetitivos.
- Saltos de página, cortes de columnas y espacios en blanco innecesarios.
- Guiones de fin de línea que parten una misma palabra por la maquetación.
- Índices, avisos o marcas técnicas insertadas por el PDF/EPUB fuera del capítulo.
- URLs de navegación, marcas de escaneo y caracteres basura cuando sean ajenos al contenido.

Conservar los guiones de diálogo, la puntuación genuina y las divisiones de sección con sentido literario. Las notas con contenido sustantivo no se deben perder; conservarlas en una ubicación inteligible dentro del Markdown, evitando interrupciones arbitrarias. Si contienen referencias meramente editoriales, evaluar su tratamiento sin borrar información relevante.

Reconstruir los párrafos originales y dejar una línea en blanco entre ellos. No agregar instrucciones de pronunciación, indicaciones escénicas, emojis ni texto conversacional.

## 4. Formato Markdown

- Primera línea: `# Título del capítulo`, tal como aparezca en la fuente.
- Subtítulos reales con `##` o `###` cuando corresponda.
- Texto narrativo como párrafos normales, sin tablas innecesarias, HTML, bloques de código ni artificios visuales.
- Mantener citas y diálogos de manera legible para el motor de voz, sin alterar el texto.
- Codificación UTF-8.
- Nombre sugerido de archivo: `Autor - Libro - Capítulo 01 - Título.md`, con caracteres no permitidos en archivos reemplazados de forma conservadora.
- No agregar prólogos del asistente, explicaciones metodológicas ni avisos dentro del archivo.

## 5. Control de calidad antes de entregar

1. Comprobar el primer y el último párrafo contra la fuente para asegurar límites correctos.
2. Verificar el orden y la presencia de todas las secciones del capítulo.
3. Revisar especialmente las zonas de cambio de página, columnas y guiones partidos, donde suelen aparecer omisiones o duplicaciones.
4. Inspeccionar cifras, nombres propios, acentos, comillas y diálogos difíciles de extraer.
5. Confirmar que el archivo existe, tiene extensión `.md` y se puede descargar.
6. Si no se puede garantizar la integridad del capítulo, indicar la limitación en el mensaje de entrega en vez de afirmar que es completo.

## 6. Entrega y alcance

- Responder de forma breve con el enlace al `.md`; sin repetir el capítulo en el mensaje.
- Crear **un archivo por capítulo solicitado**, salvo que el usuario indique otra cosa.
- No subir material de libros de terceros a repositorios públicos, sitios web ni servicios externos distintos de los necesarios para la tarea sin pedido expreso.
- Este repositorio guarda únicamente el procedimiento. No almacenar aquí los capítulos convertidos ni la fuente.
