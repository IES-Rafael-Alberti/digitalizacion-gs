# IT y OT

<center>
![](assets/it-ot.png){ width="800" }
</center>

## Definiciones

**IT (Tecnologías de la Información)**[^1]: Hace referencia al conjunto de tecnologías utilizadas para la gestión de la información en las organizaciones. Incluye sistemas como servidores, redes, bases de datos y dispositivos de almacenamiento, así como los procesos asociados que permiten la creación, procesamiento, almacenamiento y transmisión segura de los datos. Los sistemas IT están orientados a la optimización de la eficiencia, la automatización y la protección de la información empresarial.

**OT (Tecnologías Operativas)**[^2]: Se refiere al hardware y software que gestiona los sistemas físicos y controla procesos industriales. Las OT son fundamentales para supervisar y operar maquinaria, plantas de producción, sistemas de energía y otros entornos industriales. Están diseñadas para garantizar la disponibilidad y fiabilidad de los procesos críticos, priorizando el control físico de operaciones sobre la eficiencia o seguridad de la información, en entornos más robustos y longevos que los sistemas IT.

## Diferencias

|          | **IT**                                                                                        | **OT**                                                                                                 |
|----------|------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| **Alcance**           | Gestiona datos e información en entornos empresariales.                            | Controla y supervisa procesos físicos en entornos industriales.                                         |
| **Objetivo**          | Optimización de procesos y seguridad de la información.                           | Fiabilidad y disponibilidad en el control de operaciones industriales.                                  |
| **Ciclo de vida**     | Frecuente actualización de sistemas y tecnología.                                | Sistemas con ciclos de vida más largos, sin actualizaciones frecuentes.                                 |
| **Entorno**           | Oficinas, centros de datos, entornos digitales.                                   | Plantas industriales, fábricas, entornos físicos.                                                       |
| **Prioridad respecto a la ciberseguridad**           | Confidencialidad.                                   | Disponibilidad.                                                       |

## Similitudes

- Ambas utilizan tecnología digital para su funcionamiento.
- Tienen una importancia crítica para las operaciones empresariales.

## Explicación

La relación entre **IT** y **OT** puede entenderse comparando cómo gestionan diferentes aspectos de una empresa. 

Imagina que tienes una fábrica que produce electrodomésticos. 

- **IT** sería el sistema que gestiona toda la parte administrativa: la contabilidad, los pedidos, el control de stock, las comunicaciones entre departamentos. Es el "cerebro" que organiza la información sobre cómo va la producción, cuántos productos hay en el inventario o si hay que hacer más pedidos de materias primas.
  
- **OT**, por otro lado, es lo que ocurre en el "cuerpo" de la fábrica: son las máquinas que cortan, ensamblan y empaquetan los electrodomésticos. Si una máquina detecta que una parte está defectuosa y necesita ser reemplazada, el sistema OT será el encargado de controlar ese proceso en tiempo real, activando el paro de la máquina y enviando alertas.

Ambos sistemas son críticos, pero **IT** se enfoca en la gestión de información y optimización de procesos, mientras que **OT** se centra en garantizar que las operaciones físicas en la planta sean seguras, eficientes y continuas. En la actualidad, la integración de IT y OT es esencial para que una empresa funcione de manera más ágil y competitiva, especialmente con la llegada de tecnologías de la **Industria 4.0**.

## Convergencia IT/OT

La convergencia entre IT y OT[^3] es un paso fundamental en la transformación digital industrial, permitiendo que los datos generados por los sistemas OT sean accesibles y gestionados por los sistemas IT. Esta integración ofrece varios beneficios:

1. **Mayor visibilidad**: Permite obtener datos en tiempo real de los procesos industriales, mejorando la capacidad de toma de decisiones.
2. **Optimización de recursos**: La integración IT/OT ayuda a reducir costos y aumentar la eficiencia.
3. **Aumento de la productividad**: Facilita la automatización de procesos y la integración de tecnologías como el Internet de las Cosas (IoT).
4. **Seguridad integral**: Un enfoque conjunto entre IT y OT mejora la ciberseguridad de la organización.

### Ejemplo: La convergencia IT/OT de Siemens

Siemens diseñó la plataforma **MindSphere**[^4], que permite conectar equipos industriales a la nube para recopilar y analizar datos en tiempo real. Este enfoque permite a las empresas monitorizar remotamente sus procesos industriales, predecir fallos de equipos y optimizar el rendimiento, transformando así sus operaciones industriales y habilitando una mayor competitividad en el mercado global.

