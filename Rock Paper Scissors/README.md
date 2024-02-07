# Rock-Paper-Scissors Game

### Project Overview

This project involves developing a Convolutional Neural Network (CNN) model to classify images in the Rock-Paper-Scissors game. The model is trained to recognize hand gestures and classify them into one of the three categories: rock, paper, or scissors.


### Image Preprocessing

Includes:

* **Resizing**: 300x200 -> 150x100
* **Background removal**: Green -> White
* **Normalization**: convert to the range of [0-1]
* **Noise addition**: mean value 0 and standard deviation 5% of the maximum pixel value.

### CNN Architecture

The model uses convolutional layers for feature extraction from images, followed by dense layers for classification.


### Data Augmentation

Employs horizontal and vertical flips for more robust training.


## Results

The model was chosen due to the high accuracy (~97%).

The model had a higher accuracy (~99%) in the test data before adding the background remocal function but performed poorly in new images without any background (white color background). 

As a result, a green screen removal was implemented for the images to convert everything to a white background. This had an effect on the model's accuracy on the test data but had good results on the new images.

User (new) images followed a similar pre-processing such as the training data
