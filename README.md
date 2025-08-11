# YOLOv5 Object Detection in Google Colab

This notebook demonstrates how to use the pre-trained YOLOv5s model for object detection on images using PyTorch, OpenCV, and Matplotlib in a Google Colab environment.

---

## Features

- Detect objects like **person**, **car**, and **dog** in images.
- Draw bounding boxes with class labels and confidence scores.
- Upload images directly in Colab and get instant detection results.
- Save and display the processed image with bounding boxes.

---

## Installation

Run this cell to install the required dependencies:

```python
!pip install torch torchvision opencv-python matplotlib
