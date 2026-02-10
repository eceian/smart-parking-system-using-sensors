# smart-parking-system-using-sensors

🔧 Components Required

ESP32 Dev Board

5 IR Sensors

1 Entry IR

1 Exit IR

3 Slot IRs

Servo motor (SG90)

16x2 LCD with I2C

Jumper wires

Breadboard

External 5V supply (recommended for servo)

🔌 Pin Connections
🟦 IR Sensors
Purpose	ESP32 Pin
Entry IR	GPIO 18
Exit IR	GPIO 19
Slot 1 IR	GPIO 32
Slot 2 IR	GPIO 33
Slot 3 IR	GPIO 34

IR Sensor:
VCC → 5V
GND → GND
OUT → ESP32 pin

🟦 Servo Motor
Servo Wire	ESP32
Red	5V (External preferred)
Brown	GND
Yellow	GPIO 25
🟦 LCD (I2C)
LCD	ESP32
SDA	GPIO 21
SCL	GPIO 22
VCC	5V
GND	GND

I2C Address usually 0x27

📚 Required Libraries

Install these from Arduino Library Manager:

LiquidCrystal_I2C

ESP32Servo
