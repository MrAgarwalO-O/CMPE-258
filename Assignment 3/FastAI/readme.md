# FastAI Deep Learning with low code libraries

This assignment is about performing various tasks using Fast AI and writing a detailed colab which show training and inference of below tasks using fast.ai
- vision object detection task
- vision segmentation task
- tabular task
- recommendation task

## Overview

FastAI, built on top of PyTorch, is a popular library that enables the development of cutting-edge deep learning models with minimal code. This assignment demonstrates FastAI's versatility through four distinct tasks:
### Tasks Covered

1. **Vision Object Detection** - Detection of potholes in images, showcasing object detection capabilities.
2. **Vision Segmentation** - Application of semantic segmentation on the CamVid dataset for pixel-level image classification.
3. **Tabular Task** - Analysis of the Adult Census dataset to predict income levels based on multiple features.
4. **Recommendation System** - Development of a recommendation system using the University Prediction dataset, predicting university admissions based on student profiles.

## Vision Object Detection: Pothole Detection

This section focuses on detecting potholes in road images, an application crucial for road maintenance. It details the setup of the FastAI environment, dataset preparation, CNN model creation, model training, and performance evaluation using metrics like error rate and confusion matrix. The simplicity of implementing object detection tasks with FastAI is showcased.
Key Steps:
- Environment setup and data preparation.
- Dataset loading and augmentation.
- Model creation, training, and fine-tuning.
- Performance evaluation.
## Vision Segmentation: CamVid Dataset

Semantic segmentation is performed on the CamVid dataset, where each pixel is classified into categories such as roads, cars, and pedestrians. It demonstrates dataset loading and preprocessing, the use of Unet architecture with ResNet34, model training, and evaluation. Techniques for model result interpretation, including top loss image display, are also covered.
Key Steps:
- Data loading and preprocessing.
- Implementing a Unet architecture with a ResNet34 backbone.
- Model training and evaluation.
- Result interpretation and analysis.

## Tabular Task: Adult Census Dataset

This task uses the Adult Census dataset, predicting whether an individual's income exceeds $50K/year based on census data. It outlines data loading, preprocessing (addressing missing values, normalizing numerical features, categorizing categorical features), model training, and evaluation. This example emphasizes FastAI's proficiency in handling tabular data, showcasing its practicality for real-world applications.
Key Steps:
- Dataset loading and preprocessing (handling missing values, categorizing features).
- Training a model with RandomForestClassifier.
- Model evaluation and interpretation.

## Recommendation System: University Admission Prediction

The task involves building a recommendation system with the University Prediction dataset to forecast the likelihood of university admissions based on student profiles. This segment is crucial for applications in educational planning and student counseling, illustrating FastAI's application in developing recommendation systems through predictive modeling.
Key Steps:
- Preparing and processing the dataset.
- Model training and fine-tuning.
- Prediction on new data and performance evaluation.
