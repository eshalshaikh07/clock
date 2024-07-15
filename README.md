"# clock" 
# Arduino Clock with U8glib Library

This Arduino sketch displays a clock on an SSD1306 OLED display using the U8glib library. The clock shows hours, minutes, and seconds with hour digits marked around the clock face.

## Components Used

- **Arduino Board (e.g., Arduino Uno, ESP32)**
- **SSD1306 OLED Display**
- **U8glib Library**

## Circuit Diagram

### Pin Connections

Connect your SSD1306 OLED display to your Arduino board as follows:

- **VCC** to Arduino 5V
- **GND** to Arduino GND
- **SCL** (Serial Clock Line) to Arduino SCL (A5 on Arduino Uno, GPIO21 on ESP32)
- **SDA** (Serial Data Line) to Arduino SDA (A4 on Arduino Uno, GPIO22 on ESP32)

**Note:** For ESP32, ensure to use appropriate GPIO pins as per your setup.

## Installation

1. **Install U8glib Library**:
   - Download and install the U8glib library from the Arduino Library Manager or from its GitHub repository.

2. **Upload Code**:
   - Open the provided Arduino sketch (`clock_display.ino`) in your Arduino IDE.
   - Upload the sketch to your Arduino board.

## Usage

1. **Setup**:
   - Ensure your SSD1306 OLED display is correctly connected to your Arduino board as per the circuit diagram.
   - Adjust any pin configurations or settings in the sketch if necessary.

2. **Operation**:
   - The clock will display hours, minutes, and seconds on the OLED display.
   - You can modify the code to customize the clock display further or add additional features.



```cpp


