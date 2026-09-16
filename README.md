# Pedestrian Crossing Prediction for Delivery Fleet Safety

## Overview
This repository contains the code and experiments for my Bachelor's thesis at 
HAMK University of Applied Sciences.

The thesis investigates whether short-term temporal visual information improves 
early prediction of pedestrian crossing behavior compared with single-frame 
perception, using lightweight computer vision models evaluated on the PIE dataset.

## Research Question
Does adding short-term temporal visual information improve early prediction of 
pedestrian crossing behavior compared with single-frame perception?

## Dataset
[PIE (Pedestrian Intention Estimation)](http://data.nvision2.eecs.yorku.ca/PIE_dataset/)  
Rasouli et al., ICCV 2019  
74GB of continuous dashcam footage, 1,842 annotated pedestrian samples, Toronto, Canada.

## Approach
- **Baseline:** Single-frame image classifier (MobileNetV2)
- **Temporal model:** Short sequence (2.0s) with LSTM or temporal convolution
- **Evaluation:** F1, precision, recall, false negative rate, prediction horizon, 
  inference latency, memory use, model size

## Commissioning Company
Raftek Group Oy — Finnish last-mile logistics operator (DHL, FedEx, Budbee)

## Tech Stack
Python 3.11 · PyTorch · OpenCV · scikit-learn · Google Colab · Apple MPS

## Author
Kelechi Uko  
[LinkedIn](https://linkedin.com/in/kelechii) · [GitHub](https://github.com/Kelz09)  
uky4059@gmail.com
