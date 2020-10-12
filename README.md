# Image-classification-project

## Introduction
Image Detect challenge has 200 classes. Each class has 450 training images, 50 validation images, and 50 test images. We have training, validation and test sets with images and annotations. We have both class labels and bounding boxes as annotations; however, we are going to predict the class label of each image without localizing the objects. The test set has no labels.

## Installation
You need to install the following libraries,
- Numpy
- Pandas
- Seaborn
- matplotlib
- Keras

## Project Motivation
We primarily going to construct from scract a CNN (convulutional neural network) for detecting images. We have developed three CNN models for the detection of images. The first two CNN models: Network1 and Network2, are mainly developed using CNN model designs based on the research paper "DenseNet Models for Tiny ImageNet
Classification" written by Zoheb Abai and Nishad Rajmalwar, and link to their paper is given [here](https://arxiv.org/pdf/1904.10429.pdf). The original source code can be found [here](https://github.com/ZohebAbai/Tiny-ImageNet-Challenge.git). Network 3 is based on transfer learning method.

## File description
- **Final_project_report2.pdf**: is the final project report, giving details about the process.
- **Network1_Team_A3GPM.ipynb**: This is the jupyter notbook file for the Network1.
-  **Network2_Team_A3GPM.ipynb**: This is the jupyter notbook file for the Network2.
- **transfer_learning_Team_A3GPM.ipynb**: This jupyter notebook where we have implement the transfer learning method.

## Result
Originally it was reported that Network 1 and 2 gave 59% and 62% accuracy, respectively, however we have modified the training process of these CNN has achieved 62% and 63% accuracy, respectively. We were only able to achieve near about 30% accuracy.

## Licensing, Authors, Acknowledgements
Must give credit to Zoheb Abai and Nishad Rajmalwar for their developing CNN models (Network1 and Network2). You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://github.com/ZohebAbai/Tiny-ImageNet-Challenge.git).
