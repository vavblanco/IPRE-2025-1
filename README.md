# Proyecto Suelos Urbanos
Investigación para Pregrado Invierno 2025 

### Contexto Biológico
El urbanismo y la sustentabilidad son actualmente factores clave para promover el bienestar en nuestras ciudades. En este contexto, el diseño de proyectos públicos debe incorporar un enfoque basado en la naturaleza, que permita enfrentar desafíos como el calor extremo, la escasez hídrica y la pérdida de biodiversidad. Para lograrlo, es fundamental contar con herramientas tecnológicas accesibles y de bajo costo que faciliten el monitoreo ambiental en tiempo real, contribuyendo a la toma de decisiones más informadas y sostenibles.

### Objetivo
Implementar un sistema de medición de humedad y temperatura utilizando el entorno Arduino, con el fin de recopilar datos ambientales en distintas zonas del campus San Joaquín.

#### Posibles Sensores/Módulos a Usar
+ Sensor de Temperatura NTC Subterráneo
  - Motivo: Registrar temperatura del suelo.
  - Precio Referencial: $1.641 [(altronics.cl)](https://altronics.cl/electronics-products/accesorios-arduino/temp-3950-ntc); $4.290 [(Mercado Libre)](https://www.mercadolibre.cl/kit-de-modulo-de-sensor-de-temperatura-ds18b20-para-arduino/up/MLCU322909051)
  - Datasheet: [DS18B20](https://www.analog.com/media/en/technical-documentation/data-sheets/ds18b20.pdf)
+ Sensor de Humedad Subterránea
  - Motivo: Registrar humedad del suelo.
  - Precio Referencial: $2.569  [(altronics.cl)](https://altronics.cl/sensor-humedad-suelo-yl-69); $2.490 [(Mercado Libre)](https://articulo.mercadolibre.cl/MLC-435163707-modulo-sensor-humedad-suelo-yl-38-yl-69-arduino-pic-max--_JM)
  - Datasheet: [YL-69](https://www.electronicoscaldas.com/datasheet/YL-69-HL-69.pdf)
+ Sensor de Dióxido de Carbono CCS811
  - Motivo: Medir concentraciones de eCO2 y TVOC (Ver si usar o no). 
  - Precio Referencial:
  - Datasheet: [CCS811](https://cdn.sparkfun.com/assets/learn_tutorials/1/4/3/CCS811_Datasheet-DS000459.pdf)
+ Módulo Reloj de Tiempo DS3231 
  - Motivo: Registrar la hora exacta y fecha de cada medición.
  - Precio Referencial: $4.385 [(altronics.cl)](https://altronics.cl/modulo-reloj-tiempo-real-rtc-DS3231-AT24C32?search=Reloj%20de%20Tiempo); $5.490 [(Mercado Libre)](https://articulo.mercadolibre.cl/MLC-435662100-modulo-i2c-rtc-ds3231-con-bateria-y-eeprom-arduino-max--_JM)
  - Datasheet: [DS3231](https://www.analog.com/media/en/technical-documentation/data-sheets/ds3231.pdf)
+ Módulo Micro SD 74LVC125A
  - Motivo: Almacenar la información de cada medición de forma local (Discutible).
  - Precio Referencial: $1.858 [(altronics.cl)](https://altronics.cl/modulo-micro-sd-01); $3.000 [(Mercado Libre)](https://articulo.mercadolibre.cl/MLC-438595261-modulo-lector-tarjeta-micro-sd-datalogger-arduino-max--_JM)
  - Datasheet: [74LVC125A](https://assets.nexperia.com/documents/data-sheet/74LVC125A.pdf)
+ Módulo Wifi ESP8266 ó ESP32
  - Motivo: Almacenar la información de cada medición de forma remota (Discutible).
  - Precio Referencial: $5.109 [(altronics.cl - ESP8266)](https://altronics.cl/electronics-products/accesorios-arduino/wifi-module-esp8266) y $7.890 [(altronics.cl - ESP32)](https://altronics.cl/tarjeta-esp32-microusb); $6.151 [(Mercado Libre -ESP8266)](https://www.mercadolibre.cl/modulo-wifi-ch340-v3-nodemcu-esp8266-para-arduino-wi-fi/p/MLC33303211) y $7.283 [(Mercado Libre - ESP32)](https://www.mercadolibre.cl/tarjeta-de-desarrollo-esp32-wifi-bluetooth-30-pines/up/MLCU14803867) 
  - Datasheet: [ESP8266](https://www.espressif.com/sites/default/files/documentation/esp8266-technical_reference_en.pdf), [ESP32](https://www.espressif.com/sites/default/files/documentation/esp32_datasheet_en.pdf)
 
