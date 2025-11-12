# Gevako RS5 | 5-channel Smart Switch for Home Assistant

## Introduction
The Gevako RS5 is a 5-channel Smart Switch suitable for Home Assistant by using ESPHome. 5 individual relays with a maximum switching current of 16 A at max 250 VAC / 30 VDC. Using the powerful ESP32-C6 as processor.

<img width="200" height="200" alt="RS5 3D Black-T" src="https://github.com/user-attachments/assets/089008c8-97aa-40c3-a091-e8da973dbac9" />


## Pinout
#### ESP32-C6 GPIO pinout
| GPIO pin | Description             |
| :---     | :---                    |
| GPIO01   | Output 1                |
| GPIO02   | Output 2                |
| GPIO03   | Output 3                |
| GPIO04   | Output 4                |
| GPIO05   | Output 5                |
| GPIO08   | Green LED / BOOT        |
| GPIO11   | Power source detection  |

## Electrical schematic
| Number | Label | Description                                       |
| :---   | :---  | :---                                              |
| 1      | L/+   | Power source output. Max 250 VAC / 30 VDC 16 A.   |
| 2      | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 3      | O1    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 4      | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 5      | O2    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 6      | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 7      | O3    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 8      | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 9      | O4    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 10     | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 11     | O5    | Switched output. Max 250 VAC / 30 VDC 16 A.       |
| 12     | N/-   | Null 230 VAC / 0 VDC (GND).                       |
| 13     | L     | Fase 230 VAC.                                     |
| 14     | N     | Null 230 VAC.                                     |
| 22     | B     | BOOT.                                             |
| 23-24  | USB   | USB-C connector. Max 5 VDC with a current of 1 A. |

<img width="1050" height="620" alt="RS5" src="https://github.com/user-attachments/assets/dfc83b90-66c8-45a4-b20c-8a4657ff1379" />

## Electial wiring example
<img width="1050" height="669" alt="RS5 example_2 0 1" src="https://github.com/user-attachments/assets/32f1bde4-7b66-4c79-9f3c-d3e49ca0739c" />

