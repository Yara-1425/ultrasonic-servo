#  Arduino Ultrasonic & Servo Distance Detector

This project is an interactive smart automation system powered by an **Arduino** microcontroller. It combines distance sensing, physical movement, and visual indicators to react to objects in real time.

### How It Works:

1. **Detection:** The **HC-SR04 Ultrasonic Sensor** constantly measures the distance of objects in front of it using sound waves.
2. **Action:**
* If an object is detected at a distance of **10 cm or more**, the **Servo Motor** rotates to a specific angle (e.g., 90 degrees) and the **LED** lights up.
* If the object moves closer (less than 10 cm), the servo returns to its original position and the LED turns off.

## project Deom
![Project Demo](IMG_6238.gif)

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
