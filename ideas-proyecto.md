Tres ideas de proyecto

Autor: [Joshua Shaiel Duque Gonzalez]
Fecha: [ 17/sep/2026]
---
Criterios de viabilidad
Una idea es viable para esta materia si cumple los cuatro criterios:
Atiende un problema concreto de mi entorno (mi casa, la IBERO, mi colonia, mi municipio), no un tema general.
Tiene una parte física fabricable con impresión 3D, corte láser o router CNC.
Usa al menos un sensor o un actuador controlado por un microcontrolador pequeño.
Lo puede construir un equipo de principiantes en unas ocho sesiones, con materiales accesibles.
---
Idea 1: [Botón con sensor en la entrada de los cubículos de la biblioteca]
Problema. [sitios de estudio llenos en la biblioteca.]
A quién le pasa. [Estudiantes de la ibero.]
Dónde lo he visto. [Biblioteca de la ibero mientras buscas un cubiculo libre y resultan llenos todos]
Cómo funcionaría. [Un boton en la entrada de los cubiculos con sensor para indicar su uso y una pantalla en la entrada con la informacion de los cubiculos accesibles y los que estan en uso]
Qué mide o detecta (sensor): 
[La presión de la pulsacion]
Qué hace con eso (actuador, aviso, pantalla): [Manda una señal que hace actualizar la informacion en la pantalla]
Qué pieza habría que fabricar: [Caja para el sensor, base para sujetarlo a una mesa y una pequeña señal luminosa fabricada con impresión 3D o corte láser. ]
---
Idea 2: [Aviso de humedad en una maseta]
Problema. [Aveces se le da agua de mas a una planta o no se le da la suficiente]
A quién le pasa. [Muy a menudo a mi]
Dónde lo he visto. [En mi casa al momento de regar mis plantas]
Cómo funcionaría. [El dispositivo indicaria si la plantab necesita humedad o si aun tiene la necesaria]
Qué mide o detecta (sensor): [La humedad de la tierra]
Qué hace con eso (actuador, aviso, pantalla): [LED amarillo o rojo y buzzer; opcionalmente, una pantalla pequeña OLED. ]
Qué pieza habría que fabricar: [Estaca protectora para el sensor, carcasa para Arduino o ESP32 y soporte para la pantalla, fabricados con impresión 3D. ]
---
Idea 3: [Alerta de ventana o abierta]
Problema. [Muchas veces al salir de casa dejamos alguna ventana abierta sin darnos cuenta]
A quién le pasa. [A las personas en mi casa]
Dónde lo he visto. [En mi casa o casas ajenas]
Cómo funcionaría.[El sensor detectaria si la ventana esta cerrada, si esta abierta al salir mandara una señal a mi celular]
Qué mide o detecta (sensor): [Si la ventana al salir esta cerrada]
Qué hace con eso (actuador, aviso, pantalla): [Buzzer y LED rojo; opcionalmente, una pantalla que muestre “Ventana abierta”.]
Qué pieza habría que fabricar: [ Carcasa para el microcontrolador y soporte para colocar el sensor magnético en el marco, fabricados con impresión 3D o corte láser.]
---
Criterio	Idea 1: Cubículos	Idea 2: Humedad en maceta	Idea 3: Ventana abierta
Problema concreto de mi entorno	Sí	Sí	Sí
Parte física fabricable	Sí	Sí	Sí
Sensor o actuador	Parcial	Sí	Sí
Construible en ocho sesiones por principiantes	Parcial	Sí	Parcial
Qué tan seguro estoy de lo anterior	Medio	Alto	Medio
Mi elección	No	Sí	No


Idea elegida: Aviso de humedad en una maceta.
Por qué. Es la alternativa más accesible porque utiliza pocos componentes: un microcontrolador pequeño, sensor capacitivo de humedad, LEDs, buzzer y una carcasa impresa en 3D. El problema ocurre directamente en mi casa y puedo probar el prototipo con mis propias plantas. También se puede construir y calibrar en ocho sesiones sin requerir conexión a internet, aplicación para celular ni instalación dentro de la biblioteca.
Qué todavía no sé. Necesito probar qué nivel de humedad debe considerarse “tierra seca” para cada planta, porque no todas requieren la misma cantidad de agua. También debo comprobar que el sensor no se dañe con el riego, decidir cómo alimentar el dispositivo y diseñar una carcasa que proteja el microcontrolador.
Declaración de uso de IA: Le pedí a chat gpt que me ayudara a saber que partes físicas utilizaría según mis ideas porque desconozco de lo que se tendria que utilizar.  
