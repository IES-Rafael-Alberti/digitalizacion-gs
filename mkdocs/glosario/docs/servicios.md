# Tipos de servicios en la nube

<center>
![](assets/servicios.png){ width="800" }
</center>

## Definición

Los **tipos de servicios en la nube** se refieren a los diferentes modelos de implementación y provisión de recursos informáticos que las organizaciones pueden utilizar para gestionar sus necesidades tecnológicas. Estos modelos varían principalmente en función de quién gestiona cada componente de la infraestructura tecnológica y el nivel de responsabilidad que asume el cliente frente al proveedor[^1]. Los cuatro principales modelos son: **On-premise** (local), **IaaS** (Infraestructura como Servicio), **PaaS** (Plataforma como Servicio) y **SaaS** (Software como Servicio). Cada uno de estos modelos ofrece distintos niveles de control, flexibilidad y responsabilidad operativa, permitiendo a las organizaciones elegir la opción que mejor se adapte a sus necesidades específicas.

## Diferencias entre los tipos de servicios

| **Característica** | **On-premise** | **IaaS** | **PaaS** | **SaaS** |
|-------------------|----------------|----------|----------|----------|
| **Control** | Control total sobre hardware y software | Control sobre sistemas operativos y aplicaciones | Control sobre aplicaciones y datos | Control mínimo, solo sobre configuraciones básicas |
| **Responsabilidad de mantenimiento** | Cliente responsable de todo | Proveedor gestiona hardware, cliente gestiona software | Proveedor gestiona infraestructura y plataforma, cliente gestiona aplicaciones | Proveedor gestiona todo el sistema |
| **Inversión inicial** | Alta | Baja | Baja | Baja |
| **Escalabilidad** | Limitada, requiere planificación y hardware adicional | Alta, recursos bajo demanda | Alta, recursos bajo demanda | Alta, generalmente incluida en el servicio |
| **Ejemplos** | Servidores físicos en las instalaciones de la empresa | Amazon EC2, Microsoft Azure IaaS | AWS Elastic Beanstalk, Google App Engine | Microsoft 365, Salesforce, Dropbox |

## Explicación

Para entender mejor los distintos tipos de servicios en la nube, podemos utilizar la analogía de la preparación de una comida:

- **On-premise** es como cocinar en tu propia casa: tú compras los ingredientes, utensilios, electrodomésticos, y te encargas de todo el proceso. Tienes control total, pero también toda la responsabilidad y los costes asociados.

- **IaaS** equivale a alquilar una cocina equipada: alguien más proporciona y mantiene los electrodomésticos y utensilios básicos, pero tú decides qué cocinar y cómo hacerlo. Tienes menos responsabilidades de mantenimiento, manteniendo control sobre el proceso.

- **PaaS** se asemeja a utilizar un kit de comida preparada: recibes los ingredientes ya medidos y preparados junto con instrucciones, y solo tienes que combinarlos siguiendo los pasos. No te preocupas por comprar o preparar los ingredientes, solo por el proceso final.

- **SaaS** es como pedir comida a domicilio: el plato llega listo para consumir, sin que tengas que preocuparte por ningún aspecto de su preparación. Ofrece conveniencia máxima pero mínima personalización.

Esta progresión muestra cómo cada modelo va reduciendo la responsabilidad del cliente mientras aumenta la del proveedor, permitiendo a las organizaciones elegir el nivel de gestión que desean asumir sobre sus recursos tecnológicos.

## On-premise

### Características

El modelo **On-premise** (en las instalaciones) representa el enfoque tradicional donde la organización adquiere, instala y gestiona toda su infraestructura tecnológica en sus propias instalaciones físicas[^2]. En este modelo:

- La empresa es propietaria de todo el hardware y software
- Los servidores y sistemas están físicamente ubicados en las instalaciones de la organización
- Todo el mantenimiento, actualizaciones y seguridad son responsabilidad del departamento de TI interno
- Las aplicaciones se ejecutan en los servidores locales y pueden seguir funcionando incluso sin conexión a internet

### Beneficios y limitaciones

