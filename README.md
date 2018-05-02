# Neural Net Exploration


|Table of Contents |
|---|
| [Overview](#overview) |
| [Data](#data) |
| [Key Insights](#key-insights) |

## Overview
This project is an exercise in nerual network implementation using TensorFlow and Keras. I used the MNIST data set to train feed forward and convolutional neural networks using Tensorflow and Keras. The goal was to characterize each image into a digit 0-9. This was an excellent primer on the difference in implementation between Tensorflow and Keras.


## Data
The MNIST data set was retreived from Kaggle (https://www.kaggle.com/c/digit-recognizer) as part of an image recognition competition. It consists of a training and test set which have pixel data mapped into csv format. I created a validation set on the training data to tune my models and passed the testing data through the final product.


## Key Insights
Both the network structures performed well; unsurprisingly the convolutional network was the best thanks to its enhanced edge detection capacity. The most valuable outcome from this exercise was learning how Keras and Tensorflow interact with each other - my Keras models took almost twice as long to train! Early stopping will be a necessity with Keras moving forward. Keras is certainly more user friendly when setting up networks, but as of now this comes at the cost of functionality. Tensorflow networks are definitely more modular - one small example: when training my model I can print a note for every X epochs just to make sure everything is working. With Keras it's all or nothing - I can print a line for every epoch or for none at all. This obviously becomes an issue when you want to run a large number of epochs. I can certainly see the use cases for both TensorFlow and Keras. Next up for neural nets: a) LSTMs b) comparing TensorFlow and Keras with PyTorch!



## Concepts and Skills used
Python <br>
Pandas <br>
SKLearn <br>
TensorFlow <br>
Keras <br>
Feed Forward Neural Networks <br>
Convolutional Nerual Networks <br>