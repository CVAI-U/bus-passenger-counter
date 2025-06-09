# Bus Passenger Counter using Computer Vision

This project aims to count the number of passengers entering and exiting buses using front and rear cameras with computer vision techniques.

## 📌 Objectives
- Detect people using front and back cameras.
- Track each person across frames.
- Avoid double-counting by smart merging strategies.
- Output total passenger counts per trip.

## 🔧 Tech Stack
- Python
- OpenCV
- YOLOv8 / YOLOv5 (object detection)
- DeepSort / ByteTrack (object tracking)
- NumPy, Pandas

## 🚀 Getting Started
```bash
git clone https://github.com/CVAIC/bus-passenger-counter.git
cd bus-passenger-counter
pip install -r requirements.txt