# Cataract-Detection-Using-Yolo-v8
# Cataract Detection using YOLOv8

This project implements an automated **Cataract Detection** system using the **YOLOv8 object detection algorithm**. The goal is to detect and classify cataract presence in eye images with high accuracy, assisting ophthalmologists in early diagnosis.

---

## 📌 Overview

- 🔍 **Model**: YOLOv8 (Ultralytics)
- 🧠 **Task**: Object Detection / Image Classification (Cataract vs. Normal)
- 💾 **Framework**: Python, PyTorch, OpenCV
- 📊 **Output**: Bounding boxes over eye regions with cataract detection labels

---

## 🖼️ Sample Output

![Sample Cataract Detection](path_to_output_image.png)

---

## 📂 Project Structure

```bash
cataract-detection-yolov8/
├── datasets/
│   ├── images/
│   └── labels/
├── runs/                   # YOLOv8 training logs and weights
├── yolov8-cataract.ipynb   # Main notebook for training/inference
├── train.py                # Script to train model
├── detect.py               # Script to run inference
├── requirements.txt

