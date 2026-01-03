# Histopathologic Cancer Detection (Kaggle Mini-Project)

## Overview
This project tackles the Kaggle competition "Histopathologic Cancer Detection". The task is binary classification of histopathology image patches to identify metastatic cancer tissue.

## Dataset
Each image is a 96x96 RGB pathology patch.
- Label 0: No tumor tissue in the central 32x32 region
- Label 1: Tumor tissue present in the central region

## Methods
- Exploratory data analysis and visualization
- Baseline CNN model
- CNN with data augmentation
- Transfer learning using EfficientNetB0
- Fine-tuning the last 20 layers of EfficientNetB0

## Results
Best performing model: Fine-tuned EfficientNetB0  
Validation Accuracy ≈ 0.91  
Validation AUC ≈ 0.97  

## Kaggle Submission
Predictions were generated on the test set and submitted to Kaggle as `submission.csv`.
