# CycleGANs

## Overview
This repository contains the Jupyter Notebook and associated files for the CycleGANs project, which is focused on using an existing model for image-to-image translation tasks.

## Setup
The project utilises Google Colab for executing the code. The necessary libraries and dependencies are listed in the notebook and can be installed using `pip`.

## Dataset Preparation
The dataset includes various image categories such as cats, dogs, and human faces. The images are unzipped, renamed, and organised into appropriate directories for processing.

## Image Processing
The notebook details the steps for comparing images, copying them into a single folder, and renaming file extensions to `.jpg` only.

## Creating Dataset Objects
Instructions for creating dataset objects for training and testing are provided. This includes preprocessing functions and defining dataset parameters.

## Model Training
The notebook outlines the process for training the CycleGAN model using the prepared datasets.

## Visualisation
Code for visualising sample images from the datasets is included to ensure the data is correctly processed before training.

## Acknowledgements
The project makes use of TensorFlow, TensorFlow Addons, TensorFlow Datasets, and other open-source libraries.
