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
 
Note: This part of the process requires to apply LSTM/GRU. Here is a basic guide of each of them.
![LSTM](https://github.com/ucdcsl55/Generate-TV-Scripts/blob/main/basic_LSTM.png?raw=true)
![GRU](https://github.com/ucdcsl55/Generate-TV-Scripts/blob/main/basic_GRU.png?raw=true)
**********************************************************************
## Part 3 - Implementing the model
  * Generating new TV scripts using the final model created
  ![function](https://github.com/ucdcsl55/Generate-TV-Scripts/blob/main/lstm_function.png?raw=true)

And the most important lesson for this project is about tuning hyperparams
First set the parameters, then train the neural network and next tune the following parameters:

    - Set sequence_length to the length of a sequence.
    - Set batch_size to the batch size.
    - Set num_epochs to the number of epochs to train for.
    - Set learning_rate to the learning rate for an Adam optimizer.
    - Set vocab_size to the number of unique tokens in our vocabulary.
    - Set output_size to the desired size of the output.
    - Set embedding_dim to the embedding dimension; smaller than the vocab_size.
    - Set hidden_dim to the hidden dimension of your RNN.
    - Set n_layers to the number of layers/cells in your RNN.
    - Set show_every_n_batches to the number of batches at which the neural network should print progress.
