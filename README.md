# Reducing Commercial Aviation Fatalities

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Goals](#goals)
  * [Technical Aspect](#technical-aspect)
  * [To Do](#to-do)
  * [Technologies Used](#technologies-used)
  * [Credits](#credits)
  
## Overview

Most of the flight fatalities or flight accidents due to pilot error are due to the loss of airplane state awareness. Airplane state awareness (ASA) is a pilot performance attribute wherein the pilot should be able to realize and respond quickly to any change of state of the airplane. Loss of airplane state awareness may lead to many dangerous situations and may result in loss of airplane control. Loss of ASA is mainly due to loss of attention on the part of pilots who may be distracted, sleepy, or in other dangerous cognitive states. Due to the stressful environment, while flying, the possibility of the loss of awareness is common.So our challenge is to build a model to detect troubling events from aircrew's physiological data. For this project we used [LightGBM](https://lightgbm.readthedocs.io/en/latest/) for modelling. Model want to predict the cognitive state __( Baseline , Startle/Surprise (SS) , Channelized Attention (CA) , Diverted Attention (DA) )__ of a pilot using physiological data.

The data for the project was provided by Kaggle. One of the important tasks in the project is feature engineering, __How to derive new features from existing features?__ since most of the data is collected over biological sensors it is quite interesting to me learn new things about how these data are collected and derive new features. For deriving new features, we used the python [BioSPPy](https://biosppy.readthedocs.io/en/stable/) module.

## Motivation


