# New Name Please

A collection of scripts and notebooks that explore algorithms for generating new English names.
To generate new names, we use a dataset of names to learn a probability distribution of which 
characters follow which other characters.  

## Results

Comparing the outputs of different models:

Names generated using the bigram model:
```
Name: 'lli'. Name is in training set? False
Name: 'ialindarie'. Name is in training set? False
Name: 'lyamio'. Name is in training set? False
Name: 'ripa'. Name is in training set? False
Name: 'domanymy'. Name is in training set? False
Name: 'erin'. Name is in training set? True
Name: 'tietorlerle'. Name is in training set? False
Name: 'dawiki'. Name is in training set? False
Name: 'nirecondela'. Name is in training set? False
Name: 'imean'. Name is in training set? False
Name: 'mmiseryo'. Name is in training set? False
Name: 'shrvalphala'. Name is in training set? False
Name: 'clhatesoleelaynosi'. Name is in training set? False
Name: 'kka'. Name is in training set? False
Name: 'yqniavoma'. Name is in training set? False
Name: 'ialeshyamietena'. Name is in training set? False
Name: 'e'. Name is in training set? False
Name: 'lesio'. Name is in training set? False
Name: 'gay'. Name is in training set? True
Name: 'sheiruiaeli'. Name is in training set? False
```

Names generated using the multi-layer perceptron model:
```
Name: 'libiialind.'. Name is in training set? False
Name: 'reeco.'. Name is in training set? False
Name: 'amir.'. Name is in training set? False
Name: 'rophen.'. Name is in training set? False
Name: 'many.'. Name is in training set? False
Name: 'yuzann.'. Name is in training set? False
Name: 'tila.'. Name is in training set? False
Name: 'sherte.'. Name is in training set? False
Name: 'dandie.'. Name is in training set? False
Name: 'nirec.'. Name is in training set? False
Name: 'zlo.'. Name is in training set? False
Name: 'mairqua.'. Name is in training set? False
Name: 'metseryo.'. Name is in training set? False
Name: 'nasvalphila.'. Name is in training set? False
Name: 'cla.'. Name is in training set? False
Name: 'tus.'. Name is in training set? False
Name: 'shelmyndriseka.'. Name is in training set? False
Name: 'yqucavonn.'. Name is in training set? False
Name: 'iameshpi.'. Name is in training set? False
Name: 'bet.'. Name is in training set? False
```

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


## Resources

- Andrej Karpathy's *Neural Networks: Zero to Hero* lectures - [link](https://karpathy.ai/zero-to-hero.html). 
- Aladdin Persson's *Pytorch Transformers from Scratch (Attention is all you need)* - [link](https://www.youtube.com/watch?v=U0s0f995w14). 