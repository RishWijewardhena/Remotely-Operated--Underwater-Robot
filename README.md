🐠 Remotely Operated Underwater Robot using Raspberry Pi
Real-Time Navigation, Live Video Streaming, and Temperature Monitoring 🌊🤖
This project showcases a tethered underwater robot built on a Raspberry Pi 4 running Raspberry Pi OS. Designed for real-time control, live video feedback, and temperature sensing, the robot integrates multiple systems including brushless motors, electronic speed controllers (ESCs), and a waterproof temperature sensor.

The onboard PyQt-based GUI runs directly on the Raspberry Pi and is accessed remotely via RealVNC using a static-IP Ethernet connection. Our design was successfully pool-tested at a depth of 6 feet, showing excellent balance, structural integrity, and accurate environmental data collection.

⚙️ Features
🌀 Four brushless motors controlled via ESCs

🔽 2 for vertical (Z-axis) navigation

🔄 2 mirrored for balanced horizontal (X-Y plane) navigation

🧭 Torque-neutral propulsion achieved through mirrored design

🖥️ Real-time GUI with PyQt, running directly on the Raspberry Pi

📷 Live video feed via Raspberry Pi Camera

🌡️ Waterproof temperature sensor with CSV data logging

🔌 Tethered Ethernet with static IP for GUI control via RealVNC

🔋 Powered by onboard 3S LiPo battery

🧪 Pool Testing Results
🌊 Tested in a 6-foot-deep pool

🧱 No water leakage

📊 Accurate temperature readings recorded

⚖️ Stable and smooth navigation

🔁 Torque canceled effectively using mirrored motors

🧰 Tools & Libraries Used
🐍 Python 3

💠 PyQt5

🧲 RPi.GPIO or pigpio

🎥 OpenCV (optional)

🔗 RealVNC

🖥️ Raspberry Pi OS (Desktop)

Robot

🚀 Future Improvements

🧭 IMU integration for orientation sensing

📶 Wireless communication module

🤖 Autonomous navigation system

☁️ Cloud-based data sync and analytics


Cloud-based data storage and visualization
