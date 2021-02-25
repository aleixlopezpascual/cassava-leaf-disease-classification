# cassava-leaf-disease-classification
Kaggle competition 2021-02

https://www.kaggle.com/c/cassava-leaf-disease-classification

## Overview
In this computer vision competition you had to classify cassava images into four disease categories or a fifth category indicating a healthy leaf. The main challenges of this competition were the low resolution of the images and the presence of noisy labels. In order to not overfit those noisy labels, label smoothing is applied + TaylorCrossEntropyLoss. The model applied is an ensemble of EffNet-B4 + resnext50_32x4d using 5 stratified folds.
