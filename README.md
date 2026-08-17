# YOLOv8s VisDrone — Jetson Nano Deployment

This repository contains the trained YOLOv8s object-detection model, test images, and inference script prepared for deployment and testing on an NVIDIA Jetson Nano.

The model was trained/fine-tuned on the VisDrone dataset for aerial object detection.

The repository is structured so that it can be cloned directly onto the Jetson Nano, allowing the model, test images, and inference script to be transferred together.

---

## Project Overview

The current deployment workflow is:

```text
VisDrone Dataset
       |
       v
YOLOv8s Training / Fine-tuning
       |
       v
Trained Model
visdrone.pt
       |
       v
GitHub Repository
       |
       v
Clone Repository on Jetson Nano
       |
       v
Run YOLOv8s Inference
       |
       v
126 Test Images
       |
       v
Object Detection Results
