
# Ficha sobre evaluación de usabilidad

## Qué es la usabilidad?
La usabilidad hace referencia a cómo usamos las cosas, a la facilidad con la que las utilizamos y a si nos permiten hacer lo que necesitamos o deseamos hacer.  Esta se cumple cuando el diseño es intuitivo, eficiente, satisfactorio y accesible para todo tipo de usuarios.
La evaluación de la usabilidad en la ingeniería de software es un proceso que se realiza a lo largo del desarrollo para conocer el nivel de usabilidad del producto y determinar las mejoras necesarias. 
Es fundamental porque afecta directamente la satisfacción del usuario, la eficiencia y la productividad. 

## Principios de Usabilidad
### principios de Jacob Nilsen 
1. Visibilidad del estado del sistema:
Requiere mantener a los usuarios informados sobre lo que está sucediendo en el sistema, mediante indicadores claros y mensajes apropiados. El usuario sabe exactamente qué está pasando, en todo momento. 
Ejemplo: al rellenar un formulario, el usuario sabe si el envío fue procesado y cuándo se lo contactara.
2. Relación entre el sistema y el mundo real
Implica utilizar un lenguaje y convenciones familiares a los usuarios, con base en su conocimiento previo. Es decir, la información está disponible en un orden lógico y en un lenguaje convencional.
Ejemplo: eliminar lenguaje técnico en las páginas dedicadas a los consumidores finales.
3. Control y libertad del usuario
Permitir a los usuarios retroceder y salir de situaciones no deseadas, así como ofrecer un camino claro para completar tareas. Esto brinda oportunidad a que los usuarios pueden rehacer o deshacer sus pasos al navegar. 
Ejemplo: poner un botón de «Ir atrás» en una página de producto.
4. Estándares y consistencia
Implica utilizar convenciones de diseño y patrones de interacción comunes en la industria, para que los usuarios se sientan familiarizados. Cada término o situación está utilizado de manera unívoca.
Ejemplo: hacer que todos los botones de «Seguir» tengan la misma apariencia.
5. Reconocimiento en vez de recuerdo
Es necesario reducir la carga cognitiva de los usuarios, permitiéndoles identificar objetos y opciones en lugar de requerir que los recuerden. Esto significa que los usuarios no deban memorizar continuamente lo que necesitan hacer, ya que tienen sus opciones visibles. 
Ejemplo: instalar botones con iconos fácilmente reconocibles.
6. Prevención de errores
Hay que evitar que los usuarios cometan errores mediante mensajes claros y elementos de diseños preventivos. 
Ejemplo: añades un mensaje de «Confirmar envío de los datos» antes de que el usuario pase a la etapa siguiente
7. Flexibilidad y eficiencia en el uso
Debes permitir que los usuarios personalicen y adapten la interfaz a sus necesidades, así como ofrecer atajos y funciones avanzadas para usuarios con mayor experiencia. Esto significa que tus distintos tipos de usuarios encuentran un uso adecuado a sus necesidades.
Ejemplo: tienes opciones visibles para los usuarios nuevos, a la vez que cuentas con atajos para los más experimentados.
8. Diseño minimalista y estético
Prefiere utilizar un diseño atractivo, equilibrado y sencillo que no distraiga de la tarea principal. Cada pieza de información es relevante.
Ejemplo: suprimir los botones que son raramente utilizados, con el fin de que las opciones más importantes aparezcan de manera clara.
9. Ayudar a los usuarios a reconocer, diagnosticar y recuperarse de sus errores. Inevitablemente, el usuario se encontrará con un error. Cuando esto suceda, los mensajes de error deben expresarse en un lenguaje sencillo (humano), que indique con precisión el problema, su posible origen y ofrecer una solución de manera constructiva.
Ejemplo: Si un usuario introduce mal su contraseña, el sistema debería mostrar un mensaje como: "La contraseña es incorrecta. Inténtalo de nuevo" en lugar de solo "Error".
10. Ayuda y documentación
Proporciona ayuda y documentación clara y útil que los usuarios puedan buscar fácilmente. Como parte de esto, indicas los errores de manera comprensible, sin lenguaje técnico y con una solución rápida. 
Ejemplo: Un software de diseño gráfico podría incluir un apartado de "Ayuda" que ofrezca tutoriales sobre cómo utilizar las herramientas básicas para los nuevos usuarios.


