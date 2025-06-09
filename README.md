# Bus Passenger Counter using Computer Vision

This project aims to count the number of passengers entering and exiting buses using front and rear cameras with computer vision techniques.

## 📌 Objectives
- Detect people using front and back cameras.
- Track each person across frames.
- Avoid double-counting by smart merging strategies.
- Output total passenger counts per trip.

## Structure

```
│
├── README.md                → Project overview, setup, how to run
├── .gitignore               → Ignored files (e.g., __pycache__, .env)
├── requirements.txt         → Python dependencies (e.g., opencv-python, torch)
│
├── /src/                    → Source code
│   ├── main.py              → Entry point to run the bus counter
│   ├── counter.py           → Counting logic (in/out detection)
│   ├── camera.py            → Camera handling (front & back)
│   ├── tracking.py          → People tracking (e.g., SORT, Deep SORT)
│   └── utils.py             → Helper functions (drawing, logging, etc.)
│
├── /models/                 → Trained or pre-trained models (YOLO, etc.)
│   └── README.md            → Describe model name, source, size
│
├── /configs/                → Configuration files (e.g., .yaml or .json)
│   └── camera_config.yaml   → Camera IDs, zones, FPS settings
│
├── /datasets/               → Sample input videos/images
│   └── README.md            → Instruction to get the data
│
├── /results/                → Output results (annotated videos, logs)
│
├── /tests/                  → Unit tests
│   └── test_counter.py
│
└── /docs/                   → Documentation
    ├── Bus Passenger Counting System Proposal Report.pdf     → Project Proposal Document
    └── City Bus Research Proposal Presentation.pdf           → Project Proposal Slide Presentation
```

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



hello