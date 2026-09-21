Investigación: ¿esto ya existe? ¿quién lo dice?
> Instrucción: sustituye lo que está entre corchetes y borra las líneas que empiezan con
> "Instrucción:". Todos los enlaces deben abrir. Un enlace roto o inventado anula el
> criterio correspondiente.
Autor: [Tu nombre]
Fecha: [ ]
Ideas analizadas: ver [[ideas-proyecto]] o ideas-proyecto.md
---
Parte 1. Un ejemplo que ya existe, por cada idea
> Instrucción: busca algo parecido que alguien ya haya construido: un producto, un
> proyecto de otra universidad, un repositorio, un tutorial. Encontrar que ya existe no
> arruina tu idea; te dice desde dónde empezar.
Idea 1: [nombre]
Qué encontré: [ ]
Enlace: [ ]
Qué hace: [ ]
Por qué no resuelve mi caso: [precio, no existe en México, requiere internet, no
sirve para el lugar donde yo lo vi, etc.]
Idea 2: [nombre]
Qué encontré: [ ]
Enlace: [ ]
Qué hace: [ ]
Por qué no resuelve mi caso: [ ]
Idea 3: [nombre]
Qué encontré: [ ]
Enlace: [ ]
Qué hace: [ ]
Por qué no resuelve mi caso: [ ]
---
Parte 2. Fuentes de la idea que elegí
> Instrucción: de dos a tres fuentes, solo de la idea elegida. Todavía no se pide formato
> APA; eso llega más adelante en el curso. Lo que se pide es que distingas quién publicó
> la información y por qué le crees.
Fuente 1
Campo	Contenido
Autor u organización	[ ]
Título	[ ]
Año	[ ]
Enlace	[ ]
Tipo	[sitio institucional / nota periodística / documentación técnica / blog / video / foro]
Por qué le creo	[ ]
Qué dato me dio	[ ]
Fuente 2
Campo	Contenido
Autor u organización	[ ]
Título	[ ]
Año	[ ]
Enlace	[ ]
Tipo	[ ]
Por qué le creo	[ ]
Qué dato me dio	[ ]
Fuente 3 (opcional)
Campo	Contenido
Autor u organización	[ ]
Título	[ ]
Año	[ ]
Enlace	[ ]
Tipo	[ ]
Por qué le creo	[ ]
Qué dato me dio	[ ]
---
Parte 3. Qué haría distinto
[Cuatro o cinco líneas: qué cambia tu propuesta respecto a lo que ya existe. Puede ser el
costo, el contexto donde funciona, la forma de avisar, el material, quién lo usa.]
Parte 4. Qué me falta averiguar
[ ] [Pregunta técnica que no pude resolver hoy]
[ ] [Dato que no encontré]
[ ] [Algo que tendría que medir o probar en persona]
---
Declaración de uso de IA
Herramienta utilizada: [nombre y versión, o "No se utilizó IA generativa en esta entrega"]
Qué le pedí: [ ]
Qué modifiqué o rechacé de su respuesta, y por qué: [ ]

