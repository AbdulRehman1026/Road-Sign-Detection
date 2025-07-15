# 🚦 Road Sign Detection using YOLOv8 and Faster R-CNN

This project implements a robust road sign object detection system using **two complementary deep learning models**:

- ✅ **YOLOv8 (Ultralytics)** – Real-time, single-stage detection  
- ✅ **Faster R-CNN (TorchVision)** – Accurate, two-stage detection

Both models are trained and evaluated on a custom-labeled dataset containing **877 images** across **4 road sign classes**.

---

## 📂 Dataset Overview

- **Total Images:** 877  
- **Format:** Pascal VOC (XML → converted to YOLO format)  
- **Split:**
  - `train`: 701 images
  - `val`: 89 images
  - `test`: 87 images  
- **Classes:**
  1. `Traffic Light`
  2. `Stop`
  3. `Speed Limit`
  4. `Crosswalk`

All images and bounding box annotations are organized under the `Dataset/` folder:

