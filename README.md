# Intelligent-Secure-Management-System
An autonomous drone-based inventory system using Python and OpenCV to automate real-time stock verification with real time data listing.
# Intelligent Management Secure System 🚁

### 🚀 Autonomous Drone-Based Inventory Automation

*Intelligent Management Secure System* is a cutting-edge Computer Vision solution designed to automate the tedious process of warehouse inventory tracking. By integrating a commercial drone (Nabhyan Pro) with a custom Python processing engine, this system replaces manual stock verification with an autonomous aerial surveillance unit.

### 🔑 Key Innovation: The "Digital Bridge"
The biggest challenge in using commercial drones is their encrypted video feed. I engineered a novel *"Digital Bridge"* architecture using *Scrcpy* and *USB Tethering. This bypasses proprietary encryption, allowing the drone's video to be processed on a laptop with **Zero-Latency* and high definition.

---

### 🌟 Main Features

* *⚡ Zero-Latency Video Feed:* Real-time processing of drone footage without lag.
* *📷 Live QR & Barcode Detection:* Instantly detects and decodes tags using PyZbar.
* *🛡️ Intelligent Security Logic:*
    * *Green Box:* Verified Item (Matches Database).
    * *Red Box:* Intruder / Unknown Item (Security Alert).
* *📊 Automated Reporting:* Generates a timestamped .csv Excel report of all scanned items automatically.
* *🖥️ Sci-Fi HUD Interface:* A professional "Command Center" dashboard overlay for the operator.

### 🛠️ Tech Stack

* *Language:* Python 3.10+
* *Computer Vision:* OpenCV (cv2), NumPy
* *Decoding:* PyZbar
* *Screen Capture:* MSS
* *Bridge Tool:* Scrcpy (Android Mirroring)

### 📸 How It Works
1.  The drone flies over inventory shelves.
2.  Video is transmitted to the phone and bridged to the laptop via USB.
3.  The Python script scans the screen 30 times per second.
4.  Valid items are logged; invalid items trigger an alert.
