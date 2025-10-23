# Face-Mask-Detection-YOLO-ResNet-MobileNet

Face Mask Detection using **MobileNetV2**, **ResNet50**, and **YOLOv5** — a deep learning-based system that classifies and detects people wearing masks, not wearing masks, or wearing masks incorrectly using TensorFlow, Keras, OpenCV, and Ultralytics YOLO. This project can be used for real-time mask monitoring in public spaces.

---

## 📝 Overview
This project performs two types of face mask detection:

1. **Image Classification (MobileNetV2 & ResNet50)**  
   - Classifies images into three categories:  
     - `with_mask`  
     - `without_mask`  
     - `mask_weared_incorrect`
   - Uses **Transfer Learning** with pretrained CNN models.
   
2. **Object Detection (YOLOv5)**  
   - Detects and localizes faces in images/videos with bounding boxes and class labels.
   - Uses **YOLOv5** pretrained weights and fine-tunes on the dataset.

---

## 📂 Repository Structure
