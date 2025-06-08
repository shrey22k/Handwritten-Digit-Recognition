# Handwritten Digit Recognition

This project implements a handwritten digit recognition system using a Convolutional Neural Network (CNN) trained on the MNIST dataset. The system allows users to draw digits on a Pygame interface and predicts the digit in real-time using the trained model.

---

## Features

- Train a CNN model on the MNIST dataset for handwritten digit classification.
- Interactive Pygame GUI for drawing digits with mouse input.
- Real-time digit prediction displayed on the drawing board.
- Model saving and loading functionality for inference.
- Image preprocessing and normalization for accurate predictions.

---

## Project Structure

- `digit_recognition.ipynb` - Jupyter notebook containing the CNN model training pipeline.
- `app.py` - Python script with Pygame GUI for digit drawing and prediction.
- `bestmodel.h5` - Pre-trained CNN model weights (generated after training).
- `README.md` - Project documentation.

---

## Requirements

- Python 3.x
- numpy
- matplotlib
- keras (TensorFlow backend)
- pygame
- opencv-python

You can install required libraries using:

```bash
pip install numpy matplotlib tensorflow pygame opencv-python
