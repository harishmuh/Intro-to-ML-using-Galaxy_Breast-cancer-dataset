[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

# **Introduction to machine learning using Galaxy software**

## **Context**
This repository contains my completed work for the machine learning introduction tutorial using Galaxy.


## **Objectives**
- Learn how to use Galaxy for data preparation and ML modeling.
- Train a classifier (using an SVM model) to distinguish sample types.
- Create a galaxy workflow
- Obtain a prediction result (0: no breast cancer, 1: positive breast cancer) after training the model.

## **Dataset**
* The training dataset [(source)](https://zenodo.org/record/1401230/files/breast-w_train.tsv) with targets (9 features and one target)
  ![train data](https://github.com/harishmuh/Intro-to-ML-using-Galaxy_Breast-cancer-dataset/blob/main/datasets/train_data.png?raw=true) 
* The testing dataset [(source)](https://zenodo.org/record/1401230/files/breast-w_test.tsv) with targets (9 features and no target)
  ![Test data](https://github.com/harishmuh/Intro-to-ML-using-Galaxy_Breast-cancer-dataset/blob/main/datasets/test_data.png?raw=true)

## **Results**

**Workflow of the analysis (using Galaxy)**

![workflow](https://github.com/harishmuh/Intro-to-ML-using-Galaxy_Breast-cancer-dataset/blob/main/Docs/Breast%20Cancer%20Classification_Workflow.PNG?raw=true)

**Prediction results**
* The targets (0: no breast cancer, 1: positive breast cancer) can be seen in the last column of the table below. 

![Prediction result](https://github.com/harishmuh/Intro-to-ML-using-Galaxy_Breast-cancer-dataset/blob/main/Docs/Prediction%20result.PNG?raw=true)

## **Assets**
* [My analysis in Galaxy](https://usegalaxy.eu/u/harish_muh12/w/workflow-constructed-from-history-machine-learningintrobreast-cancer)
