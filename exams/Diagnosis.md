# Evaluación de Redes y Sistemas Operativos

| Nombre: | Fecha: | Matrícula: |
|---------|--------|------------|
|Sandra Gabriela Velasco Guzman | 22/08/2024| 20620165|

## Instrucciones 

Responde las siguientes preguntas de manera clara y concisa. Cada sección tiene un peso específico, así que distribuye tu tiempo en consecuencia..

## Sección 1: Componentes de un Sistema de Red (20%)

Pregunta de Opción Múltiple:<br>
Identifica cuáles de los siguientes elementos son componentes fundamentales de un sistema de red:<br>

- [x] Switch
- [x] Router
- [ ] Monitor
- [x] Cableado
- [ ] CPU
- [ ] Firewall

Pregunta Abierta:<br>
Explica la función de un router en una red y cómo se diferencia de un switch.<br>
___Respuesta___
La función de un router se basa en establecer la conexión entre diferentes redes, mientras que el switch se basa en crear una red que conecte diferentes dispositivos.

Pregunta de Emparejamiento:<br>
Relaciona los siguientes componentes de una red con su función principal:<br>

| Componente                      | Función principal |
|---------------------------------|-------------------|
| [D] Servidor                    | A) Protege la red de accesos no autorizados. |
| [A] Firewall                    | B) Facilita la conectividad inalámbrica. |
| [B] Punto de acceso inalámbrico | C) Transmite datos entre dispositivos de la red. |
| [C] Cable de par trenzado       | D) Proporciona recursos a los usuarios de la red. |

## Sección 2: Protocolo de Conexión TCP/IP (20%)

Pregunta Verdadero/Falso:<br>
TCP/IP es un protocolo que se utiliza exclusivamente para redes privadas, como las LANs.

- [ ] Verdadero
- [X] Falso

Justifique su respuesta.<br>
___Respuesta___
No solo se utiliza para redes privadas sino tambien para redes publicas como internet.
Pregunta Abierta:<br>
Describe las diferencias clave entre TCP y UDP en términos de fiabilidad y uso.<br>
El TCP es mas fiable, ya que ofrece una mejor garantia para la entrega de datos correctamente y en el orden que estos se envian, asi como se encarga de verificacion de errores y la recuperacion de los datos que en el camino se pierdan o se dañen.
a diferencia del UDP no tiene garantia de entrega ni que lleguen en el orden correcto, tampoco tiene mecanismos de confirmacion.
cabe resaltar que el TCP es mas lento debido a que como se mencionaba este es mas fiable  en el manejo de errores, y el UDP es más rápido ya que no maneja la fiabilidad y el orden de los datos.

Pregunta de Desarrollo:<br>
Explica cómo se utilizan las direcciones IP y las máscaras de subred en el protocolo TCP/IP para enrutar datos a través de una red.<br>
___Respuesta___
Las direcciones IP son básicamente una etiqueta numérica única asignada a cada dispositivo en una red que usa TCP/IP, esta la definimos en que su funcion principal es identificar y localizar dispositivos en una red.
las mascaras de subred son una secuencia de bits que se utiliza en combinacion con una direccion ip para definir que parte de la direccion ip se refiere a la red y que parte se refiere a los hosts dentro de esa red.
## Sección 3: Normas y Estándares de la Industria (10%)

Pregunta de Selección Múltiple:<br>
¿Cuál de los siguientes es un estándar de la industria para redes inalámbricas?<br>

- [ ] IEEE 802.3
- [X] IEEE 802.11
- [ ] IEEE 802.15
- [ ] IEEE 802.16

Pregunta de Desarrollo:<br>
Explica la importancia de seguir normas y estándares de la industria al diseñar redes en una organización. Proporcione ejemplos de dos normas específicas.<br>
___Respuesta___
Es crucial para asegurar el funcionamiento, es decir la interoperabilidad, seguridad, eficacia y eficiencia de la red. ya que esto garantiza que los sistemas sean compatibles con otros y sean seguros contra amenazas.
EJEMPLOS:
IEEE802.3 (ETHERNET) Este define los estandares para redes ethernet, incluye los protocolos de comunicacion y las especificaciones fisicas para cables y conexiones.
ISO/IEC 27001 Este establece los requisitos que deben cubrirse para un sistema de gestion de seguridad de la informacion, es importante para proteger la integridad y disponibilidad de la informacion en las redes.

Pregunta de Análisis de Caso:<br>
Una empresa está planeando la expansión de su red. Describe cómo aplicarías las normas y estándares de la industria para garantizar la compatibilidad y el rendimiento.<br>
___Respuesta___
Iniciaria con la evaluacion del problema y su posterior planificacion haciendo uso de las normas IEEE 802.3 ETHERNET ya que este asegurarí a que los nuevos equipos, cables cumplen con las especificaciones de ethernet para garantizar que la red existente y la expansion que se pretende funcionen sin problemas.


## Sección 4: Sistemas Operativos (10%)

Pregunta de Comparación:<br>
Compara las características principales de dos sistemas operativos populares (por ejemplo, Windows y Linux) en el contexto de su uso en redes.<br>
___Respuesta___
Windows: ofrece una interfaz amigable y facil de usar, lo cual es ventajoso para administradores de red que sean mas de trabajo con herramientas visuales, al igual que las herramientas de administración de red están integradas en el sistema, como el Administrador de Servidores y el Panel de Control, proporcionando una configuración sencilla y accesible para usuarios menos técnicos.
LINUX: La administración y configuración a menudo se realiza a través de la línea de comandos (CLI), lo que puede tener una curva de aprendizaje empinada, pero ofrece un control más detallado y flexible.

