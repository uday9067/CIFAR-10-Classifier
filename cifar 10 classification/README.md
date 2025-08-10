# CIFAR-10 Image Classification

## Project Overview
This project demonstrates image classification on the CIFAR-10 dataset using three different models:

1. **V1 – Fully Connected Network**
   - Accuracy: 42.13%
2. **V2 – Convolutional Neural Network (CNN)**
   - Accuracy: 67.21%
3. **V3 – CNN + Data Augmentation**
   - Accuracy: 70.36%

## Files & Structure
```
cifar10_classifier/
├── 1.baseline/              # Code and results for V1
├── 2.cnn/                   # Code and results for V2
├── 3.aug_dropout/           # Code and results for V3
├── accuracy_loss_graphs/    # Training graphs
└── predictions.png          # Sample predictions with true vs predicted labels
```

## Dataset
CIFAR-10 dataset from `tensorflow.keras.datasets`.

## Requirements
- Python 3.x
- TensorFlow / Keras
- Matplotlib
- NumPy

## How to Run
1. Clone the repository
2. Install dependencies
3. Run the notebook or Python scripts inside each version folder
