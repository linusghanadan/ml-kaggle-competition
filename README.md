# Building a predictive model using deep learning to predict dissolved inorganic carbon (DIC) in water samples

## Background
Using the online platform Kaggle, my machine learning class is having a competition to see who can create the best predictive model (goal is to build model with lowest MSE for testing data). Our task is to build a model that predicts dissolved inorganic carbon (DIC) content in water samples based on other ocean chemistry features measured in the sample. Our data set comes from the California Cooperative Oceanic Fisheries Investigations (CalCOFI), an oceanographic and marine ecosystem research program located in California ([link to data set source](https://calcofi.org/data/oceanographic-data/bottle-database/)). All water samples were taken off the California coast.

## My approach
For this competition, I'll be experimenting with deep learning techniques that we have only briefly covered in the class. I'm skeptical that this approach will yield better results than a technique based on decision trees, but I'm curious to gain some experience building artificial neural networks and see how the tuning process compares to the other techniques we have practiced in class.

## Repository contents
    ml-kaggle-competition
    └───data
        │   Training data: train.csv
        │   Testing data for competition (with empty DIC column): test.csv
        │   Submission template for competition: sample_submission.csv
    │   README.md
    │   .ipynb
