# Emotion Detection using YOLOv8

This repository contains a project aimed at detecting human emotions in real-time using the YOLOv8 model. The model is trained to classify four distinct emotions: `angry`, `happy`, `sad`, and `surprised`. 

## Table of Contents
- [Overview](#overview)
- [Model Architecture](#model-architecture)
- [Dataset](#dataset)
- [Training](#training)
- [Usage](#usage)
  - [Installation](#installation)
  - [Running the Model](#running-the-model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview
Emotion recognition is a critical task in various fields like mental health, security, and human-computer interaction. This project leverages the YOLOv8 model, a state-of-the-art object detection algorithm, to classify emotions from images or video streams.

The YOLOv8 model has been trained to detect the following emotions:
- **Angry**
- **Happy**
- **Sad**
- **Surprised**

## Model Architecture
We used the YOLOv8 architecture, which offers superior speed and accuracy for real-time object detection. The model was fine-tuned to detect facial features and classify them into the aforementioned emotions.

## Dataset
The model was trained on a custom dataset containing images annotated with facial expressions representing different emotions. The dataset includes a diverse set of images representing the following classes:
- Angry
- Happy
- Sad
- Surprised

The dataset is split into training, validation, and test sets to ensure the model generalizes well to unseen data.

## Training
The YOLOv8 model was trained using the following key parameters:
- **Batch size**: 16
- **Image size**: 640x640
- **Epochs**: 100
- **Learning rate**: 0.001

### Model Performance
The model achieved high accuracy in detecting emotions across various test images, demonstrating the effectiveness of YOLOv8 for this task.

## Usage

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/Musawer1214/Emotion-Detection.git
   cd Emotion-Detection-yolov8
