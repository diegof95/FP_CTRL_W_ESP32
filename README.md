# FP CTRL W ESP32
Proyecto final realizado para el curso de Diseño y Construcción de Dispositivos Electrónicos, perteneciente a la carrera de Ingeniería en Electrónica en Universidad Galileo.  Este proyecto representa mi acercamiento al Internet de las Cosas (IoT), marcando mi primer diseño y ensamblaje de un dispositivo de este tipo en Guatemala.


# ¿Qué podemos hacer?

Desplegar información por medio de un web server o dashboard MQTT por medio de conexión WiFi. Obtener mediciones de temperatura, humedad y presión atmosférica a través del sensor BME280,  controlar cargas AC por medio del relé y una tira led de tipo NeoPixel por medio de la programación y un Buzzer para emitir algún sonido.

# Pinout


### Buzzer
Nombre | GPIO 
--- | --- 
DATA | 12
VDD | 3V3
VSS | GND

### Relé
Nombre | GPIO 
--- | --- 
DATA | 13
VDD | 5V
VSS | GND

### Tira led - WS2812B
Nombre | GPIO 
--- | --- 
DATA | 14
VDD | 5V
VSS | GND

### Sensor de temperatura, humedad y presión - Comunicación I2C (Pendiente de funcionamiento)
BME280 | ESP32
--- | ---
SDI 3 | SDA 21
SCK 4 |  SCL 22 

# Licencia

Hardware License: CERN Open Hardware License Version 2

Software License: GNU General Public License Version 3.0

Documentation License: CC BY 4.0 International

![](/img/oshw_facts.svg)

# Contacto e información adicional

Autor: Diego Iboy (diego.iboy@galileo.edu)

Vídeo del funcionamiento: https://youtu.be/rUuOkdmCc4Q
