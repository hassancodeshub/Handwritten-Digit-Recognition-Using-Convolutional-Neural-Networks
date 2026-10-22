# Handwritten Digit Recognition Using CNN

## Overview
This project uses deep learning to recognize handwritten digits from images. A Convolutional Neural Network (CNN) is trained on the MNIST dataset to classify digits from 0 to 9.

## Objectives
- Understand image preprocessing techniques.
- Build and train a CNN model.
- Recognize handwritten numerical digits.
- Evaluate the model using test data and classification metrics.

## Technologies Used
- Python
- Jupyter Notebook
- TensorFlow and Keras
- NumPy
- Matplotlib
- Scikit-learn

## Dataset
The project uses the MNIST dataset, which contains 70,000 grayscale images of handwritten digits. Each image is 28 × 28 pixels.

Dataset documentation: https://keras.io/api/datasets/mnist/

## Algorithm
1. Load the MNIST dataset.
2. Normalize pixel values between 0 and 1.
3. Build a CNN using convolution, pooling, dropout, and dense layers.
4. Train the model on the training dataset.
5. Evaluate performance on the test dataset.
6. Visualize predictions and training performance.

## Installation
Install the required libraries:

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

## How to Run
1. Open `02_handwritten_digit_recognizer.ipynb` in Jupyter Notebook.
2. Run each cell from top to bottom.
3. Allow the notebook to download MNIST.
4. Train the CNN model.
5. Review the accuracy graphs, confusion matrix, and sample predictions.

## Expected Outcome
The trained CNN predicts the digit represented by an input image and reports its performance on unseen test images.

## Limitations
The model is trained on small, centered MNIST images. It may perform less accurately on real-world photographs or unusual handwriting styles.

## Author
Add your name here.
