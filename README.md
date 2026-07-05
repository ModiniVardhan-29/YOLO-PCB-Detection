
YOLO-PCB-Detection/
│
├── README.md
│
├── dataset/
│   └── sample_images/
│       ├── image1.jpg
│       
│
├── project_code/
│   └── Project.ipynb
│
├── results/
│   ├──



Overview

Printed Circuit Boards (PCBs) are the foundation of modern electronic devices. Ensuring the quality of PCBs is crucial for maintaining product reliability and reducing manufacturing costs. Manual inspection of PCB defects is time-consuming, labor-intensive, and prone to human error.

This project presents an automated PCB defect detection system using the YOLOv8 object detection framework. The model is trained to identify and classify PCB defects with high accuracy, enabling faster and more reliable quality inspection in industrial manufacturing environments.

Problem Statement

Traditional PCB inspection methods rely heavily on manual visual examination or specialized inspection systems, which can be expensive and difficult to scale.

The objective of this project is to develop an efficient computer vision-based solution capable of automatically detecting PCB defects in real time, thereby improving inspection accuracy, reducing human intervention, and increasing manufacturing productivity.

Objectives
Develop an automated PCB defect detection system using YOLOv8.
Detect and classify multiple PCB defect categories accurately.
Reduce dependency on manual inspection processes.
Optimize the trained model for efficient deployment.
Enable real-time defect detection for industrial applications.
Evaluate model performance using standard object detection metrics.
Achievements
Successfully trained a YOLOv8-based PCB defect detection model.
Achieved 98.5% mAP@0.5 on the test dataset.
Built a lightweight model suitable for edge deployment.
Exported the trained model to ONNX format (~12 MB).
Achieved approximately 10 FPS inference speed on Raspberry Pi 5.
Developed a scalable solution for automated PCB quality inspection.


Download the repo as a zip file to access the code.
