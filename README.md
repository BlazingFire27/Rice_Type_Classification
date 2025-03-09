# Rice Type Classification Project
This repository contains a machine learning project focused on the classification of Rice Types from the Rice Type Classification dataset. 
The project leverages the PyTorch framework to train a neural network model capable of accurately predicting between different Rice Types. 

## Data Source
The project utilizes the Rice Type Classification dataset, which is publicly available on Kaggle at the following URL: [https://www.kaggle.com/datasets/hojjatk/mnist-dataset/data](https://www.kaggle.com/datasets/mssmartypants/rice-type-classification)

## Project Overview
The core of the project is to learn on how to build and train a neural network using PyTorch. 
The model is trained on the Rice Type Classification dataset to learn the distinct features of each type, enabling it to accurately classify between them.
The Jupyter Notebook included in this repository provides a detailed walkthrough of the model architecture, training process, and evaluation metrics.

## Data Acquisition and Preparation: 
To replicate the project results, it is necessary to download the Rice Type Classification dataset from the specified Kaggle URL.
Ensure that the downloaded .csv file is placed in the same directory as the Jupyter Notebook for data loading and processing.

## Note: 
The project code assumes that the required data file(.csv) is present in the same directory as the Jupyter Notebook. Please follow the instructions above to acquire and prepare the data accordingly.

## Training Results

The following plots illustrate the training and validation performance of the neural network:

### Model Accuracy

![Model Accuracy Plot](images/Training%20and%20Validation%20Accuracy.PNG)

This plot shows the training and validation accuracy over the epochs.

### Model Loss

![Model Loss Plot](images/Training%20and%20Validation%20Loss.PNG)

This plot shows the training and validation loss over the epochs.