Pregunta Abierta:<br>
Explica cómo se puede seleccionar un sistema operativo adecuado para un servidor en una organización.<br>
___Respuesta___
Podria considerar los siguientes puntos al momento de elegir:
Evaluar requisitos de aplicaciones y servicios.
Considerar la Escalabilidad y Rendimiento
Evaluar la seguridad
Analizar costos
Conocimiento y experiencia del personal, el administrador que ocupe el sistema operativo.

Pregunta de Opción Múltiple:<br>
¿Cuál de los siguientes sistemas operativos es conocido por su estabilidad y seguridad en entornos de red?<br>

- [] Windows Server
- [ ] macOS
- [X] Linux
- [ ] Android

## Sección 5: Diseño de Redes Aplicando Normas y Estándares (10%)

Pregunta de Escenario:<br>
Tienes la tarea de diseñar una red para una oficina de 100 empleados. Describe los pasos que tomarías para asegurarte de que el diseño cumpla con las normas y estándares vigentes.<br>
___Respuesta___
Primeramente se hace la recolección de requisitos, posterior a eso se realiza la recolección de requisitos, como siguiente paso la planificacion y diseño de la red, consecuente a ello podria hacer la seleccion de equipos y tecnologia, para posteriormente verificar la seguridad de la red, tambien verificar el cumplimiento de normas y estandares.
despues se implementa y se configura segun las necesidades, se realiza una documentacion y posterior a ello se hace el seguimiento mediante un monitoreo.

Pregunta de Desarrollo:<br>
Explica el impacto de no seguir normas y estándares oficiales en el diseño de una red. Proporciona ejemplos de posibles problemas.<br>
___Respuesta___
No seguir normas y estandares oficiales en el diseño de una red puede tener un impacto significativo en su funcionalidad, seguridad y mantenimiento.

DOS EJEMPLOS:
Podria presentar problemas de interoperbilidad y compatibilidad , ya que puede resultar que no sea compatible con algunos dispositivos. y problemas de conectividad.

## Sección 6: Metodologías para el Análisis, Diseño e Instalación de Redes (10%)

Pregunta de Ensayo Corto:<br>
Describe brevemente una metodología comúnmente utilizada en el análisis y diseño de redes, como la metodología OSI.<br>
___Respuesta___
OSI, es un modelo que divide el proceso de comunicacion en 7 capas distintas, cada una de las cuales representa una funcion especifica en el proceso de transmision de datos, esta la fisica, la de enlace de datos, la de red, la de transporte, sesion, presentacion y aplicacion.

Pregunta de Caso Práctico:<br>
Un cliente te ha pedido que diseñes e instales una red para su nueva sucursal. Explica cómo utilizarías una metodología para abordar este proyecto, desde el análisis de requerimientos hasta la instalación.<br>
___Respuesta___
Analisis de requerimientos, es decir, reunir la informacion, es decir, las necesidades del cliente, evaluar el entorno. despues con los requisitos ya recopilados hacer el diseño de la red, en la capa fisica, es decir, seleccionar el hardware, y despues planificar el cableado, en la capa 2 de enlace de datos proceder a configurar switches e implementar seguridad de enlace.
en la capa 3 asignaria direcciones IP, y procceder a la configuracion de ruteo. en la capa 4 de transporte, verificar y asegurar la transmision, posteriormente en la capa 5 de presentacion se realizara el formateo de datos para asegurar que los datos presenten un formato correcto, y en la capa 7 de aplicacion procederia a la configuracion de servicios.

## Sección 7: Seguridad en Redes (10%)

Pregunta de Opción Múltiple:<br>
¿Cuál de las siguientes medidas es más efectiva para proteger una red de accesos no autorizados?<br>

- [X] Cortafuegos
- [ ] Antivirus
- [ ] Actualizaciones de software
- [ ] Contraseñas seguras

Seleccione la respuesta correcta.

Pregunta de Desarrollo:<br>
Explica la importancia de implementar medidas de seguridad en una red y cómo estas pueden proteger la información confidencial de una organización.<br>
___Respuesta___
Para que usuarios extraños y externos no accedan a la red y a la informacion que en esta se comparte.
## Sección 8: Resolución de Problemas en Redes (10%)

Pregunta de Caso Práctico:<br>
Un usuario informa que no puede acceder a Internet desde su computadora. Describe los pasos que seguirías para identificar y resolver el problema.<br>
___Respuesta___
Verificar la conexion fisica del cableado, verificar el funcionamiento de router y switch, comprobar la configuracion de la red, realizar pruebas basicas como hacer ping  y por ultimo verificar la configuracion del navegador, tambien verificar la configuracion del ordenador. o bien probar el acceso desde otros dispositivos.

Pregunta de Desarrollo:<br>
Explica la importancia de tener habilidades para la resolución de problemas en redes y cómo estas pueden impactar en la eficiencia y productividad de una organización.<br>
___Respuesta___
Es imprtante para que uno mismo como usuario pueda ayudar en la resolucion del problema y no tener que acudir a algun otro tecnico de ordenador.
