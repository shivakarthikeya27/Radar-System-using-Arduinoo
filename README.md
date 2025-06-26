🔭 Radar System Using Ultrasonic Sensor and Arduino UNO
A mini radar system built using Arduino UNO, HC-SR04 ultrasonic sensor, and a servo motor, capable of detecting objects within a specified range and visualizing their position on a radar-like display using the Processing IDE. This project simulates basic radar functionalities by using ultrasonic sound waves for distance measurement and scanning.

📌 Project Overview
This project replicates the core functionality of a radar system on a small scale. Using an ultrasonic sensor mounted on a servo motor, the system sweeps through a defined angle range and detects nearby objects by measuring the time taken for sound waves to reflect back. The collected data is then transmitted to a computer and visualized in real-time as a radar sweep using a custom interface built with the Processing IDE.

🎯 Key Features
Object detection using ultrasonic sonar principles
Rotational scanning with a servo motor
Real-time 2D radar-style graphical interface
Live distance feedback and angular positioning
Seamless Arduino–Processing IDE integration

🔧 Components Used
Arduino UNO

HC-SR04 Ultrasonic Sensor

SG90 Servo Motor

USB cable (for serial communication)

Jumper wires and breadboard

PC with Processing IDE installed

⚙️ How It Works
The servo motor sweeps the ultrasonic sensor from left to right (e.g., 0° to 180°).

At each angle, the HC-SR04 sensor emits a sound pulse and waits for the echo.

The distance to the nearest object is calculated based on the time delay.

The Arduino sends this angle and distance data over serial communication to the PC.

A Processing sketch reads the incoming data and plots it in a radar-like display, updating in real time.

🖥️ Software & Programming
Arduino IDE
Used to write and upload the sensor and servo control logic to the Arduino UNO.

Processing IDE
A simple GUI application is built in Processing to visualize the radar scan and object detection output dynamically.

📊 Output Preview
You can add images or GIFs here showing:

The physical setup

The radar sweep interface

Detection of objects at various distances

📷 Add a screenshot or short GIF of your radar interface in action!

 Applications & Learning Outcomes
Understanding of ultrasonic sensing and distance calculation

Integration of hardware and software for real-time systems

Basics of servo motor control and angle tracking
