# Medical Image Analysis - AI Project
## Group members:
### Laiba Shafqat
### Haider Ali Kayani

## Overview
This Jupyter Notebook contains code for a Chest X-ray Classifier designed to detect pneumonia from medical images. The project utilizes deep learning techniques with TensorFlow and OpenCV to process and classify chest X-ray images into healthy or pneumonia categories.

## Features
Image preprocessing and augmentation using OpenCV

Deep learning model built with TensorFlow/Keras

Visualization tools with Matplotlib and Seaborn

Model evaluation with confusion matrices and performance metrics

Pretrained model loading and prediction capabilities

## Dataset
Dataset link: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia?resource=download

This dataset contains a total of 5 folders:
1. NORMAL
2. PNEUMONIA
3. test
4. validation
5. train

We used NORMAL and PNEUMONIA to train our model and made the test, validation and train splits manually in our code. We did not use the given test, validation and train folders. 
NORMAL and PNEUMONIA folders contained a total of 5863 images of which there were 4273 pneumonic samples and 1583 normal samples.

## Directory structure:
 ![image](https://github.com/user-attachments/assets/acbc18ad-83c1-4be6-96d0-9b5cf203162a)

