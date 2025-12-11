# FinalProjectComputerVision – YOLO-based Computer Vision Project

This repository contains my final project for the **Computer Vision** course at Afeka Academic College of Engineering.  
The project uses **YOLO** for object detection on a custom dataset.

---

## Project Overview

The project focuses on building an end-to-end pipeline for object detection using YOLO:

- Preparing and organizing a custom dataset in **YOLO format** (images + labels).
- Training YOLO models (e.g. `yolo11n`, `yolov8m`) on this dataset.
- Comparing model performance and analyzing detection quality.
- Running inference on images and visualizing the results.

The repository is centered around a single Jupyter notebook that contains all the main experiments and analysis.

---

## Repository Structure

```text
.
├─ dataset/                         # Custom dataset (images + labels in YOLO format)
├─ yolo_dataset/                    # Additional YOLO-style dataset folder / version
├─ yolo_DATANEW/                    # Newer/alternative processed dataset
├─ runs/
│  └─ detect/                       # YOLO outputs: training/inference results, logs, images
├─ FinalProjectComputerVision.ipynb # Main Jupyter notebook with all experiments
├─ data.yaml                        # YOLO data config (paths, classes, names)
├─ data2.yaml                       # Alternative YOLO data config / split
├─ yolo11n.pt                       # Trained YOLO weights (small model variant)
└─ yolov8m.pt                       # Trained YOLO weights (medium model variant)
