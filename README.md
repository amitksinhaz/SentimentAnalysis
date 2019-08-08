# Sentiment Analysis of Movie Review

Sentiment analysis of movie review using neural network. Looking at a review, the CNN model predicts if the sentiment expressed about a movie is positive or negative.

[//]: # (Image References)

[image1]: ./images/sentiment_network.png "Sentiment Network for Negative Review "
[image2]: ./images/sentiment_network_pos.png "Sentiment Network for Positive Review"


# Classification of Dog Breeds

## Introduction

This is a dog classification project using the Convolutional Neural Networks (CNN)! In this Udacity project for AI, we will learn how to build a deep learning pipeline to train and test CNN that can be used within a web or mobile app to process user provided images of dogs. Given an image of a dog, the trained CNN model algorithm will estimate the probability of the canine’s breed. For fun, if supplied with a human image, the model will predict the dog breed the human resembles!.



## Description 

Along with exploring state-of-the-art CNN models for classification and localization, you will make important design decisions about the user experience for your app.  Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  Your imperfect solution will nonetheless create a fun user experience!


![Sentiment Network for Negative Review][image1]
![Sentiment Network for Positive Review][image2]

## Getting Started

### Clone the repository and navigate to the downloaded folder.
* git clone https://github.com/udacity/deep-learning-v2-pytorch.git
* cd project-directory
	
### Data
* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
* Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
	
### Setting up Python Environment

* Refer to link https://github.com/udacity/deep-learning-v2-pytorch/blob/master/README.md
* In summary, install the miniconda environment followed by the machine learning libraries including PyTorch

### Jupyter Notebook
* From the repo, dog_app Python notebook files can be used
* jupyter notebook dog_app.ipynb

