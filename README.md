# Actividad-4
Actividad de micros, relacionada con mediapipe y la secuencia de bombillos led.

Esta actividad basa su funcionamiento en tres etapas:

1. Reconocimiento de gestos por medio de camara web
  En esta etapa se realiza un programa por medio de html, el cual se encarga de hacer que la      camara web registre en tiempo real el video, y en el analice y detecte los gestos               configurados. la librería MediaPipe detecta los 21 puntos clave de la mano para poder           determinar que gesto se está realizando y a partir de eso generar el funcionamiento necesario   de los leds.

2. Transmisión por red.
   La comunicación entre la página html y la tarjeta Esp-32 se da por medio de red wifi, donde     se le proposition la información de la red wifi em el código y esta responde con la             dirección IP de la esp, la cual se ingresa en el código de la página html para poder lograr     una conexión exitosa para la transmisión de información.

3. Control de Hadware
   La ESP actúa como un servidor local, donde analiza y define que acción realizar a partir de     los gestos registrados en camara, a partir de ello, genera en encendido o apagado de los        leds segun la configuracion y el gesto detectado.

   video: https://drive.google.com/file/d/1EJ5STCSctIWHh1vtKEMAkTKSFR2Rr0V-/view?usp=sharing
