# Flow 7 Estacion climatica
 Usando el ESP32CAM se detectan las variavles de temperatura y humedad con el sensor DHT11 y se comunica a Node Red por MQTT

## Creado por :Ramsés Ortiz Castro
Fecha: 18 de agosto del 2022

*[Se usaron de referencia el repositorio de     CodigoIoT](https://github.com/codigo-iot/publicar-strings-json-mqtt-nodemcu-wifi/blob/main/nodemcu-mqtt-json/nodemcu-mqtt-json.ino)
para el codigo que va en la ESP32CAM

Se cambiaron los valores de:
Nombre de red inalambrica
Contraseña de red
IP para el broker local
Tema de publicación en broker local y luego publico
Tema de suscripción de broker local y de publico 

El circuito para probar el correcto funcionamiento del sensor DHT11 se consiguio de:
[geekfactory](https://www.geekfactory.mx/tienda/sensores/dht11-sensor-de-humedad-y-temperatura/)

A su vez lo redirecciona a la bilioteca de AdaFruit


Para el llamado de la API Openweathermap se tuvo dificultad con la sintaxis pero usamos la documentación de la misma pagina [Current air pollution data](https://openweathermap.org/api/air-pollution#current)

