**Humidity Calculation with LED Toggle**
Hardware Requirements
Tiva C Series TM4C123G microcontroller

Humidity sensor (e.g., DHT11 or DHT22)

4 LEDs (Red, Green, Blue, and Off)

1 Button

Resistors for the LEDs (220Ω recommended)

Breadboard and jumper wires (for connections)
Pin Configuration
Button Pin: PF4 (GPIO)

Red LED Pin: PF1

Green LED Pin: PF3

Blue LED Pin: PF2

Humidity Sensor Data Pin: PA0 (or any available GPIO pin)
Circuit Diagram
For the complete circuit setup, connect the humidity sensor and LEDs to the specified GPIO pins on the Tiva C Series board as described above. The button is used to toggle through different LED colors.

Software Requirements
Keil uVision IDE for code development and programming the Tiva C Series board

TivaWare library for peripheral drivers

**🧑‍💻 Author**
**Muhindhar**
**KIOT - Department of ECE**
