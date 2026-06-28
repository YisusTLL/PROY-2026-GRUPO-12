# PROYECTO INICIAL 2026


Repositorio del grupo X para el proyecto del ramo *Proyecto Inicial (IWG400)* – 2026.

## 👥 Integrantes del grupo

| Nombre y Apellido | Usuario GitHub | Correo USM               | Rol USM      |
| ----------------- | -------------- | ------------------------ | ------------ |
| Bastián Johnson | @baston444     | bjohnson@usm.cl | 202630016-1 |
| Nicolas Alvarez | @nicoko10      | nalvarezgu@usm.cl | 202630034-k |
| Jesus Galeas |@Yisus_TLL  | jgaleas@usm.cl |202621814-7 |
| Lucas Castro| @lumino38    | lcastroav@usm.cl | 202630044-7 |

## 📝 Descripción breve del proyecto

> Nuestro proyecto tiene como objetivo apoyar los ámbitos laboral y de investigación científica mediante el uso de un robot llamado “Sentinel”. Su función es acceder a entornos que resultan inaccesibles o peligrosos para las personas, y medir con precisión, distancia, temperatura, etc gracias a sus sensores. Por ello, Sentinel es desplegado para llevar a cabo estas tareas, permitiendo realizar trabajos en condiciones de riesgo de manera más segura y eficiente.

---

## 🎯 Objetivos

- Objetivo general:
  - Diseñar un brazo mecatronico que sea capaz de obtener data de humedad del suelo, hidrogeno, Co2, nitrogeno, temperatura, humedad ambiente, y que tenga la capacidad de identificar su radio de vision a travez de un giroscopio, más señales ultrasonicas.

- Objetivos específicos:
  - Aprender y crear una aplicacion que sea capaz de controlar al robot, las lecturas y el brazo mecatronico a travez de un modulo bluetooth que se conectara al arduino.
  - Realizar el diseño esquematico del circuito del control del brazo mecatronico mas sensores.
  - Diseñar la estructura del brazo mecatronico y sus anclajes (sensores, motores y taladro).

---

## 🧩 Alcance del proyecto

> El proyecto logrará una movilidad óptima y la instalación funcional de sus sensores, cumpliendo con el objetivo de recopilar datos medioambientales como: humedad del suelo, temperatura, humedad ambiente, e índices de hidrógeno, Co2 y nitrógeno. Por otro lado, el desarrollo del brazo mecatrónico queda fuera del alcance debido a limitaciones de tiempo y experiencia técnica. Su complejidad estructural, tanto interna como externa, impide su correcta ejecución dentro del plazo establecido.
> *Definir qué aspectos cubre el proyecto y qué queda fuera del alcance (limitaciones).*

---

## 🛠️ Tecnologías y herramientas utilizadas

- Lenguaje(s) de programación:
  - HTML: Para la pagina web
  - C++: Para el Arduino y Esp8266
- Microcontroladores
  - Arduino MEGA 2560 y ESP8266
- Sensores
  - M9-7: Sensor Monoxido de Carbono (CO) y Hidrogeno (H).
  - M9-8: Sensor de Hidrogeno (H).
  - M9-135: Sensor Calidad del aire detecta amoniaco, oxido nitrogeno, Benceno, Humo, CO2.
  - BME 280: Sensor de temperatura °c, Presion Atmosferico y Humedad relativa.
  - M9-2: Sensor de detección de gases conmbustibles.
---

## 🗂️ Estructura del repositorio

```
/PROY-2026-GRUPOX
│
├── docs/               # Documentación general y reportes
├── src/                # Código fuente del proyecto
├── tests/              # Casos de prueba
├── assets/             # Imágenes, diagramas, etc.
└── README.md           # Este archivo
```

---

## 🚀 Instrucciones de Instalación y Uso

### Códigos del Robot

Los códigos utilizados por el robot están disponibles en el siguiente repositorio:

**[Códigos del Robot](https://github.com/baston444/C-digos-del-robot)**

Para instalar y ejecutar los códigos:

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/baston444/C-digos-del-robot.git
   ```

2. **Dependencias:**

   Instalar **Arduino IDE 2.x**, la tarjeta **ESP32 by Espressif Systems** y las siguientes librerías:

   * WiFi
   * WebServer
   * Wire
   * Adafruit GFX Library
   * Adafruit SSD1306

3. **Ejecución:**

   Abrir los archivos `ULTRA_ESP32.ino` y `ULTRA_ARDU.ino` en Arduino IDE, configurar las credenciales de la red WiFi, cargar cada programa en su placa correspondiente (ESP32 y Arduino Mega 2560) y ejecutar el sistema.


---

## 📐 Diseño del Sistema
![Diagrama de Conexiones](./assets/diagrama_conexiones.png)

*Explicacion grafica de como es la conexion entre el microcontrolador y los sensores*

---

## 📅 Cronograma de trabajo

[[Carta Gantt](https://google.com)](https://usmcl-my.sharepoint.com/:x:/r/personal/jgaleas_usm_cl/Documents/Carta%20Gantt.xlsx?d=w419b2eb64bce4d5b9386c1a2a08d7fc1&csf=1&web=1&e=5rILhX)

---

## 📚 Bibliografía

[Enlace](https://google.com)

---

## 📌 Notas adicionales

Debido a la falta de tiempo y a problemas externos que impidieron una mejor organizacion nuestro proyecto se vio limitado y no se llego a concretar al 100% por lo solo se pudo presentar lo que seria la base del robot junto a su movimiento controlado mediante la pagina web que hicimos especialmente para el robot.
