# NutriLens

*An AI-powered food detection and calorie estimation platform built for comparative analysis of deep learning models and datasets for Indian food recognition.*

| Resource              | Link                                                          |
| --------------------- | ------------------------------------------------------------- |
| 🌐 Live Demo          | https://nutrients-frontend.vercel.app/                        |
| 🤗 Hugging Face Space | https://huggingface.co/spaces/nix2205/nutrilens-api/tree/main |

---

## Overview

NutriLens is a research-driven food recognition platform that combines computer vision, deep learning, and nutritional analysis to identify food items from images and estimate their nutritional content.

Unlike traditional food recognition systems, NutriLens was designed as a flexible evaluation platform where different CNN architectures and datasets can be tested, compared, and deployed through a common interface.

The project focuses on Indian food recognition, addressing the challenges posed by diverse cuisines, complex textures, and visually similar dishes. The system performs food detection, classification, confidence-based prediction, portion estimation, and calorie calculation from a single image.

---

## Research Objective

The primary goal of this research was to perform a comparative analysis of multiple deep learning architectures and determine the most effective model for Indian food recognition.

The study evaluated:

* RegNetY-400MF
* EfficientNet-B0
* GoogLeNet
* MobileNet
* ShuffleNet
* MNASNet

using multiple performance metrics including:

* Top-1 Accuracy
* Top-5 Accuracy
* Precision
* Recall
* F1 Score
* Inference Time
* Computational Efficiency

The best-performing architecture was then integrated into the deployed application.

---

## Key Features

* Food detection using YOLO-based object detection
* Automatic bounding box generation
* Deep learning-based food classification
* Confidence score visualization
* Portion size estimation
* Calorie estimation
* Nutritional information mapping
* Multiple food item detection
* Real-time web interface
* Comparative model evaluation framework
* Plug-and-play architecture for testing different trained models

---

## Datasets Used

### Khana Dataset

* ~131,000 images
* 80 Indian food categories
* Primary dataset used for Indian cuisine recognition

### Food-101 Dataset

* 101,000 images
* 101 food categories
* Used for benchmarking and comparison

### Indian Food Images Dataset

* ~4,000 images
* 80 Indian food classes
* Used to improve Indian food classification performance

The combination of these datasets helped improve model robustness and generalization for real-world food recognition scenarios.

---

## System Workflow

1. User uploads a food image.
2. YOLO identifies food regions and generates bounding boxes.
3. Detected food regions are passed to the classification model.
4. The selected CNN architecture predicts food categories.
5. Confidence scores are generated for predictions.
6. Portion size is estimated.
7. Nutritional information is mapped.
8. Calories and macronutrient values are displayed.

---

## Technology Stack

### Frontend

HTML | CSS | JavaScript

### Backend

Python | FastAPI

### Computer Vision

YOLO | OpenCV

### Deep Learning

PyTorch | CNN Architectures

### Models Evaluated

RegNetY-400MF | EfficientNet-B0 | MobileNet | GoogLeNet | ShuffleNet | MNASNet

### Deployment

Vercel | Hugging Face Spaces

---

## Why NutriLens?

Most food recognition systems only focus on classification.

NutriLens was designed as a reusable research platform where different datasets and trained models can be swapped and evaluated through a common interface. This enables researchers and developers to:

* Compare CNN architectures
* Benchmark new datasets
* Evaluate model performance
* Analyze confidence scores
* Deploy improved food recognition models without rebuilding the application

---

## Applications

* Dietary Assessment
* Calorie Tracking
* Nutrition Monitoring
* Healthcare Systems
* Fitness Applications
* Obesity Management
* Food Recognition Research

---

## Screenshots

### Uploading Interface

<img width="1914" height="864" alt="image" src="https://github.com/user-attachments/assets/a05184f4-977d-4ea1-872a-24e2c5146f83" />

### Results
<img width="1895" height="872" alt="image" src="https://github.com/user-attachments/assets/e09e748b-2f8f-46be-82f6-ce3761297323" />


---

## Future Work

* Larger Indian food datasets
* Transformer-based architectures
* Real-time video analysis
* Personalized dietary recommendations
* Mobile application integration
* Cloud-based nutrition tracking

---

## Developed With

Python • PyTorch • YOLO • OpenCV • FastAPI • Computer Vision • Deep Learning
