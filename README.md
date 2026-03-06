# IOT Beacon Web

Plataforma web encargada de **visualizar los datos enviados por la aplicación Android** tras detectar beacons emitidos por un sensor Arduino.

Los datos se almacenan en una base de datos **MySQL** y se muestran en una interfaz web para su consulta.

## Proyecto relacionado

Sistema IoT basado en beacons compuesto por: Arduino Sensor → Android App → Web Dashboard

Este repositorio forma parte de un proyecto completo compuesto por tres partes:

- Arduino Beacon Sensor → https://github.com/holiwiiss/iot-beacon-arduino
- Android Scanner App → https://github.com/holiwiiss/iot-beacon-android-studio
- Web Monitoring Platform → https://github.com/TUUSUARIO/beacon-monitoring-web

## Tecnologías

- HTML
- CSS
- JavaScript
- PHP
- MySQL
- XAMPP

## Instalación

1. Instalar **XAMPP**
2. En el panel de control de **XAMPP**, iniciar:
   - Apache
   - MySQL
3. Copiar el proyecto dentro del directorio `xampp/htdocs`, al que se puede acceder pulsando el botón *explorer* en el panel de control de **XAMPP**.
4. Importar la base de datos, que se puede encontrar en este repositorio en la ruta: `doc/sprint0_pbiometria`. Para ello:
    1. Abrir **phpMyAdmin** desde el botón *Admin* de MySQL.
    2. Crear una nueva base de datos
    3. Importar el archivo SQL

## Acceso

Una vez configurado el servidor, la web puede abrirse desde cualquier navegador con la siguiente URL: `http://localhost/Sprint_0Web/src/app/sensores/`, siempre que **Apache y MySQL estén activos** en XAMPP.

Si el sistema está funcionando correctamente aparecerán datos almacenados en la base de datos.

Para visualizar nuevos datos enviados desde la aplicación Android basta con **recargar la página**.

