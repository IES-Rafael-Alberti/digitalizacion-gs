# Agentes

<center>
![](assets/agentes.png){ width="800" }
</center>

## Definición

Un agente es un modelo de lenguaje grande (LLM) combinado con un "system prompt" específico que le permite ejecutar acciones concretas en el mundo real. Estos agentes están diseñados para ser más que simples modelos de generación de texto; están habilitados para actuar de forma autónoma e interactuar con sistemas externos. Opcionalmente, un agente puede integrar un sistema de Recuperación Aumentada (RAG) para acceder a información adicional y proporcionar respuestas más precisas.

La característica fundamental de un agente es su **acceso a herramientas** (tools), que le permite interactuar con sistemas externos como bases de datos, APIs, o incluso ejecutar acciones físicas mediante hardware conectado. Esto convierte a los agentes en asistentes sumamente versátiles y útiles en una variedad de contextos empresariales e industriales.

## Explicación intuitiva

Podemos imaginar un LLM como un estudiante que posee un vasto conocimiento gracias a su formación. Sin embargo, este estudiante solo puede responder preguntas con base en lo que ha aprendido. Un **agente** es como ese mismo estudiante, pero equipado con una serie de herramientas que le permiten ir más allá. Por ejemplo, si se le pide al agente que busque información sobre un tema específico, no solo dará una respuesta general, sino que también podrá utilizar una **herramienta de búsqueda web** para recopilar datos actualizados y proporcionar una respuesta mucho más precisa y contextualizada.

Otro ejemplo sería pedirle al agente que realice un cálculo complejo. En este caso, el agente puede usar una **herramienta de calculadora** para realizar el cálculo exacto y proporcionar una respuesta precisa. Esto es especialmente útil en contextos donde se requieren operaciones matemáticas avanzadas o cálculos financieros.

Esto hace que los agentes sean extremadamente útiles en tareas donde la simple generación de texto no es suficiente, ya que pueden ejecutar acciones y buscar información en tiempo real para cumplir con las expectativas del usuario.

## Ejemplo de aplicación en la empresa

Consideremos el caso de una empresa de **atención al cliente** que implementa un agente para gestionar las consultas. Supongamos que un cliente pregunta: "¿Cuál es el estado de mi pedido?". En este caso, el agente no se limita a dar una respuesta genérica sobre los tiempos de entrega. En cambio, utiliza una **herramienta conectada a la base de datos** de la empresa para consultar el estado exacto del pedido del cliente y proporcionar una respuesta precisa, como: "Tu pedido se encuentra en tránsito y llegará el 15 de noviembre".

Este nivel de precisión solo es posible gracias a la capacidad del agente para acceder a herramientas específicas y ejecutar acciones en sistemas externos. De esta manera, mejora la eficiencia y la satisfacción del cliente al proporcionar respuestas útiles y específicas.

## Tipos de herramientas

Un agente puede acceder a una variedad de herramientas, dependiendo de las tareas que necesite realizar. Algunos ejemplos comunes de herramientas disponibles para los agentes son:

- Búsqueda en internet: Permite al agente buscar información actualizada en la web. Esto es particularmente útil cuando se necesita información reciente o en constante cambio.

- Generación de imágenes: Permite al agente crear imágenes a partir de un texto descriptivo. Esto puede ser útil en marketing o cuando se necesitan visualizaciones rápidas.

- Acceso a bases de datos: Permite al agente consultar y actualizar información en bases de datos. Esto es esencial para tareas de atención al cliente o administración interna.

- Ejecución de acciones en sistemas externos: Permite al agente realizar operaciones específicas como ejecutar un pago, enviar un correo electrónico, o activar un dispositivo IoT.

Estas herramientas permiten a los agentes ir más allá de la simple generación de respuestas textuales y realizar acciones que pueden tener un impacto tangible en el entorno real.

## Funcionamiento Interno

El funcionamiento de un agente se basa en un esquema de comunicación estructurado que facilita la planificación y ejecución de acciones. El proceso típico que sigue un agente es el siguiente:

1. Question: El usuario realiza una pregunta o solicita una acción.

2. Thought: El agente genera un "pensamiento" interno para planificar la acción que debe realizar.

3. Action: El agente selecciona la herramienta más adecuada para responder a la pregunta o llevar a cabo la acción.

4. Action Input: El agente define los parámetros de entrada necesarios para utilizar la herramienta.

5. Observation: La herramienta se ejecuta y devuelve un resultado o respuesta al agente.

6. Final Answer: El agente utiliza la observación para elaborar una respuesta final para el usuario.

Este flujo de trabajo es invisible para el usuario, quien únicamente observa la consulta inicial y la respuesta final proporcionada por el agente. Gracias a este esquema, los agentes pueden planificar y ejecutar múltiples pasos para responder de manera precisa y efectiva a una consulta compleja.

## Ejemplos

- [ChatGPT](https://chat.com): Permite activar la búsqueda en internet o generar imágenes en la versión gratuita.
- [Perplexity](https://perplexity.ai): Realiza búsquedas en internet utilizando RAG para elegir la información relevante para contestar.
- [HuggingChat](https://huggingface.co/chat/): Ofrece herramientas nativas y permite integrar herramientas personalizadas.

Los agentes son una evolución natural de los modelos de lenguaje y, gracias a su capacidad para interactuar con herramientas externas, abren la puerta a una enorme cantidad de aplicaciones prácticas que pueden facilitar tanto tareas empresariales como personales.