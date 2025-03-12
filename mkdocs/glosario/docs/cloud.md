# Paradigmas de computación distribuida

<center>
![](assets/cloud.png){ width="800" }
</center>

## Definición

Los **paradigmas de computación distribuida** representan diferentes enfoques para distribuir las capacidades de procesamiento, almacenamiento y análisis de datos en sistemas informáticos interconectados. Estos modelos han evolucionado desde arquitecturas completamente centralizadas hasta sistemas altamente descentralizados que acercan el procesamiento a la fuente de los datos. Entre los principales paradigmas destacan: **Cloud Computing** (computación en la nube), **Edge Computing** (computación en el borde), **Fog Computing** (computación en la niebla) y **Mist Computing** (computación en la bruma), cada uno con características distintivas que responden a diferentes necesidades de procesamiento, latencia y optimización de recursos[^1].

## Tipos y características

### Cloud Computing

La **computación en la nube** se basa en la utilización de una red de servidores remotos conectados a internet para almacenar, administrar y procesar datos[^2]. Este modelo permite acceder a recursos informáticos (servidores, almacenamiento, bases de datos, redes, software) a demanda a través de la red, sin necesidad de gestión directa por parte del usuario. Sus principales características incluyen:

- **Ubicación**: Grandes centros de datos, generalmente alejados de los dispositivos que generan los datos.
- **Modelos de servicio**: IaaS (Infraestructura como Servicio), PaaS (Plataforma como Servicio) y SaaS (Software como Servicio).
- **Pago por uso**: Modelo económico basado en el consumo real de recursos.
- **Centralización**: Procesamiento y almacenamiento centralizados en infraestructuras de gran escala.

### Edge Computing

La **computación en el borde** lleva el procesamiento y almacenamiento de datos más cerca de donde se generan, en lugar de depender exclusivamente de un centro de datos centralizado en la nube[^3]. Este paradigma responde a la necesidad de reducir la latencia en aplicaciones críticas y optimizar el uso del ancho de banda. Sus principales características son:

- **Ubicación**: En dispositivos de usuario final o en servidores locales muy próximos a los dispositivos que generan los datos.
- **Procesamiento local**: Análisis y procesamiento de datos en tiempo real cerca de su origen.
- **Reducción de latencia**: Tiempos de respuesta significativamente menores en comparación con el cloud computing.
- **Autonomía parcial**: Capacidad para funcionar incluso con conectividad limitada o intermitente a la nube.

### Fog Computing

La **computación en la niebla** establece una capa intermedia entre los dispositivos de borde y la nube, extendiendo las capacidades de esta última más cerca de donde se generan los datos[^4]. Este modelo facilita el procesamiento de datos en nodos distribuidos estratégicamente en la red. Sus características principales incluyen:

- **Ubicación**: Nodos intermedios entre los dispositivos finales y la nube, como routers, gateways o servidores locales.
- **Arquitectura multicapa**: Estructura en tres niveles (dispositivos edge, nodos fog y nube).
- **Agregación de datos**: Capacidad para recibir, procesar y filtrar datos de múltiples dispositivos antes de enviarlos a la nube.
- **Distribución geográfica**: Nodos fog desplegados en diferentes ubicaciones para optimizar la cobertura y el rendimiento.

### Mist Computing

La **computación en la bruma** representa el nivel más extremo de descentralización, llevando las capacidades de procesamiento directamente a los dispositivos finales que generan los datos[^5]. Este paradigma minimiza al máximo la latencia y optimiza el uso del ancho de banda. Sus principales características son:

- **Ubicación**: Integrada directamente en los dispositivos finales y sensores.
- **Procesamiento extremadamente local**: Análisis de datos en el mismo punto donde se generan.
- **Latencia mínima**: Tiempos de respuesta que pueden medirse en microsegundos.
- **Completa autonomía**: Capacidad para operar de forma independiente, incluso sin conectividad.

## Comparativa entre paradigmas