Investigación: ¿esto ya existe? ¿quién lo dice?
Autor: [Joshua Duque]
Fecha: 20 de septiembre de 2026
Ideas analizadas: ideas-proyecto.md
Parte 1. Un ejemplo que ya existe, por cada idea
Idea 1: Botón con sensor en la entrada de los cubículos de la biblioteca
Qué encontré: Arduino-powered real-time library seating availability system, proyecto de la Universiti Teknologi MARA.
Enlace: UiTM Institutional Repository
Qué hace: Usa Arduino UNO, sensores infrarrojos y una pantalla LCD para detectar lugares de estudio disponibles y mostrar la información en tiempo real. El proyecto fue publicado en 2023. Fuente del proyecto
Por qué no resuelve mi caso: Es un sistema de laboratorio pensado para monitorear asientos; no está instalado en los cubículos de la biblioteca de la IBERO. Además, requeriría autorización de la biblioteca, varios sensores y cableado. Para que mi idea detecte realmente el uso, convendría cambiar el botón por un sensor infrarrojo o de distancia: un botón solo funciona si cada estudiante lo presiona correctamente.
Idea 2: Aviso de humedad en una maceta
Qué encontré: Build a Circuit to Automatically Water Your Plants, proyecto educativo de Science Buddies.
Enlace: Science Buddies
Qué hace: Usa Arduino, un sensor de humedad de suelo y una bomba de agua para detectar tierra seca y regar automáticamente una planta.
Por qué no resuelve mi caso: El proyecto incluye bomba, depósito de agua, manguera y un sistema de riego automático. Mi propuesta será más sencilla: solo medirá la humedad y avisará con LEDs y buzzer cuándo conviene regar. Así será más barata, tendrá menos riesgos de fugas de agua y será adecuada para un equipo principiante. Science Buddies indica que el sistema automático requiere calibración para evitar regar de más o de menos. Fuente del proyecto
Idea 3: Alerta de ventana abierta
Qué encontré: Door Sensor with Arduino Nano Every, proyecto publicado en Arduino Project Hub.
Enlace: Arduino Project Hub
Qué hace: Usa Arduino Nano Every, un interruptor magnético tipo reed switch y un buzzer para detectar la apertura o cierre de una puerta.
Por qué no resuelve mi caso: Detecta una puerta y produce un aviso local. Mi idea debería adaptarse a una ventana concreta de mi casa y, si se quiere notificación al celular, requeriría un ESP32, conexión Wi-Fi y programación adicional. Eso aumenta la complejidad del proyecto.
Parte 2. Fuentes de la idea elegida
La idea elegida es: Aviso de humedad en una maceta.
Campo	Fuente 1
Autor u organización	Ben Finio, PhD / Science Buddies
Título	Build a Circuit to Automatically Water Your Plants
Año	Sin fecha indicada
Enlace	Science Buddies
Tipo	Sitio educativo y proyecto de ingeniería
Por qué le creo	El autor es identificado como PhD y Science Buddies publica proyectos educativos con materiales, diagramas y procedimiento de prueba.
Qué dato me dio	Que un Arduino puede leer un sensor de humedad de suelo y utilizar esa lectura para avisar o actuar; también indica que el sensor debe calibrarse para la tierra y planta específicas.


Campo	Fuente 2
Autor u organización	SparkFun Electronics
Título	SparkFun Qwiic Soil Moisture Sensor Capacitive Hookup Guide
Año	2026
Enlace	Documentación de SparkFun
Tipo	Documentación técnica
Por qué le creo	SparkFun es fabricante de componentes electrónicos y publica documentación de conexión, funcionamiento, código y calibración de sus sensores.
Qué dato me dio	Que un sensor capacitivo mide cambios de capacitancia relacionados con la humedad de la tierra; la tierra húmeda y seca producen lecturas distintas. También explica que se deben medir valores en tierra seca y en tierra saturada para fijar los umbrales del aviso.


Campo	Fuente 3
Autor u organización	Limor Fried, conocida como Ladyada / Adafruit Learning System
Título	Adafruit STEMMA Soil Sensor I2C Capacitive Moisture Sensor
Año	2018; actualización principal en 2023
Enlace	Guía de Adafruit
Tipo	Documentación técnica
Por qué le creo	Adafruit diseña y documenta productos electrónicos para aprendizaje; la guía identifica autora, fecha, funcionamiento y nivel principiante.
Qué dato me dio	Que los sensores resistivos de bajo costo pueden oxidarse por sus partes metálicas expuestas. Por ello, usaré un sensor capacitivo, ya que no deja metal expuesto en la parte que se inserta en la tierra.


Parte 3. Qué haría distinto
Mi propuesta no regará automáticamente la planta; solo dará una alerta visual y sonora cuando la tierra esté seca. Esto reduce el costo, evita tener una bomba, depósito y mangueras, y disminuye el riesgo de derramar agua cerca de la electrónica. Usaré un sensor capacitivo de humedad, un microcontrolador pequeño, LEDs y un buzzer. La carcasa y la estaca protectora se fabricarán con impresión 3D. El dispositivo estará pensado para una maceta específica de mi casa y se calibrará con esa misma tierra.
Parte 4. Qué me falta averiguar
- ¿Qué valores exactos entrega el sensor capacitivo cuando la tierra de mi maceta está seca, húmeda y demasiado mojada?
- ¿Qué nivel de humedad necesita específicamente la planta con la que se probará el prototipo?
- ¿Qué fuente de alimentación será más conveniente: cable USB, batería recargable o adaptador de corriente?
- ¿Cómo protegeré la placa y los cables de salpicaduras durante el riego?
- ¿Cuántos días debe probarse el prototipo para comprobar que el aviso coincide con el estado real de la planta?
Declaración de uso de IA
