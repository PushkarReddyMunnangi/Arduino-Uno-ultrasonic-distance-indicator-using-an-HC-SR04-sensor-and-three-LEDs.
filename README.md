Arduino Ultrasonic Distance Indicator

About the Project
This is my first Arduino electronics project! I built it using an Arduino Uno, an HC-SR04 ultrasonic sensor, and three LEDs.
The main goal of this project is to measure how far an object is from the sensor and use different LEDs to show the distance. 
I also made it display the distance readings on the Serial Monitor
Components Used:
1. Arduino Uno
2. HC-SR04 ultrasonic sensor
3. Red LED
4. Yellow LED
5. Green LED
6. 3 x 220 ohm resistors
7. Breadboard
8. Jumper wires
9. USB cable

How It Works
The HC-SR04 sensor sends ultrasonic waves and detects the echo that returns from an object.
The Arduino uses the echo's travel time to calculate the distance.
Based on the distance, one of the three LEDs turns on:
1. Red LED: The object is 10 cm or closer.
2. Yellow LED: The object is more than 10 cm away but not more than 20 cm.
3. Green LED: The object is more than 20 cm away.
4.No echo detected: All three LEDs turn off.
The distance is also displayed on the Serial Monitor so I can see the readings while testing the project.
How to Run the Project:
1. Connect all the components according to the wiring table.
2. Open distance_indicator.ino in the Arduino IDE.
3. Select Arduino Uno and the correct port.
4. Upload the code to the Arduino.
5. Open the Serial Monitor and set the baud rate to 9600.
6. Move an object closer to and farther away from the sensor to see the LEDs change.

What I Learned:
I learned how to :
1. Properly integrate the code so that it takes the sensor's output.
2. How to physically use the wires so that they can work in unison.
3. Overall, I learnt how to have fun with engineering.
Future Improvements:
1. I would like to improve this project by:
2. Adding a buzzer that warns when an object gets too close.
3. Using an LCD or OLED display to show the distance.
4. Making the distance limits adjustable.
5. Using what I learned to build an obstacle-detecting robot.

Demonstration:
I will add photos and a video of my project working here.

Author:
This project is part of my journey into learning Arduino, electronics, and robotics.
I built it to get more hands-on experience with sensors, coding, and hardware.


