# Project 3 - Generate-TV-Scripts

This Repository stores my solution to the "Generate TV Script" problem presented as the third project in the Deep Learning Nano Degree by Udacity.

In this project, I'll generate my own Seinfeld TV scripts using RNNs. I'll be using part of the Seinfeld dataset of scripts from 9 seasons. 
The interesting part about this project 3 I'll build will generate a new ,"fake" TV script, based on patterns it recognizes in this training data using RNN.

**********************************************************************
## Part 1 - Implementing pre-processing functions

 * Lookup Table
 * Tokenize Punctuation

**********************************************************************
## Part 2 - Building Recurrent Neural Network
 * Building the Neural Network:
     * Batching the data
     * Creating dataloaders
     * Initializing RNN acchitecture
     * Defining layers
     * Applying FeedForward behaviour
     * Initializing hidden state of an LSTM/GRU
     * Applying Forward and Backpropagation
  * Training the model
  * Setting and tuning hyperparameters 
 
Note: This part of the process requires to apply LSTM. Here is a basic guide of LSTM.
[!LSTM](https://github.com/ucdcsl55/Generate-TV-Scripts/blob/main/Basic_LSTM.png?raw=true)
**********************************************************************
## Part 3 - Implementing the model
  * Generating new TV scripts
