# Sistemas complejos

<center>
![](assets/sistemascomplejos.png){ width="800" }
</center>

## Definición[^1]

Un **sistema complejo** en el contexto de la Inteligencia Artificial se refiere a la integración de múltiples llamadas a modelos de lenguaje grandes (LLMs) como parte del algoritmo de una funcionalidad específica. Esto implica la creación de una **secuencia de pasos**, donde cada paso puede involucrar un LLM diferente o el mismo LLM ejecutando diversas tareas. La salida de cada paso puede servir como **entrada para el siguiente**, permitiendo la colaboración entre múltiples instancias de modelos para resolver tareas de manera más sofisticada y precisa.

Este enfoque permite abordar problemas complejos dividiéndolos en subtareas que son gestionadas de manera individual por distintos LLMs, optimizando así la solución global y mejorando la eficiencia del proceso.

## Explicación intuitiva

En lugar de realizar una única llamada a un LLM para resolver una tarea, un **sistema complejo** descompone la tarea en varias subtareas que se resuelven mediante una serie de LLMs interconectados. Imagina una **cadena de montaje** donde cada trabajador (es decir, cada LLM) se especializa en una tarea específica. El producto final se ensambla pasando de un trabajador al siguiente, y cada uno aporta su especialidad al proceso. De manera similar, en un sistema complejo, cada LLM procesa la información y la pasa al siguiente en la cadena, construyendo así una solución más completa y sofisticada.

Por ejemplo, si quieres escribir un artículo sobre un tema complejo, un sistema complejo podría empezar generando un índice, luego buscar información sobre cada apartado, redactar el contenido, y finalmente, formatearlo de manera adecuada. Así, el resultado es más preciso y profundo que si se intentara generar todo de una sola vez.

## Ejemplos de aplicación concretos

Un ejemplo concreto del uso de un sistema complejo es la **generación de artículos estilo Wikipedia**[^2]. Supongamos que un usuario quiere crear un artículo detallado sobre un tema en particular. Un sistema complejo podría implementar los siguientes pasos:

1. **Crear un borrador del índice**: Un LLM genera un esquema inicial del artículo para organizar el contenido de manera lógica.

2. **Refinar el borrador**: Otro LLM más potente mejora el esquema inicial, utilizando información adicional de otros modelos y aportando más contexto.

3. **Identificar temas relacionados**: Un tercer LLM identifica temas relacionados que podrían ser relevantes para enriquecer el artículo.

4. **Buscar información en Wikipedia**: El sistema utiliza una herramienta de búsqueda para acceder a Wikipedia y recopilar información sobre estos temas.

5. **Discutir y elaborar el contenido**: LLMs especializados en cada tema desarrollan el contenido de cada sección, basándose en la información recopilada previamente.

6. **Escribir el artículo**: Un LLM compone el artículo completo utilizando toda la información estructurada y desarrollada en las etapas anteriores.

7. **Dar formato Wiki**: Finalmente, un LLM especializado aplica el formato necesario para que el artículo cumpla con los estándares de Wikipedia.

Otro ejemplo puede ser una **traducción contextualizada**[^3], donde un sistema complejo gestiona múltiples etapas para lograr una traducción precisa y adaptada al contexto:

1. **Generar un glosario**: Un LLM identifica los términos que necesitan una explicación específica o contextualizada.

2. **Crear un glosario contextualizado**: Se utiliza otro LLM para buscar definiciones de estos términos y adaptarlas al contexto deseado.

3. **Realizar una traducción básica**: Un LLM realiza una primera traducción del texto.

4. **Revisar y criticar la traducción**: Un LLM adicional evalúa la traducción inicial basándose en el glosario y destaca áreas de mejora.

5. **Elaborar la traducción final**: Un último LLM, teniendo en cuenta la traducción básica y las críticas recibidas, produce la versión final adaptada.

## Aplicaciones que implementan sistemas complejos para programación

Existen diversas aplicaciones que utilizan sistemas complejos, algunas de las más destacadas incluyen:

- [V0 de Vercel](https://v0.dev): Una aplicación web que permite a los usuarios crear aplicaciones web utilizando un sistema complejo que genera código de programación paso a paso, optimizando cada segmento.

- [Cursor](https://www.cursor.com): Un entorno de desarrollo integrado (IDE) que ayuda a los programadores mediante la integración de sistemas complejos que asisten en la generación y mejora de código, similar a GitHub Copilot pero con un enfoque más modular.

- [Winsurf](https://codeium.com/windsurf): Un IDE que utiliza sistemas complejos con un comportamiento más "agéntico" que Cursor, permitiendo una interacción más dinámica y personalizada para la creación de software.

Estos sistemas complejos permiten generar código de programación, interactuar con interfaces de usuario, planificar y ejecutar acciones, dividir tareas en subtareas, y crear aplicaciones web completas de manera más eficiente y autónoma.

## Beneficios de los sistemas complejos

Los sistemas complejos ofrecen una serie de ventajas que los hacen particularmente útiles en escenarios empresariales y de desarrollo avanzado:

- **Mayor precisión y sofisticación**: Al dividir una tarea en subtareas y utilizar LLMs especializados para cada una, se obtienen resultados más precisos y complejos que con una única llamada a un LLM.

- **Adaptación a diferentes tareas**: Los sistemas complejos pueden diseñarse para abordar una amplia variedad de tareas, desde la generación de texto hasta la programación y la automatización de procesos.

- **Automatización de procesos complejos**: Estos sistemas permiten automatizar tareas que tradicionalmente requerían una intervención humana significativa, mejorando la eficiencia y reduciendo los costos operativos.

## Consideraciones

Si bien los sistemas complejos presentan un gran potencial, también conllevan algunos desafíos y limitaciones que es importante considerar:

- **Complejidad de diseño e implementación**: Diseñar e implementar un sistema complejo puede ser un desafío técnico, ya que requiere coordinar de manera eficiente múltiples LLMs y flujos de trabajo.

- **Costo computacional**: Ejecutar múltiples LLMs implica un consumo significativo de recursos computacionales, lo cual puede incrementar los costos de implementación y operación.

- **Limitaciones de los LLMs**: Los LLMs individuales tienen limitaciones inherentes que pueden afectar el rendimiento del sistema complejo, como la generación de errores o sesgos en las respuestas.

Es fundamental evaluar si un sistema complejo es la solución más adecuada para una tarea específica, considerando siempre las alternativas más simples y los posibles desafíos que pueden surgir durante la implementación.

[^1]: [The Shift from Models to Compound AI Systems](https://bair.berkeley.edu/blog/2024/02/18/compound-ai-systems)

[^2]: [Assisting in Writing Wikipedia-like Articles From Scratch with Large Language Models](https://arxiv.org/abs/2402.14207)

[^3]: [Aphra](https://github.com/DavidLMS/aphra)