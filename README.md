Water Level Indicator using Arduino Uno and Ultrasonic Sensor (Tinkercad Simulation)

Overview:
This project is a Water Level Indicator designed and tested in Tinkercad Circuits using an Arduino Uno and an HC-SR04 Ultrasonic Sensor. The ultrasonic sensor measures the distance between the sensor and the water surface, and the Arduino controls three LEDs to indicate the water level inside the tank.


 Designed and simulated in Tinkercad Circuits
 Real-time water level monitoring using an ultrasonic sensor
 Three-level LED indication:
   🟢 Green LED – Tank Full
   🟡 Yellow LED – Half Tank
   🔴 Red LED – Low Water Level
 Displays the measured distance on the Arduino Serial Monitor
  Updates every 50 ms

Components Used

Arduino Uno
HC-SR04 Ultrasonic Sensor
 Green LED
 Yellow LED
 Red LED
220 Ω Resistors
Breadboard
connecting Wires

Pin Connections

Component| Arduino Pin
Trig Pin| D8
Echo Pin| D9
Green LED| D6
Yellow LED| D5
Red LED| D3

Working Principle

1. The Arduino sends a trigger pulse to the HC-SR04 ultrasonic sensor.
2. The sensor measures the distance to the water surface.
3. The measured distance is displayed on the Serial Monitor.
4. The LEDs indicate the water level based on the measured distance:
   - Distance < 100 cm: Green LED ON (Tank Full)
   - 100 cm ≤ Distance < 200 cm: Yellow LED ON (Half Tank)
   - Distance ≥ 200 cm: Red LED ON (Low Water Level)

Applications

Water tank level monitoring

Simulation

This project was designed, programmed, and tested entirely in Tinkercad Circuits to simulate the behavior of a real-time water level monitoring system before physical implementation.

