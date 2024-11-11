# GB Road Condition Detection Using YOLOv8 🚗🛣️

This repository contains a deep learning project aimed at detecting and classifying road conditions in the mountainous region of Gilgit Baltistan (GB), Pakistan, using the YOLOv8 object detection model. The primary goal of this project is to improve road safety by accurately identifying and classifying various road conditions, such as sharp turns, slopes, and hazardous areas, to inform drivers and local authorities.

---

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## 📖 Project Overview

### Objective
This project aims to detect and classify road conditions to support safer travel in the mountainous terrains of GB, where road conditions can be unpredictable and dangerous.

### Model
The project utilizes the **YOLOv8** model from the **Ultralytics** library, renowned for its fast and accurate object detection capabilities. This pre-trained model has been fine-tuned on a custom dataset of GB road images, making it specifically effective at identifying conditions in similar environments.

---

## 🚀 Features

- **Accurate Road Condition Detection**: Identifies different road types, including sharp turns, curves, slopes, flat terrain, and hazardous conditions.
- **Real-Time Processing Potential**: The YOLOv8 model's lightweight architecture allows for real-time detection capabilities.
- **Custom Dataset**: Utilizes a unique dataset of road conditions from the GB region, tailored for mountainous road conditions.

---

## 📂 Dataset

### Description
The dataset used for this project includes various images of roads in different conditions specific to the GB region. Images are categorized into five classes:
1. **Sharp Turns**
2. **Curved Roads**
3. **Steep Slopes**
4. **Flat Terrain**
5. **Hazardous Conditions**

> Note: Due to the unique nature of the GB region, this dataset may not be publicly available. However, users can use similar datasets or capture their own images for training.

### Structure
Once downloaded, organize the dataset as follows:
```plaintext
data/
├── images/
│   ├── train/
│   ├── valid/
│   └── test/
└── labels/
    ├── train/
    ├── valid/
    └── test/

