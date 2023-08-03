# Malaria-cell-image-classification model

## Overview
This repository contains code and data intended to classify microscopic images of human blood smear samples into infected or non-infected. Image classification is a fundamental task in computer vision and has numerous applications in the healthcare industry.

## Dataset
The dataset used for training and evaluation is the "Malaria cells," which consists of a large collection of labeled images from two categories. The dataset is labeled accordingly into parasitized cells and uninfected cells. 

The dataset was split into a train, validation, and test set.

## Model Architecture
The binary image classification model is based on a convolutional neural network (CNN) architecture. CNNs are well-suited for image classification tasks as they can automatically learn relevant features from the images, enabling high accuracy in classification.

The model architecture consists of multiple convolutional layers, followed by pooling layers for down-sampling and one fully connected layer as the final classification head. The final layer uses a sigmoid activation function to produce a probability for each input image.

Input images were resized to 50x50 pixels.

## Code Organization
- 'Malaria cells/cell_images: Contains the dataset used for training, validation, and evaluation.

- 'malaria-cell-classification.ipynb': Script for training the classification model on the dataset.

## Training
The model was trained for 20 epochs and a learning rate scheduler was set up to escape saddle points.

## Evaluation
The model was evaluated on the held-out unseen test dataset.

## Results
The model's performance on the test set will be displayed, including metrics such as binary accuracy and F1 score.

## Acknowledgments
I would like to acknowledge Arunava for providing the data used in this project.

## Contact
For any inquiries or issues, please contact uzoigodo@gmail.com.
