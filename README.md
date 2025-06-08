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
```

## Usage
### Training the Model
1. Open digit_recognition.ipynb notebook.
2. Run the cells sequentially to load data, preprocess, build the CNN model, and train it on MNIST.
3. The best model is saved as bestmodel.h5.

### Running the Digit Recognition App
1. Ensure bestmodel.h5 is in the same directory as app.py.

2. Run the app:
```bash
python app.py
```
3. Use your mouse to draw a digit on the Pygame window.

4. Release the mouse button to see the predicted digit displayed below your drawing.

5. Press 'n' to clear the screen and draw a new digit.

## How It Works
- The CNN model is trained on 28x28 grayscale images of handwritten digits from the MNIST dataset.

- The Pygame app captures mouse input, extracts the region where the digit is drawn, preprocesses it to match the input shape of the model, and predicts the digit.

- The prediction label is displayed in real-time on the drawing board.

## Acknowledgments
- MNIST dataset: http://yann.lecun.com/exdb/mnist/

- Keras library for building deep learning models.

- Pygame library for creating the interactive drawing interface.


