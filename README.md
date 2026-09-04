#🚗 Arduino Motor Control




📌 Project Overview

This project demonstrates basic DC motor control using Arduino.
The Arduino controls two motors — a left motor and a right motor — using four digital output pins.

The program makes each motor rotate in one direction for 1 second and then reverse its direction for 1 second.

🔧 Components Required
Arduino Uno
2 × DC Motors
Motor Driver (L298N/L293D or equivalent)
Jumper Wires
External Motor Power Supply
🔌 Pin Configuration
Arduino Pin	Function
D2	Left Motor Input 1
D3	Left Motor Input 2
D4	Right Motor Input 1
D5	Right Motor Input 2
⚙️ Working Principle

The Arduino uses two digital pins for each motor to control its direction.

HIGH, LOW → Motor rotates in one direction
LOW, HIGH → Motor rotates in the opposite direction
LOW, LOW → Motor stops

🎯 Applications

This basic motor-control concept can be used in:

🤖 Line-following robots
🚗 Robot cars
🛞 Two-wheel robotic systems
🏭 Automated machines
🔄 Motor direction control experiments
🚀 Future Improvements

The project can be extended by adding:

Bluetooth control
Obstacle detection
IR sensors
Ultrasonic sensors
Speed control using PWM
Remote-controlled robot functionality

The program first rotates the left motor forward, then reverses it. After that, the same operation is performed for the right motor.

Each direction is maintained for 1 second using the delay() function.
