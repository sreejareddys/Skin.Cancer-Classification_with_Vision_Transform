# Skin Cancer Detection using Vision Transformer (ViT)

This repository contains code for a cancer detection model using a Vision Transformer (ViT) architecture. The model is trained on a dataset of benign and malignant cancer images and aims to classify new images accordingly.

## Dataset

The dataset used for training and evaluation consists of images organized into two folders: 'Benign' and 'Malignant'. The dataset path is specified in the code and should be updated to reflect the location of your dataset.
**Dataset Source:** [https://www.kaggle.com/datasets/subho117/train-cancer](https://www.kaggle.com/datasets/subho117/train-cancer)

## Model

The model is based on the ViT architecture with pretrained weights. It includes dropout layers for regularization and additional fully connected layers to adapt to the specific classification task. The model is implemented using PyTorch.

## Training

The model is trained using the Adam optimizer and cross-entropy loss function. Early stopping is implemented to prevent overfitting. Training and validation metrics are tracked and plotted for analysis.

## Evaluation

The trained model is evaluated on a separate test dataset to assess its performance. The test accuracy is reported.

## Usage

1.  Clone this repository.
2.  Update the dataset path in the code to reflect the location of your dataset.
3.  Install the necessary dependencies (PyTorch, torchvision, etc.).
4.  Run the code to train and evaluate the model.

## Dependencies

*   Python 3.x
*   PyTorch
*   torchvision
*   matplotlib
*   numpy
*   PIL
*   pandas
*   os

## Results

The model achieves a test accuracy of 96.30%.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.
