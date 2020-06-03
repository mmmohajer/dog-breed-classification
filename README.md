# End - to - End Multicalass Dog Breed Classification

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub.

## 1. Problem

Identifying the breed of a dog given an image of a dog.

When I am sitting at the cafe and I take a photo of a dog, I want to know what breed of dog it is. 

## 2. Data

The data we are using is from Kaggle's dog breed identification competition (https://www.kaggle.com/c/dog-breed-identification/data).

## 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image. (https://www.kaggle.com/c/dog-breed-identification/overview/evaluation)

## 4. Features

Some information about the data:

- We are dealing with images (unstructured data) so it is probably best we use deep learning/transfer learning.
- There are 120 breeds of dogs (this means there are 120 different calsses).
- There are around 10000 + images in the training set (these images have labek).
- There are around 10000 + images in the test set (these images have no label, because we want to predict them).