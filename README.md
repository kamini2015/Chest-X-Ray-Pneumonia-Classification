# Chest X-Ray Pneumonia Classification

This project focuses on classifying chest X-ray images as either normal or pneumonia-infected using deep learning techniques. It utilizes the Xception pre-trained model for transfer learning.

## Dataset Description

The dataset consists of chest X-ray images categorized into two classes: normal and pneumonia-infected. The images are obtained from the Chest X-Ray Images (Pneumonia) dataset on Kaggle.

## Importing Libraries

The code imports necessary libraries including TensorFlow, Keras, OpenCV, and others for data preprocessing, model building, and visualization.

## Loading Data

The dataset is loaded from the specified directories containing chest X-ray images for training and testing. Data paths along with corresponding labels are collected into Pandas DataFrames for further processing.

## Data Preprocessing

Data preprocessing steps include normalization of pixel values, encoding of labels, and visualization of data distributions.

## Model Building

Transfer learning with the Xception pre-trained model is employed for building the classification model. Additional layers are added for fine-tuning the model to classify chest X-ray images.

## Compile and Fit

The model is compiled with appropriate loss function and metrics, and then fitted to the training data. Early stopping is used to prevent overfitting.

## Model Evaluation

The trained model is evaluated on the validation dataset to assess its performance in terms of loss and accuracy. Training and validation loss and accuracy are visualized over epochs.

## Model Predictions

Model predictions are made on the testing dataset, and a visualization of predicted labels along with actual images is provided.

## How to Use

To run the code:

1. Ensure all necessary libraries are installed.
2. Load the dataset into the specified directories.
3. Execute each code cell sequentially in your Python environment.
4. Follow the instructions provided in the comments to understand each step of the code.
