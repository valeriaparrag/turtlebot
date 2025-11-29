# Velociraptor robot
## Project's description
This project is a differential drive robot with an ultrasonic sensor that implements ROS 2. The robot can move forward, backward, left, and right by commands, and if it detects an obstacle, it automatically stops.

## Parts of the project
holi holi holi  
nodos de ROS en py  
código de esp32 en c++  

## Hardware components
holi
## Software architecture
holi

## Configuración e instalación
### ESP32 configuration
1. Download the package titled WifiESP
   
3. Check the port to which the ESP32 is connected  
   a. Go to PlatformIO's configuration  
   b. Follow the route  
     `Default` → `general` → `devices`  
   c. Check the port's number on the terminal  
     For example:  
     `/dev/ttyUSB0`  
5. Grant permits to the port  // REVISAR CONCEPTOS

### Configuración de ROS2

### 

### 

## Diagrama de bloques del sistema
holi

## Robot terminado y funcionando

## Autores
- **Valeria Andrea Parra García** – *valeriaparrag@javeriana.edu.co*
- **María Alejandra Díaz Ortiz** – *mariaa-diaz@javeriana.edu.co*
---
# Este es un Título Principal (H1)

## Este es un Subtítulo (H2)

### Este es un Sub-subtítulo (H3)

---

Texto normal en Markdown.

**Texto en negrita**

*Texto en cursiva*

***Texto en negrita y cursiva***

---

## Listas de ejemplo

### Lista con viñetas
- Elemento 1
- Elemento 2
  - Sub-elemento 2.1
  - Sub-elemento 2.2

### Lista numerada
1. Paso uno
2. Paso dos
3. Paso tres

---

## Código de ejemplo

### Código en una línea:
`int velocidad = 100;`

### Código en bloque:
```cpp
#include <Arduino.h>

void setup() {
    Serial.begin(115200);
}

void loop() {
    Serial.println("Hola desde el ESP32");
    delay(1000);
}
