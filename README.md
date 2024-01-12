# Project Description

In this project, the goal is to build a classifier that distinguishes videos of five different activities using transfer learning and image classification techniques. The project involves training a convolutional neural network (CNN) for image classification and then converting it into a video classifier using moving averages to address the flickering phenomenon. 

## Dataset

The dataset consists of several hundred images per class, and pre-trained models such as ResNet50, EfficientNetB0, and VGG16 are utilized.

## Training

The networks are trained for at least 50 epochs, and the model's performance is evaluated using metrics such as confusion matrix, precision, recall, accuracy, and F1 score for both the training and test sets, considering the multi-class classification nature of the problem.

## Evaluation

The video classification model is evaluated using moving averages and the performance metrics are reported for the test data, which consists of videos.

![image](https://github.com/drewm8080/Video_Classification/assets/71193439/db964764-19b5-478e-996d-5fe578ede840)

