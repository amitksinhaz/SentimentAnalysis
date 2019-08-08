# Sentiment Analysis of Movie Review

[//]: # (Image References)

[image1]: ./images/sentiment_network.png "Sentiment Network for Negative Review "
[image2]: ./images/sentiment_network_pos.png "Sentiment Network for Positive Review"

## Introduction

Sentiment analysis of movie review using neural network. Looking at a review, the CNN model predicts if the sentiment expressed about a movie is positive or negative.

## Description 

This is a Udacity project to predict whether a movie review is negative or positive based on the reviews entered by viewers of a movie. You should concepts like forward and back-propagation, stochastic gradient descent, mean squared error and how to split data for training and testing the neural network. The project begins by creating a simple network, and then makes it better by reducing noise in text vocabulary, converting text to numbers using hot-encoding and by analyzing ineffinciencies in the network.

Following images show the neural network. Layer_0 is the input, layer_1 is the hidden layer and layer_2 is the output for positive and negative reviews.

![Sentiment Network for Negative Review][image1]
![Sentiment Network for Positive Review][image2]

## Getting Started

### Clone the repository and navigate to the downloaded folder.
* git clone https://github.com/amitksinhaz/SentimentAnalysis.git
* cd project-directory
	
### Data

Download the data.zip file from data folder. Unzip the files at the roote folder. The zipped file contains two files:
* labels.txt - this has POSITIVE or NEGATIVE value
* reviews.txt - this is the text representing the movie review


### Setting up Python Environment

* Refer to link https://github.com/udacity/deep-learning-v2-pytorch/blob/master/README.md
* In summary, install the miniconda environment followed by the machine learning libraries including PyTorch

### Jupyter Notebook
From the repo, Python notebooks files can be used:
* jupyter notebook Sentiment_Classification_Projects.ipynb
* jupyter notebook Sentiment_Classification_Solutions.ipynb

