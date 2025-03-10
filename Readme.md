# Assignment 5: Pytorch for Machine Learning

In this assignment, we'll go over the pytorch basics. 

## Assignment Objectives
- Learn the basics of the Pytorch 
- Use pytorch for a ful machine learning workflow 
- Utilize pandas with a dataset 
- Create a pytorch dataloader 
- Get first-hand exposure in developing a MLP 
- Do hyper-paramter tuning 
- Analyze and report tuning results 

## Pre-Requisites
Knowledge of the basic syntax of Python is expected, as is background knowledge of the algorithms you will use in this assignment.

If part of this assignment seems unclear or has an error, please reach out via our course's CampusWire channel.

<!-- ## Rubric

| Task                          | Points | Details                                                   |
|-------------------------------|--------|-----------------------------------------------------------|
| Code Runs                      | 10      | Notebook runs without error                              |
| Part 1                         | 10     | Completion of Part 1: Pytorch Basics                      |
| Part 2                         | 10     | Completion of Part 2: Dataset Exploration and  Feature Clean up  |
| Part 3                         | 10     | Completion of Part 3: Data Loader Creation                |
| Part 4                         | 20     | Completion of Part 4: Creating a MLP                      |
| Part 4                         | 20     | Completion of Part 5: Creating a training and Evaluation Loop                  |
| Part 6                         | 20     | Completion of Part 6: Basic Hyper-parameter Tuning               |
| **Total Points**               | **100** |                                                           | -->

# Part 1: Pytorch Tutorial 

## Overview

In the first component of this assignment we will ask you to go over the basics of pytorch and follow the tutorial. We will then ask you to do simple operations using pytorch so that you can gain an understadning of the basics. We highly recommend that you go through the basics and understand each steps.

This component of the assignment uses the iris dataset TODO: Add description and citation of the dataset. 


## Documentation and Resources

### Pytorch 
Todo: Add resources for pytorch  

# Part 2: Titanic Dataset Prediction 

## Overview
In this component of the assignment we will ask you to go through the machine learning workflow using Pytorch. We will first ask you to load and explore the dataset. Next, you will modify the data according to specifications. You will then create a dataset loader, write out the mult-layer percepto

## Instructions
First, load the cleaned titanic dataset. Clean the dataset according to the specification given in the jupyter notebook, using the pandas library. Next, your will create Dataloader using the pytorch standards. 

The rest is placeholder that I am using, will remove ... .
For grading consistency, please use the cleaned dataset included in this assignment `ckd_feature_subset.csv` instead of your version from Assignment 3 and use `42` as your random seed. Place your code and report for this section after in the same notebook, creating code and markdown cells as needed. 

Next, you will train and evaluate the following classification models:
- Logistic Regression
- Support Vector Machines (see SVC in SKLearn)
- k-Nearest Neighbors
- Neural Networks

To measure the performance of the models, perform 5 fold cross validation using the entire dataset. Report these measurements in a table where you report the average and standard deviations. Summarize these results afterwards. Which model performed the best and why do you think that is?

Finally, experiment with a handful of different configurations for the neural network (report a minimum of 3 different settings) and report on the results in a table as you did above. Summarize your findings, which parameters made the biggest difference in the for classification?

> **💡 Tip:**  LLMs are great for transforming messy outputs into clean tables quickly

## Submission 

- To make a submission for the project, submit a pdf of sklearn_sample_notebook jupyter notebook under *Assignment 4 - SKLearn for Machine Learning* on Gradescope. 
- How to generate a pdf of your jupyter notebook:
    - On your Github repository after finishing the assignment, click on sklearn_sample_notebook.ipynb to open the markdown preview.
    - Ensure that the notebook has outputs for all the cells included
    - Use your browser's "Print to PDF" feature to save your PDF.
    - On Gradescope, please assign the pages of your pdf to the specific questions/sections outlined.