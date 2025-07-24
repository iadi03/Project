🌾 Smart Weed Detection Using YOLOv5
This repository contains a computer vision project that detects crops and weeds in agricultural field images using YOLOv5. The aim is to enable targeted pesticide spraying, reducing chemical use and improving food safety.

🔍 Problem Statement
Traditional pesticide application sprays the entire field, often affecting healthy crops and leaving behind harmful residues. This project addresses the problem by developing a system that detects and classifies weeds separately from crops, allowing pesticides to be sprayed only where necessary.

🎯 Objectives
Detect and classify crops and weeds from aerial or field images.

Use object detection to localize weeds precisely.

Reduce pesticide use and minimize crop contamination.

🧠 Dataset
Total Images: ~1300 (512x512)

Classes: crop, weed

Format: YOLO (images + labels)

Data split into train and val sets

🛠️ Tools & Technologies
YOLOv5n (Ultralytics)

PyTorch

Google Colab

OpenCV

LabelImg for annotation

✅ Results
Successful detection of weed and crop bounding boxes
