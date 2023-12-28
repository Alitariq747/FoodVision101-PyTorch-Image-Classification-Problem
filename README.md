# FoodVision101-PyTorch-Image-Classification-Problem

# Image Classification Project with PyTorch

## Overview

This project focuses on image classification using PyTorch, targeting a subset of the Food101 dataset. The goal is to classify images into three food categories: pizza, steak, and sushi.

## Notebooks

### 1. Custom-dataset using PyTorch

-  This notebook focuses on preparing the data to fit in with a neural network. Specifically data transformation and creating baseline models including the one from CNN Explainer website known as TinyVGG were implemeneted.
  
### 2. Creating PyThon scripts for future use

- The entire setup code was shifted from being in cell-mode to script mode to modularize it for ease in future.

### 3.  Transfer learning 

- Using a pretrained model from PyTorch knownn as EffecientNetB0 was trained on our custom dataset which improved test accuracy to nearly 93%

### 4. Experiment Tracking

- Using tensorboard extension in PyTorch we tracked multiple experiments on our dataset including testing new and bigger models like EfficientNetB2 and doubling our dataset to include 600 images now.

### 5. Paper replicating

- Using PyTorch replicated the full Vision Transformer Architecture from Paper `An Image is worth 16 x 16 words` and then again applied to our own custom dataset.

## Requirements

All experiments and code are in google colab workbooks which are easily accessible on a CLICK..


## Results

- The major results from the study are that pretrained models like EfficientNetB0 performed the best even on our tiny custom dataset with minimal loss and test-accuracy of nearly 93%

## Acknowledgments

The code is part of course work from Zero To Mastery's Pytorch course from Daniel Bourke

## Author

Ali Tariq

