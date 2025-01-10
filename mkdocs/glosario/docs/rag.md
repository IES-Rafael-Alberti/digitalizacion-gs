# Retrieval Augmented Generation (RAG)

<center>
![](assets/rag.png){ width="800" }
</center>

## Definición

Retrieval Augmented Generation (RAG)[^1] es una técnica de inteligencia artificial que combina dos enfoques principales: la recuperación de información y la generación de lenguaje natural. La idea detrás de RAG es potenciar los modelos generativos, como los Grandes Modelos de Lenguaje (LLM), con acceso a una base de datos o documentos externos que les proporcionen información actualizada y específica, mejorando así la precisión y relevancia de las respuestas generadas.

En un modelo RAG, el proceso comienza con un módulo de **recuperación de información** que busca en una base de datos o en un conjunto de documentos para extraer datos relevantes relacionados con una consulta o "prompt" del usuario. Estos datos recuperados se utilizan como contexto adicional para el modelo de lenguaje, que luego genera una respuesta basada tanto en el conocimiento general del modelo como en la información específica recuperada.

Este enfoque es particularmente útil cuando el modelo debe responder a preguntas sobre información reciente o muy específica, que de otro modo no podría conocer solo con el entrenamiento previo. Al proporcionar acceso a fuentes de información actualizadas, RAG supera una de las principales limitaciones de los LLM convencionales: su falta de conocimientos sobre eventos o información posterior a su entrenamiento.

## Explicación intuitiva

Podemos imaginar RAG como un "estudiante" que, además de haber leído una vasta biblioteca, tiene acceso a una colección de enciclopedias o bases de datos específicas para consultas puntuales. Supongamos que a este estudiante se le pide responder una pregunta sobre un tema muy específico y reciente, como "¿Cuáles fueron las medidas más recientes adoptadas para combatir el cambio climático en la Unión Europea?". En lugar de solo confiar en su conocimiento previo (que podría estar desactualizado), este estudiante primero consulta sus enciclopedias más actualizadas para obtener la información más reciente. Luego, con esos datos frescos en mente, elabora una respuesta completa y precisa.

Este enfoque hace que el modelo sea mucho más versátil y útil, especialmente en contextos donde la precisión y la actualidad de la información son críticas. La generación de respuestas se ve potenciada porque el modelo no solo utiliza patrones generales del lenguaje, sino que también integra información recuperada en tiempo real, lo cual mejora tanto la relevancia como la calidad de las respuestas.

## Ejemplo de aplicación en la empresa

Un ejemplo concreto del uso de RAG podría ser el caso de **una consultora financiera**, que necesita proporcionar a sus clientes análisis en tiempo real sobre tendencias del mercado. La empresa **FinSmart Consulting** decide implementar un sistema de asistencia virtual basado en RAG para responder las consultas de sus clientes.

Supongamos que un cliente pregunta: "¿Cuál es la situación actual del mercado energético en Europa?". El módulo de recuperación de información del sistema buscará en fuentes de datos confiables y actualizadas, como informes de agencias energéticas o noticias financieras recientes, para proporcionar contexto relevante. Luego, el LLM generará una respuesta informada que combina este contexto con el conocimiento general sobre el mercado energético.

Este sistema permite a FinSmart Consulting ofrecer respuestas detalladas y actuales sin que los consultores humanos necesiten revisar constantemente las últimas noticias o informes. Los beneficios incluyen:

1. **Mayor precisión en las respuestas**: El sistema utiliza datos actualizados, reduciendo el riesgo de información desactualizada o inexacta.
2. **Ahorro de tiempo para los consultores**: Los consultores pueden centrarse en casos más complejos y en el análisis en profundidad, mientras el sistema maneja las consultas más generales.
3. **Mejora de la satisfacción del cliente**: Las respuestas rápidas y actualizadas generan confianza y mejoran la experiencia del cliente.

## Aplicación en el desarrollo de software

En el desarrollo de software, RAG está permitiendo a los desarrolladores contar con **asistentes técnicos inteligentes** que, además de generar fragmentos de código, tienen acceso a documentación externa y fuentes específicas para proporcionar soluciones más exactas y adaptadas a las necesidades del usuario. Algunas de las aplicaciones más relevantes incluyen:

- **Generación asistida de código con acceso a documentación**: Un desarrollador puede consultar al asistente sobre cómo implementar una funcionalidad específica. En lugar de depender únicamente del conocimiento general del modelo, el asistente utiliza RAG para buscar en la documentación de una API o en foros de desarrolladores para ofrecer una solución precisa y bien fundamentada.
- **Resolución de errores y problemas**: Un sistema basado en RAG puede buscar en bases de datos de errores conocidos, como Stack Overflow, para proporcionar al desarrollador sugerencias relevantes y probadas que solucionen problemas comunes de programación.

Gracias a RAG, los desarrolladores no solo obtienen respuestas contextuales, sino también información específica que puede estar más allá del conocimiento directo del modelo, haciendo la asistencia técnica mucho más precisa y útil.

## Herramientas de ejemplo

- **[HuggingChat](https://huggingface.co/chat)**: Permite crear asistentes personalizados con acceso a fuentes de información específicas para consultas. Ofrece funcionalidades similares a los GPTs de OpenAI, pero puede implementarse de manera gratuita, lo que lo convierte en una opción accesible para desarrolladores y empresas.
- **[Perplexity](https://www.perplexity.ai/)**: Responde a consultas realizando primero una búsqueda en Internet y aplicando RAG sobre las fuentes encontradas antes de mostrar una respuesta al usuario. Esto permite generar respuestas actuales y basadas en información confiable.
- **[NotebookLM](https://notebooklm.google)**: Herramienta gratuita de Google que permite a los usuarios subir archivos o acceder a distintas fuentes y responder preguntas citando directamente esos contenidos. Utiliza RAG para integrar la información relevante en las respuestas, asegurando precisión y trazabilidad.

[^1]: [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401)