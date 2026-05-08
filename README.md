### Multimeter: From Schematic to PCB

This project is a custom designed **Arduino Uno Shield** that transforms the microcontroller into a functional digital multimeter. The project covers the full development from schematic design to a physical 2 layer PCB, optimized for reliable analog measurements and clear visual feedback.

### 🚀 Features

*   **Voltage Measurement:**
    *   Low Range: 0–5 V
    *   High Range: 5–35 V
    *   Dedicated Battery Check function
*   **Resistance Measurement:**
    *   Low Range: 0–1 kΩ
    *   High Range: 1–99.9 kΩ
*   **Continuity Tester:** Integrated buzzer (beeper) for short-circuit detection.
*   **Visual Interface:** 3-digit 7-segment LED display for real time value output.
*   **Manual Control:** Rotary select switch for toggling between measurement modes and ranges.

### 🛠 Hardware Specifications

### PCB Design
*   **Dimensions:** 68.6 × 65.0 mm (Compatible with Arduino Uno footprint).
*   **Layer Count:** 2-layer design.
*   **Material:** FR4 laminate, 1.5 mm thickness with 18 µm copper.

### Pins
The shield is designed to be stackable with an Arduino Uno using standard 2.54 mm headers.

| Arduino Pin | Function | Description |
| :--- | :--- | :--- |
| **A0 / A1** | Volt Low / High | Analog inputs for voltage ranges |
| **A2 / A3** | Res Low / High | Analog inputs for resistance ranges |
| **A4 / A5** | Battery / Beeper | Battery monitoring and buzzer |
| **D2 - D5** | BCD A-D | Binary Coded Decimal inputs for display |
| **D6** | Decimal Point | Controls the display's DP |
| **D7 - D10** | Function Select | Input from the rotary switch |
| **D11 - D13** | Digit 1-3 | Common cathode/anode digit selection |
| **Vin** | Power Input | Sources power from 9V battery to Arduino |

### 🔋 Power Management
*   **Primary Power:** Powered by a 9V battery via soldered jumper cables.
*   **Arduino Integration:** The shield supplies power to the Arduino Uno via the `Vin` pin.

### 📝 Project Context

This project was developed as a school project as part of my education at *YRGO*. Voltage dividers), PCB routing constraints, and hardware-software interfacing. The primary focus was on the hardware design and practice soldering.
