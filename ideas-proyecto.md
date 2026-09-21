Propuestas de proyecto
Autor: Joshua Shaiel Duque González
Fecha: 17 de septiembre de 2026  
Idea 1: Sistema de disponibilidad de cubículos en la biblioteca
Problema
En la biblioteca de la IBERO, los espacios de estudio y cubículos suelen estar ocupados. Los estudiantes tienen que recorrer la biblioteca para saber si hay un cubículo disponible.
A quién le pasa
A los estudiantes de la IBERO que buscan un cubículo libre para estudiar.
Dónde lo he visto
En la biblioteca de la IBERO, cuando busco un cubículo libre y descubro que todos están ocupados.
Cómo funcionaría
Cada cubículo tendría un botón para que el estudiante indique que está usando el espacio. Una pantalla en la entrada mostraría cuáles cubículos están disponibles y cuáles están en uso.
Qué mide o detecta
La presión al presionar el botón.
Qué hace con eso
Envía una señal al microcontrolador para actualizar en la pantalla el estado del cubículo.
Qué pieza habría que fabricar
Caja para el botón, soporte para instalarlo en cada cubículo y señal luminosa fabricada con impresión 3D o corte láser.
Idea 2: Aviso de humedad en una maceta
Problema
A veces se riega demasiado una planta o no se le da suficiente agua. Esto puede afectar su crecimiento o hacer que se seque.
A quién le pasa
A mí, al cuidar las plantas de mi casa.
Dónde lo he visto
En mi casa, al momento de regar mis plantas.
Cómo funcionaría
El dispositivo indicaría si la planta necesita agua o si la tierra todavía tiene la humedad suficiente.
Qué mide o detecta
La humedad de la tierra.
Qué hace con eso
Enciende un LED amarillo o rojo y activa un buzzer cuando la tierra está seca. Opcionalmente, puede mostrar el nivel de humedad en una pantalla OLED.
Qué pieza habría que fabricar
Estaca protectora para el sensor, carcasa para Arduino o ESP32 y soporte para la pantalla, fabricados con impresión 3D.
Idea 3: Alerta de ventana abierta
Problema
Muchas veces, al salir de casa, se puede quedar una ventana abierta sin que nadie se dé cuenta.
A quién le pasa
A las personas que viven en mi casa.
Dónde lo he visto
En mi casa, al salir y darme cuenta de que una ventana había quedado abierta.
Cómo funcionaría
Un sensor detectaría si la ventana está cerrada. Si está abierta al momento de salir, el sistema activaría una alerta; posteriormente podría enviar un aviso al celular.
Qué mide o detecta
Si la ventana está abierta o cerrada mediante la separación entre un imán y un sensor magnético.
Qué hace con eso
Activa un buzzer y un LED rojo. Opcionalmente, muestra el mensaje “Ventana abierta” en una pantalla.
Qué pieza habría que fabricar
Carcasa para el microcontrolador y soporte para colocar el sensor magnético en el marco, fabricados con impresión 3D o corte láser.
Tabla de viabilidad
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
Declaración de uso de IA: Le pedí a chat gpt que me ayudara a saber que partes físicas utilizaría según mis ideas porque desconozco de lo que se tendria que utilizar y le pedi que revisara las faltas de ortografia.  
