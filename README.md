#  Arduino Ultrasonic & Servo Distance Detector

##  Project Demo


##  Components Needed

1. **Arduino Board** (e.g., Arduino Uno)
2. **Ultrasonic Sensor** (HC-SR04)
3. **Servo Motor** (e.g., SG90)
4. **LED Light**
5. **Resistor** (220 ohm for the LED)
6. **Breadboard & Jumper Wires**


## Pin Connections

| Component | Component Pin | Arduino Pin | Description |
| --- | --- | --- | --- |
| **HC-SR04 Ultrasonic** | VCC | 5V | Power |
|  | GND | GND | Ground |
|  | Trig | Digital Pin 9 | Send sound waves |
|  | Echo | Digital Pin 8 | Receive sound waves |
| **Servo Motor** | VCC (Red) | 5V | Power |
|  | GND (Brown/Black) | GND | Ground |
|  | Signal (Yellow/Orange) | Digital Pin 10 | Control movement |
| **LED** | Positive (Long leg) | Digital Pin 7 (with 220Ω resistor) | Turn on light |
|  | Negative (Short leg) | GND | Ground |
