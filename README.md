# Nombre del proyecto Soportefresh-DI-

## Visión  del proyecto
El objetivo principal de este proyecto es diseñar y desarrollar un dispositivo innovador que mantenga fresco a sus usuarios en diversas situaciones cotidianas y ofrezca capacidades para monitorear elementos generales del cuerpo y del ambiente, proporcionando una experiencia de comodidad y bienestar en la vida diaria. El mercado actual cuenta con varios dispositivos que ofrecen funciones de refrigeración personal, monitoreo corporal y ambiental, aunque ninguno integra todas estas capacidades en un solo dispositivo portátil. Este dispositivo beneficiará a una amplia gama de personas:

  -Profesionales: Trabajadores de oficinas y profesionales de campo que buscan mantenerse frescos y monitorear su salud y el ambiente.
  
  -Deportistas: Corredores, ciclistas, excursionistas y campistas que necesitan mantenerse frescos y monitorear su estado físico y las condiciones ambientales.
  
  -Personas con necesidades médicas especiales: Aquellos con problemas de regulación de la temperatura o condiciones de salud crónicas que requieren monitoreo constante.
  
  -Público en general: Personas en climas cálidos y usuarios de tecnología de bienestar interesados en monitorear su salud y el entorno.

## Integrantes
- Jesus Fernando Gonzalez Pedroza
- Edna Nazaret Martinez Prado

## Software Empleado

<div align="center">

| ID | Software    | Versión | Tipo                                                    |
|----|-------------|---------|---------------------------------------------------------|
| 01 | Github      | N/A     | Plataforma de alojamiento (licencia libre)              |
| 02 | Arduino IDE | 2.3.2   | Entorno de desarrollo (licencia libre)                  |
| 03 | Krita       | 4.4.3   | Software de pintura digital e ilustración - Licencia pública general GNU (versión 3 o posterior)              |
| 04 | Tinkercad   | N/A     | Herramienta para crear modelos tridimensionales - (Licencia libre)    |
| 05 | Paint       | 22H2    | Programa editor de imágenes desarrollado por Microsoft - (Licencia libre)    |

</div>

## Software librerias
<div align="center">

| ID | Libreria    | Versión | Por/Para                                                     |
|----|-------------|---------|---------------------------------------------------------|
| 01 | DHT sensor library      | 1.4.6    | Adafruit/Sensor de temperatura y humedad dht11             |

</div>


## Hardware Empleado

