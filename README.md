# 📡 ESP32 IoT Node - 4-Layer PCB Design

This repository contains the hardware design files for a compact, high-performance IoT node based on the **ESP32-WROOM-02-H4** module. This project highlights advanced PCB layout techniques in **KiCad**, focusing on power integrity, RF performance, and industrial-grade connectivity.

## 🚀 Design Highlights
The board is engineered for reliability in dense IoT deployments. It utilizes a **4-layer stackup** (Signal-GND-VCC-Signal) to ensure low electromagnetic interference (EMI) and provide a stable power delivery network (PDN) for the SoC and high-speed peripherals.

## 🛠️ Technical Specifications
* **EDA Tool:** KiCad 8.0 (or your version)
* **Layer Count:** 4 Layers (Internal Ground and Power planes)
* **Connectivity:** WiFi 2.4GHz, Bluetooth LE, UART, I2C, and SPI breakouts
* **Power:** Integrated 3.3V LDO with optimized decoupling for the ESP32 radio
* **Security:** Optional footprint for secure authentication chips via I2C

## 🧩 Key Features
* **Power Integrity:** Extensive use of stitching vias and dedicated planes to minimize voltage ripple.
* **RF Optimization:** Adheres to strict clearance and keep-out zones for the PCB antenna to ensure maximum signal range.
* **Compact Form Factor:** Optimized footprint for small-scale enclosure integration.
* **Manufacturing Ready:** Includes precise footprints and libraries for automated assembly (CPL and BOM).

## 🖼️ Gallery

<img width="1173" height="685" alt="ESP32_IOT_PCB" src="https://github.com/user-attachments/assets/726b1033-2749-49a3-8a95-ab1e515412a1" />
<img width="1724" height="930" alt="ESP32_IOT" src="https://github.com/user-attachments/assets/a25c3573-be3a-429a-8515-f588e176a4b0" />
