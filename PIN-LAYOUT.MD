# ESP32 Pin Layout

This document provides a clear layout of the ESP32 pins for easier reference and use in your projects.

## Pin Labeling

The following table organizes the pins based on your description:

| **Side 1**                  | **Side 2**            |
|-----------------------------|-----------------------|
| `3V3` - 3.3V Power Source  | `VIN` - Voltage In    |
| `GND` - Ground             | `GND` - Ground        |
| `D15`                      | `D13`                 |
| `D2`                       | `D12`                 |
| `D4`                       | `D14`                 |
| `RX2` - UART2 Receive      | `D27`                 |
| `TX2` - UART2 Transmit     | `D26`                 |
| `D5`                       | `D25`                 |
| `D18`                      | `D33`                 |
| `D19`                      | `D32`                 |
| `D21` - I2C SDA            | `D35`                 |
| `RXD` - UART0 Receive      | `D34`                 |
| `TX0` - UART0 Transmit     | `UN`                  |
| `D22` - I2C SCL            | `UP`                  |
| `D23`                      | `EN` - Enable Pin     |

---

## Notes
- **I2C Pins**:
  - `D21` is the default SDA pin for I2C communication.
  - `D22` is the default SCL pin for I2C communication.
  
- **UART Pins**:
  - `RXD` and `TX0` are UART0's receive and transmit pins.
  - `RX2` and `TX2` are UART2's receive and transmit pins.

- **Power Pins**:
  - `3V3` provides 3.3V power.
  - `VIN` is the input voltage pin (use when powering via an external source).
  
- **Enable Pin**:
  - `EN` is used to enable or reset the ESP32.

Feel free to update this layout or add additional details as needed!
