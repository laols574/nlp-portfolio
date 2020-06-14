# nlp-portfolio
This tar file contains multiple nlp projects which can be run by executing "pytest" in each repository.

Decompressing files depends on your OS but you can use

tar -xvf nlp_portfolio.tar.gz

on the command line

## Project #1: transition-parser

This program acts as a transition dependency parser. It reads in text data, parses the input and
uses an oracle to predict the transition for all dependency trees in the training set. This is then used to train a classifer which predicts transitions for dependency trees in the testing set.


## Project #2: memm-classifier

This Maximum-entropy Markov model is a discriminative model which assumes conditional dependence. This program uses logistic regression to make a part of speech prediction for each word.

## Project #3: ngram-classifier

A simple logistic regression model which determines the difference between spam and ham samples.

## Project #4: words

This project uses word vectors to determine parts of speech.


