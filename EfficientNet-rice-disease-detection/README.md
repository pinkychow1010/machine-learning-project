# Paddy Doctor: Paddy Disease Classification

## Identify the type of disease present in paddy leaf images


### Problem Statement

Rice (Oryza sativa) is one of the staple foods worldwide. Paddy, the raw grain before removal of husk, is cultivated in tropical climates, mainly in Asian countries. Paddy cultivation requires consistent supervision because several diseases and pests might affect the paddy crops, leading to up to 70% yield loss. Expert supervision is usually necessary to mitigate these diseases and prevent crop loss. With the limited availability of crop protection experts, manual disease diagnosis is tedious and expensive. Thus, it is increasingly important to automate the disease identification process by leveraging computer vision-based techniques that achieved promising results in various domains.

<br>

### Objective

The main objective of this competition is to develop a machine or deep learning-based model to classify the given paddy leaf images accurately. Training dataset includes 10,407 labeled images across ten classes (nine disease categories and normal leaf). Each paddy image is classified into one of the nine disease categories or a normal leaf.

### Project

In this project, several layers are added on top of a pretrained CNN model EfficientNet for the training using tensorflow framework. Input data is preprocessed, argumented, and resampled. Exploratory data analysis is performed before the building of the model. Data is trained in 10 - 20 epoch in several runs and the validation accuracy ranges from 97% - 98,7%. 

![alt text](https://github.com/pinkychow1010/machine-learning-project/blob/main/image/rice.png)

![alt text](https://github.com/pinkychow1010/machine-learning-project/blob/main/image/acc.png)
