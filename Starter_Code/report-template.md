# Module 21 Report Template

## Overview of the Analysis


* The purpose of the analysis is to showcase our abilities with deep learning using the features provided in the data set and creating a classifier that predicts if applicants will be successful if funded.
* We processed the data, validated the data and evaluated the model.
* The supervised learning classification models we used were logistic regression and probability.

## Results
Data Preprocessing

What variable(s) are the target(s) for your model? 'IS_SUCCESSFUL' column is the targer variable
What variable(s) are the features for your model? The feature variables are all columns but 'IS_SUCCESSFUL' column.
What variable(s) should be removed from the input data because they are neither targets nor features? Both 'EIN' and 'NAME' were removed as they were non-beneficial ID columns.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? I attempted 80 and 30 based off the example provided from class.
Were you able to achieve the target model performance? I was not able to achieve the 75% accuracy target model performance in any of my numerous attempts.
What steps did you take in your attempts to increase model performance? I adjusted neurons, layers and activation functions without success to achieve 75% accuracy.

## Summary

We saved 3 neural network models for this evaluation. Further model evaluations may provide better predictions, including review with TensorFlow and removing further non-beneficial columns. Consistently with the models run, the accuracy reported was 73%.
