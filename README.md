# Brain Tumor Detection using MobileNetV2

## Overview
Designed and implemented a deep learning-based brain tumor classification system using MRI images. Leveraged MobileNetV2 with frozen ImageNet pretrained layers and custom classification head. Applied data preprocessing, train-validation split, and model evaluation using accuracy, precision, recall, F1-score, and confusion matrix. Integrated Grad-CAM visualization to improve interpretability by highlighting tumor-relevant regions. Built an end-to-end reproducible pipeline using Kaggle API for automated dataset retrieval.

## Dataset
Brain MRI Images for Brain Tumor Detection (Kaggle)

Dataset not included due to size.
Use Kaggle API to download.

## Model Architecture
- MobileNetV2 (ImageNet pretrained)
- Global Average Pooling
- Dense 128
- Dropout 0.3
- Softmax output

## Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision / Recall / F1-score

## Grad-CAM
Used for model interpretability.

## Disclaimer
This model is for research and educational purposes only.
Not clinically validated.
