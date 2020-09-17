# Logistic-Regression-from-Scratch

## Objective
The goal of this project is to implement Logistic Regression from scratch using Pytorch.
The Logistic regression and Polynomial Logistic Regression are trained on real-world diabetes data.

## Blog Post
Please visit the [link](https://consciousml.github.io/blog/logistic-regression/polynomial-regression/diabetes/pytorch/from-scratch/2020/09/17/Logistic-Regression.html) to see the blog post associated to this repository.

## Dataset
The [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database) has been gathered by the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

This data set contains the following features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insuline
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (has diabetes or not)

## Setup
In order to install the conda environment needed to run the notebook, run the following line:
```console
conda env create --file requirements.yml
conda activate torch
```

