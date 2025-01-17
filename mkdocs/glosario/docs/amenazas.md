# Principales amenazas y copias de seguridad

<center>
![](assets/amenazas.png){ width="800" }
</center>

## Principales amenazas a la seguridad

Las amenazas relacionadas con la información son diversas y evolucionan constantemente a medida que surgen nuevas tecnologías y métodos de ataque. A continuación, se describen algunas de las amenazas más comunes y sus implicaciones:

1. **Malware**: Software malicioso diseñado para infiltrarse o dañar sistemas sin el conocimiento del usuario. Incluye virus, gusanos, troyanos y spyware. Estas herramientas pueden robar información confidencial, corromper datos o incluso deshabilitar sistemas críticos.

2. **Phishing**: Técnicas de ingeniería social que buscan engañar a los usuarios para que revelen información confidencial, como contraseñas o datos bancarios. Los ataques de phishing suelen realizarse a través de correos electrónicos fraudulentos que simulan provenir de fuentes confiables.

3. **Ransomware**: Un tipo específico de malware que cifra los datos de una víctima y exige un rescate a cambio de la clave de descifrado. Este tipo de ataque puede paralizar operaciones empresariales enteras si no se dispone de copias de seguridad actualizadas.

4. **Ataques de denegación de servicio (DDoS)**: Sobrecargan los recursos de un sistema o red, haciéndolos inaccesibles para los usuarios legítimos. Estos ataques pueden interrumpir servicios críticos y generar pérdidas económicas significativas.

5. **Errores humanos**: Aunque no son intencionados, los errores humanos representan una de las mayores vulnerabilidades. Ejemplos incluyen el uso de contraseñas débiles, la descarga de archivos sospechosos o el acceso no autorizado debido a configuraciones incorrectas.

6. **Amenazas internas**: Empleados o socios con acceso legítimo que utilizan su posición para robar o comprometer información confidencial. Estas amenazas pueden ser intencionales o resultado de negligencia.

7. **Explotación de vulnerabilidades**: Los ciberdelincuentes aprovechan errores o fallos en el software o hardware para obtener acceso no autorizado. La falta de actualizaciones y parches de seguridad incrementa este riesgo.

8. **Ataques a IoT (Internet de las Cosas)**: Dispositivos conectados, como cámaras de seguridad o termostatos inteligentes, pueden ser vulnerables si no están configurados adecuadamente. Esto permite que los atacantes los utilicen como puntos de entrada a redes más amplias.

Estas amenazas no solo afectan la infraestructura tecnológica, sino también la reputación y la confianza de las organizaciones. La adopción de estrategias proactivas es esencial para minimizar los riesgos.

### Ingeniería social: manipulando al eslabón más débil

La ingeniería social es una técnica que no se basa en vulnerabilidades tecnológicas, sino en la explotación de la psicología humana para obtener acceso a información o sistemas. Los atacantes utilizan la manipulación emocional, la confianza o el miedo para convencer a las víctimas de realizar acciones que comprometen la seguridad. Este tipo de ataques demuestra que, en muchos casos, el eslabón más débil en la ciberseguridad es el factor humano.

Por ejemplo, un atacante puede hacerse pasar por un técnico de soporte informático que necesita acceso inmediato al sistema de un empleado para solucionar un problema urgente. Con un tono profesional y una narrativa convincente, logra que el empleado comparta sus credenciales sin cuestionar la legitimidad de la solicitud. Otro ejemplo común es el phishing emocional, donde un correo electrónico alerta al destinatario sobre un problema con su cuenta bancaria y lo insta a ingresar a un enlace para solucionarlo de inmediato.

La clave del éxito en estos ataques radica en el aprovechamiento de emociones como la urgencia, el miedo o la empatía. Los ciberdelincuentes adaptan sus tácticas según las circunstancias de la víctima, utilizando información obtenida de redes sociales o filtraciones previas para personalizar el ataque.

