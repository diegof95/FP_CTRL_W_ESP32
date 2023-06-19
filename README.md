# FP CTRL W ESP32
Proyecto final realizado para el curso de Diseño y Construcción de Dispositivos Electrónicos, perteneciente a la carrera de Ingeniería en Electrónica en Universidad Galileo.  Este proyecto representa mi acercamiento al Internet de las Cosas (IoT), marcando mi primer diseño y ensamblaje de un dispositivo de este tipo en Guatemala.


## Pinout


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

### Temperatura, humedad y presión atmosférica - Comunicación I2C
ESP32 | BME280
--- | ---
SCL 21 | SCK 4
SDA 22 | SDI 3
