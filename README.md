# Turtlebot
## Descripción del proyecto
Este proyecto es un robot de accionamiento diferencial con sensor de ultrasonido que utiliza ROS 2. El robot puede moverse hacia adelante, atrás, izquierda y derecha mediante comandos, y si detecta un obstáculo, automáticamente retrocede y cambia su ruta.

## Partes del proyecto
holi holi holi  
nodos de ROS en py  
código de esp32 en c++  

## Componentes del Hardware
holi
## Arquitectura del Software
holi
## Diagrama de flujo del sistema
holi
## Robot terminado y funcionando

## Autores
- **Valeria Andrea Parra García** – *valeriaparrag@javeriana.edu.co*
- **María ALejandra Díaz Ortiz** – *mariaa-diaz@javeriana.edu.co*
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
