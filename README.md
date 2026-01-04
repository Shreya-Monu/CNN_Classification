# CNN_Classification
This project fixes TensorFlow DLL errors on Windows by setting up Python 3.10, installing compatible TensorFlow versions, and configuring VS Code correctly for smooth deep learning execution.

# CNN Image Classification using TensorFlow

## Project Overview

This project implements a Convolutional Neural Network (CNN) for image classification using TensorFlow and Keras. The dataset is provided in Excel format and includes training and testing inputs with corresponding labels. The project focuses on preprocessing data, applying augmentation, training a CNN model, and evaluating its performance.

## Files Description

```
animals.ipynb     - Main Jupyter Notebook containing the CNN implementation
input.xlsx        - Training data (input images/features)
input_test.xlsx   - Testing data (input images/features)
labels.xlsx       - Training labels
labels_test.xlsx  - Testing labels
README.md         - Project documentation
```

## Technologies Used

* Python 3.10
* TensorFlow (Keras API)
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook / VS Code

## Environment Setup

1. Install Python 3.10 (64-bit)
2. Install Microsoft Visual C++ Redistributable (x64)
3. Install required libraries:

```
pip install tensorflow-intel==2.12.0 numpy pandas matplotlib pillow
```

## Data Preprocessing

* Data loaded from Excel files
* Reshaping input data to 100×100×3 format
* Normalization using division by 255
* Labels reshaped for model compatibility

## Data Augmentation

To improve model performance, the following augmentation techniques are used:

* Rotation
* Zoom
* Width and height shifting
* Horizontal flipping

## CNN Architecture

* Convolutional layers (Conv2D)
* MaxPooling layers
* Flatten layer
* Dense (fully connected) layers
* Dropout layer to reduce overfitting

## How to Run the Project

1. Open `animals.ipynb` in Jupyter Notebook or VS Code
2. Ensure the correct Python interpreter is selected
3. Run all cells in order to train and test the model

## Output

* Trained CNN model
* Classification predictions on test data
* Improved accuracy using data augmentation

## Learning Outcomes

* Understanding CNN architecture
* Image data preprocessing
* TensorFlow and Keras implementation
* Handling Excel-based datasets
* Debugging TensorFlow environment issues


