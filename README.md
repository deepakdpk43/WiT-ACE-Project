# REDUCING CARBON DIOXIDE LEVEL BY GROWING TREES AND GRASS (Tree and Grass Land Prediction System)

## Contents
* Short Description
* Problem Statement
* Solution Statement
* The idea
Demo video
The architecture
* Long description
* Getting started
Live demo
* Versioning
* Authors
* Acknowledgments

## Short Description:
This is a Machine Learning Predictor Model that can predict No. of Trees and Grass Land Area for a given Geographical Area of a Region on the basis of plantation, population and carbon dioxide exchange.

## Problem Statement:
Nowadays Global Warming is a very big threat to the Earth and one of its major cause is increase in CO2 level. 

## Solution Statement:
A reason to the increased CO2 level is deforestation so in this project we are promoting afforestation and grass planting.
Through our project, we are aiming to predict number of trees and area of grass to be planted in a particular region to reduce the CO2 level of that region.

### How can Technology help?
* We used Feature Engineering for data preparation.
* We trained a Machine Learning Model MultiOutputRegressor on our DataFrame to predict the No. of Trees and Grass Land Area required to plant to reduce Carbon Dioxide leven in that region.
* We used IBM Watson Machine Learning for Deployment.

## Idea:
* We collected data of Forests Area, Population and Carbon Dioxide Emission of every district of India and calulated it's carbon dioxide exchange.
* We created a Machine Learning Predictor Model that can predict No. of Trees and Grass Land Area for a given Geographical Area of a Region on the basis of plantation, population and carbon dioxide exchange.

## Demo Video:

## Architecture:


## Long Description:
* We collected data of Forests of every district of India and calulated it's carbon dioxide exchange.
* We did same for the population data of India
* We gathered data from carbon dioxide emission from every district
* All the above data was accumulated to form our dataset
* Based on the following facts we did carbon dioxide exchange calculations:
  * One acre of trees removes up to 2.6 tons of carbon dioxide each year.
  * A typical tree can absorb around 21 kilograms of carbon dioxide (CO2) per year, 
  * A 1,000-square-metre area of grass will take up around one tonne of carbon per year
* On this dataset we split and normalized the data to make it fit to be trained to a model
* We used MultiOutputRegressor model to do regression and find out the  No. of Trees and Grass Land Area required to plant to reduce Carbon Dioxide leven in that region.
* Then we used IBM Watson Machine Learning and IBM Cloude storage to make a demployment space and deploy the model.

## Get Started:

### First download the dataset:
* Go to the data folder and download the dataset FinalTrees.csv

### Train the model and Deployment:
* Download the libraries - pandas, sklearn, numpy, ibm_watson_machine_learning
* Make an IBM Cloud account
* Train the model
* Create Deployment Space in Watson Studio Storage
* Generate API Key from your account and paste them in the apikey section of the wrl apikey in your code
* Run it and then test for different inputs

## Live Video:


## Version:
Version of our project: Version 1.0

## Authors:
* Hemangee De
* Kundan Prakash Jha
* Neha Jhawar
* Rachna Agarwal
* Deepak Kumar


## Acknowledgement:
We are very thankful to the IBM Mentors in slack who have been helping us for completing our project. We would also like to thank WiT-ACE for giving us this opportunity to showcase our skills in this platform.

