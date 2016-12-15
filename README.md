# Probando Circuit Playground de Adafruit


![Circuit Playground](https://cdn-learn.adafruit.com/assets/assets/000/031/961/medium800/circuit_playground_3000_front_lit_ORIG.jpg?1461687520)

Se trata de una placa compatible con arduino Leonardo (usa el mismo micro ATmega32u4)

## Características

* ATmega32u4
* Funciona a 3.3V
* Micro-USB

y una enorme cantidad de periféricos incluidos

* 10 x mini NeoPixels (RGBs) (conectados al pin #17)
* 1 x Sensor de movimiento (LIS3DH triple-axis accelerometer with tap detection, free-fall detection)
* 1 x Sensor de Temperatura (thermistor Murata NCP15XH103F03RC) #A0
* 1 x Sensor de luz (phototransistor ALS-PT19) #A5
* 1 x Sensor de sonido (MEMS microphone) #A4
* 1 x Mini altavoz (magnetic buzzer) #5
* 2 x Pulsadores, #4 left and # 19 right
* 1 x Conmutador #21
* 8 x Conectores de pinzas con pines de entrada salida
  * I2C (#2 y #3), UART (#0 y #1), and 4 pines para entradas analógicas o salidas PWM (#6, #9, #10 y #12)
  * Los 8 conectores se pueden usar como sensores capacitivos
* LED verde de encendido
* LED en la patilla  "#13" LED for basic blinking
* Pulsador de Reset

## Instalación

Añadimos la placa al entorno

    https://adafruit.github.io/arduino-board-index/package_adafruit_index.json

Y para instalar la librería basta con buscar Circuit Playground en el gestor de librería

Si tenemos problemas para subir el programa:

  sudo apt remove modemmanager

## Referencia


[Aprende a usar Circuit Playground](https://learn.adafruit.com/introducing-circuit-playground?view=all)

[Página de Circuit Playground en bricogeek](http://tienda.bricogeek.com/modelos-arduino/869-adafruit-circuit-playground-developer-edition.html)