| **Característica** | **Cloud Computing** | **Fog Computing** | **Edge Computing** | **Mist Computing** |
|-------------------|---------------------|-------------------|--------------------|--------------------|
| **Ubicación del procesamiento** | Centros de datos remotos | Nodos intermedios entre dispositivos y nube | Servidores locales o dispositivos de borde | Directamente en los dispositivos finales |
| **Latencia** | Alta (100-500 ms) | Media (10-50 ms) | Baja (1-10 ms) | Mínima (<1 ms) |
| **Capacidad de procesamiento** | Muy alta | Alta/Media | Media/Baja | Limitada |
| **Consumo de ancho de banda** | Alto | Medio | Bajo | Mínimo |
| **Dependencia de conectividad** | Total | Parcial | Baja | Mínima o nula |
| **Almacenamiento de datos** | A largo plazo, centralizado | Temporal/Intermedio | Temporal/Local | Limitado/Efímero |
| **Consumo energético en dispositivos** | Bajo | Medio | Alto | Muy alto |
| **Escalabilidad** | Muy alta | Alta | Media | Limitada |

## Explicación

<center>
![](https://cdn-bdmhh.nitrocdn.com/JNiKLBzGPsfbQJqUQoZqIbUrxBklWopT/assets/images/optimized/rev-b47509f/objectbox.io/wordpress/wp-content/uploads/2021/01/edge-mist-fog-cloud-2.jpg){ width="800" }
</center>

Los diferentes paradigmas de computación distribuida pueden entenderse como un continuo que va desde la centralización total hasta la descentralización extrema, adaptándose a diferentes necesidades de procesamiento y latencia.

Imaginemos un ejemplo práctico: una red de cámaras de seguridad inteligentes en una ciudad.

- Con un enfoque de **Cloud Computing** puro, todas las imágenes capturadas por las cámaras se enviarían directamente a servidores en la nube para su procesamiento. Esto permitiría realizar análisis complejos y almacenar grandes volúmenes de datos, pero con una latencia significativa que podría retrasar la detección de incidentes.

- Utilizando **Edge Computing**, cada cámara o un servidor local cercano podría procesar las imágenes para detectar situaciones de interés (como una persona en una zona restringida) y responder inmediatamente, enviando a la nube solo los eventos relevantes. Esto reduciría drásticamente la latencia y el ancho de banda utilizado.

- En un modelo de **Fog Computing**, un conjunto de servidores distribuidos por la ciudad actuaría como intermediarios, recibiendo datos de múltiples cámaras, realizando un primer nivel de procesamiento para detectar patrones más complejos (como el seguimiento de un vehículo sospechoso a través de diferentes cámaras) y enviando a la nube solo información agregada o eventos específicos.

- Con **Mist Computing**, los propios sensores y cámaras tendrían capacidad para realizar análisis básicos (como detectar movimiento o reconocer formas simples) y tomar decisiones inmediatas sin necesidad de comunicarse con otros sistemas, utilizando la conectividad solo cuando fuera necesario compartir información.

En aplicaciones reales, estos paradigmas suelen implementarse de forma complementaria, creando una arquitectura híbrida donde cada tipo de procesamiento se realiza en el nivel más adecuado según sus requisitos de latencia, capacidad de procesamiento y consumo de recursos.

## Casos de aplicación

### Internet de las cosas (IoT)

<center>
![](https://blogs.salleurl.edu/sites/default/files/styles/800x800/public/content/nodes/Noticia/image/21498/39358/cloud-fog-edge.jpg){ width="800" }
</center>

El ecosistema IoT se beneficia enormemente de la integración de estos paradigmas[^6]:

- **Cloud Computing**: Proporciona el almacenamiento a largo plazo de datos históricos de sensores y permite realizar análisis complejos como el aprendizaje automático para identificar patrones en grandes volúmenes de datos.

- **Fog Computing**: Gestiona y procesa datos de múltiples dispositivos IoT en tiempo real, como en sistemas de monitorización de consumo energético en edificios inteligentes, donde los nodos fog pueden agregar y procesar datos de diversos sensores antes de enviar información relevante a la nube.

- **Edge Computing**: Implementado en dispositivos como termostatos inteligentes o asistentes de voz, que procesan datos localmente para proporcionar respuestas inmediatas a los usuarios mientras envían solo información relevante a sistemas centralizados.

- **Mist Computing**: Utilizado en sensores autónomos como detectores de humo inteligentes, que pueden tomar decisiones inmediatas (activar alarmas) sin depender de conectividad externa.

### Industria 4.0

En entornos industriales, estos paradigmas están impulsando la transformación digital de la manufactura:

- **Cloud Computing**: Utilizado para análisis predictivo de mantenimiento, planificación de recursos y optimización global de la producción basada en datos históricos.

- **Fog Computing**: Implementado en sistemas de supervisión de planta que coordinan múltiples máquinas y procesos, permitiendo respuestas rápidas a condiciones cambiantes mientras mantienen la visión general de la producción.

- **Edge Computing**: Aplicado en sistemas de control de calidad visual que inspeccionan productos en tiempo real durante la fabricación, tomando decisiones inmediatas sobre piezas defectuosas.

- **Mist Computing**: Integrado en sensores y actuadores de maquinaria para monitorización continua de parámetros críticos como temperatura o vibración, permitiendo detecciones y respuestas inmediatas ante anomalías que podrían indicar fallos inminentes.

### Vehículos conectados y autónomos

El sector de la automoción ilustra claramente la complementariedad de estos paradigmas:

- **Cloud Computing**: Proporciona actualizaciones de software, mapas detallados, análisis de rutas óptimas y aprendizaje colectivo basado en datos de toda la flota de vehículos.

- **Fog Computing**: Implementado en infraestructuras de carretera inteligentes que coordinan múltiples vehículos en zonas específicas, como intersecciones o áreas de tráfico denso.

- **Edge Computing**: Utilizado en los sistemas a bordo del vehículo para procesamiento de datos de sensores y cámaras, permitiendo decisiones de conducción y navegación con baja latencia.

- **Mist Computing**: Aplicado en sensores críticos como radares, lidars y sistemas anticolisión que requieren respuestas en milisegundos para garantizar la seguridad.

## Tendencias futuras

El futuro de los paradigmas de computación distribuida apunta hacia una mayor integración y especialización[^7]:

1. **Arquitecturas híbridas inteligentes**: Sistemas que distribuyen dinámicamente el procesamiento entre cloud, fog, edge y mist según las necesidades específicas de cada momento, optimizando latencia, consumo energético y recursos de red.

2. **IA distribuida**: Modelos de inteligencia artificial desplegados en múltiples niveles, con inferencia en dispositivos edge y mist, coordinación en fog y entrenamiento en cloud.

3. **Microservicios modulares**: Aplicaciones diseñadas como componentes independientes que pueden ejecutarse en diferentes niveles de la arquitectura según el contexto y los recursos disponibles.

4. **Seguridad multicapa**: Enfoques de seguridad y privacidad adaptados a cada nivel, con mayor protección de datos sensibles en capas más cercanas a los usuarios.

5. **Eficiencia energética**: Optimización del consumo energético mediante la distribución inteligente de cargas de trabajo, especialmente importante en dispositivos edge y mist con limitaciones de batería.

Estas tendencias están impulsando un ecosistema tecnológico más adaptable y eficiente, donde la computación se vuelve cada vez más ubicua e integrada en todos los aspectos de nuestra vida cotidiana.

[^1]: HP. (s.f.). Procesamiento de datos: diferencias entre Cloud, Edge y Fog Computing. https://www.hp.com/pe-es/shop/tech-takes/procesamiento-datos-diferencias-cloud-edge-fog-computing

[^2]: Wikipedia. (s.f.). Computación en la nube. https://es.wikipedia.org/wiki/Computaci%C3%B3n_en_la_nube

[^3]: Akamai. (s.f.). What is Edge Computing? https://www.akamai.com/es/glossary/what-is-edge-computing

[^4]: IONOS. (s.f.). Fog Computing. https://www.ionos.es/digitalguide/servidores/know-how/fog-computing/

[^5]: TaskBCN. (s.f.). Sistemas en la nube. https://taskbcn.com/sistemas-en-la-nube/

[^6]: DataCenterMarket. (s.f.). Edge Computing y Fog Computing: La computación se acerca a los usuarios en el mundo del IoT. https://www.datacentermarket.es/mercado/edge-computing-y-fog-computing-la-computacion-se-acerca-a-los-usuarios-en-el-mundo-del-iot/

[^7]: Radiocrafts. (s.f.). Cloud vs. Fog vs. Mist Computing: Which One Should You Use? https://radiocrafts.com/cloud-vs-fog-vs-mist-computing-which-one-should-you-use/