## Caso práctico: Diferencias y convergencia entre IT y OT en una fábrica automotriz

Imaginemos una **fábrica de automóviles** que ha incorporado tanto sistemas IT como OT en sus operaciones diarias. A continuación, detallamos cómo funcionan por separado y cómo se integran para maximizar la eficiencia y la productividad:

### **IT en la fábrica**
- El **departamento de IT** gestiona los sistemas de **planificación de recursos empresariales (ERP)**, que organizan la logística, los recursos humanos, la contabilidad y la cadena de suministro. Los empleados de oficina utilizan estos sistemas para llevar un control detallado del stock de piezas, los pedidos de proveedores y la facturación.
- El sistema IT también gestiona la **seguridad de la red corporativa**, asegurando que la información sensible, como los contratos con proveedores y los datos financieros, esté protegida.
- Además, IT se encarga del **software de gestión de calidad**, donde se registran las especificaciones y normativas de cada vehículo producido, así como la información que se comparte con los clientes a través del CRM (gestión de relaciones con el cliente).

### **OT en la fábrica**
- Mientras tanto, los sistemas **OT** operan en la línea de montaje. Las máquinas controladas por **PLC** (Controladores Lógicos Programables) ensamblan las piezas del automóvil, soldando y uniendo componentes según las especificaciones precisas del diseño.
- Los **sensores** colocados en las máquinas supervisan en tiempo real la temperatura, la presión y otros parámetros críticos para garantizar que el proceso de producción se realice sin errores. Si un sensor detecta una anomalía, el sistema OT detiene automáticamente la máquina y activa una alerta para que los técnicos intervengan, minimizando el riesgo de errores graves o accidentes.
- La **supervisión en tiempo real** de la maquinaria permite que los operadores de planta puedan monitorizar los procesos industriales mediante **pantallas de control**, priorizando la disponibilidad y fiabilidad del sistema para evitar tiempos de inactividad.

### **Convergencia IT/OT en la fábrica**
La convergencia entre **IT y OT** ocurre cuando los datos de la planta (OT) son integrados en los sistemas de gestión empresarial (IT) para proporcionar una **visión integral** de la producción.

- Gracias a esta integración, los datos generados por los sensores en la línea de montaje se envían al sistema IT, permitiendo que el **software de análisis predictivo** identifique patrones de uso en las máquinas. Si una máquina muestra signos de desgaste inusual, el sistema genera una alerta para que el equipo de mantenimiento programe una reparación antes de que ocurra una avería.
- Además, la **gestión de inventario** en tiempo real se ve beneficiada. Por ejemplo, cuando una máquina consume una cantidad crítica de piezas, los datos se sincronizan con el ERP gestionado por IT, que automáticamente realiza un pedido de reposición al proveedor.
- De cara a la **optimización de la producción**, la información de OT también se cruza con datos del sistema IT para ajustar la velocidad de producción según la demanda del mercado o para ajustar los turnos de trabajo en función del rendimiento de las máquinas.

En este caso práctico, **IT** es responsable de la gestión administrativa, financiera y logística, mientras que **OT** controla los procesos físicos y operativos en la planta de producción. La convergencia de ambos sistemas permite que la fábrica funcione de manera más eficiente, evitando paradas imprevistas, optimizando los recursos y mejorando la toma de decisiones en tiempo real. De este modo, la integración entre IT y OT habilita la fábrica para competir en la **Industria 4.0**, al tener un control total de sus operaciones, tanto en el ámbito digital como en el físico.


[^1]: Gartner Glossary. (s.f.). Information Technology (IT). [https://www.gartner.com/en/information-technology/glossary/it-information-technology](https://www.gartner.com/en/information-technology/glossary/it-information-technology)

[^2]: Gartner Glossary. (s.f.). Operational Technology (OT). [https://www.gartner.com/en/information-technology/glossary/operational-technology-ot](https://www.gartner.com/en/information-technology/glossary/operational-technology-ot)

[^3]: Deloitte. Managing the successful convergence of IT and OT. [https://www2.deloitte.com/content/dam/Deloitte/global/Documents/Risk/gx-deloitte-managing-the-successful-convergence-of-it-and-ot.pdf](https://www2.deloitte.com/content/dam/Deloitte/global/Documents/Risk/gx-deloitte-managing-the-successful-convergence-of-it-and-ot.pdf)

[^4]: Siemens. (s.f.). MindSphere: The Industrial IoT as a Service Solution. [https://www.siemens.com/es/es/productos/software/mindsphere.html](https://www.siemens.com/es/es/productos/software/mindsphere.html)