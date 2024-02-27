# Satellite Aircraft Detection with YOLOv8

## Table of Contents

  * [1. Project Overview](#1-project-overview)
  * [2. Key Features](#2-key-features)
  * [3. Dataset](#3-dataset)
  * [4. Model Performance Results](#4-model-performance-results)
  * [5. Getting Started](#5-getting-started)

## 1. Project Overview

Welcome to the Satellite Aircraft Detection project. This initiative is focused on combining Earth Observation imagery analysis with the latest in Deep Learning technology, specifically using the Ultralytics implementation of [YOLOv8](https://www.ultralytics.com/blog/ultralytics-yolov8-turns-one-a-year-of-breakthroughs-and-innovations) model for detecting aircraft in satellite images. This project demonstrates a practical approach to leveraging AI for remote sensing tasks.

## 2. Key Features:

- **Advanced Object Detection:** Utilizes YOLOv8 for high-accuracy aircraft detection.

- **Efficient Data Handling:** Demonstrates processing of large satellite images through tiling.

- **Detailed Data Preparation:** Focuses on meticulous data annotation.

- **Comprehensive Model Evaluation:** Employs key metrics for in-depth performance analysis.

- **Interactive Experiment Tracking:** Features experiment tracking with TensorBoard.

## 3. Dataset

The project uses a high-resolution satellite image dataset from the [Airbus Aircraft Sample Dataset](https://www.kaggle.com/datasets/airbusgeo/airbus-aircrafts-sample-dataset), emphasizing a variety of aircraft types and imaging conditions to test YOLOv8's capabilities in Earth Observation imagery.

## 4. Model Performance Results

The model's performance was evaluated based on several key metrics, which provide insights into its ability to accurately detect aircraft in satellite images. The results are as follows:

- **Precision:** 72.8% - High accuracy in identifying relevant objects.

- **Recall:** 70.8% - Effectively detects a significant proportion of actual aircraft.

- **mAP50:** 70.7% - Indicates a balanced precision and recall at a moderate IoU threshold.

- **mAP50-95:** 44.5% - Shows consistent performance across a range of detection strictness.

- **Fitness:** 47.1% - A composite metric highlighting the model's overall effectiveness.

These results were achieved with a streamlined approach, balancing performance with computational efficiency, and lay a strong foundation for future enhancements.

## 5. Getting Started

To get started with the Satellite Aircraft Detection project, follow

1. **Clone the Project Repository**

   ```bash
   git clone https://github.com/riaa3102/satellite-aircraft-detection-yolov8.git
   ```

2. **Set Up the Environment**

   ```bash
   pip install -r requirements.txt
   ```

4. **Data Preparation and Exploration**

   ```bash
   jupyter lab notebooks\Aircraft_EDA.ipynb
   ```
   
5. **Train the YOLOv8 Model**

   ```bash
   jupyter lab notebooks\Aircraft_YOLOv8_Training.ipynb
   ```
   
6. **Experiment Tracking with TensorBoard**

   ```bash
   tensorboard --logdir notebooks\runs\detect
   ```
   
View in your browser at [localhost:6006](http://localhost:6006/).

For any questions or additional information needed, reaching out is always welcome!