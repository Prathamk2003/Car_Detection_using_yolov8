# Car Object Detection using YOLOv8 

This project performs object detection on images of cars using the YOLOv8 architecture from the Ultralytics library. It includes a pipeline for training, evaluation, and visualization.

---

## 🚀 Features

- - YOLOv8-based object detection
- Custom dataset integration
- Real-time detection window for analyzing live or sample input
- Trained `.pt` model saved for reuse — no need to retrain every time
- Bounding box and confidence visualization
- Training, testing, and evaluation workflows
---

## 🛠️ Installation & Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/car-object-detection-yolov8.git
   cd car-object-detection-yolov8
    ```

## Install dependencies:

```bash
pip install -r requirements.txt
```
If requirements.txt is not present, you can manually install:

```bash
pip install ultralytics numpy pandas
```

## Dataset Setup:

Ensure the dataset (images and annotations) is placed in an accessible folder structure like:
```
dataset/
├── images/
│   ├── train/
│   └── val/
└── labels/
    ├── train/
    └── val/
```

## 📊 Model
Architecture: YOLOv8 (You Only Look Once, Version 8)
Library: Ultralytics
Training: Trains on a custom dataset of car images
Output: Trained weights, metrics, and detection results

## 📁 Folder Structure (Expected)

```bash
car-object-detection-yolov8/
│
├── dataset/               # Images and labels in YOLO format
├── runs/                  # YOLO training outputs
├── yolov8_car_detection.ipynb
├── README.md
└── requirements.txt
```
## Run the Notebook:

Open and execute yolov8_car_detection.ipynb in Jupyter Notebook or VS Code. The notebook will:

Train a YOLOv8 model on the dataset

Save the trained model to a .pt file (e.g., best.pt)

Launch a real-time detection window for inference and visualization

## 🎯 Output

A trained YOLOv8 model saved as best.pt

Real-time object detection window for live testing

Detection results and annotated frames

Training metrics and logs saved in the runs/ directory
