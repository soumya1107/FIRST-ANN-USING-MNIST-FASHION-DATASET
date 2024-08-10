# FIRST-ANN-USING-MNIST-FASHION-DATASET

# Fashion MNIST Neural Network

This repository contains a neural network implementation for classifying the Fashion MNIST dataset using TensorFlow and Keras. The project includes code for model training, evaluation, and visualization using TensorBoard.

![Fashion MNIST Sample](images/fashion_mnist_samples.png)

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Ablation Study](#ablation-study)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

![image](https://github.com/soumya1107/FIRST-ANN-USING-MNIST-FASHION-DATASET/assets/64662510/a63db089-7db8-40c6-b7f0-74443679be5c)

## Introduction

Fashion MNIST is a dataset of Zalando's article images, consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes.

## Dataset

The dataset contains 10 classes:

- 0: T-shirt/top
- 1: Trouser
- 2: Pullover
- 3: Dress
- 4: Coat
- 5: Sandal
- 6: Shirt
- 7: Sneaker
-
![image](https://github.com/soumya1107/FIRST-ANN-USING-MNIST-FASHION-DATASET/assets/64662510/3fdc0127-5af2-44a8-9b3f-a5e37d2c8219)

## Ablation Study

An ablation study was conducted to analyze how the accuracy changes with different configurations of the neural network:

1. Varying the number of hidden layers.
2. Varying the number of neurons per layer.

The configurations tested are:
 flatten_20 (Flatten)        (None, 784)               0         
                                                                 
 dense_54 (Dense)            (None, 240)               188400    
                                                                 
 dense_55 (Dense)            (None, 30)                7230      
                                                                 
 dense_56 (Dense)            (None, 20)                620       
                                                                 
 dense_57 (Dense)            (None, 10)                210       
                                                              

## Results

The results of the ablation study are as follows:

| Configuration | Test Accuracy |
|---------------|---------------|
| 4 layers |0.9750000238418579] |


## Installation

To run this project, you need to have Python 3.x and the following libraries installed:

- TensorFlow
- NumPy
- Matplotlib
- Pandas
