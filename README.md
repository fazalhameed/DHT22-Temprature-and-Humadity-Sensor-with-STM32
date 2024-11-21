# DHT22 Temperature and Humidity Sensor with STM32

This project demonstrates interfacing the **DHT22 sensor** with an **STM32 microcontroller** and displaying the sensor readings on an **OLED SSD1306 display** using I2C communication.

## Features
- Reads temperature (°C/°F) and humidity data from the DHT22 sensor.
- Displays the sensor output on an OLED SSD1306 screen.

## Hardware Requirements
- STM32 Microcontroller
- DHT22 Temperature and Humidity Sensor
- SSD1306 OLED Display
- Supporting components: Breadboard, jumper wires, etc.

## Connections
| **Component** | **Pin**     | **STM32 Pin**   |
|---------------|-------------|-----------------|
| DHT22         | Data        | PB9             |
| SSD1306       | SCL         | I2C1_SCL (PB6)  |
|               | SDA         | I2C1_SDA (PB7)  |

## Repository Structure
- **`Core/Inc`**: Header files for application logic, DHT22, and SSD1306 drivers.
- **`Core/Src`**: Source files for implementing sensor reading and OLED updates.
- **`Drivers`**: Peripheral drivers and HAL library for STM32.

## Example Output
Temperature and humidity data displayed on the OLED screen in real-time.

## License
This project is licensed under the MIT License.
