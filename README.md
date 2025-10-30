# deepfake_detection
AI video detection system built to identify deepfakes and protect against video misinformation. Uses computer vision and transfer learning techniques.

# Deepfake Detection using FaceForensics++ Dataset

A CNN-based deepfake detection model that classifies videos as real or AI-generated using facial analysis.

## Results
- **Real Video Detection**: 59% recall
- **Fake Video Detection**: 64% recall  
- **Overall Accuracy**: 63%
- **Tested on**: 7,000 videos from FaceForensics++ dataset

## Features
- Face extraction from video frames
- Transfer learning with ResNet18
- Class imbalance handling through data augmentation
- Real-world YouTube video testing

## Quick Start
1. Install dependencies: `pip install torch torchvision opencv-python scikit-learn`
2. Download FaceForensics++ dataset
3. Run the Jupyter notebook: `deepfake_detection.ipynb`

## Model Performance
The model successfully distinguishes between real and AI-generated videos, achieving balanced performance across both classes through systematic debugging and transfer learning techniques.

## Dataset
Uses the FaceForensics++ dataset containing:
- Original videos (real)
- 6 deepfake categories: Deepfakes, Face2Face, FaceSwap, etc.


