# Disaster Damage Assessment using Satellite Imagery

## Overview

This project uses Deep Learning to automatically detect and classify disaster damaged buildings from satellite imagery.

The system leverages xBD/xView2 datasets and segmentation networks for building localization and damage assessment.

---

## Models Implemented

- U-Net
- VGG16 + U-Net
- EfficientNet-B0
- Attention U-Net
- Siamese Network
- DeepLabV3+

---

## Dataset

xBD Dataset

https://xview2.org

---

## Workflow

![Architecture](assets/architecture.png)

---

## Attention U-Net

![Attention U-Net](assets/attention_unet.png)

---

## Performance

| Metric | U-Net |
|----------|----------|
| Accuracy | 99.33% |
| Precision | 74.69% |
| Recall | 67.81% |
| F1 Score | 71.08% |
| IoU | 55.13% |
| Dice | 71.08% |

![Metrics](assets/performance_metrics.png)

---

## Segmentation Results

![Results](assets/segmentation_output.png)

---

## Damage Classification Map

![Damage Map](assets/damage_map.png)

---

## Research Report

Full report available in:

paper/Disaster_Damage_Assessment_Report.pdf

---

## Technologies

Python
TensorFlow
Keras
OpenCV
Satellite Imagery
Deep Learning
Computer Vision