Prevenir ataques de ingeniería social requiere una combinación de conciencia y capacitación. Las organizaciones deben educar a sus empleados sobre cómo identificar señales de manipulación, como solicitudes inesperadas de información confidencial, enlaces sospechosos o mensajes que provocan urgencia injustificada. Además, fomentar una cultura en la que los empleados se sientan seguros de verificar la autenticidad de cualquier solicitud sospechosa es fundamental.

La ingeniería social nos recuerda que la tecnología más avanzada no puede protegernos completamente si no prestamos atención al factor humano. Por eso, una defensa efectiva contra estos ataques empieza por empoderar a las personas con el conocimiento necesario para reconocer y resistir intentos de manipulación.

## Copias de seguridad

Las **copias de seguridad** (o backups) son duplicados de datos que se crean y almacenan para garantizar la recuperación de la información en caso de pérdida, daño o ataque. Estas copias son esenciales para mantener la continuidad del negocio, proteger la información crítica y minimizar el impacto de incidentes como fallos del sistema, errores humanos o ciberataques.

### Tipos de copias de seguridad

1. **Completa**: Realiza un duplicado completo de todos los datos seleccionados. Aunque es la más segura, también consume más tiempo y espacio de almacenamiento.

2. **Incremental**: Copia solo los datos que han cambiado desde la última copia de seguridad (ya sea completa o incremental). Es más rápida y eficiente, pero requiere todas las copias previas para una recuperación completa.

3. **Diferencial**: Copia todos los datos modificados desde la última copia completa. Consume más espacio que la incremental, pero facilita la restauración al necesitar solo la copia completa y la más reciente copia diferencial.

### Importancia de las copias de seguridad

Las copias de seguridad son fundamentales para:

- **Recuperación ante desastres**: Garantizan la disponibilidad de datos tras incidentes graves, como desastres naturales o fallos críticos en los sistemas.
- **Mitigación de ataques de ransomware**: Permiten restaurar los datos sin pagar rescates a los atacantes.
- **Protección frente a errores humanos**: Recuperan información borrada accidentalmente o sobrescrita.
- **Cumplimiento normativo**: Ayudan a cumplir regulaciones que exigen la protección y disponibilidad de datos sensibles.

### Estrategias recomendadas para copias de seguridad efectivas

- **Regla 3-2-1**: Mantén al menos tres copias de tus datos, almacenadas en dos tipos de medios diferentes, y guarda una copia en una ubicación remota o en la nube.
- **Automatización**: Configura copias de seguridad automáticas para reducir la dependencia de la intervención humana y garantizar la regularidad.
- **Pruebas periódicas**: Verifica que las copias de seguridad funcionan correctamente y que los datos se pueden restaurar sin problemas.
- **Cifrado de backups**: Protege las copias de seguridad con cifrado para garantizar que estén seguras incluso si son robadas o comprometidas.
- **Control de acceso**: Limita quién puede acceder a las copias de seguridad, reduciendo el riesgo de manipulaciones indebidas.

## Caso práctico: Recuperación tras un ataque de ransomware

Una pequeña empresa de servicios financieros sufrió un ataque de ransomware que cifró todos sus datos operativos, incluyendo información sensible de sus clientes. Los atacantes exigieron un rescate de 50.000 euros para liberar los datos.

Afortunadamente, la empresa contaba con una estrategia sólida de copias de seguridad basada en la regla 3-2-1. Las copias estaban almacenadas en servidores locales, dispositivos externos y en la nube. Tras el ataque:

1. La empresa aisló los sistemas infectados para evitar la propagación del ransomware.
2. Procedieron a restaurar los datos desde las copias más recientes almacenadas en la nube.
3. En menos de 24 horas, la empresa volvió a estar operativa sin pagar el rescate, demostrando la importancia de una planificación adecuada.

Este caso subraya cómo las copias de seguridad no solo protegen los datos, sino que también pueden salvar a las empresas de pérdidas económicas y de reputación significativas.
