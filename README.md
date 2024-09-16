# Image Classification Project

This project demonstrates an image classification model using PyTorch, focusing on transfer learning with a pre-trained ResNet-18 model. The project includes data preparation, augmentation, model fine-tuning, and evaluation.

## Authors
- Alaa Sweed - 318462959

## Project Overview

The project is divided into several phases:
1. **Importing Libraries**: Importing necessary libraries for deep learning and computer vision tasks.
2. **Data Transformations**: Applying data augmentation and normalization techniques for training and validation datasets.
3. **Data Loaders**: Setting up data directories and creating data loaders for efficient data handling.
4. **Model Setup and Transfer Learning**: Using a pre-trained ResNet-18 model, freezing layers, and fine-tuning for specific classification tasks.
5. **Training and Evaluation**: Training the model and evaluating its performance on the validation dataset.

## Getting Started

### Prerequisites

- Python 3.x
- PyTorch
- torchvision
- numpy
- matplotlib

Install the required libraries using pip:

```bash
pip install torch torchvision numpy matplotlib

