# Logistic-Regression-from-Scratch

## Objective
The goal of this project is to implement Logistic Regression from scratch using Pytorch.
The Logistic regression and Polynomial Logisitc Regression are trained on real-world diabetes data.

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

## Notebook
The experiment can be found in the notebook at the root of the project.
