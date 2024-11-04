![Profile Views](https://komarev.com/ghpvc/?username=anay-a-joshi&color=green)  

# CS 5173 (Deep Learning) 
### Homework 2: Convolutional Neural Network   
```Level: Undergraduate```  
  
```Language: Python``` 


## Overview
This repository contains the code and models for ```Homework 2``` of the ```CS 5173``` ```Deep Learning``` course. The objective of this project is to classify handwritten digits from the MNIST dataset using different deep learning architectures, including **Deep Neural Network (DNN)**, **Convolutional Neural Network (ConvNet or CNN)**, and **Residual Network (ResNet)**.

The dataset used is the ```MNIST``` dataset, which consists of 70,000 grayscale images of handwritten digits ranging from 0 to 9, with each image sized at ```28x28``` pixels. The goal is to assign the correct label to each image that represents a particular digital number, which ranges from 0 to 9 (both inclusive).

The homework involves testing different neural network models, experimenting with hyperparameters such as learning rate, etc., and comparing their performances using metrics such as **Accuracy**, **F1 Score**, and **AUC**.
 

## Repository Structure  
* ```Screenshots```  
  The screenshots of the all the Models' Training Plots and AUC-ROC Curves, along with all the outputs/results.  
  All the models were tested with ```epochs=5```  and ```batch_size=64```.  
* ```Homework_2_CS5173_AnayAbhijitJoshi.ipynb```  
  The code of all the models (```DNN```, ```CNN or ConvNet```, ```ResNet```); along with all the required outputs.
* ```Anay_Joshi_hw2.pdf```  
  The answers to **Step 1**, **Step 2**, **Step 4**, **Step 5**, and **Step 6**.  
* ```README.md```

## Models  
* ```Deep Neural Network (DNN)```
* ```Convolutional Neural Network (CNN or ConvNet)```  
* ```Residual Neural Network (ResNet)```
  

## Functions & Parameters  
* ```create_dnn_model()```  
* ```create_convnet_model()```  
* ```create_resnet_model()```  
* ```test_model(*, model_type: str, learning_rate:Any)```  
* ```model_performance(*, model_type: str)```
* ```plots_training_and_validation_loss(*, model_type: str)```
* ```plots_AUC_ROC_curve```
* ```plot_F1_score(*, model_type: str)```

``` 
  All these functions use keyword-only arguments, and all parameters are required.
  Ensure that you specify the parameter names when passing values.

  All these functions have docstrings, please refer them for more information.
```
  

## Instructions to Run  
* Clone this repository or Download ``` Homework_2_CS5173_AnayAbhijitJoshi.ipynb ``` file.  
* Modify the parameters in the functions as per the requirements. Just a gentle reminder again, all functions use keyword-only arguments, and all parameters in each of these functions are required.  
* After setting the desired parameters in the function(s), please compile the code to see the results.  
