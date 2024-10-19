# CIFAR-10 Classifier

This project implements a convolutional neural network (CNN) to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset contains 60,000 images in 10 classes, with 6,000 images per class. The classes are:

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

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Plotting Predictions](#plotting-predictions)
- [Results](#results)

## Installation

To run this project, ensure you have Python installed (preferably version 3.6 or above). You will also need to install the following packages:

```
pip install torch torchvision matplotlib
```

Clone this repository:

```
git clone https://github.com/yourusername/cifar10-classifier.git
cd cifar10-classifier
```

Download the CIFAR-10 dataset: The dataset will be automatically downloaded when you run the script for the first time.

Run the classifier:

```
python cifar10_classifier.py
This script will train the model and display the training progress, including training and testing loss and accuracy.
```

## Training the Model
The model is trained using the following hyperparameters:

```
Learning Rate: 0.001
Batch Size: 64
Number of Epochs: 40
```
You can modify these parameters in the script to experiment with different training configurations.

## Plotting Predictions
After training the model, you can visualize the predictions on the test dataset using the plot_predictions function. This will display sample images along with the model's predicted and actual labels.

## Results
The model's performance will be displayed during training, including training and test accuracy. After training, the final accuracies will also be printed.
