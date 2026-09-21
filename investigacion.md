
Investigación: ¿esto ya existe? ¿quién lo dice?
Autor: [Joshua Duque]

Fecha: 20 de septiembre de 2026

Ideas analizadas: ideas-proyecto.md

Parte 1. Un ejemplo que ya existe, por cada idea

Idea 1: Botón con sensor en la entrada de los cubículos de la biblioteca

Qué encontré: Arduino-powered real-time library seating availability system, proyecto de la Universiti Teknologi MARA.

Enlace:
 https://ir.uitm.edu.my/id/eprint/133402/
Qué hace: Usa Arduino UNO, sensores infrarrojos y una pantalla LCD para detectar lugares de estudio disponibles y mostrar la información en tiempo real.

Por qué no resuelve mi caso: Es un sistema de laboratorio pensado para monitorear asientos; no está instalado en los cubículos de la biblioteca de la IBERO. 
Requeriría autorización de la biblioteca, varios sensores y cableado. Para detectar realmente el uso, convendría cambiar el botón por un sensor infrarrojo o de distancia, porque un botón depende de que cada estudiante lo presione.


Idea 2: Aviso de humedad en una maceta
Qué encontré: Build a Circuit to Automatically Water Your Plants, proyecto educativo de Science Buddies.

Enlace:
 https://www.sciencebuddies.org/science-fair-projects/project-ideas/PlantBio_p055/plant-biology/arduino-automatic-plant-watering
 
Qué hace: Usa Arduino, un sensor de humedad de suelo y una bomba de agua para detectar tierra seca y regar automáticamente una planta.

Por qué no resuelve mi caso: El proyecto incluye bomba, depósito de agua, manguera y riego automático. Mi propuesta solo medirá la humedad y avisará con LEDs y buzzer cuándo conviene regar. Así será más sencilla, barata y segura para un equipo principiante.

Idea 3: Alerta de ventana abierta

Qué encontré: Door Sensor with Arduino Nano Every, publicado en Arduino Project Hub.
Enlace:
 https://projecthub.arduino.cc/enriquekirkpatrickc/door-sensor-with-arduino-nano-every-520189
 
Qué hace: Usa Arduino Nano Every, un interruptor magnético tipo reed switch y un buzzer para detectar la apertura o cierre de una puerta.

Por qué no resuelve mi caso: Detecta una puerta y produce un aviso local. Mi idea debe adaptarse a una ventana concreta de mi casa y, para enviar una señal al celular, requeriría un ESP32, Wi-Fi y programación adicional.

Parte 2. Fuentes de la idea elegida

Idea elegida: Aviso de humedad en una maceta.

Fuente 1
Autor u organización: Ben Finio, PhD / Science Buddies

Título: Build a Circuit to Automatically Water Your Plants

Año: Sin fecha indicada

Enlace:
 https://www.sciencebuddies.org/science-fair-projects/project-ideas/PlantBio_p055/plant-biology/arduino-automatic-plant-watering
 
Tipo: Sitio educativo y proyecto de ingeniería.

Por qué le creo: Science Buddies publica proyectos educativos con materiales, diagramas y procedimientos de prueba; el autor está identificado como PhD.

Qué dato me dio: Un Arduino puede leer un sensor de humedad de suelo y usar esa lectura para avisar o actuar. También se debe calibrar el sensor para la tierra y la planta específicas.

Fuente 2

Autor u organización: SparkFun Electronics

Título: SparkFun Qwiic Soil Moisture Sensor Capacitive Hookup Guide

Año: 2026

Enlace:
 https://docs.sparkfun.com/SparkFun_Capacitive_Soil_Moisture_Sensor_CY8CMBR3102/single_page/
 
Tipo: Documentación técnica.

Por qué le creo: SparkFun fabrica componentes electrónicos y publica documentación sobre conexión, programación y calibración de sus sensores.

Qué dato me dio: El sensor capacitivo detecta cambios relacionados con la humedad de la tierra. Se deben obtener mediciones con tierra seca y tierra saturada para definir los valores que activarán el aviso.

Fuente 3
Autor u organización: Limor Fried, conocida como Ladyada / Adafruit Learning System

Título: Adafruit STEMMA Soil Sensor I2C Capacitive Moisture Sensor

Año: 2018; actualización principal en 2023

Enlace:
 https://learn.adafruit.com/adafruit-stemma-soil-sensor-i2c-capacitive-moisture-sensor?view=all

Tipo: Documentación técnica.

Por qué le creo: Adafruit diseña y documenta productos electrónicos para aprendizaje; la guía identifica autora, fecha y funcionamiento.

Qué dato me dio: Los sensores resistivos pueden oxidarse por sus partes metálicas expuestas. Por eso usaré un sensor capacitivo, que es más adecuado para dejarse insertado en la tierra.

Parte 3. Qué haría distinto

Mi propuesta no regará automáticamente la planta; solo dará una alerta visual y sonora cuando la tierra esté seca. Esto reduce el costo, evita tener una bomba, depósito y mangueras, y disminuye el riesgo de derramar agua cerca de la electrónica. Usaré un sensor capacitivo de humedad, un microcontrolador pequeño, LEDs y un buzzer. La carcasa y la estaca protectora se fabricarán con impresión 3D. El dispositivo estará pensado para una maceta específica de mi casa y se calibrará con esa misma tierra.

Parte 4. Qué me falta averiguar

- ¿Qué valores exactos entrega el sensor capacitivo cuando la tierra de mi maceta está seca, húmeda y demasiado mojada?
- ¿Qué nivel de humedad necesita específicamente la planta con la que se probará el prototipo?
- ¿Qué fuente de alimentación será más conveniente: cable USB, batería recargable o adaptador de corriente?
- ¿Cómo protegeré la placa y los cables de salpicaduras durante el riego?
- ¿Cuántos días debe probarse el prototipo para comprobar que el aviso coincide con el estado real de la planta?

- Declaración de IA: le pedí a chat gpt que me ayudara criticando mis ideas para ver que me falto averiguar o puntos que no tome en cuenta y que me ayudara con la formalidad de mi redacción para que se vea mas presentable.
