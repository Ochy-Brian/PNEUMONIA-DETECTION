# PNEUMONIA-DETECTION
The project focuses on leveraging a dataset of chest X-ray images to develop machine learning models capable of accurately diagnosing pneumonia.PNEUMONIA-DETECTION-USING-DEEP-LEARNING-
image

Authors: Jane Martha, Najma Abdi, Brian Ochieng, Eunice Ngunjiri, Jubilant Mutuku, Frida Oyucho

Project Overview
The project focuses on leveraging a dataset of chest X-ray images to develop machine learning models capable of accurately diagnosing pneumonia. The dataset sourced from Kaggle, comprises of images classified into two categories: pneu,onia and normal. This project aims to build and optimize convolutional neural network(CNN) models to achieve high diagnostic accuracy.

Business problem
image

Early detection and treatment of pneumonia are essential for avoiding complications and enhancing clinical results. Chest X-rays are a frequently used imaging modality for diagnosing pneumonia. Healthcare professionals, patients, hospitals, researchers and government agencies stand to benefit from these advancements, using the advanced technology models to deepen disease understanding and ensure regulatory compliance.

Data Understanding
Source: Kaggle's Chest X-Ray Images (Pneumonia) dataset. Structure: The dataset is organized into three primary directories: train: Contains training images categorized into 'PNEUMONIA' and 'NORMAL'. val: Contains validation images for model tuning and performance evaluation. test: Contains test images for final model evaluation.

Objectives
Traditionally, diagnosing pneumonia requires time-consuming physical examinations and lab tests, often necessitating multiple doctor visits. We aim to develop a deep learning model capable of accurately detecting pneumonia from chest x-ray images

Methodology
Data modelling was based on clients tested for pneumonia with Xray test results as either normal or Pneumonia

Data preparation and understanding
To understand the structure of the dataset first we examined the directory structure and counted the number of images in each class for training, validation, and testing sets.
Exploratory Data analysis was done on: the training, validation and test datasets. This was done by: - visualizing outputs in Barcharts, to understand the distribution of data - Visualization of images to understand the dimensions and pixels values of images in order to perform preprocessing.

Data Preprocessing was done to prepare the data for modeling(Resizing the images and Normalization)

Data modelling was done using two models with hyperparameter tunings to improve their performances:

Baseline Convolutional Neural Network Model(CNN)
Tuned Convolutional Neural Network Model(CNN)
Complex Model
ResNet50V2 Model
Results
image

We visualzed the data from the three datasets to check for class imbalance. From the barchart, the data was highly imbalanced.

Modelling: image

Duration:

Baseline Model took 2hrs 42mins 18secs
Tunned baseline model: 8hrs 44mins 19secs for the best trial
Complex architecture: 2hrs 20mins 15sec
ResNET59V2 model: 1hr 30mins
Model Comparison: image

Observations:
We observed that execution time decreases each time a new model is executed and the accuracy becomes better each time hence boosting performance.

The best model is the ResNET50V2, which has nalidation accuracy of 0.938 and took the shortest execution time of 1hr 30min 10 secs.

The least was Baseline model and the second improved model was complex architecutre.

Early Stoping model helped in minimizing overfitting hence boosting performance.

Conclusion:
Incorperations of these models can help in boosting treatment, detecting level of pneumonia at different level in both first and critical stages and widening doctors knowledge in finding the best cure for pneumonia in both adults and children hence reducing death rates.

Recommendation:
Validation the developed model through clinical trials is needed to ensure its reliability for diagnoses.
Focus on creating a system that functions effectively with limited computational resources
Further optimization of hyperparameters such as dropout rate and batch size to enhace model performance
