##Task:  Multiclass Classification 

Framewise phoneme prediction from speech. 

What is a phoneme? 
Wiki: A unit of sound that can distinguish one word from another in a particular language. ● Machine Learning → M AH SH IH N  L ER N IH NG

Model: LSTM + FC

Tricks: 
* Orthogonal initialization: Initialize the weights of the gating units in your network to be orthogonal to one another. This can help prevent vanishing or exploding gradients.

* Bias initialization: Set the bias of the forget gate to 1. This can help the network to remember information from previous time steps.

* Cosine annealing: Use a learning rate scheduler that decreases the learning rate slowly and smoothly over time, rather than in fixed steps. Cosine annealing is one such technique.

* Batch normalization: Normalize the activations of your network's hidden layers by taking the mean and variance of each batch of training examples. This can help to speed up training and improve generalization.

* Dropout: Randomly set some of the activations in your network to zero during training. This can help to prevent overfitting.
