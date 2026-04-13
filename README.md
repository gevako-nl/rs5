# Gevako RS5 | 5-Channel Smart Relay for Home Assistant

## Overview
The Gevako RS5 is an industrial-grade 5-channel Smart Relay board designed for Home Assistant via ESPHome. Powered by the ESP32-C6 RISC-V processor, it provides rock-solid local control using either **WiFi 6** or the **Thread** protocol. 

It features five relays with a common power source input, capable of handling demanding loads.

<a href="https://www.gevako.com/shop/" target="_blank">
<img alt="gevako-rs5-smart-relay-3d-front-left-thread-wifi" src="https://github.com/user-attachments/assets/703d3c49-ddfa-4aa3-8898-c16afbebe669" width="200"/>
</a>

🔗 **Hardware Details & Store:**
* [Gevako RS5 - Thread Edition](https://www.gevako.com/shop/gevako-rs5-thread-smart-relay-home-assistant/)
* [Gevako RS5 - WiFi Edition](https://www.gevako.com/shop/gevako-rs5-wifi-smart-relay-home-assistant/)

---

## ⚡ Technical Specifications

### ESP32-C6 GPIO Pinout

| GPIO Pin | Function                  |
| :---     | :---                      |
| `GPIO01` | Relay Output 1            |
| `GPIO02` | Relay Output 2            |
| `GPIO03` | Relay Output 3            |
| `GPIO04` | Relay Output 4            |
| `GPIO05` | Relay Output 5            |
| `GPIO08` | Status LED (Green)        |
| `GPIO09` | BOOT Button               |
| `GPIO14` | Power source detection    |

### Electrical Schematic & Terminals

| Terminal | Label | Description                                       |
| :---     | :---  | :---                                              |
| 1        | L/+   | Power source input. Max 250 VAC / 30 VDC.         |
| 2        | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 3        | O1    | Switched output 1. Max 250 VAC / 30 VDC 16 A.     |
| 4        | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 5        | O2    | Switched output 2. Max 250 VAC / 30 VDC 16 A.     |
| 6        | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 7        | O3    | Switched output 3. Max 250 VAC / 30 VDC 16 A.     |
| 8        | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 9        | O4    | Switched output 4. Max 250 VAC / 30 VDC 16 A.     |
| 10       | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 11       | O5    | Switched output 5. Max 250 VAC / 30 VDC 16 A.     |
| 12       | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 13       | L     | Board Power: Phase 230 VAC.                       |
| 14       | N     | Board Power: Null 230 VAC.                        |
| 22       | B     | BOOT / Reboot (2 s) / Factory reset (10 s)        |
| 23-24    | USB   | USB-C connector. Max 5 VDC (1 A) for provisioning.|

<img alt="Gevako RS5 PCB Layout and Schematic" width="600" src="https://github.com/user-attachments/assets/dfc83b90-66c8-45a4-b20c-8a4657ff1379" />

---

## 🛠️ Installation & Wiring

### Wiring Example
<img alt="Gevako RS5 Wiring Example Home Assistant" width="600" src="https://github.com/user-attachments/assets/32f1bde4-7b66-4c79-9f3c-d3e49ca0739c" />

### Provisioning (WiFi & Thread)
The RS5 is fully compatible with ESPHome and can be provisioned using standard WiFi or integrated directly into a **Thread** network using USB TLV code provisioning.

1. **WiFi / Thread ESPHome Installer:** [gevako.com/esphome](https://www.gevako.com/esphome/)
2. **Thread Provisioning Tool:** [gevako.com/thread](https://www.gevako.com/thread/)
3. **Official ESPHome Web:** [web.esphome.io](https://web.esphome.io/)
