# Classifying Facial Expressions using Convolutional Neural Networks

## Introduction

Facial expression is perhaps the most unique method of communication between human beings 
(and perhaps other between other species as well), so I wondered about the plausibility of
tackling the deciphering of facial expressions using computational vision techniques.
Initially, I wondered if I should perhaps use some dimensionality reduction or feature extraction
techniques amongst the ones we learnt in class: principal component analysis, diffusion
mapping, etc to preprocess the data and then perform some perceptron analysis, but after
seeing how powerful convolutional neural networks could be, especially for images, I decided to
pivot to those!

The end result is a trained model and corresponding script for which we can further train or
evaluate our model on the validation set.

## Dataset

I utilized a pre-existing dataset, found on Kaggle, available here
(www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset).
The data labels about 36,000 48 x 48 grayscale images into 7 emotions: anger, disgust, fear,
happiness, neutrality, sadness, and surprise. This dataset was well-maintained, organized, and
suitable for my project. Example images from this dataset are shown below:
**Figure 1. Sample Images From Dataset**
(from left to right: anger, disgust, fear, happiness, neutrality, sadness, surprise)

## Methodology

My chosen model architecture for this computer vision task was a convolutional neural network
(CNN), which, as I’ve learned, are specifically designed to process grid-like data like images,
and have demonstrated remarkable success in various image recognition and classification tasks. 

## Usage Instructions

Run by using Jupyter or Colab on a Python Notebook Runtime Environment.

Install requirements by running, and ensure all relative directories are available in the runtime environment:
```
python -m pip install  -r requirements.txt
```
Run cells!

