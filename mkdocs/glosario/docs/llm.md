# Grandes Modelos de Lenguaje (LLM)

<center>
![](assets/llm.png){ width="800" }
</center>

## Definición

Los Grandes Modelos de Lenguaje (Large Language Models, LLM) son modelos de inteligencia artificial generativa entrenados mediante técnicas avanzadas de aprendizaje profundo (Deep Learning) para procesar y generar lenguaje natural. Utilizan redes neuronales con un gran número de parámetros, que les permiten aprender relaciones complejas y patrones a partir de enormes volúmenes de datos textuales. A partir de la aplicación de la arquitectura Transformer[^1], los resultados empezaron a ser verdaderamente útiles.

El entrenamiento de un LLM se divide en varias etapas clave:

1. **Preentrenamiento**: En esta fase, el modelo se entrena con cantidades masivas de datos textuales (libros, artículos, sitios web, etc.) para aprender patrones del lenguaje, como gramática, contexto, tono y semántica. Utiliza técnicas de aprendizaje no supervisado o autosupervisado para predecir la siguiente palabra en una oración, basándose en el contexto anterior.

2. **Fine-tuning con RLHF (Reinforcement Learning from Human Feedback)**: Una vez preentrenado, el modelo pasa por una fase de ajuste fino, en la cual se refuerzan sus capacidades para responder de manera específica a indicaciones humanas. En este proceso, se aplica aprendizaje por refuerzo a partir de la retroalimentación humana, para mejorar la calidad de las respuestas que genera. Este proceso permite que el modelo se adapte a tareas más específicas o aplicaciones concretas, haciendo que sea más efectivo al responder a instrucciones complejas. Es decir, pasamos de un modelo que completa texto a un modelo que puede responder a interacciones tipo chatbot.

El proceso de **inferencia** de un LLM consiste en generar una respuesta a partir de un input de texto (un prompt). Durante este proceso, se utiliza la información aprendida durante el entrenamiento para producir una salida que sea coherente y relevante para el contexto dado.

Cada LLM se distingue por ciertas características que determinan su rendimiento y capacidades, como el **número de parámetros** del modelo y la cantidad de tokens de contexto que puede manejar. Un mayor número de parámetros permite al modelo captar patrones más complejos, mientras que un mayor límite de **tokens de contexto** facilita mantener conversaciones más largas y coherentes.

Para personalizar las respuestas, se pueden ajustar ciertos parámetros clave del modelo, tales como la **temperatura**. Este parámetro controla el grado de aleatoriedad en las respuestas del modelo. Un valor bajo de temperatura resulta en respuestas más predecibles y repetitivas, mientras que un valor alto introduce mayor creatividad y variación, lo que puede ser útil dependiendo del tipo de aplicación.

## Explicación intuitiva

Los Grandes Modelos de Lenguaje se pueden imaginar como un estudiante extremadamente aplicado que ha leído una vasta biblioteca, cubriendo todos los temas posibles. Este "estudiante" es capaz de recordar detalles específicos y también de generar contenido nuevo basado en lo que ha aprendido.

El proceso de preentrenamiento es como la etapa inicial en la que el estudiante lee todos estos libros. Aprende las reglas del idioma, las relaciones entre palabras, y cómo se estructuran las oraciones y los conceptos. Posteriormente, el fine-tuning es como si un profesor le enseñara al estudiante a responder preguntas de forma más específica y útil, corrigiendo errores y guiando las respuestas hacia un comportamiento deseado.

Cuando le haces una pregunta a este estudiante (es decir, cuando realizas una consulta al modelo), usa toda la información almacenada para darte una respuesta coherente. La "temperatura" de la respuesta es como su estado de ánimo: si le pides que sea muy creativo, te dará respuestas más imaginativas; si le pides que sea preciso, te dará respuestas más habituales.

Los LLM son herramientas que pueden "hablar" y "escribir" imitando la capacidad humana, utilizando todo lo que han aprendido a partir de los datos, lo que los convierte en asistentes poderosos para muchas tareas.

## Ejemplo de aplicación en la empresa

Un ejemplo claro de cómo un LLM puede mejorar la productividad es el caso de **una empresa de atención al cliente online**. Supongamos que la empresa **SoporteMax** recibe cientos de consultas al día relacionadas con sus productos y servicios. La implementación de un LLM para la gestión de estas consultas puede optimizar significativamente su proceso.

En lugar de depender exclusivamente de agentes humanos, SoporteMax utiliza un LLM para proporcionar respuestas automatizadas a preguntas frecuentes y resolver problemas básicos de los clientes. El modelo es capaz de entender el contexto de cada consulta, ofrecer una respuesta precisa, e incluso derivar casos más complejos a un agente humano si es necesario.

Con esta implementación, SoporteMax ha conseguido los siguientes beneficios:

1. **Reducción del tiempo de respuesta**: Las consultas simples se resuelven en cuestión de segundos, mejorando la satisfacción del cliente.
2. **Aumento de la capacidad de gestión**: Los agentes humanos pueden enfocarse en problemas más complejos, mientras que el LLM se ocupa de las consultas más comunes y repetitivas.
3. **Disponibilidad 24/7**: El LLM está disponible en todo momento, proporcionando soporte a los clientes incluso fuera del horario de oficina, lo cual incrementa el nivel de servicio.

Además, el equipo de desarrollo del modelo puede hacer reentrenamientos sucesivos con los datos recogidos de las interacciones previas, mejorando constantemente refinando sus respuestas y adaptándose mejor a las necesidades específicas de los clientes de SoporteMax.

## Algunos LLMs SOTA - Noviembre 2024

- **Comerciales**: [GPT-4o](https://openai.com/index/hello-gpt-4o/), [Gemini 1.5](https://blog.google/technology/ai/google-gemini-next-generation-model-february-2024/) y [Claude 3.5 Sonnet](https://www.anthropic.com/news/claude-3-5-sonnet).
- **Open Source**: [La familia de modelos Llama](https://www.llama.com) y [los modelos Qwen](https://qwenlm.github.io). Se pueden probar en [HuggingChat](https://huggingface.co/chat).

[^1]: [Attention Is All You Need](https://arxiv.org/abs/1706.03762)