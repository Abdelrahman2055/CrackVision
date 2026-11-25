# A Classical Digital Image Processing Framework for Concrete Crack Detection, Segmentation, and Analysis

## Project Overview
This project aims to develop a classical Digital Image Processing framework for detecting, segmenting, and analyzing cracks in concrete surfaces.

The project focuses on traditional image processing techniques without using Deep Learning models.

## Problem Statement
Concrete cracks can affect the safety and durability of structures. Detecting and analyzing these cracks through image processing can help identify damaged areas and support structural inspection.

## Dataset
- **Dataset:** Concrete400
- **Total Images:** 379
- **Image Resolution:** 512 × 512 pixels
- **Ground Truth:** Pixel-level segmentation masks
- **Source:** [Concrete400 Dataset – Zenodo](https://zenodo.org/records/21193945)

## Main Objectives
- Analyze concrete surface images.
- Apply image enhancement and preprocessing techniques.
- Investigate noise and frequency-domain characteristics.
- Detect and segment concrete cracks using classical image processing.
- Apply morphological operations.
- Measure and analyze detected crack regions.
- Evaluate segmentation performance using Intersection over Union (IoU).

## Technologies and Tools
- Python
- Google Colab
- NumPy
- OpenCV
- Matplotlib
- SciPy
- Scikit-image
- Pandas
- GitHub

## Evaluation Metric
The primary evaluation metric is **Intersection over Union (IoU)**, which measures the overlap between the predicted crack segmentation and the ground-truth mask.

## Team
This project is developed by a team of six members as part of the Digital Image Processing course.

## Project Status
Currently in the dataset preparation and image analysis stage.
