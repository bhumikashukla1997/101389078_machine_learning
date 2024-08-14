# Concrete Accessment with Yolov9

## Table of Contents
[Overview](#overview)

[Code](#code)

- [Training](#training)

- [Inference](#inference)

[Datasets](#datasets)

[Documentation](#documentation)

## Overview
This project focuses on fine-tuning a YOLOv9 model to segment cracks in concrete from images. By utilizing a concrete crack dataset, the model is trained to accurately identify and outline cracks, providing a powerful tool for automated inspection and analysis in structural health monitoring.

## Code
This section covers the steps to train and use the models using the pre-processed datasets.

### Training
From the train folder, run ```python yolov9_concrete_assessment_train.py```. This will take photos and masks from the dataset folders containing pictures of concrete cracks then preprocess and train a model that will be saved inside the 'runs/segment/' folder.

For more details, refer to the [Training page](https://github.com/Jaideep-Prasad/Kinectrics-Coop-Projects/tree/main/Concrete%20Assessment/4.%20Analysis/Group%201/1.%20Code/Concrete_Inspection_Yolov9/train).

### Inference
From the inference folder, run ```python yolov9_inference.py path_to_your_input_image.jpg```. This will load the fine-tuned model,  run inference on the specified image and display the results.
The result will also be saved under `runs\segment`. You can find the finetuned model [here](https://drive.google.com/drive/folders/1RAtZ58EishQCzD4Xbsrd6GBa8uVw_dpK?usp=sharing).

For more details, refer to the [Inference page](https://github.com/Jaideep-Prasad/Kinectrics-Coop-Projects/tree/main/Concrete%20Assessment/4.%20Analysis/Group%201/1.%20Code/Concrete_Inspection_Yolov9/train).

## Datasets
This section includes both the original and pre-processed datasets used for training the model. You can find detailed information and access the datasets by visiting the [Datasets page](https://github.com/Jaideep-Prasad/Kinectrics-Coop-Projects/tree/main/Concrete%20Assessment/4.%20Analysis/Group%201/2.%20Data).

## Documentation
Explore detailed guides on training, inference, and dataset usage. Navigate through the project’s documentation by visiting the [Documentation Page](https://github.com/Jaideep-Prasad/Kinectrics-Coop-Projects/tree/main/Concrete%20Assessment/4.%20Analysis/Group%201/3.%20Documentation).
