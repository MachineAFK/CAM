# ESP32CAM


## 🔧 Objetivo del Proyecto
Capturar imágenes desde la cámara integrada en el módulo ESP32-CAM, procesarlas o enviarlas según el caso (guardar, transmitir, análisis, etc.).

## 📦 Requisitos de Hardware

Módulo ESP32-CAM con cámara OV2640.

Módulo FTDI para cargar código vía USB.

### Conexiones:

  GND ↔ GND

  5V ↔ 5V

  U0R ↔ TX

  U0T ↔ RX

  GPIO0 a GND para entrar en modo carga

## 🔧 Configuración de Arduino IDE
Instalar la placa ESP32:

Ir a Archivo > Preferencias → Añadir URL:

```bash
https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
```
### Seleccionar placa:

AI Thinker ESP32-CAM

### Configurar:

Velocidad: 115200

### Flash Mode: QIO

### Flash Frequency: 40 MHz

### Partition Scheme: Huge APP

