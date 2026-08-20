# Speech Emotion Recognition - A Lightweight CNN Model

This repository contains an speech emotion detection project. The project includes Jupyter Notebooks and a pre-trained model for analyzing emotions from speech.

## Research Paper Link - https://ieeexplore.ieee.org/document/11448083

## Overview

We have developed an emotion classification model based on a CNN architecture.
The primary focus of the project was to design a lightweight model capable of running on devices with limited computational resources.
We have largely succeeded in this goal — the final trained model is less than 5 MB in size without significant compromise on accuracy or performance.

## Files

- `EmotionRecognition.ipynb`: A Jupyter Notebook for emotion detection.
- `emotion_detection_model.h5`: A pre-trained model for emotion detection.

## How to Use

To use the pre-trained model for emotion detection:
1. Clone this repository to your local machine.
2. Open `EmotionRecognition.ipynb` in a Jupyter environment.
3. Follow the instructions in the notebook to load the `emotion_detection_model.h5` file and run the emotion detection analysis.

## Training Information
The model was trained using Kaggle's remote GPU server for faster computation. If you wish to retrain the model, ensure that your system has at least 14 GB of GPU memory to handle the training workload efficiently. You are free to train on any environment, but the hardware requirements must be met for optimal performance.

## License

This project is licensed under [MIT License](LICENSE).
