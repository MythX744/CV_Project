# CV_Project

## Project Description

This project involves training a Convolutional Neural Network (CNN) to classify images from the CIFAR10 dataset into two categories based on their ability to fly:

 * Can Fly (class 1): Includes images of objects that can fly, such as birds and airplanes.

 * Cannot Fly (class 0): Includes images of objects that cannot fly, such as frogs, deer, trucks, etc.

The main objective is to develop a CNN model that effectively discriminates between these two categories using TensorFlow/Keras, ensuring accurate model evaluation using standard classification metrics.


## Model Architecture

Outline the CNN architecture used in the project. For instance:

 * Input layer: Accepts 32x32 RGB images.
 * Convolutional and Pooling layers: Multiple layers for feature extraction.
 * Dense layers: For classification based on features extracted by convolutional layers.
 * Output layer: A single neuron with a sigmoid activation function to classify the images into 'can fly' or 'cannot fly'.
