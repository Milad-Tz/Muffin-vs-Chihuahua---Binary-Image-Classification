# Muffin vs Chihuahua - Binary Image Classification using Transfer Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Milad-Tz/Muffin-vs-Chihuahua---Binary-Image-Classification/blob/main/Muffin_vs_Chihuahua.ipynb)

---

## Overview

This project aims to build a binary image classifier to distinguish between images of muffins (1) and chihuahuas (0) using transfer learning. The project utilizes the VGG16 convolutional neural network pre-trained on ImageNet, with a focus on feature extraction and model selection through K-Fold Cross Validation.

## Dataset

The dataset used for this project is available on Kaggle: [Muffin vs Chihuahua - Image Classification](https://www.kaggle.com/datasets/samuelcortinhas/muffin-vs-chihuahua-image-classification).

## Project Workflow

### 1. Data Preparation & Preprocessing
- **Google Colab & Google Drive Integration**: Access and organize the dataset using Google Drive.
- **Data Generators**: Set up to preprocess images for feature extraction.

### 2. Exploratory Data Analysis (EDA)
- **Class Distribution**: Analyze the distribution of muffins and chihuahuas.
- **Visualizations**: Visualize sample images from the dataset to understand its structure.

### 3. Feature Extraction
- **VGG16 Model**: Extract high-level features from images using the pre-trained VGG16 model.

### 4. Model Selection
- **K-Fold Cross Validation**: Evaluate three different neural network architectures.
- **Performance Evaluation**: Identify the most suitable architecture based on cross-validation results.

### 5. Hyperparameter Tuning
- **Learning Rate Tuning**: Fine-tune the model’s hyperparameters to optimize performance.

### 6. Model Evaluation
- **Test Set Performance**: Evaluate the final model on the test dataset.
- **Metrics**: Analyze accuracy, confusion matrices, and other key metrics.

## Usage

To run the notebook in Google Colab:

1. Click the "Open In Colab" badge at the top of this README.
2. Change the file paths in the notebook to match your own Google Drive setup.
3. Follow the instructions in the notebook to train and evaluate the model.
