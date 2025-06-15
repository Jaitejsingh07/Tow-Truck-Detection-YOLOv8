# YOLOv8-based Tow Truck Detection - An E-Challan Knowledge Gap

This project explores the application of the YOLOv8 model for real-time tow truck detection within the context of an E-Challan system. Tow truck detection is a critical aspect of traffic management, especially in emergency scenarios, breakdowns, and accidents. The YOLOv8 model, known for its accuracy and speed, is leveraged to address the knowledge gap in this specific domain.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
  - [YOLOv8 Framework](#yolov8-framework)
  - [Dataset Description](#dataset-description)
  - [Benchmarking](#benchmarking)
- [Performance Evaluation and Results](#performance-evaluation-and-results)
- [Conclusion](#conclusion)

## Introduction

In the realm of computer vision and intelligent traffic management, precise vehicle detection is crucial. This project focuses on the application of YOLOv8, an evolution in the YOLO series, to fill the research gap in tow truck detection within E-Challan systems. The study includes innovative features and adaptations of YOLOv8, a curated dataset, and benchmarking of different YOLOv8 models for comprehensive tow truck detection.

## Methodology

### YOLOv8 Framework

The YOLOv8 framework is at the core of this project, integrating innovative features like the CSPDarknet53 backbone, PAN-FPN structure, and anchor-free detection. The detection head utilizes Binary Cross-Entropy Loss and Distribution Focal Loss with Complete Intersection over Union for bounding box regression. The framework's extensibility allows seamless switching between different versions, making it adaptable for various scenarios.

### Dataset Description

The dataset for training and evaluation comprises 2000 images sourced from images.cv, shutterstock.com and internet-sourced videos, focusing on tow truck instances. The images are categorized into two classes: "tow truck" and "tow truck with vehicle." The dataset forms the basis for training YOLOv8 models.

### Benchmarking

Three YOLOv8 models—YOLOv8n, YOLOv8s, and YOLOv8m—are benchmarked for tow truck detection. Each model serves a specific purpose, exploring trade-offs between resource efficiency, speed, and comprehensive detection. The benchmarking involves iterative training, adjusting weights, and optimizing parameters. Evaluation metrics, including mAP-50 and mAP50-95, provide insights into the accuracy of tow truck detection.

## Performance Evaluation and Results

This section showcases the effectiveness of the YOLOv8-based tow truck detection system. Evaluation metrics such as mAP-50, mAP50-95, precision, and recall quantify the accuracy of tow truck detection. YOLOv8s emerges as the standout model, exhibiting superior performance.


| Model    | mAP-50 | mAP50-95 | Precision | Recall |
|----------|--------|----------|-----------|--------|
| YOLOv8n  | 0.885  | 0.70     | 0.80      | 0.78   |
| YOLOv8s  | 0.895  | 0.72     | 0.81      | 0.86   |
| YOLOv8m  | 0.894  | 0.71     | 0.89      | 0.73   |

**Note:** The performance metrics include mean Average Precision (mAP-50), mean Average Precision across a range of IoU thresholds (mAP50-95), Precision, and Recall. YOLOv8s stands out as the most adept model, exhibiting superior performance with a mAP-50 of 0.895, mAP50-95 of 0.72, precision at 0.81, and recall at 0.86.

## Conclusion

This research contributes to the field of intelligent traffic management by addressing the knowledge gap in tow truck detection. The YOLOv8 model, with its accuracy, precision, and recall, proves to be a promising solution for real-time tow truck detection in E-Challan systems. The study emphasizes the significance of tow truck detection in traffic rule enforcement and showcases the potential of YOLOv8 in enhancing traffic management.

Feel free to clone, fork, and contribute to this project. For any questions or collaborations, contact [Jaitej Singh and 21it180@charusat.edu.in].
