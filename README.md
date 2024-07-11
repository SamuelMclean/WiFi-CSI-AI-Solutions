# WiFi CSI Activity Prediction with CNN
## Overview

This project explores the effectiveness of using WiFi Channel State Information (CSI) for predicting patient activities. Specifically, it investigates the differences in performance when training and inferencing a Convolutional Neural Network (CNN) using two different types of CSI data:

1. Full complex number data.
2. Only the real component of the data.

The goal of this analysis is to determine whether the full complex number data offers a significant advantage over using only the real component in terms of prediction accuracy and model performance.

## Motivation
I undertook this task during my capstone project at deakin univercity. It seemed like an interesting task and application for machine learning methods I had recently learnt.


## Replication
#### Used Libraries and Versions:
Python 3.12
Tensorflow 2.x
sklearn 1.5
pandas 2.x
matplotlib 3.9
seaborn 0.13
Other versions are likely to work but these are just what I used


1. Download the dataset from [Here](https://drive.google.com/file/d/18y3NSijQwISNWvKji2s-9odgW2ws3kPr/view?usp=drive_link) ~4GB
2. Pick one of the two notebook files run them with the dataset in the same folder.
