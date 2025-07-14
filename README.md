# Smart Cane for the Visually Impaired

An offline-first assistive navigation system using a camera, ultrasonic sensor on a servo, and voice feedback — built on Raspberry Pi.

## 🧠 Features
- Real-time object detection with bounding boxes
- Distance sensing with ultrasonic sweep
- Terrain detection (stairs, slopes, edges)
- Spoken instructions via headset
- Visual path confirmation
- Fully offline (no internet needed)
- Auto-start on boot (via systemd service)

## 🛠 Requirements
- Raspberry Pi 4 Model B
- Camera (USB or PiCam)
- Ultrasonic Sensor (e.g. HC-SR04)
- Servo Motor (for scanning)
- Headset or speaker for audio
- Python 3.9+

## 📦 Setup

```bash
# Clone the repo
git clone https://github.com/JosephMponda/smart-cane.git
cd smart-cane

# Install dependencies
pip3 install -r requirements.txt
