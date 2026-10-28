# Reglas para resúmenes de libros destinados a ElevenReader

## Propósito

Crear un **resumen narrativo capítulo por capítulo de un libro completo**, en un único archivo Markdown (`.md`) listo para escuchar con ElevenReader. El resumen sirve para conocer el argumento del libro, explorar ideas y decidir si vale la pena leer el original completo.

**Este procedimiento es distinto de la conversión de capítulos íntegros definida en `REGLAS.md`.** Usarlo cuando el usuario pida un resumen del libro, no cuando pida solamente «Capítulo N».

## 1. Fuente y cobertura

1. Trabajar con el libro original aportado por el usuario. No reconstruir el contenido desde recuerdos, reseñas, contratapas o resúmenes ajenos.
2. Verificar el índice real e identificar **todos los capítulos**, prólogo, introducción, conclusión y epílogo cuando tengan contenido argumental relevante.
3. Leer suficiente contenido de cada capítulo para comprender su tesis, razonamiento y ejemplos principales. No resumir un capítulo a partir de su encabezado, sus primeras páginas o su conclusión únicamente.
4. Respetar el orden y los títulos de la fuente. No inventar capítulos, autores, citas, resultados, ejemplos ni argumentos.
5. Si hay páginas inaccesibles o ilegibles, indicar la limitación en el mensaje de entrega y no presentar el resumen como exhaustivo.

## 2. Contenido del resumen

- **Resumir directamente todos los capítulos** sin pasar antes por un resumen general de cinco minutos, salvo pedido expreso.
- Para cada capítulo, explicar en prosa breve y clara **qué plantea el autor, cómo lo fundamenta y qué aporta al hilo del libro**. Priorizar el argumento sobre la mera enumeración de conclusiones.
- Mantener las distinciones, matices, dudas e hipótesis del autor. Presentar sus interpretaciones como interpretaciones, no como hechos verificados.
- Incluir ejemplos solo cuando sean necesarios para comprender la idea central.
- Evitar repetición entre capítulos, pero conservar las conexiones importantes para que la escucha resulte coherente.
- No agregar análisis crítico, objeciones, opiniones del asistente, recomendaciones ni comparaciones externas, a menos que el usuario los pida.
- No adornar, exagerar ni vender las ideas del libro como novedosas si el propio contenido no lo justifica.
- Evitar citas textuales extensas: el resultado debe ser una síntesis original y fiel, no una reproducción sustancial del libro.

## 3. Extensión y narración

- El punto de partida es un resumen **corto pero sustantivo por capítulo**, normalmente uno o dos párrafos. La longitud debe adaptarse a la densidad del contenido; no forzar una cuota fija de palabras.
- Procurar que el conjunto pueda escucharse en una sesión relativamente breve (como referencia, entre 10 y 25 minutos para libros corrientes de no ficción), sin sacrificar argumentos esenciales.
- Redactar en **español natural de Argentina**, con frases fluidas para lectura en voz alta. No introducir muletillas conversacionales ni entusiasmo artificial.
- Explicar siglas o términos poco familiares la primera vez que aparezcan. Evitar símbolos, tablas, listas extensas, notas técnicas, bibliografías y enlaces que interrumpan la narración.
- Usar transiciones naturales cuando el autor desarrolla un razonamiento a lo largo de varios capítulos.

## 4. Formato del archivo

- Entregar **un solo archivo `.md` por libro**, no un archivo separado por capítulo.
- Estructura recomendada:

  ```md
  # Título del libro
  Autor

  ## Prólogo
  Resumen, si contiene ideas relevantes.

  ## Capítulo 1 — Título
  Resumen en prosa.

  ## Capítulo 2 — Título
  Resumen en prosa.

  ...

  ## Conclusión
  Resumen de la conclusión del autor, si existe.
  ```

- Mantener solo las secciones que existan en la fuente. No escribir una conclusión inventada ni una evaluación personal.
- Markdown simple, codificación UTF-8, párrafos separados por líneas en blanco.
- Nombre de archivo sugerido: `Autor - Título - Resumen completo.md`.
- No agregar prefacios del asistente, advertencias genéricas, emojis ni metacomentarios dentro del archivo.

## 5. Control de calidad

Antes de entregar:

1. Contrastar la lista de capítulos con el índice original y confirmar que ninguno quedó omitido.
2. Comprobar en cada capítulo que la síntesis refleja **la tesis y sus razones**, y que no mezcla ideas de capítulos distintos.
3. Distinguir entre lo que afirma el autor, la evidencia que cita y las inferencias que el resumen formula para conectar el argumento.
4. Revisar que nombres, citas atribuidas, números y conceptos principales estén correctamente representados.
5. Verificar que el `.md` exista, se pueda abrir y tenga texto apto para ElevenReader.
6. Comunicar cualquier parte no verificada o incompleta sin completar los huecos con imaginación.

## 6. Entrega y uso

- Dar el **enlace de descarga del Markdown** y, como máximo, una breve indicación de su extensión o tiempo estimado de escucha.
- El resumen sirve como **filtro de lectura**, no como reemplazo perfecto del texto. Si un capítulo despierta interés, el usuario puede pedir profundizar o leer el original.
- No descartar categóricamente un libro por la síntesis: un resumen comprime estilo, pruebas y matices.
- **No subir al repositorio libros, capítulos íntegros ni los resúmenes de obras de terceros**. Este repositorio almacena únicamente reglas y procedimientos.
