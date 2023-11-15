![image](https://github.com/AdrianaSanjuan/GradientBoosting_WineClassification_Wandb/assets/146115600/9500a4ab-0748-4f46-a1b7-62ccf9ceda29)


# GradientBoosting_WineClassification_Wandb
This repository contains an experimentation project for the Data Science class at Upgrade Hub. We utilize Weights & Biases to systematically tune and evaluate the hyperparameters of a Gradient Boosting Classifier. The dataset we are working with is the Wine dataset.

## Results
The experimentation results can be viewed in detail on the Weights & Biases dashboard. This includes various performance metrics such as accuracy, along with the hyperparameters used for each experiment.

https://wandb.ai/adrianasanjuanj/vinito-upgrade/reports/Untitled-Report--Vmlldzo1ODk4Mjk5

## Problem Description
The task at hand is a classic example of a multi-class classification problem. We aim to predict the category of wine based on several physicochemical attributes. The Wine dataset is a common benchmark dataset in the machine learning community.

## Dataset
The Wine dataset is a publicly available dataset that contains 178 samples of wines with 13 different attributes such as Alcohol content, Malic acid, Ash, etc. There are three classes, representing three different types of wines. The dataset is well-suited for classification experiments.

## Experimentation
For this project, we utilize the Gradient Boosting Classifier, a powerful ensemble machine learning algorithm that builds on decision trees. It is particularly known for its effectiveness in classification problems.

To find the best model, we explore various combinations of hyperparameters such as learning rate, maximum depth of the trees, the number of estimators, etc. Through systematic experimentation, we aim to understand the effect of these hyperparameters on the model's performance and find the combination that yields the best results.

We integrate Weights & Biases into our experimentation pipeline, which allows us to log the hyperparameters and the performance metrics for each experiment. Weights & Biases provides us with an interactive dashboard where we can visualize and analyze the results.

## Hyperparameter Tuning and Bes Model
During the experimentation process, we performed an extensive search over the hyperparameter space. A total of 770 different combinations of hyperparameters were tested to find the model that yields the best performance. The hyperparameters that we tuned include:

Learning rate
Maximum depth of the trees
Number of estimators
Loss function
Subsample fraction
Minimum number of samples required to split an internal node
Minimum number of samples required to be at a leaf node

This extensive search allowed us to explore a wide range of models and identify the combination of hyperparameters that optimizes the performance for this specific dataset.

The model with the best score achieved an accuracy of 0.9815. This high level of accuracy indicates that the model is highly effective in classifying the wine samples correctly. The hyperparameters of the best model are as follows:

learning rate: 0.25
max depth: 5
number of estimators: 150
loss function: deviance
subsample: 1.0
minimum samples split: 4
minimum samples leaf: 2

This combination of hyperparameters allowed the Gradient Boosting Classifier to capture the underlying patterns in the data efficiently and make highly accurate predictions.

## Contributions
Contributions to this repository are welcome. Please, ensure that the code follows best practices and is well-documented.

## License
This project is licensed under the MIT License.
