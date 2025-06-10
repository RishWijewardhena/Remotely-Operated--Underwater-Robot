# 🐠Underwater Robot Using Raspberry Pi | Real-Time Control & Temperature Monitoring

This project features a custom-built tethered underwater robot powered by a Raspberry Pi 4 running Raspberry Pi OS. The robot is capable of real-time navigation and temperature sensing in underwater environments using brushless motors with ESCs, a waterproof temperature sensor, and a Raspberry Pi Camera for live video streaming.

The system is operated via a PyQt-based GUI, which is hosted directly on the Pi and accessed remotely through RealVNC over a static-IP Ethernet connection. The robot was tested in a 6-foot-deep pool and successfully captured accurate temperature data while maintaining perfect balance and watertight integrity.

🛠 Features
4 Brushless Motors controlled via Electronic Speed Controllers (ESCs)

2 propellers for Z-axis (vertical) navigation

2 mirrored propellers for balanced X-Y plane movement

Real-time GUI using PyQt (runs directly on Raspberry Pi)

Raspberry Pi Camera Module for live visual feedback

Temperature sensor (waterproof) for environmental data collection

Tethered Ethernet connection with static IP for GUI control via RealVNC

Power source: Inbuilt 3S LiPo battery

🧪 Testing Results
Tested in a 6-foot pool with stable and smooth navigation

No water leakage during the test

Collected accurate temperature measurements

Balanced propulsion achieved by mirroring propellers to cancel torque

🧰 Tools & Libraries
Python 3

PyQt5

RPi.GPIO or pigpio (depending on your PWM control method)

OpenCV (optional, for camera streaming)

RealVNC

Raspberry Pi OS (Desktop version)


