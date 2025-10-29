---
title: "Research Intern - Vehicle Indicator Detection System"
excerpt: "Developed and benchmarked state-of-the-art YOLO and Transformer models (RT-DeTR) for real-time vehicle turn indicator detection to enhance Intelligent Transportation Systems (ITS)."
collection: portfolio
date: 2024-12-30 
---

<!-- <img src="/images/vehicle_detection_system.png" alt="Diagram or demonstration of the Vehicle Indicator Detection System." style="max-width: 100%; height: auto; margin-bottom: 20px;"> -->

## Project Overview

This project focused on advancing **Intelligent Transportation Systems (ITS)** by creating a highly accurate and stable **Deep Learning system** capable of detecting vehicle turn indicators from challenging real-world video and image data. The core deliverable involved a rigorous comparative analysis of leading object detection and multi-object tracking frameworks to identify the optimal solution for real-time deployment.

### Technology Stack

* **Primary Tools:** YOLOv12, RT-DeTR, BoT-SORT, ByteTrack
* **Languages:** Python
* **Concepts:** Deep Learning, Computer Vision, Multi-Object Tracking (MOT)
* **Pre-processing:** CLAHE, Bilateral Filtering, Wiener Filtering

## Key Achievements & Findings

* **Model Benchmarking:** Systematically **trained, validated, and comparatively analyzed** four cutting-edge object detection models: YOLOv8, YOLOv11, YOLOv12, and RT-DeTR on a custom dataset.
* **Optimal Solution Identified:** Identified **YOLOv12** as the optimal model, which provided the best balance between detection accuracy and stable bounding box localization crucial for ITS applications.
* **Real-time Tracking:** Implemented and evaluated multi-object tracking algorithms (**ByteTrack and BoT-SORT**) to ensure stable, real-time tracking performance in sequential video analysis.
* **Problem Mitigation:** Successfully diagnosed and resolved **severe overfitting and validation instability** encountered during the initial investigation of a CNN-LSTM model, enabling a successful pivot to superior object detection frameworks.

<br>

## Technical Deep Dive: Key Skills Demonstrated

The research involved proficiency across the entire computer vision pipeline:

| Skill Category | Demonstrated Expertise |
| :--- | :--- |
| **Deep Learning** | Training, testing, and rigorous validation of neural networks. |
| **Object Detection** | Implementing and comparing state-of-the-art models (YOLOv12 vs. RT-DeTR). |
| **Multi-Object Tracking** | Evaluating tracking algorithms (ByteTrack and BoT-SORT) for sequential data. |
| **Model Evaluation** | Benchmarking performance using metrics like Precision, Recall, mAP@50, and mAP@50-95. |
| **Data Preprocessing**| Applying image enhancement techniques (CLAHE, Bilateral/Wiener Filtering) to improve model robustness. |

---
