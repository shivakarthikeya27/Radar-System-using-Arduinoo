 Radar System using Arduino & Ultrasonic Sensor

This project simulates a basic radar system using an "Arduino UNO", "HC-SR04 ultrasonic sensor", and a "servo motor". It scans a 180° area and detects nearby objects using ultrasonic pulses. Detected objects are visualized on a radar-style interface built in "Processing IDE".

 Features

- Object detection using ultrasonic sensor  
- 180° scanning using servo motor  
- Real-time graphical radar visualization using Processing  
- Displays both angle and distance of detected objects  
- Ideal for learning embedded systems and sensor interfacing

How It Works

1. The "servo motor" rotates the ultrasonic sensor between 0° to 180°.
2. At each angle, the "HC-SR04 sensor" sends out an ultrasonic pulse and measures the time for the echo to return.
3. The "Arduino" calculates the distance based on the time delay.
4. Angle and distance data are sent over serial to the "Processing IDE".
5. The "Processing sketch" plots this data on a radar-like display, mimicking real radar scans.

Components Required

- Arduino UNO  
- HC-SR04 Ultrasonic Sensor  
- SG90 Servo Motor  
- Jumper Wires  
- Breadboard  
- USB Cable  
- Processing IDE (for visualization)

#Software & Tools

- Arduino IDE  
- Processing IDE  
- C++/Arduino language  
- Serial Communication

 Applications

- Obstacle detection
- Smart parking assistance
- Intro to radar systems
- Educational demonstrations
