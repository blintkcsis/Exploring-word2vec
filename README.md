

![Simpson's image from WikiPedia](https://user-images.githubusercontent.com/45124913/215531489-e6f9efa2-c86f-4f73-b226-05d542159ffa.png)

# Explorations on word2vec algorithm on dialogue from Simpson's

As a first exploration I looked into different implementations of word2vec. Quickly found 'gensim', which as far as i know, is the first implementation of the original algorithm we explored in class for INST0075. It also seems relatively widely used and quickly found many example tutorials. Using the dialouge from 27 seasons of The Simpson's seemed like a silly enough way to get started without much plan. This project could be broken down into three parts (1) following the original tutorial (referenced later) to clean, initialize and train the model on all dialouges, then (2) looking into new ways to understand the results and (3) aggregating dialoges by character to understand how characters are represented by what they say.


## Code dependencies from the following libraries:

* gensim        4.3.0
* scikit-learn  1.2.1
* plotly        5.13.0
* spacy         3.5.0
* seaborn       0.12.2

Python          3.8.15


Much of the first half directly comes from [this](https://www.kaggle.com/code/pierremegret/gensim-word2vec-tutorial/notebook#Materials-for-more-in-depths-understanding:) tutorial. It also points to the used dataset, which is available [here](https://www.kaggle.com/code/ambarish/fun-in-text-mining-with-simpsons/data). 

The whole code is ran through the jupyter notebook, which also explains everything as it is ran. The original visualisation is referenced from another tutorial and the last exploration is largely my own code.
