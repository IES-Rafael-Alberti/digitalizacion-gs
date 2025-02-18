# Autenticación y contraseñas

<center>
![](assets/autenticacion.png){ width="800" }
</center>

## Definición de autenticación

La **autenticación** es el proceso mediante el cual se verifica la identidad de un usuario o sistema antes de permitir el acceso a un recurso protegido. Este proceso es fundamental para garantizar la seguridad y proteger la información sensible frente a accesos no autorizados.

## Métodos de autenticación

### Basada en conocimiento (contraseñas)

Este método utiliza algo que el usuario conoce, como una contraseña o un PIN. Es el sistema más común, pero también uno de los más vulnerables si no se implementa correctamente.

### Basada en posesión

Se basa en algo que el usuario posee, como una tarjeta de seguridad, un token físico o una aplicación móvil que genera códigos de acceso temporales. Este método agrega una capa adicional de protección, ya que requiere un objeto físico.

### Basada en características biométricas

Este método se basa en algo que el usuario es, como su huella digital, reconocimiento facial o escaneo de iris. Es altamente seguro, aunque plantea preocupaciones sobre la privacidad y el almacenamiento seguro de los datos biométricos.

## El certificado digital

El **certificado digital** es un método de autenticación basado en posesión, donde el usuario utiliza un documento electrónico emitido por una Autoridad de Certificación (CA) para verificar su identidad. Este certificado contiene información como el nombre del titular, una clave pública y la firma digital de la CA que lo respalda.

En España, el certificado digital es ampliamente utilizado en la interacción con la administración pública. Permite a los ciudadanos autenticarse de manera segura para realizar trámites como:

- Presentación de declaraciones de impuestos.
- Consulta de vida laboral.
- Solicitud de subvenciones.

Además, garantiza la integridad y confidencialidad de las transacciones electrónicas, evitando la manipulación o interceptación de los datos.

Podríamos decir que el certificado digital es una forma de identificarte en Internet como lo harías de forma presencial enseñando tu Documento Nacional de Identidad (DNI).

## Características de una contraseña segura

Durante mucho tiempo, se han promovido contraseñas complejas con combinaciones de números, letras y caracteres especiales, lo que ha llevado a problemas como la reutilización de contraseñas y el uso de variaciones predecibles. Una alternativa eficaz y fácil de recordar es el uso de **tres palabras aleatorias**. Por ejemplo, "MercadoJupiterTerremoto" es una contraseña lo suficientemente larga y robusta para resistir ataques, pero también fácil de recordar para el usuario.

Otra solución es el uso de **gestores de contraseñas**. Estos permiten generar y almacenar contraseñas únicas para cada cuenta, eliminando la necesidad de recordarlas todas. Sin embargo, el punto débil de esta estrategia es la **contraseña maestra**, que debe ser segura y no compartida.

## El problema de las contraseñas débiles

Las contraseñas débiles siguen siendo una de las principales causas de brechas de seguridad. Problemas comunes incluyen:

- Uso de contraseñas cortas o predecibles (como "123456" o "password").
- Reutilización de contraseñas en múltiples cuentas.
- Almacenamiento de contraseñas en lugares inseguros, como notas adhesivas o documentos sin protección.

Estos hábitos comprometen la seguridad y facilitan ataques como el de fuerza bruta o el phishing.

## Autenticación Multifactor (MFA): Un nivel adicional de seguridad

La autenticación multifactor combina dos o más métodos de autenticación, como:

- Algo que el usuario sabe (contraseña).
- Algo que el usuario posee (token o código de un dispositivo).
- Algo que el usuario es (características biométricas).

Por ejemplo, al acceder a una cuenta bancaria en línea, un usuario podría necesitar ingresar su contraseña y un código generado en su teléfono móvil. Esto hace que sea mucho más difícil para los atacantes comprometer el acceso, incluso si obtienen la contraseña.

## Buenas prácticas en la gestión de contraseñas

1. Utilizar contraseñas largas y fáciles de recordar, como combinaciones de tres palabras aleatorias.
2. Evitar la reutilización de contraseñas en diferentes cuentas.
3. Implementar gestores de contraseñas para generar y almacenar contraseñas únicas de forma segura.
4. Habilitar la autenticación multifactor siempre que sea posible.
5. Cambiar inmediatamente contraseñas comprometidas.
6. No compartir contraseñas y desconfiar de solicitudes no verificadas para compartir datos de autenticación.
