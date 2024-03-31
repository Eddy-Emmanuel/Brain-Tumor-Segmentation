# Brain Tumor Segmentation

This repository contains a model for segmenting brain tumors from medical images. The model has achieved the following metrics on the provided dataset:

- **Accuracy**: 0.654
- **Validation Accuracy**: 0.6555
- **IoU Score**: 5.9268
- **Validation IoU Score**: 6.1657
- **Loss**: -0.6885
- **Validation Loss**: -0.682

## Limitations

Due to limited computational resources, the image size was reduced to (48,48) to expedite training. This reduction in image size may affect the model's performance, particularly in accurately segmenting smaller or more detailed regions of tumors.

## Dataset

The dataset used for training and validation consists of medical images containing brain scans with tumor annotations.

## Model Architecture

The model architecture used for segmentation can be found in the notebook used for training.

## Training

The training process involves optimizing the model parameters to minimize the loss function, thereby improving segmentation accuracy. The provided metrics indicate the performance of the model on the training and validation sets.