![Principios de usabilidad](/principicos de usabilidad / principicos de usabilidad.JPG "PRINCIPIOS")

## Tipos de evaluación
### 1. Métodos de Evaluación por Inspección
En estos métodos, los expertos en usabilidad evalúan la interfaz sin la intervención directa de los usuarios. Se basan en principios de diseño y heurísticas.
+ Evaluación heurística: Un grupo de expertos revisa la interfaz en función de principios de usabilidad (heurísticas) para detectar problemas.
+ Revisión de expertos (Expert Review): Un evaluador especializado revisa la interfaz, identificando problemas sin un conjunto formal de reglas.
+ Inspección cognitiva: Los expertos simulan ser usuarios y evalúan cómo completarían tareas específicas, identificando barreras en la interfaz.
+ Walkthrough de usabilidad:
  + Walkthrough cognitivo: El evaluador recorre cada paso que un usuario tomaría al realizar una tarea, analizando los problemas potenciales.
  + Walkthrough plural: Un grupo de evaluadores recorre conjuntamente las tareas, debatiendo y descubriendo problemas de usabilidad.


### 2. Métodos de Evaluación por Indagación
Estos métodos implican obtener información directamente de los usuarios a través de preguntas, observación o diálogo, para comprender su experiencia y percepciones.
+ Observación de campo: Los usuarios son observados en su entorno de trabajo real, sin interferencia del evaluador, para ver cómo interactúan con el sistema.
+ Entrevistas: Los usuarios responden preguntas sobre sus expectativas y experiencias, proporcionando información detallada sobre su uso del sistema.
+ Cuestionarios y encuestas (Surveys): Se recopilan respuestas estructuradas de los usuarios sobre su experiencia de uso.
+ Grupo de discusión dirigido (Focus Group): Un moderador guía una discusión entre varios usuarios para recoger opiniones y percepciones sobre el sistema.
+ Grabación del uso (Logging): Se registra automáticamente el comportamiento de los usuarios (clics, tiempo, navegación) para analizar cómo interactúan con la interfaz.


### 3. Métodos de Evaluación por Test
Estos métodos implican que los usuarios interactúen con el sistema, y los evaluadores miden su desempeño o registran sus opiniones y comportamientos.
+ Pruebas de usabilidad (User Testing): Los usuarios realizan tareas en el sistema, mientras se registran métricas de éxito, tiempo y errores.
+ Pensando en voz alta (Thinking Aloud): Los usuarios verbalizan sus pensamientos mientras realizan tareas, lo que permite entender su razonamiento.
+ Card Sorting: El card sorting o clasificación de tarjetas es una prueba que consiste en escribir los temas clave en diferentes tarjetas (que pueden ser físicas o digitales). A continuación, se pide a los participantes que clasifiquen las tarjetas en grupos que tengan sentido para ellos. Al preguntar a los participantes sobre sus decisiones, los equipos de producto comprenden las expectativas de los usuarios sobre cómo debe organizarse la información.
+ Pruebas de guerrilla: Se realizan pruebas rápidas y económicas en entornos informales, como cafeterías o eventos, con usuarios aleatorios para obtener retroalimentación rápida y detectar problemas iniciales de usabilidad.
+ Tree Testing: El testing es una prueba que sirve para determinar si los usuarios pueden encontrar lo que buscan en la jerarquía de un sitio web. Consiste en mostrar a los participantes una versión solo de texto de la estructura de navegación de un sitio y preguntarles a dónde irían para completar ciertas tareas (como darse de baja de correos electrónicos)
+ Prueba de los cinco segundos: Esta prueba consiste en mostrar a los participantes durante solo cinco segundos un elemento clave de un sitio web, como el esquema de una página de inicio o un logotipo. A continuación, los participantes deben responder a preguntas sobre qué recuerdan, lo que revela sus primeras impresiones sobre el diseño. Las pruebas de los cinco segundos son excelentes para determinar si la introducción de la página de inicio 