<div align="center">

  | Nombre                         | Imagen                                                                                       | Descripción                                     | Cantidad |
  |--------------------------------|----------------------------------------------------------------------------------------------|-------------------------------------------------|----------|
  | ESP32                          | ![Imagen1](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/esp32.jpg)       | Microcontrolador con Wi-Fi y Bluetooth integrado| 1        |
  | USB (Transferencia de datos)   | ![Imagen2](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/usb.jpg)         | Cable estándar para la transferencia de datos   | 1        |
  | Led                            | ![Imagen3](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/LEDs.jpg)         | Dispositivo de iluminación                      | 2        |
  | Sensor DHT11                   | ![Imagen4](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/dht11.jpg)       | Sensor de temperatura y humedad                 | 1        |
  | Foco                           | ![Imagen5](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/foco.jpg)         | Fuente de luz eléctrica                         | 1        |
  | Soquet                         | ![Imagen6](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/socket.jpg)      | Conector para bombillas                         | 1        |
  | Módulo relay                   | ![Imagen7](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/relay.jpg)       | Dispositivo de conmutación controlado           | 1        |
  | Sensor de temperatura infrarrojo | ![Imagen8](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/sensorinfrarrojo.jpg) | Sensor de temperatura por infrarrojos        | 1        |
  | Sensor de pulso cardiaco       | ![Imagen9](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/sensorCardiaco.png) | Sensor para medir la frecuencia cardíaca     | 1        |
  | Zumbador                       | ![Imagen10](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/zumbador.jpg)   | Dispositivo que emite sonido                    | 1        |
  | Motor de vibración             | ![Imagen11](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/motorvibracion.jpg) | Dispositivo que produce vibraciones             | 3        |
  | Pantalla                       | ![Imagen12](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/pantalla.jpg)   | Dispositivo de visualización                    | 1        |
  | Cables Jumper| ![Imagen13](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/CablesJumper.jpg)|  | 60        |
  | Fotorresistencia                       | ![Imagen14](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/Fotorresistencia.jpg)   | Es una resistencia, cuyo valor en ohmios, varía ante las variaciones de la luz.                    | 1        |
  | Raspberry pi 4| ![Imagen15](https://github.com/Fer33U/Soportefresh-DI-/blob/main/hardware/RaspberryPi.jpg)| Ordenador de bajo coste y formato compacto destinado al desarrollado | 1        |

</div>


## Historias de usuario épicas 
### Historia de Usuario Épica 1: Monitoreo de Factores Ambientales y del Usuario
**Como** usuario del dispositivo inteligente,  
**quiero** que el dispositivo pueda detectar y monitorear diversos factores ambientales y corporales,  
**para que** pueda obtener información en tiempo real sobre mi entorno y mi estado de salud.

### Historia de Usuario Épica 2: Activar diversos actuadores conforme a los factores ambientales o del usuario
**Como** usuario del dispositivo inteligente,  
**quiero** que el dispositivo pueda activar diferentes actuadores para diversos propositos conforme a los factores ambientales y corporales,  
**para que** pueda aprovechar las funcionaledades del dispositivo.

### Historia de Usuario Épica 3: Creacion de interfaz para monitoreo y control
**Como** usuario del dispositivo inteligente,  
**quiero** que el dispositivo tenga una interfaz donde pueda monitorear los factores ambientales y corporales ademas de activar a su conveniencia las funcionalidades incorporadas,  
**para que** pueda conocer de manera grafica los factores ambientales y corporales y/o activacion de las funcionaledes del dispositivo.

   
# Prototipo propuesto
## Primer Boceto
![Primer Boceto](https://github.com/Fer33U/Soportefresh-DI-/blob/main/Bocetos/BocetoProyecto.png)

## Arquitectura del proyecto
### Sensores
  -Sensor DHT11 
  -Sensor de temperatura infrarrojo
  -Sensor de pulso cardiaco
### Actuadores (Por definir correctamente "linterna")
  -Ventilador
  -Foco
  -Zumbador
  -Motor de vibración
  -Módulo relay
  -Pantalla
### Controladores
  -ESP32
### Plataforma de base de datos
  -SQLite (Posible cambio)
### Protocolo de comunicación
  -MQTT (Message Queuing Telemetry Transport)
### Gestión de energía
  -Baterias recargables (Por definir)
### Dispositivos receptores y/o transmisores
  -Adaptadores de corriente y conectores
  
## Tablero kanban
### Sprint 1
![Sprint 1](https://github.com/Fer33U/Soportefresh-DI-/blob/main/SprintsTrello/SprintsTrello.png) 
  
## Circuito diseñado para el proyecto completo 
| Nombre    | Versión | Sprint | Ilustración  |
|-----------|---------|-------------|---------|
| Linterna  | 1.0.0   | Sprint 1 | ![Ilustración](https://github.com/Fer33U/Soportefresh-DI-/blob/main/Circuitos/Linterna%20V1.0.png)  |
| Ventilador | 1.0.0   | Sprint 1| ![Ilustración](https://github.com/Fer33U/Soportefresh-DI-/blob/main/Circuitos/Ventilador%20V1.0.png)  |

## Resultados
### Sprint 1
  -Encender luz conforme a la luz detectada:
  Se tuvieron complicaciones en el hardware para poder detectar la fotorresistencia correctamente se logro codificar la funcionalidad pero aun sin probar con un componente funcional, de momento se enciende el led pero no toma la lectura de los datos lanzados por la fotorresistencia
  
  -Codigo:
  
  ![CodigoLinterna](https://github.com/Fer33U/Soportefresh-DI-/blob/main/Sprints/Sprint%201/CodigoLinterna.png) 
  
  -Circuito:
  
  ![CircuitoLinterna](https://github.com/Fer33U/Soportefresh-DI-/blob/main/Sprints/Sprint%201/CircuitoLinterna.jpeg)

  -Encender mini ventilador conforme a la temperatuta ambiente:
  Se logro codificar la funcionalidad de encender el mini ventilador cuando hay una temperatura mayor o igual a 34 grados.
  
  -Codigo:
  
  ![CodigoVentilador](https://github.com/Fer33U/Soportefresh-DI-/blob/main/Sprints/Sprint%201/CodigoVentilador.png) 
  
  -Circuito:
  
  ![CircuitoVentilador](https://github.com/Fer33U/Soportefresh-DI-/blob/main/Sprints/Sprint%201/CircuitoVentilador.jpeg)

  -Conclusiones:
  Se observo que se requiere adquirir componentes nuevos que sean necesarios para poder realizar la funcionalidad de la "linterna", se adquiriran en el siguiente sprint lo necesario para continuar con el proyecto, como sensores y otros actuadores necesarios.




  
