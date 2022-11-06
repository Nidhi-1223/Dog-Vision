# End-to-end Multi-class Dog Breed Classification

This notebook builds an end-to-end multi-class image classifier using Tensorflow and Tensor-flow hub

## 1. Problem Statement

Identifying the breed of a dog, given an image

## 2. Data

Data is taken from Kaggle's dog breed identification competition.
[Link](https://www.kaggle.com/competitions/dog-breed-identification/data)

## 3. Evaluation

Submissions are evaluated on `Multi Class Log Loss` between the predicted probability and the observed target.
The evaluation is a file with prediction probabilities for each dog breed of each test image.

## 4. Features

Some information about the data :
* We're dealing with images (unstructured data) so it's probably best we use Deep Learning / transfer learning. 
* There are 120 breeds of dogs (this means there are 120 different classes)
* There are around 10,000+ images in the training set (these images have labels)
* There are around 10,000+ images in the test set (these images don't have labels)