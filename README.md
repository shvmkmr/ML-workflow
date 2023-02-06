# ML-workflow
A comprehensive framework that guides you through the complete machine learning (ML) pipeline, from data prep to model building.

# Design
This repository contains code in the form of a Jupyter notebook, which will guide you step by step to complete the specific exercise/task. The results are saved as per the directory structure mentioned below, but the user can choose to set their own preferences. The saved results are used in subsequent executions to extend the current results for the next step.

## Dataset 
Please download the dataset from any repository, use a dataframe to store the data, and keep the last columns as class **Label**

## Usage
### Major packages required
* Pandas
* Numpy
* scikit-learn
* Matplotlib

### Directory structure
* code directory (example: exp1)
* Input/raw/exp1
* Input/prep/exp1
* Output/exp1/Results/
### Prepare your own dataset before running experiments.
* Use [Feature selection](Feature%20selection.ipynb) notebook to obtain the importance score of all the features and save it as a file.
* Use [Curve Fitting](Model%20comparison.ipynb) notebook to find an optimal set of features from a score file (containing the scores of all the features).
* Use [Model comparison](Model%20comparison.ipynb) notebook to compare various feature sets on multiple ML models to obtain the best-performing model and feature combination.
