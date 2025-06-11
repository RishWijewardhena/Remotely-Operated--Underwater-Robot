🐠 Remotely Operated Underwater Robot using Raspberry Pi
Real-Time Navigation, Live Video Streaming, and Temperature Monitoring 🌊🤖
This project showcases a tethered underwater robot built on a Raspberry Pi 4 running Raspberry Pi OS. Designed for real-time control, live video feedback, and temperature sensing, the robot integrates multiple systems including brushless motors, electronic speed controllers (ESCs), and a waterproof temperature sensor.

The onboard PyQt-based GUI runs directly on the Raspberry Pi and is accessed remotely via RealVNC using a static-IP Ethernet connection. Our design was successfully pool-tested at a depth of 6 feet, showing excellent balance, structural integrity, and accurate environmental data collection.

🛠️ Features
  . Four brushless motors controlled via ESCs

  . 2 for vertical (Z-axis) navigation

  . 2 mirrored for balanced horizontal (X-Y plane) navigation

  . Torque-canceling propulsion via mirrored propeller design

  . Real-time GUI using PyQt, hosted directly on Raspberry Pi

  . Raspberry Pi Camera for live video feed

  . Waterproof temperature sensor to log environmental data to CSV

  . Tethered Ethernet connection with static IP for reliable GUI control via RealVNC

  . Powered by onboard 3S LiPo battery

🧪 Pool Testing Results
  . Successfully tested at 6 ft depth

  . No water leakage observed

  . Accurate temperature readings recorded

  . Stable motion and perfect balance during navigation

  . Torque-neutral behavior achieved via mirrored motor design

🧰 Tools & Libraries Used
  .Python 3

  .PyQt5

  .RPi.GPIO or pigpio for motor PWM control

  .OpenCV (optional) for camera streaming

  .RealVNC for remote GUI access

  .Raspberry Pi OS (Desktop)

🚀 Future Improvements

  .IMU integration for orientation and motion tracking

  .Wireless control interface

  .Autonomous path planning

  .Cloud-based data storage and visualization
