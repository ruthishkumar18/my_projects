Defect Detection in Steel using YOLOv11
Overview:
This project implements YOLOv11 for defect detection in steel using two datasets, NEU and Severstal. The goal is to detect and classify defects with high accuracy. The datasets were prepared and augmented to enhance their quality and diversity, with all training and evaluation performed on Google Colab.
Datasets:
1. NEU Dataset
Annotations: Provided with the original dataset.
Augmentation: Applied to increase diversity and improve generalization.
Access NEU Dataset
Augmented NEU Dataset
2. Severstal Dataset
Annotations: Manually created for 2,000 images.
Augmentation: Performed after annotation to increase dataset size and variability.
Access Severstal Dataset
Augmented Severstal Dataset
Tools Used
Google Colab: For training and evaluation of the YOLOv11 model.
Roboflow: For dataset preparation and augmentation.
Ultralytics: For implementing YOLOv11 using their powerful object detection framework.
YOLOv11 Framework: For defect detection using a state-of-the-art object detection architecture.
Python Libraries: TensorFlow, Matplotlib, NumPy, OpenCV, and other essential libraries.
Data Augmentation
To enhance the datasets, the following augmentations were applied using Roboflow:

Resizing: (640 x 640)
Rotation: ±5°
Horizontal and vertical flipping
Brightness adjustment: ±5%
Shearing: ±5%
These augmentations helped improve the generalization ability of the YOLOv11 model by diversifying the dataset.
Analysis
NEU Dataset: Achieved higher accuracy due to simpler defect patterns and smaller dataset size.
Severstal Dataset: Lower performance is attributed to:
Greater dataset size and variability.
Complex defect patterns.
Potential inconsistencies introduced by manual annotations.
