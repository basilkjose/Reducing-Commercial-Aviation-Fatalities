# Reducing Commercial Aviation Fatalities

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Aim](#aim)
  * [Technical Aspect](#technical-aspect)
  * [To Do](#to-do)
  * [Technologies Used](#technologies-used)
  * [Credits](#credits)
  
## Overview

Most of the flight fatalities or flight accidents due to pilot error are due to the loss of airplane state awareness. Airplane state awareness (ASA) is a pilot performance attribute wherein the pilot should be able to realize and respond quickly to any change of state of the airplane. Loss of airplane state awareness may lead to many dangerous situations and may result in loss of airplane control. Loss of ASA is mainly due to loss of attention on the part of pilots who may be distracted, sleepy, or in other dangerous cognitive states. Due to the stressful environment, while flying, the possibility of the loss of awareness is common.So our challenge is to build a model to detect troubling events from aircrew's physiological data. For this project we used [LightGBM](https://lightgbm.readthedocs.io/en/latest/) for modelling. Model want to predict the cognitive state __( Baseline ,Startle/Surprise (SS) ,Channelized Attention (CA) ,Diverted Attention (DA) )__ of a pilot using physiological data.

The data for the project was provided by Kaggle. One of the important tasks in the project is feature engineering, __How to derive new features from existing features?__ since most of the data is collected over biological sensors it is quite interesting to me learn new things about how these data are collected and derive new features. For deriving new features, we used the python [BioSPPy](https://biosppy.readthedocs.io/en/stable/) module.

## Motivation 

It is my first full stretch data cycle project I have been involved in, Project very interesting to me because of the features present in the data set. Most of the features are a biologically related feature , before starting the project I had only know the names like ECG, EEG, R, GSR. So this project enhanced me to learn new things about how these sensors are worked? how data is collected using sensors? how these sensors are related to the human body?

## Aim

Every year thousands of people lose theirs due to aircraft fatalities. Still, we are trying strategies to reduce the accident. There are different reasons for aircraft fatalities, one of the primary reasons is pilot error. So the goal of the project is, When the pilot enters into any one of the dangerous cognitive states, he/she should be alerted, thereby preventing any possible accident.

## Technical Aspect

* Complete code written on python (jupyter notebook).
* Google Cloud Platform (GCP) is used for training the model.
* Perfromance metric used for the project is multi class log loss

## To Do

* Removing noises from biological sensors data.
* Done bit more feature engineering.
* Try some deep learning algorithms for modelling.

## Technologies Used 

![](https://forthebadge.com/images/badges/made-with-python.svg)


 [<img target="_blank" src="https://imgur.com/05j8LAQ.jpg" width=200>](https://lightgbm.readthedocs.io/en/latest/Python-Intro.html)......[<img target="_blank" src="https://imgur.com/EiX2o88.jpg" width=200>](https://scikit-learn.org/stable/)

[<img target="_blank" src="https://imgur.com/Bmwklam.jpg" width=200>](https://console.cloud.google.com/)        


## Credits

 * [Kaggle](https://www.kaggle.com/c/reducing-commercial-aviation-fatalities) - For conducting problem and providing this wonderful dataset.
 * [BioSPPy](https://biosppy.readthedocs.io/en/stable/) - Without this python toolbox , not possible to derive new features.

 
