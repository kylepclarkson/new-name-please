# New Name Please

A collection of scripts and notebooks that explore algorithms for generating new English names.
To generate new names, we use a dataset of names to learn a probability distribution of which 
characters follow which other characters.  

## Topics explored

### Bigrams

A bigram is a sequence of two characters - say `xy`. It is a useful to model words as given `x`, we can associate the probability that `y` follows it. 
Bigrams can be generalized to *n-grams* a sequence of n characters.

### Negative log likeihood

Negative-log likelihood (NLL) is a measure how well a model fits a set of data. *likelihood* is simply the product of the probabilities our model gives. The negative-log part has to do with how we optimize this value when training our models. 

### Multi-layer perceptron

An artificial neural network that can learn complex relationships between input and output data.
A multi-layer perceptron (MLP) consists of an input, output, and at least one hidden layer. 
The connections between these layers allow the network to learn these relationships. 
