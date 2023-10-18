# EVSE_Business_Hardware
## Introducción
En este repo se almacenará el desarrollo del hardware correspondiente al cargador de 22 kW business.

# Dependencias
Se debe instalar la siguiente librería para tener el símbolo del microcontrolador ESP32 WROOM 32E -> https://github.com/espressif/kicad-libraries
* Una vez en el repo, ir a "tags" y seleccionar la versión **2.0.3**

  ![image](https://github.com/Vulletic/EVSE_Business_Hardware/assets/59293767/444a2766-6da2-4ebd-a2f7-7d186f62cf02)

* Luego, descargar el archivo **espressif-kicad-addon.zip**

  ![image](https://github.com/Vulletic/EVSE_Business_Hardware/assets/59293767/988467ae-311c-4c4e-ba84-f5375b3d09ca)

* Posicionar este archivo en la carpeta Kicad -> 7.0 -> plugins.

* A continuación, abrir el **Administracion de complementos y contenido**

 ![image](https://github.com/Vulletic/EVSE_Business_Hardware/assets/59293767/b2ce2fea-4dcd-4479-b48c-b33e11e9d28a)

* Presionar **Instalar desde un archivo**

![image](https://github.com/Vulletic/EVSE_Business_Hardware/assets/59293767/0f6c0195-3e4a-4b01-bc36-d76ef24ec654)

* Por último, para verificar la instalación, ingresar a la pestaña **Instalado** y debe verse así:

  ![image](https://github.com/Vulletic/EVSE_Business_Hardware/assets/59293767/629c6f57-d78e-4627-b036-8a820263d9b4)




## Prestaciones del cargador:
* Comunicación CP con el vehículo.
* Leds RGB para indicar el estado del cargador.
* Medición de potencia consumida.
* Posibilidad de conectar sensor de corriente de fuga de 6mA CC.
* Comunicación OCPP con servidor.
* Pantalla TFT Nextion 4.3".
* Conectividad WiFi.
* Conectividad 3G/4G y Ethernet como opcionales. 
 
