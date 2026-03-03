# RainShield-Automatic-Cover-Deployment-System
This project is a simulation-based implementation of an automatic rain protection system using ESP32. The idea was inspired by a concept demonstration, and I recreated and tested the logic using Wokwi simulation.

Since a rain sensor is not available in Wokwi, a push button was used to simulate rain detection.

Working Principle:

ESP32 monitors rain detection input

When rain is triggered (button press), the system:

Displays “Rain Detected” on LCD

Activates servo motor to deploy protective cover

Updates LCD status as:

“Deploying Cover”

“Cover Deployed”

When rain stops, the servo returns to its initial position.

Components Used (Simulated):

ESP32

Push button (rain simulation)

Servo motor (cover deployment mechanism)

16x2 LCD display

What I Focused On:

State-based logic implementation

Servo motor control using PWM

LCD interfacing with ESP32

Event-driven embedded programming

Simulation testing using Wokwi

Key Learning:

This project strengthened my understanding of actuator control and real-time status handling in embedded systems, even in a simulation environment.
