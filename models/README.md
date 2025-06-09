# models/ — Bus Counter Detection Models

This folder contains pre-trained and fine-tuned models used in the **Bus Passenger Counting System**. These models are responsible for detecting and tracking people entering and exiting through the front and back cameras.

---

## Contents

| Filename                  | Description                             | Source/Framework       |
|--------------------------|-----------------------------------------|------------------------|
| `yolov5s.pt`             | YOLOv5 small model for real-time use    | Ultralytics YOLOv5     |
| `mobilenet_tracker.pth`  | Lightweight tracker backbone            | PyTorch                |
| `sort_model.pkl`         | Tracking model used with SORT algorithm | Custom / Local training|

---

## Model Usage

All models are loaded by the detection/tracking module in the `src/` directory.

```python
# Example usage
from yolov5 import load_model
model = load_model('models/yolov5s.pt')
```