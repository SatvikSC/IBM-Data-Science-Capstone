# Capstone Project - Car accident severity 

Data Science Professional Certificatoin form IBM - Capstone Project
---
This project will be mainly used for the Applied Data Science Capstone, which is the part of my Data Science Professional certificate by IBM.

## Introduction

Street traffic wounds are at present assessed to be the eighth driving reason for death over all age bunches all around the world and are anticipated to turn into the seventh driving reason for death by 2030. 

Breaking down a huge scope of components, including climate conditions, unique occasions, roadworks, gridlocks among others, a precise forecast of the seriousness of the mishaps can be performed. 

These bits of knowledge could permit law implementation bodies to apportion their assets all the more adequately ahead of time of possible mishaps, forestalling when and where serious mishaps can happen just as sparing both, time and cash. Moreover, this information on an extreme mishap circumstance can be cautioned to drivers with the goal that they would drive all the more cautiously or even change their course on the off chance that it is conceivable or to the medical clinic which might have set everything prepared for a serious intercession ahead of time. 

Governments ought to be profoundly inspired by, exact expectations of the seriousness of a mishap, so as to diminish the hour of appearance and subsequently spare a lot of individuals every year. Others intrigued could be privately owned businesses putting resources into advancements meaning to improve street safeness. 

This task comprises of a few sections separated into two unique note pads.

## Feature Selection

This first notebook contains all the steps and transformations I performed for the feature selection. You can find the information on the raw data in the following [kaggle page](https://www.kaggle.com/ahmedlahlou/accidents-in-france-from-2005-to-2016).I've selected the most relevant and useful data for my analysis.

## Predicting Traffic Accident Severity - Technical Overview

+ Data Description
+ Data Cleaning
+ Exploratory data analysis
+ Model Development
  + Decision Tree
    + Random Forest
  + Logistic Regression
  + KNN
  + SVM
  
## Results:
    
|**Algorithm**|**Jaccard**|**f1-score**|**Precision**|**Recall**|**Time(s)**|
|---------|-------|----|-------------|------|-------|
|**Random Forest**| 0.722  | 0.72  | 0.724  | 0.591  |  6.588 |
|**Logistic Regression**|  0.661 |  0.65 |  0.667 | 0.456  | 6.530 |
|**KNN**| 0.664  | 0.66  |  0.652 | 0.506  |  200.58 |
|**SVM**| 0.659  | 0.65  |  0.630 |  0.528 |  403.92 |

For this particular issue *precision* implies the % of anticipated serious mishaps that were really extreme. The *recall* rather, is the % of genuinely serious mishaps that were appropriately anticipated. For this particular issue, the review is a higher priority than the exactness as a high review will support that all necessary assets will be prepared up to the seriousness of the accident.\ 

For this situation, the review is a higher priority than the exactness as a high review will support that all necessary assets will be prepared up to the seriousness of the mishap. The *logistic regression*, *KNN*, and *SVM* models have comparable precision, be that as it may, the computational time from the relapse is obviously better than the other two models. Without no uncertainty, the *Random Forest* is the best model, simultaneously as the *log. res.* it improves the precision from 0.66 to 0.72 and the review from 0.45 to 0.59.


## Links for Dataset: [Drive Link](https://drive.google.com/drive/folders/1N8_Mv3Z3UOmm8t1aAZ63i3iGczajsDWN?usp=sharing)
