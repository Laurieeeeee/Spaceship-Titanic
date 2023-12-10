# Spaceship Titanic Kaggle Competition

## Overview
Welcome to my repository for the "Spaceship Titanic" Kaggle competition. Set in the year 2912, this challenge tasks me with predicting which passengers were transported to an alternate dimension after the Spaceship Titanic collided with a spacetime anomaly. This repository documents my approach to solve this cosmic mystery using various machine learning models.

## Repository Contents
- `Decison_tree.ipynb`: Implementation of a decision tree model.
- `Decison_tree_HPO.ipynb`: Hyperparameter optimization for the decision tree model.
- `Insights_Visualization.ipynb`: Data analysis and insights visualization.
- `Naive_Bayes.ipynb`: Implementation of a Naive Bayes model.
- `Naive_Bayes_HPO.ipynb`: Hyperparameter optimization for the Naive Bayes model.
- `rf.ipynb`: Implementation of a random forest model.
- `rf_HPO.ipynb`: Hyperparameter optimization for the random forest model.
- `rf_autosklearn.ipynb`: Random forest model using Auto-sklearn.
- `comparision.csv`: Comparisons of model performances.
- `submission.csv`: Example submission file for the competition.
- `submission_naive_bayes.csv`: Submission file generated from the Naive Bayes model.
- `test.csv`: Test dataset provided by Kaggle.
- `train.csv`: Training dataset provided by Kaggle.

## Competition Details
In this competition, I am tasked with using data from the Spaceship Titanic's damaged computer system to predict which passengers were transported to an alternate dimension. This is a binary classification problem with the target variable being the 'Transported' status.

### Evaluation
Submissions are evaluated based on their classification accuracy, the percentage of correctly predicted labels.

### Submission Format
The expected submission format is a CSV file with two columns:
- `PassengerId`: The ID of the passenger.
- `Transported`: A boolean value (True or False) indicating the passenger's transportation status.

## Getting Started
For those new to Kaggle or machine learning, this competition serves as a great starting point. My `Getting Started Notebook` offers a quick introduction to my approach.

## Acknowledgments
Special thanks to Addison Howard, Ashley Chow, and Ryan Holbrook for creating the Spaceship Titanic dataset.

## Connect and Learn
Join the Kaggle community on Discord to discuss this competition, share insights, and collaborate with fellow data enthusiasts.

## Citation
For more information about the competition and dataset, visit the [Spaceship Titanic Kaggle Competition Page](https://kaggle.com/competitions/spaceship-titanic).
