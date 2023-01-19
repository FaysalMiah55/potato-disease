# Potato Disease

## Table of Contents:
### 1. Description
### 2. Dataset
### 3. Data Preprocessing 
### 4. Building the Model
### 5. Evaluation

### 1. Description
I build a `machine learning` model using `tensorflow` that can detect if there are `early blight` and `late blight` diseases in potato plant. 
The goal of this project to accurately identify those disease so that farmers can take step.

### 2. Dataset
The datset is collected from [kaggle](https://www.kaggle.com/datasets/arjuntejaswi/plant-village).

### 3. Data Preprocessing 
1. Data analysis
2. Split the dataset
      * I split the dataset with `80%` of `training set` and `20%` of `test set`.

### 4. Building the Model
1. Creating a Layer for `resizing` and `normalization`.
2. Data Augmentation
3. Model Architecture
    * `Conv2D` for *CNN* 
    * `MaxPooling2D` for *pooling*
    * `relu` & `softmax` for *activation function*
    * `adam` for *optimization* 
### 5. Evaluation
    * `accuracy`






