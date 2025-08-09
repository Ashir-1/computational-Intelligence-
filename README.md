Optimization & Image Classifiers – Computational Intelligence Project
Course: CSE473: Computational Intelligence
Programs: MCT & MCTA
Semester: Fall 2024

📌 Project Overview
This project is divided into two milestones:

Milestone 1: Optimization Algorithm Comparison
We compare the performance of the following optimization algorithms on the CIFAR-10 dataset using a shallow neural network:

Stochastic Gradient Descent with Warm Restarts (SGDR)

Nesterov Accelerated Gradient (NAG)

RMSProp

Nadam

Learning Rate Schedulers:

Exponential Decay

Step Decay

For each optimizer, we:

Train a shallow neural network for character recognition (CIFAR-10 dataset)

Record training time, accuracy, and loss

Visualize and compare performance

Milestone 2: Encoder-Decoder Networks for Face Recognition
We train and evaluate different autoencoder architectures for face recognition using CASIA-WebFace or FRGC datasets.

Steps:

Data Splitting:

70% Training

15% Validation

15% Testing

Data Normalization:

Subtract mean and divide by standard deviation for each dimension

Visualize normalized data

Model Architectures:

Vanilla Autoencoder (AE)

Variational Autoencoder (VAE)

Convolutional Autoencoder (CAE)

Cross-Validation:

Find the best number of hidden layers and nodes per layer

Training Visualization:

Plot Loss vs Iterations for each model

Performance Metrics:

Report best accuracy achieved

Use encoder output as feature vectors

Apply Minimum Euclidean Distance Classifier for recognition accuracy
