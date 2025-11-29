# MNIST Image Classification

This repository contains code for MNIST image classification using a convolutional neural network (CNN) and an autoencoder model with an encoder component. Maintained by Arun Kumar Reddy Vemula, the code preprocesses the MNIST dataset, visualizes the data, trains a CNN model for image classification, and evaluates its performance. Additionally, it demonstrates the use of an autoencoder and its encoder for feature extraction.

### Data Preprocessing

- The MNIST dataset is loaded and normalized to a range between 0 and 1.

- The images are resized to 32x32 pixels to match the model's input shape.

- Data augmentation is applied to increase model robustness.

### Image Classification Models

- A CNN model is built for image classification. The model architecture includes convolutional layers, max-pooling layers, and dense layers.

- An autoencoder is created to compress and reconstruct MNIST images. However, the focus is on the encoder part of the autoencoder to classify images.

## Results

- The CNN model achieves an accuracy of 99.40%
- The Autoencoder based encoder classifier achieves an accuracy of 96.22%

## Maintainer

Arun Kumar Reddy Vemula
AI/ML Engineer
Email: arunkumarreddy952@gmail.com

### About the Developer

Arun is an AI/ML Engineer with over 5 years of experience building practical machine learning solutions for autonomous vehicles, fraud detection, and industrial IoT. He specializes in deploying computer vision models on edge devices, optimizing inference costs through quantization, and managing scalable workflows using Kubernetes and distributed computing. He is dedicated to transforming complex business challenges into high-performing AI applications.

Key Skills: Python, SQL, Java, C++, Bash, R, JavaScript, TypeScript, FastAPI, Flask