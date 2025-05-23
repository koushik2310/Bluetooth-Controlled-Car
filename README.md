# Bluetooth-Controlled-Car
This small project is about a Bluetooth-controlled robotic car, operated using a mobile phone app. The app we are using to control the car is called 'Bluetooth RC Controller'.
Components used:
1.Arduino UNO
2.LM298 Motor Driver
3.HC05 Bluetooth Module
4.Four Servo Motors and Four Wheels
5.Rechargeable Bateteries
6.LED's (Optional)

Circuit Connections:
1.L298N Motor Driver to Arduino:
IN1 (Motor A Forward) → Arduino Pin 5
IN2 (Motor A Reverse) → Arduino Pin 6
IN3 (Motor B Forward) → Arduino Pin 10
IN4 (Motor B Reverse) → Arduino Pin 11
Enable Pins (ENA/ENB): Controlled using digital pins 8 and 12 (used for direction control)
Motor Power Supply: Connected to battery.
GND: Common ground with Arduino.

2.HC-05 Bluetooth Module to Arduino:
VCC → 5V
GND → GND
TX → Arduino RX (Pin 0)
RX → Arduino TX (Pin 1)

You can refer to the provided image for the wiring connections. After completing the connections, upload the provided Arduino code to the board. Make sure to install any necessary libraries. Once the code is uploaded, open the 'Bluetooth RC Controller' app on your phone, connect it to the Bluetooth module, and you will be able to control the robotic car using the app.
