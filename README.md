# Ultrasonic Sensor with Servo Motor Control

<p align-item=justify> This Arduino sketch is designed to control an Ultrasonic Sensor with a Servo Motor. The code allows the servo motor to rotate from 15 to 165 degrees, while the ultrasonic sensor measures the distance at each degree of rotation. The measured distance data is then sent via Serial communication for further processing or visualization.</p>

<img src="img/pic 1.png" alt="radar">

## Features:
- Utilizes the Servo library to control the movement of a servo motor.
- Uses an Ultrasonic Sensor to measure distance.
- Rotates the servo motor from 15 to 165 degrees in steps.
- Calculates and sends distance data for each degree of rotation via Serial communication.

## Components Required:
- Arduino board
- HC-SR04 Ultrasonic Sensor
- Servo Motor

## How It Works:
1. The code initializes the trigPin and echoPin for the Ultrasonic Sensor, as well as the servo motor.
2. The servo motor is rotated from 15 to 165 degrees in steps.
3. At each degree of rotation, the Ultrasonic Sensor measures the distance.
4. The measured distance data is sent via Serial communication in the format: "degree,distance."

## Usage:
1. Connect the Ultrasonic Sensor and Servo Motor to the specified pins on the Arduino board.
2. Upload the sketch to your Arduino board.
3. Open the Serial Monitor to view the measured distance data.

Feel free to modify and adapt this code for your own projects or experiments involving servo motor control and distance measurement with an Ultrasonic Sensor.

For more details and explanations, refer to the comments within the code.

Happy tinkering! 🤖✨
