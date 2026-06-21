# IMAGE-CLASSIFICATION-MODEL

# PROJECT OVERVIEW

This project implements an Image Classification Model using a Convolutional Neural Network (CNN) built with TensorFlow. The model is trained on the CIFAR-10 dataset, which contains images from ten different categories. The objective is to automatically classify images into their respective classes using deep learning techniques.

# OBJECTIVES

- Build a Convolutional Neural Network (CNN) for image classification.
- Train the model using the CIFAR-10 dataset.
- Evaluate model performance on test data.
- Visualize training and validation accuracy.
- Predict image classes using the trained model.

# FEATURES

- Image Preprocessing
- CNN Architecture
- Model Training
- Performance Evaluation
- Accuracy Visualization
- Classification Report
- Sample Prediction Display

# TECHNOLOGIES USED

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

# DATASET

## CIFAR-10 Dataset

The CIFAR-10 dataset contains 60,000 color images divided into 10 classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

Dataset Split:

- Training Images: 50,000
- Testing Images: 10,000

# PROJECT WORKFLOW

1. Load CIFAR-10 Dataset
2. Normalize Image Pixel Values
3. Build CNN Architecture
4. Train Model Using TensorFlow
5. Evaluate Model Performance
6. Generate Predictions
7. Display Classification Results
8. Visualize Accuracy Graphs

# CNN ARCHITECTURE

The model consists of:

- Convolution Layer (32 Filters)
- Max Pooling Layer
- Convolution Layer (64 Filters)
- Max Pooling Layer
- Convolution Layer (64 Filters)
- Flatten Layer
- Dense Layer (64 Neurons)
- Output Layer (10 Classes)


# MODEL EVALUATION

The model is evaluated using:

- Test Accuracy
- Classification Report
- Precision
- Recall
- F1-Score

# SAMPLE OUTPUT

```text
Test Accuracy: 0.72

Classification Report:

Airplane      0.78
Automobile    0.82
Bird          0.65
Cat           0.60
Deer          0.69
Dog           0.67
Frog          0.79
Horse         0.75
Ship          0.83
Truck         0.80
```

# HOW TO RUN

## Install Required Libraries

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

## Start Jupyter Notebook

```bash
jupyter notebook
```

## Open Notebook

```text
Image_Classification_Model.ipynb
```

## Run All Cells

The model will:

- Load Dataset
- Train CNN
- Evaluate Performance
- Generate Predictions
- Display Accuracy Graphs

# RESULTS

- Successfully trained a CNN model.
- Classified images into 10 categories.
- Evaluated model performance on test data.
- Generated prediction results.
- Visualized training and validation accuracy.

# CONCLUSION

This project demonstrates the implementation of an Image Classification Model using a Convolutional Neural Network (CNN) in TensorFlow. The model successfully learns image features and performs classification on the CIFAR-10 dataset. The project highlights the effectiveness of deep learning techniques for image recognition tasks and provides a foundation for more advanced computer vision applications.