**Beneficios:**
- Control total sobre la infraestructura y los datos
- Mayor seguridad percibida para información sensible
- Independencia de la conectividad a internet para operaciones básicas
- Personalización completa de sistemas según necesidades específicas
- Cumplimiento más sencillo de ciertos requisitos regulatorios en sectores específicos

**Limitaciones:**
- Alta inversión inicial en hardware y software (CAPEX)
- Necesidad de personal especializado para mantenimiento
- Escalabilidad limitada que requiere planificación anticipada
- Actualizaciones costosas y que requieren tiempo
- Responsabilidad total sobre seguridad y recuperación ante desastres

## IaaS (Infraestructura como Servicio)

### Características

**IaaS** (Infrastructure as a Service) proporciona infraestructura de computación virtualizada a través de internet[^3]. Este modelo incluye:

- Recursos computacionales virtualizados (servidores, almacenamiento, redes)
- Facturación basada en el consumo (pago por uso)
- El proveedor gestiona y mantiene la infraestructura física
- El cliente mantiene el control sobre sistemas operativos, aplicaciones y configuraciones
- Alta elasticidad para escalar recursos según demanda

### Beneficios y limitaciones

**Beneficios:**
- Reducción significativa de inversión inicial en hardware
- Mayor flexibilidad y escalabilidad para adaptarse a demandas cambiantes
- Conversión de gastos de capital (CAPEX) en gastos operativos (OPEX)
- Acceso a infraestructura de nivel empresarial sin inversiones masivas
- Reducción de responsabilidades de mantenimiento de hardware

**Limitaciones:**
- Dependencia de la conectividad a internet
- Preocupaciones sobre seguridad y privacidad de datos
- Posibles costes impredecibles si no se gestiona adecuadamente el consumo
- Curva de aprendizaje para administrar recursos virtualizados
- Mantenimiento de responsabilidad sobre sistemas operativos y aplicaciones

## PaaS (Plataforma como Servicio)

### Características

**PaaS** (Platform as a Service) proporciona una plataforma completa que incluye hardware, sistema operativo y herramientas de desarrollo para crear, probar y desplegar aplicaciones[^4]. Este modelo incluye:

- Entorno de desarrollo completo accesible vía internet
- Herramientas preconfiguradas para desarrollo, pruebas y despliegue
- Gestión automatizada de infraestructura subyacente
- Frameworks y bibliotecas integradas para agilizar el desarrollo
- Servicios integrados para bases de datos, seguridad y escalabilidad

### Beneficios y limitaciones

**Beneficios:**
- Aceleración del ciclo de desarrollo de aplicaciones
- Eliminación de la necesidad de gestionar infraestructura
- Entorno consistente para desarrollo, pruebas y producción
- Facilitación de la colaboración entre equipos distribuidos geográficamente
- Acceso inmediato a herramientas y servicios avanzados

**Limitaciones:**
- Posible dependencia del proveedor (vendor lock-in)
- Limitaciones en personalización de la infraestructura subyacente
- Posibles restricciones en lenguajes de programación o frameworks soportados
- Preocupaciones de seguridad al ejecutar código en plataformas compartidas
- Dependencia de la disponibilidad y rendimiento del proveedor

## SaaS (Software como Servicio)

### Características

**SaaS** (Software as a Service) proporciona aplicaciones completas alojadas y gestionadas por el proveedor, accesibles a través de internet[^5]. Este modelo incluye:

- Aplicaciones listas para usar sin instalación local
- Acceso a través de navegador web o aplicaciones cliente ligeras
- Actualizaciones y mantenimiento gestionados por el proveedor
- Modelo de suscripción (mensual o anual) en lugar de compra de licencias
- Datos almacenados en la infraestructura del proveedor

### Beneficios y limitaciones

**Beneficios:**
- Implementación inmediata sin requisitos de instalación
- Actualizaciones automáticas sin intervención del usuario
- Accesibilidad desde cualquier dispositivo con conexión a internet
- Previsibilidad de costes mediante modelo de suscripción
- Eliminación de responsabilidades de mantenimiento técnico

**Limitaciones:**
- Control limitado sobre funcionalidades y configuraciones
- Dependencia total de la disponibilidad del servicio
- Preocupaciones sobre seguridad y privacidad de datos sensibles
- Posible falta de personalización para necesidades específicas
- Costes acumulativos a largo plazo en comparación con licencias perpetuas

