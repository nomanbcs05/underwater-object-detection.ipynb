# underwater-object-detection.ipynb
This project uses the YOLOv8 deep learning model to detect and classify underwater objects such as marine debris, fish, and submerged structures. Trained on annotated images with varied lighting, turbidity, and depth, the model delivers high accuracy and real-time performance in challenging underwater conditions.
# 🪸 Underwater Object Detection using YOLOv8

## 📘 Overview
This project uses the **YOLOv8** deep learning model to detect and classify **underwater objects** such as marine debris, fish, and submerged structures.  
Trained on annotated images with varied lighting, turbidity, and depth, the model delivers **high accuracy** and **real-time performance** in challenging underwater conditions.  
The results highlight YOLOv8’s effectiveness for **marine research**, **pollution monitoring**, and **autonomous underwater vehicle (AUV)** vision systems.

## 📊 Dataset
- Dataset: [Underwater Object Detection Dataset (Kaggle)](https://www.kaggle.com/code/quydau/underwater-object-detection-with-yolo-v8)
- Format: YOLO annotations (images + labels)
- Includes marine debris, fish, coral reefs, and other underwater structures.

## 🧠 Model Details
- Model: **YOLOv8 (Ultralytics)**
- Framework: **PyTorch**
- Image size: **640×640**
- Epochs: **100**
- Batch size: **16**
- Optimizer: **Adam**
- Learning rate: **0.001**

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/underwater-object-detection.git
