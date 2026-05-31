# Image Colorization using Autoencoder

## Project Overview
Grayscale images ko color mein convert karna using CNN Autoencoder and CIFAR-10 dataset.

## Technologies Used
- Python
- TensorFlow/Keras
- OpenCV
- NumPy
- Matplotlib
- CIFAR-10 Dataset

## Model Architecture
- Encoder: Conv2D + MaxPooling layers
- Decoder: Conv2D + UpSampling layers
- Loss: Mean Squared Error (MSE)
- Optimizer: Adam

## Results
- Training Loss decreased from 0.014 to 0.007
- Model successfully colorizes grayscale images

## How to Run
1. Install dependencies: pip install tensorflow opencv-python matplotlib numpy
2. Open image_colorization.ipynb in VS Code
3. Run all cells
