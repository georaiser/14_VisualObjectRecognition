# 14_VisualObject_VOC2012
# Faster R-CNN & Mask R-CNN for Object Detection and Segmentation

Welcome to our implementation of advanced object detection and instance segmentation using **Faster R-CNN** and **Mask R-CNN** on the Pascal VOC dataset. 
---

## 📋 **Features**
- **Faster R-CNN:** Robust object detection using ResNet-50 backbone.
- **Mask R-CNN:** Pixel-level segmentation for instance-level insights.
- **Pascal VOC Dataset:** Focused on balanced subsets for key object categories.
- **Performance Evaluation:** Detailed metrics including mAP, IoU, Precision, and Recall.

---

## 📂 **Project Structure**
```
|-- MaskRCNN_VOC.py                # Training and fine-tuning Mask R-CNN
|-- MaskRCNN_VOC_Inference.py      # Inference and visualization for Mask R-CNN
|-- FasterRCNN_VOC.py              # Training and fine-tuning Faster R-CNN
|-- README.md                      # Project documentation
```

---

## 🚀 **Getting Started**

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- PyTorch 1.10+
- torchvision 0.11+
- Additional packages: `matplotlib`, `numpy`, `pandas`, `opencv-python`, `memory-profiler`, `Pillow`

---

## 📊 **Results**
- **Metrics:** mAP, IoU, Precision, Recall, and Dice Coefficient.
- **Visualization:** Bounding boxes and segmentation masks overlayed on input images.

---

## 🛠 **Customization**
- **Backbone Fine-tuning:** Adjust `trainable_backbone_layers` for ResNet-50.
- **Data Augmentation:** Modify preprocessing in `ResizeNormalizeTransform`.
- **Hyperparameters:** Update learning rate, batch size, or epochs in `Config`.

---
 [![VisualObjectRecognition](https://github.com/georaiser/14_VisualObjectRecognition/blob/master/FasterRCNN_MaskRCNN.gif?raw=true)](https://github.com/georaiser/14_VisualObjectRecognition)
---
