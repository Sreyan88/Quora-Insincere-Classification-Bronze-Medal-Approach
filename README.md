[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3892920.svg)](https://doi.org/10.5281/zenodo.3892920)
# Quora-Insincere-Classification-Bronze-Medal-Approach

### This Repository contains the code for Quora Insincere Questions Classification Competition hosted on Kaggle

### Problem Statement:

An existential problem for any major website today is how to handle toxic and divisive content. Quora wants to tackle this problem head-on to keep their platform a place where users can feel safe sharing their knowledge with the world.

Quora is a platform that empowers people to learn from each other. On Quora, people can ask questions and connect with others who contribute unique insights and quality answers. A key challenge is to weed out insincere questions -- those founded upon false premises, or that intend to make a statement rather than look for helpful answers.

In this competition, Kagglers will develop models that identify and flag insincere questions.

<p align="center">
  <b> Architecture of the model used </b><br>
  </p></br>
 
<p align="center">
<img width="299" height="451" src="https://github.com/Sreyan88/Quora-Insincere-Classification-Bronze-Medal-Approach/blob/master/Extra/Quora Model.png">
</p></br>

<p align="center">
  <b> Steps to final prediction </b><br>
  </p></br>
 
 1. Cleaning the data of all possible errors. Cleaning included correcting spelling mistakes, expanding contractions, removing numbers and punctuations, etc.
 2. Defining the extra features for auxiliary input.
 2. Defining the perfect model.
 3. Training on Stratified 5-Fold K-Folds and ensembling the results for final predictions.
 
<p align="center">
  <b> Things which helped in the Bronze Medal </b><br>
  </p></br>
  
  1. Cyclic Learning Rate
  2. Using an ensmeble of pre-trained Glove and Paragram word embeddings
  3. Gradient Clipping of 1.0
  4. Auxiliary Input of statistical features related to the sentences
  
  
