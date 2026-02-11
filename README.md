# OLED I2C Demo (Arduino UNO R4)

## IDE
- IDE: CLion
- Version used: `CLion 2025.3.2` (Windows)

## Code overview
- Entry point: `src/main.cpp`
- Behavior: Initializes an SSD1306 OLED over I2C and prints:
  - `Arduino UNO R4`
  - `OLED with I2C`
  - `Hello Students!`
- `loop()` is currently empty (extend to update display or show sensor data).

## Libraries
- `Arduino.h`
- `Wire.h` (I2C)
- `Adafruit_GFX.h`
- `Adafruit_SSD1306.h`

## Dependencies
- Arduino core for `Arduino UNO R4` (install via Arduino IDE or Arduino CLI)
- Arduino CLI or toolchain integration for CLion (to build/flash)
- Adafruit SSD1306 and Adafruit GFX libraries (install via Library Manager or `arduino-cli lib install`)
- I2C support on the board (Wire library)

## Components / Wiring (OLED)
- OLED module (SSD1306, I2C, address `0x3C`)
- Microcontroller: `Arduino UNO R4`
- Typical wiring:
