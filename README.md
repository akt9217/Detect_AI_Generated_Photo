# Detect-AI-generated-photos
Building a Robust model that can identify a fake photo created by AI

## Project Overview
In a world where most services are available online, identity verification is crucial to ensure that only real individuals can access and use these services. However, with the rise of generative AI, fake identities can be easily created using sophisticated algorithms. This has led to an increase in identity fraud, as fake identities can be used to gain access to online services and commit fraudulent activities.


## Dataset
As an active participant on Bitgrit competition https://bitgrit.net/competition/18?ref=mlcontests, datasets were provided with training set having target labels
and test set for making prediction. You can access them from the provided link after registering.
Both were in .csv format

## How to Design a good model
training a deep CNN with conventional layers is not going to help for a variety of datasets and may result in overfitting, The model must learn specific features which can detect manipulation in image.To do so one technique can be to compute co-occurrence matrices directly on the image pixels on each of the red, green and blue
channels and pass them through a convolutional neural network, thereby allowing the network to learn important features from the co-occurrence matrices.

## Implement The model Yorself 
1. set the Runtime as GPU(T4) in  colaboratory
2. import train and test .csv files in colab
3. convert them in dataframes and follow the .py file

## Resources 
https://arxiv.org/pdf/1903.06836.pdf