## Caso práctico: Gestión de correo electrónico empresarial

Para ilustrar las diferencias entre los modelos, consideremos cómo una empresa podría implementar su sistema de correo electrónico corporativo en cada uno de ellos:

### On-premise
La empresa instalaría y mantendría sus propios servidores de correo (como Microsoft Exchange o Zimbra) en sus instalaciones. Su departamento de TI se encargaría de toda la configuración, mantenimiento, copias de seguridad, seguridad y actualizaciones. La empresa tendría control total sobre todos los aspectos del sistema, pero también sería responsable de garantizar su disponibilidad y rendimiento.

### IaaS
La empresa alquilaría servidores virtuales en un proveedor como AWS o Azure, donde instalaría su software de servidor de correo preferido. El proveedor se encargaría del hardware y la infraestructura de red, mientras que la empresa seguiría siendo responsable de instalar, configurar y mantener el software del servidor de correo. Este enfoque reduce las responsabilidades de infraestructura física pero mantiene el control sobre el software.

### PaaS
La empresa utilizaría una plataforma especializada para implementar un sistema de correo electrónico, como Amazon WorkMail o Heroku con Mailgun. En este modelo, la empresa no necesita preocuparse por la infraestructura ni por la instalación del software base, pero mantiene cierto control sobre la configuración y personalización del servicio según sus necesidades específicas.

### SaaS
La empresa simplemente se suscribiría a un servicio de correo electrónico como Microsoft 365 o Google Workspace. Todo el sistema sería gestionado por el proveedor, y la empresa solo necesitaría configurar cuentas de usuario y algunas políticas básicas. Este enfoque ofrece la máxima simplicidad pero el menor control sobre el funcionamiento interno del sistema.

## Tendencias actuales

El panorama de los servicios en la nube continúa evolucionando, con varias tendencias significativas emergiendo en los últimos años[^6]:

1. **Modelos híbridos y multi-nube**: Las organizaciones están adoptando cada vez más enfoques que combinan varios modelos (on-premise + cloud) o utilizan servicios de múltiples proveedores cloud para optimizar costes y minimizar la dependencia.

2. **Contenedores y microservicios**: Tecnologías como Docker y Kubernetes están transformando la forma en que se implementan aplicaciones, borrando algunas líneas tradicionales entre IaaS y PaaS.

3. **Serverless computing**: Este paradigma emergente permite a los desarrolladores crear aplicaciones sin preocuparse por la infraestructura subyacente, pagando solo por el tiempo de ejecución real del código.

4. **Edge computing**: La necesidad de procesamiento cercano al punto de origen de los datos está llevando a modelos distribuidos que complementan los servicios de nube centralizada.

5. **FinOps**: Las organizaciones están adoptando prácticas de gestión financiera específicas para la nube para optimizar costes y maximizar el valor de sus inversiones en servicios cloud.

La elección entre los diferentes modelos raramente es absoluta, y muchas organizaciones optan por estrategias híbridas que aprovechan las ventajas de cada modelo según las necesidades específicas de cada carga de trabajo o proceso de negocio.

[^1]: IBM. (s.f.). IaaS vs PaaS vs SaaS. https://www.ibm.com/es-es/think/topics/iaas-paas-saas

[^2]: Ekon. (s.f.). On-Premise vs Cloud: ¿qué es mejor? https://www.ekon.es/blog/on-premise-vs-cloud-que-es-mejor/

[^3]: OVHcloud. (s.f.). ¿Qué son IaaS, PaaS y SaaS? https://www.ovhcloud.com/es-es/learn/iaas-paas-saas/

[^4]: Stackscale. (s.f.). Modelos de servicio cloud: IaaS, PaaS y SaaS. https://www.stackscale.com/es/blog/modelos-de-servicio-cloud/

[^5]: Cosmoconsult. (s.f.). IaaS, PaaS y SaaS: definición y diferencias. https://www.cosmoconsult.com/es/insights/blog/iaas-paas-y-saas-definicion-y-diferencias

[^6]: Codster. (s.f.). On Premise Computing vs Cloud Computing: comparación. https://codster.io/blog/cloud-computing/on-premise-computing-cloud-computing-comparacion/