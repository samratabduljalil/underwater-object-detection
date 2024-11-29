# Underwater Object Detection

This project focuses on detecting underwater objects using two different approaches: **YOLO** (You Only Look Once) and **Detectron**. The goal is to accurately identify and classify objects submerged in aquatic environments. Special techniques, including data augmentation, were applied to enhance model performance with Detectron.

---

## Features

1. **YOLO**:
   - Utilized for real-time underwater object detection.
   - Efficient and fast object detection suitable for resource-constrained environments.

2. **Detectron**:
   - A powerful object detection framework used for underwater object classification and segmentation.
   - Integrated with **data augmentation** techniques to improve detection accuracy in diverse underwater conditions.

3. **Data Augmentation**:
   - Applied to enhance the training dataset for Detectron, including transformations like rotation,  flipping, and brightness adjustment, to simulate real-world underwater variations.

---

## How It Works

1. **YOLO-Based Detection**:
   - Uses a pre-trained YOLO model fine-tuned on an underwater dataset.
   - Efficiently detects and classifies underwater objects with real-time inference.

2. **Detectron with Augmentation**:
   - Detectron model trained with enhanced datasets created using augmentation techniques.
   - Provides robust detection, even in challenging underwater conditions like murky water or varying lighting.

---
