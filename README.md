# SMART-RIDE
This project focuses on the development of a multi-dimensional intelligent system integrated with Artificial Intelligence (AI) and the Internet of Things (IoT) to enhance driving safety and comfort.

# SmartRide – AI Driver Drowsiness Detection

## Overview
SmartRide is an intelligent driving assistance system designed to improve road safety by monitoring driver behavior and detecting signs of fatigue. This project focuses on the development of an AI-based driver drowsiness detection module that analyzes facial landmarks and eye movement patterns in real time.

The system detects early symptoms of driver fatigue and provides alerts to prevent potential accidents caused by drowsy driving.

---

## Problem Statement
Driver fatigue is one of the leading causes of road accidents. Traditional monitoring methods rely on manual observation or vehicle-based signals that may not accurately capture a driver's physiological state.

An automated system capable of continuously monitoring the driver and identifying early signs of drowsiness can significantly improve road safety.

---

## Solution
This project proposes an AI-based driver monitoring system that analyzes facial features and eye behavior using computer vision techniques. The system calculates eye-blink frequency and eye closure duration to detect fatigue.

A **Fuzzy Inference System (FIS)** is used to evaluate drowsiness levels and classify the driver's state into different alertness levels.

---

## Key Features
- Real-time driver monitoring using computer vision
- Eye-blink detection and eye closure analysis
- Drowsiness classification using Fuzzy Inference System
- Early warning alerts when fatigue is detected
- Modular design for integration with smart vehicle systems

---

## Methodology

### 1. Face Detection
The system first detects the driver's face from the video stream.

### 2. Facial Landmark Extraction
Facial landmarks are extracted to identify eye regions.

### 3. Eye State Analysis
Eye-related features are computed:
- Eye closure duration
- Blink frequency
- Eye openness ratio

### 4. Drowsiness Detection
A **Fuzzy Inference System** processes these inputs to determine the driver's fatigue level.

---

## Technologies Used

- Python
- OpenCV
- MediaPipe / Facial Landmark Detection
- Fuzzy Logic
- NumPy
- Computer Vision

---

## Results
The system successfully detects abnormal eye behavior and identifies drowsiness patterns in real time. The fuzzy logic model allows flexible classification of fatigue levels based on driver behavior.

---

## Project Structure

