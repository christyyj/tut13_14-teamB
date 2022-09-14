# Traffic Sign Detection and Recognition System
> This project emphasizes on the segmentation of traffic sign images based on the Chinese Traffic Sign Database (CTSD). The classification model is based on the SVM classifier trained with HOG and color features.

## Table of Contents
* [General Info](#general-information)
* [Libraries](#libraries)
* [Dataset](#dataset)

## General Information
Source code for the whole project is available in the main.ipynb file, including the segmentation and classification model.
The color of traffic sign and category (0 - 57) would be classified based on the input image.
Segmentation Model has been tested with 90 images from the CTSD, the image files can be read based on the "SignSeg90Annotation.txt" file
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Libraries
- OpenCV
- sklearn


## Dataset
Dataset [_here_](https://drive.google.com/drive/folders/1ffKs7IHSph3TxakJhKlRz6XzholLMfAU?usp=sharing). <!-- demo link -->
- category_sample: sample sign images of the 58 categories based on the CTSD dataset
- tsrd_train: 4170 sign images to train the classifier
- tsrd_test: 1994 sign images to test the classifier
