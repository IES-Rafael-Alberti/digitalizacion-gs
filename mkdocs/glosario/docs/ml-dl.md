# Machine Learning y Deep Learning

<center>
![](assets/ml-dl.png){ width="800" }
</center>

## Definición

**Machine Learning (ML) o aprendizaje automático** y **Deep Learning (DL) o aprendizaje profundo** son subcampos de la Inteligencia Artificial que se centran en la capacidad de las máquinas para aprender de los datos sin necesidad de programación explícita para cada tarea específica. Machine Learning se basa en el uso de algoritmos que aprenden de los datos y hacen predicciones o toman decisiones basadas en patrones observados. Deep Learning es un **subcampo** de Machine Learning que utiliza redes neuronales artificiales, lo que permite a los modelos aprender de manera jerárquica, detectando patrones más complejos y abstractos.

## Diferencias entre Machine Learning y Deep Learning

| **Aspecto**                 | **Machine Learning (ML)**                                                                                          | **Deep Learning (DL)**                                                                                                                                                   |
| --------------------------- | ------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Estructura de modelo**    | Utiliza algoritmos como árboles de decisión, máquinas de vectores de soporte (SVM), regresión lineal, entre otros. | Utiliza redes neuronales profundas con múltiples capas (deep neural networks) que procesan la información de manera jerárquica, inspiradas en el cerebro humano.         |
| **Requisitos de datos**     | Funciona bien con conjuntos de datos de tamaño moderado.                                                           | Requiere grandes volúmenes de datos para entrenar modelos eficaces debido a la cantidad de parámetros que necesita ajustar.                                              |
| **Hardware necesario**      | Se puede ejecutar en hardware convencional, como una CPU.                                                          | Requiere GPU (unidades de procesamiento gráfico) o TPU para acelerar el entrenamiento, dado el alto poder de cómputo necesario para procesar grandes volúmenes de datos. |
| **Tiempo de entrenamiento** | El entrenamiento suele ser más rápido y puede realizarse con menos recursos.                                       | Requiere mucho tiempo para entrenar, especialmente con grandes volúmenes de datos y modelos complejos.                                                                   |
| **Nivel de automatización** | Necesita intervención humana para la selección de características relevantes de los datos (feature engineering).   | Aprende automáticamente características y patrones a través de sus múltiples capas, reduciendo la necesidad de intervención humana en la extracción de características.  |

## Explicación

**Machine Learning** es como enseñar a un programa a reconocer patrones y hacer predicciones usando datos. Imagina que quieres enseñarle a un modelo a distinguir entre gatos y perros en una imagen. En Machine Learning tradicional, los algoritmos necesitan ejemplos etiquetados de gatos y perros, y un humano debe realizar una selección de características (feature engineering) que describan mejor a cada uno (como la forma de las orejas o la textura del pelaje). Algoritmos como la **regresión lineal** o los **árboles de decisión** analizan estas características para aprender a clasificar las imágenes correctamente.

Por otro lado, **Deep Learning** lleva este proceso un paso más allá al utilizar **redes neuronales profundas**, lo que significa que el propio modelo puede aprender qué características son importantes. No es necesario decirle qué buscar en las imágenes; la red neuronal aprende automáticamente a reconocer patrones complejos como los bordes, las texturas y las formas. Esto hace que Deep Learning sea altamente eficaz para tareas como el reconocimiento de imágenes y el procesamiento del lenguaje natural.

## Aplicaciones de Machine Learning y Deep Learning

### **Machine Learning en acción**

- **Predicción de ventas**: Las empresas utilizan modelos de Machine Learning para analizar datos históricos y predecir ventas futuras. Un ejemplo concreto es la cadena de supermercados **Walmart**[^1], que usa ML para prever la demanda de productos y optimizar su inventario.
- **Detección de fraude**: Instituciones financieras como **PayPal**[^2] aplican ML para detectar patrones anómalos en las transacciones y alertar sobre posibles fraudes, aprendiendo constantemente de los cambios en los patrones de conducta de los usuarios.

### **Deep Learning en acción**

- **Reconocimiento de imágenes**: Un ejemplo clásico es el uso de convoluciones en redes neuronales para identificar objetos en imágenes. **Google Photos** utiliza DL para clasificar automáticamente fotos y reconocer elementos como rostros[^3] y lugares.
- **Asistentes virtuales**: Los asistentes como **Alexa** o **Google Assistant** usan Deep Learning para entender el habla humana y mejorar sus respuestas, utilizando redes neuronales recurrentes (RNN) y redes neuronales transformers para interpretar y responder a los comandos de voz de manera precisa.

## Caso práctico: Machine Learning vs Deep Learning en la industria del desarrollo de software

Para comprender mejor la diferencia entre **Machine Learning** y **Deep Learning**, veamos ejemplos relativos al sector de **desarrollo de software**:

- **Machine Learning** se puede utilizar para la priorización de bugs y predicción de fallos en el software. Por ejemplo, **GitHub**[^4] ha implementado modelos para ayudar a identificar problemas potenciales en el código y priorizarlos según su gravedad. De esta forma, los desarrolladores pueden centrarse en corregir primero los fallos más críticos.

- **Deep Learning**, por otro lado, se puede aplicar para la generación automática de código. Un ejemplo destacado es **GitHub Copilot**[^5], desarrollado por GitHub en colaboración con OpenAI, utiliza modelos de lenguaje para analizar el contexto del código y sugerir líneas completas, funciones, e incluso corregir errores. Esto permite a los desarrolladores ahorrar tiempo y mejorar la calidad del software.


[^1]: [https://tech.walmart.com/content/walmart-global-tech/en_us/blog/post/walmarts-element-a-machine-learning-platform-like-no-other.html](https://tech.walmart.com/content/walmart-global-tech/en_us/blog/post/walmarts-element-a-machine-learning-platform-like-no-other.html)

[^2]: [https://www.paypal.com/us/brc/article/payment-fraud-detection-machine-learning](https://www.paypal.com/us/brc/article/payment-fraud-detection-machine-learning)

[^3]: [https://static.googleusercontent.com/media/research.google.com/es//pubs/archive/36368.pdf](https://static.googleusercontent.com/media/research.google.com/es//pubs/archive/36368.pdf)

[^4]: [https://github.blog/security/vulnerability-research/leveraging-machine-learning-find-security-vulnerabilities/](https://github.blog/security/vulnerability-research/leveraging-machine-learning-find-security-vulnerabilities/)

[^5]: [https://github.com/features/copilot](https://github.com/features/copilot)