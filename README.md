# Malaria-Detection-with-MLOps
Deep Learning

This project focuses on using deep learning techniques to classify cell images as malaria-infected or uninfected. It integrates powerful tools such as **WandB (Weights and Biases)** for experiment tracking, hyperparameter tuning, and visualization of model performance.

## Features
- **Data Preparation**: Loading, preprocessing, augmenting, and visualizing the dataset.
- **Model Development**: Utilizing **TensorFlow/Keras** to build and train deep learning models.
- **Experiment Tracking**: Incorporating **WandB** for logging metrics, hyperparameter tuning, and dataset versioning.
- **Performance Evaluation**: Detailed evaluation using confusion matrix, ROC plots, and performance metrics.
- **Model Saving**: Efficient saving and loading of trained models for reuse.

## Workflow

### 1. WandB Installation and Configuration
- Initialize WandB for experiment tracking and dataset versioning.

### 2. Data Preparation
- **Load and preprocess malaria dataset**: Import dataset and apply preprocessing steps.
- **Data Augmentation**: Improve model generalization by augmenting the dataset.

### 3. Model Creation and Training
- **Build models using Keras Sequential API**: Create deep learning models using TensorFlow/Keras.
- **Track models with WandB**: Track both untrained and trained models using WandB's logging features.

### 4. Experiment Tracking
- **Log Metrics**: Track important metrics such as accuracy, loss, and validation performance with WandB.
- **Hyperparameter Tuning**: Use WandB’s sweep functionality to tune hyperparameters for optimal model performance.

### 5. Model Evaluation
- **Confusion Matrix**: Visualize and analyze classification performance.
- **ROC Curve**: Demonstrate the tradeoff between sensitivity and specificity.
- **Performance Metrics**: Evaluate model performance on the test dataset.

## Visualizations
- **Confusion Matrix**: Provides insights into classification performance.
- **ROC Curve**: Demonstrates the tradeoff between sensitivity and specificity.
