# Recurrent Network to Predict Multivariate Data

This repository contains a basic, easy to understand and customize, Neural Network architecture template that can predict multiple dimensions for a single recurrent step from previous time series like data. A simple example is predicting both the X & Y coordinates of a ball moving around a 2D grid. A more complex example would be satellite imagery of a ship moving across the ocean.

Currently, most available code examples of similar models only predict a single output (class or true value) for each recurrent step.

Key highlights include: 
1.	Input/Output Data Structures
2.	Proper Scaling of the Data
3.	Activation Function Selection

This base template is easily enhanced to use more advanced recurrent cells (LSTM/GRU), add convolutional layers, additional dimensions, embeddings, network layers, etc.

The architecture of this model follows the traditional PyTorch “cadence”. Please see here for the excellent introduction videos on the PyTorch “cadence”. 

https://github.com/hunkim/PyTorchZeroToAll
