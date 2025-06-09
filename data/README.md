# data/ — Dataset for Bus Passenger Counter

This folder is used for storing datasets related to the **Bus Passenger Counting System** project. The data includes video footage from the front and back cameras of the bus, used for training, testing, and validating computer vision models.

---

## Data Source

All data used in this project is stored and shared via a Google Drive folder:

🔗 [Click to Access the Dataset](https://drive.google.com/drive/folders/1LzKtqTbhYf6HeKMkgyCEkBGHZ_Gq-fFV?usp=sharing)

>  Access Level: View Only  
>  You cannot upload, modify, or delete files.  
>  You can download and use the data for training, evaluation, or testing.

---

## How to Use

1. **Go to the Google Drive link** above.
2. **Download** the required datasets (e.g., videos or annotations).
3. Place the downloaded files inside this `data/` directory following the structure below:

```bash
data/
├── front_camera/
│   ├── front_001.mp4
│   └── ...
├── back_camera/
│   ├── back_001.mp4
│   └── ...
├── annotations/
│   ├── labels_front.json
│   ├── labels_back.json
│   └── ...
