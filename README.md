# FacialExpressions

## Contents
1. [Introduction](#introduction)
2. [DataSet](#DataSet)
3. [CNN Architectures](#CNNArchitectures)
4. [Results](#Results)
6. [Authors](#authors)
 
 ## Introduction
Welcome to the Facial Expression Recognition project! This project aims to develop a deep learning model for accurately classifying facial expressions and estimating arousal and valence values from images. The model is based on two different CNN architectures, ResNet and EfficientNetB0, which have been fine-tuned and trained on a large dataset of images and corresponding label files.

## DataSet
For this project we have used a private dataset, you can use your own dataset with specified annotations for class categories and arousal and valance values.

## CNN Architectures
We have used SIFT as feature extractor and used K-Means to cluster the similar features. SVM and Random forests are used for the classification. In the code you need to add the paths to the train and test image folder if dataset is already splitted other wise use DataSet 2 portion and just add the images folder path in it. You need to specify the images classes names, in the manner already defined in the code, in the variable class_indices. While i have used string processing to get the class name for each image using folder name, so set that according to the path settings. Another important thing to mention is that choose the value of K while calling create clusters function carefully, that can effect performance and efficiency as well.

## Results



## Authors
Israr Ahmed <iahmed.msds22seecs@seecs.edu.pk>

