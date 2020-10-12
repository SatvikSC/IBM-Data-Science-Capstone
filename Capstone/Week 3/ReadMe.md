# Capstone Project - Car accident severity 

Data Science Professional Certificatoin form IBM - Capstone Project
---
This project will be mainly used for the Applied Data Science Capstone, which is the part of my Data Science Professional certificate by IBM.

## Introduction

Street mishaps are incredibly normal. Customarily they lead to lost property and even life. Wouldn't it be extraordinary to have the option to comprehend what are the most well-known causes, so as to keep them from occurring? With this investigation, I am endeavoring to comprehend these variables and their relationship. This examination has different applications like an application that will incite the drivers to be more cautious relying upon the climate and street conditions on some random day or a path for the police to implement more wellbeing conventions. In this example, I am utilizing the information from the City of Seattle's police division indicating all the crashes from 2004 till present.

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
