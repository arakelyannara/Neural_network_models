
## Neural_network_models

The purpose of the this project is to build and save models to predict if the investment would be succesful. We build the prediction based on the sample data from the applicants_data.csv file in the Resources folder. First, we will prepare the initial data, then we will try apply neural network tools to create 4 different models.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Neural network Model with 2 hidden layers and 50 epochs:

The accuracy and loss will look like

loss: 0.5576 - accuracy: 0.7287 
  

* Neural network Model 1 with 3 hidden layers and 50 epochs (optimizer="adamax") :

The accuracy and loss will look like

oss: 0.1844 - accuracy: 0.7300 



* Neural network Model 2 with 3 hidden layers and 200 epochs(doesn't help much):

The accuracy and loss will look like

loss: 0.1854 - accuracy: 0.7315

* Neural network Model 2 with 4 hidden layers() and 50 epochs(activation model - linear):

The accuracy and loss will look like

loss: 0.1873 - accuracy: 0.7292 



## Summary

Summarizing the results of the neural network models we can see that the accuracy of models is close to each other. However, the loss decreased up to 0.18, which is a good improvement.

## Technologies

JupyterLab web application

This project leverages python 3.7 with the following packages:

* pathlib
* pandas
* hvplot
* and sklearn machine learning library
* TenserFlow and Keras

---

## Usage


To use the "Neural_network_models" clone the repository, open it with Jupyterlab and run the 

    * venture_funding_with_deep_learning.ipynb

The models are saved in the "NN_models" folder.

---
    
## Contributor

Nara Arakelyan

---

## Licence 

UC Berkley
    

