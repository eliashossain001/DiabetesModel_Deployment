<br />
<p align="center">
  <a href="https://github.com/eliashossain001/DiabetesModel_Deployment">
   
  </a>
     <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcScDpcfouWyxASZ6BWhVRP__l2USpXwXEJkEfDmJVZWuYt_5Z7IWvdNeksjykcjPO2ddDY&usqp=CAU" alt="diabates">  
  <h3 align="center">Diabetes-prediction Web Application</h3>

  <p align="center">
    Forecasting diabetes using machine learning algorithms 
    <br />
    <a href="https://diabetes-prediction01.herokuapp.com/"><strong>View Deployment»</strong></a>
    <br />
    <br />
    <a href="https://github.com/eliashossain001/DiabetesModel_Deployment">View Codes</a>
    ·
    <a>Report Bug -> elias.hossain191@gmail.com</a>
    
  </p>
</p>


### Abstract 
Diabetes Mellitus is one of the most severe diseases, and many studies have been conducted to anticipate diabetes. This research aimed to develop an intelligent mobile application based on machine learning to determine the diabetic, pre-diabetic, or non-diabetic without the assistance of any physician or medical tests. This study’s methodology was classified into two the Diabetes Prediction Approach and the Proposed System Architecture Design. The Diabetes Prediction Approach uses a novel approach, Light Gradient Boosting Machine (LightGBM), to ensure a faster diagnosis. The Proposed System Architecture Design has been combined into seven modules; the Answering Question Module is a natural language processing Chabot that can answer all kinds of questions related to diabetes. The Doctor Con- sultation Module ensures free treatment related to diabetes. In this research, 90% accuracy was obtained by performing K-fold cross-validation on top of the K nearest neighbor’s algorithm (KNN) & LightGBM. To evaluate the model’s performance, Receiver Operating Characteristics (ROC) Curve and Area under the ROC Curve (AUC) were applied with a value of 0.948 and 0.936, respectively. This manuscript presents some exploratory data analysis, including a correlation matrix and survey report. Moreover, the proposed solution can be adjustable in the daily activities of a diabetic patient. 

<a href="https://www.techscience.com/cmc/v72n1/46912"><strong>Download the full paper»</strong></a>


### Overall Architecture 

<center><img width="380" alt="Diabete" src="https://user-images.githubusercontent.com/54431128/193620080-41f5eae8-c1e7-4fa2-9f93-c45ebd1856ac.PNG"> </center>

Experimentation Setup, Data Preprocessing, Algorithm Selection, and Model Deployment are the four components of the Diabetes Prediction Method. This research utilizes the dataset as described in the Research Dataset Section. In the Data Preprocessing section, the data preprocessing pipeline is explained in depth. The Algorithm Selection section describes all the machine learning algorithms utilized in this study. A model is finally deployed and connects with a mobile application, as described in the section on model deployment. There are numerous reasons to employ a variety of machine learning algorithms in this research, and specific algorithms have been regularly employed for this type of work in the past. Those who undertake study will rapidly comprehend all these soft computing's performance. This research also adopted the LightGBM algorithm, which was effective while developing the model and estimating the likelihood of diabetes. 


### Framework/ Language

* [Python](python)
* [Flask](flask)



<!-- GETTING STARTED -->
## Getting Started

Clone the repo and extract it ....

### Prerequisites

This is the list of things you need to use the software and how to install them.
* Python
```
Version python 3+
```
* Pandas
* sklearn
* numpy
* matplotlib
* flask

### Installation
 
1. Clone the repo
```
https://github.com/eliashossain001/DiabetesModel_Deployment.git
```
2. Install Python Libraries
```
pip install pandas,sklearn,numpy,matplotlib,flask

```

3. Required Imports:
```
import numpy as np
import pandas as pd
import matplolib.pyplot as plt
from flask import Flask,request, url_for, redirect, render_template
import pickle
```
## Lead Author

Elias Hossain 



<!-- CONTACT -->
## Contact

Name - Elias Hossain 

Email: elias.hossain191@gmail.com 


## References
* Stackoverflow
* flask
