This project simulates a basic radar system using an Arduino UNO, an Ultrasonic Sensor (HC-SR04), and a servo motor. The system scans its surroundings by rotating the ultrasonic sensor and detecting objects within range. The data is visualized on a Processing IDE or a similar GUI to mimic a real radar screen.

📌 Features
Object detection using HC-SR04 ultrasonic sensor

0° to 180° servo sweep to scan the environment

Distance data sent to PC via serial communication

Real-time radar-like display using Processing or Serial Plotter

 Components Used
Arduino UNO

HC-SR04 Ultrasonic Sensor

Servo Motor (e.g., SG90)

Breadboard & Jumper Wires

USB Cable (for power and data)

Optional: LCD/LED indicators or buzzer

⚙️ How It Works
The servo motor rotates the ultrasonic sensor from 0° to 180° and back.

At each step, the ultrasonic sensor measures the distance to any obstacle.

The distance and angle data are sent to a PC over serial communication.

The data is plotted as a radar-like visual using Processing or Serial Plotter.
