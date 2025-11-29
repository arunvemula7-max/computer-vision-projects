# Eye Disease Classification

## Overview
This repository contains code for a deep learning project focused on the classification of eye diseases using Convolutional Neural Networks (CNNs). The project utilizes transfer learning with the InceptionResNetV2 architecture and includes implementations of custom CNNs, including one with a Parallel Convolution Architecture.

## Code Structure

- **Data Preparation**: The dataset is loaded, and dataframes are created to organize file paths and labels. Data distribution is visualized using a count plot.

- **Data Augmentation**: ImageDataGenerator is used for data augmentation during training to improve model generalization.

- **Model Architecture**: The InceptionResNetV2 model is used for transfer learning. Custom CNNs, including one with a parallel convolutional architecture, are also implemented and trained.

- **Model Training**: The model is compiled using the Adamax optimizer and categorical cross-entropy loss. Training and validation results are visualized using accuracy and loss plots.

- **Model Evaluation**: The trained model is evaluated on the test set, and metrics such as accuracy, loss, classification report, and confusion matrix are displayed.

- **Activation Maps**: Activation maps and Grad-CAM (Gradient-weighted Class Activation Mapping) are visualized to understand which parts of the image the model focuses on during predictions.

## Requirements
- Python 
- TensorFlow
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- OpenCV

## Results
The project achieved promising results in terms of accuracy and provides visualizations to aid in model interpretation.

| Model | Accuracy |
|----------|----------|
| Transfer Learning | 94.31% |
| Custom CNN | 89.81% |
| CNN with Parallel Convolution | 93.36% |

## Maintainer
**Arun Kumar Reddy Vemula**
AI/ML Engineer
Email: arunkumarreddy952@gmail.com

I am an AI/ML Engineer with over 5 years of experience building practical machine learning solutions for autonomous vehicles, fraud detection, and industrial IoT. My expertise includes deploying computer vision models that run in real time on edge devices, optimizing cloud inference through quantization, and scaling training workflows using distributed computing. I specialize in turning complex business problems into functional AI systems and maintaining robust CI/CD pipelines for model deployment.