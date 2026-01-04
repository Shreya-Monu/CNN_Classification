# CNN_Classification
This project fixes TensorFlow DLL errors on Windows by setting up Python 3.10, installing compatible TensorFlow versions, and configuring VS Code correctly for smooth deep learning execution.
Sure 👍
Below is a **ready-to-use README.md** file.
You can **copy–paste it directly** without changing anything.

---

# CNN Image Classification using TensorFlow

## Project Overview

This project implements a Convolutional Neural Network (CNN) for image classification using TensorFlow and Keras. It covers image preprocessing, data augmentation, model training, and evaluation. The project also includes proper environment setup to avoid common TensorFlow DLL errors on Windows.

## Technologies Used

* Python 3.10
* TensorFlow (Keras API)
* NumPy
* Matplotlib
* VS Code / Jupyter Notebook

## Project Structure

```
dataset/
├── train/
└── test/
cnn_model.py
test_tf.py
README.md
```

## Environment Setup

1. Install Python 3.10 (64-bit)
2. Install Microsoft Visual C++ Redistributable (x64)
3. Install required libraries:

```
pip install tensorflow-intel==2.12.0 numpy matplotlib pillow
```

## Data Preprocessing

* Images resized to 100×100 pixels
* Normalization using division by 255
* Data augmentation techniques:

  * Rotation
  * Zoom
  * Width and height shifting
  * Horizontal flipping

## CNN Architecture

* Convolutional layers with ReLU activation
* MaxPooling layers
* Flatten layer
* Dense (fully connected) layers
* Dropout for reducing overfitting

## How to Run the Project

1. Open the project folder in VS Code
2. Select Python 3.10 interpreter
3. Run the model file:

```
python cnn_model.py
```

## Output

* Trained CNN model
* Improved accuracy using data augmentation
* Successful execution of TensorFlow without DLL errors

## Learning Outcomes

* Understanding CNN fundamentals
* Image preprocessing and augmentation
* TensorFlow and Keras implementation
* Debugging TensorFlow environment issues


