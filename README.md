# Trabajo de Final de Master, Master en Periodismo y Visualización de Datos, UAH
## Por Karel W. F. De Pourcq

Este trabajo es parte del Master en Periodismo y Visualización de datos de la Universidad de Alcalá. Es el proyecto de final de master del alumno Karel De Pourcq y pretende hacer uso de algunas de las herramientas utilizadas durante el curso académico.



### El trabajo se ha basado en varios ejes:
Se ha pretendido buscar una temática relacionada con la polarización en redes sociales, con objeto de aprender sobre ella.

**1. Recogida de datos de Reddit**
*-Selección de subreddit*
*-Recogida de datos (id) a través de pushshift, por fecha*
*-Bajada y filtrado de datos a través de praw (mediante el id anterior)*

**2. Análisis de datos**
*-Análisis cualitativo*
*-Estadísticos generales*
*-Análisis de sentimiento y barplot*
*-Nube de palabras*
*-Representación en 3D + GIF animado*

**3. Subida a la web**
*-Búsqueda de plantilla de uso libre*
*-Adaptación/inclusión del contenido*

**4. No ejecutado: mapeado de conexiones y dibujo de grafo.**
Idea que no ha llegado a ser plasmada: análisis de grafo de conexiones. La lógica detrás se basa en las siguientes premisas:
*-Cada post tiene un autor.*
*-Ese autor puede ser a su vez autor de comentarios en otros posts.*
*-Eso genera un nexo entre autores que se responden mutuamente en determinados posts.*
*-Esas interacciones se pueden mapear, asignando más "intensidad" o "peso" en función de su número.*
*-Esas conexiones se pueden enriquecer a nivel informativo (p.ej. a través de análisis de sentimiento + coloreado, etc.).*

Algunas barreras/problemas que superar:
*-! Obtención de todos los comentarios y sus autores de los posts de interés.*
*-! Cuestión de fondo: ¿qué constituye una interacción mapeable? ¿La respuesta directa a la persona, o la simple participación en el diálogo?*
*-!! Jerarquización de las conexiones acorde al concepto decidido.*
*-!! Ideado de la estructura de grafo adecuada y creación del código necesario para su obtención.*
*-Representación en Gephi.*
*-A considerar: enriquecimiento de la información visual: p.ej. colorear de diferente color interacciones con sentimiento positivo.*
*-Evaluación del grafo, visualmente.*
