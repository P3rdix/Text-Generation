# Text-Generation

This project makes use of Recurrent Neural Networks to predict text data. It uses four models of RNNs, the first being a classical RNN, with the remaining three being a mix of an RNN and a normal Artificial Neural Network. These models will further be used for two types of propagation, complete propagation, in which the entire data is fed through the network before backtracking, and partial propagation, in which the data is fed value by value, and backtracked simultaneously.



In addition to this, the data will also be run on different variables and their combinations. Currently being run simply on word index.



Each network is run on the same data set, for the same number of epochs(n = 500). The networks will then be tested by entering a single word, and viewing the 1000 word text that comes from it. The text will not contain punctuation marks, due to its removal from the training data. A text synthesizer containing punctuations may be attempted in the future.