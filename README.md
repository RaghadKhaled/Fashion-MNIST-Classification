# Fashion-MNIST-Classification
Build and train a deep neural network model, to recognize and classify images of clothing, like sneakers and shirts in the Fashion-MNIST dataset, using Keras and Tensorflow.

## Overview
Here I add a validation set to test for `overfitting` while training.
During training I looked at the training and validation losses, there was overfitting. So I applied two ways to prevent my model from overfitting, `Early Stopping` and `Dropout`.
After the model is trained, I  used it to perform `inference` on 30 images and print the labels in green if my model's prediction matches the true label. On the other hand, if my model's prediction doesn't match the true label, I print the label in red.
This is a mini project I did during the Machine Learning nanodegree at Udacity. 
