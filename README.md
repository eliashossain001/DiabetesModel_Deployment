<br />
<p align="center">
  <a href="https://github.com/eliashossain001/DiabetesModel_Deployment">
   
  </a>

  <h3 align="center">Diabetes-prediction Web Application</h3>

  <p align="center">
    Forecasting diabetes using machine learning algorithms 
    <br />
    <a href="https://diabetes-prediction01.herokuapp.com/"><strong>View the Web App »</strong></a>
    <br />
    <br />
    <a href="https://github.com/eliashossain001/DiabetesModel_Deployment">View Codes</a>
    ·
    <a>Report Bug -> elias.hossain191@gmail.com</a>
    
  </p>
</p>


### Abstract 

Diabetes Mellitus is one of the most severe diseases, and many studies have been conducted to anticipate diabetes. This research aimed to develop an intelligent mobile application based on machine learning to determine the diabetic, pre-diabetic, or non-diabetic without the assistance of any physician or medical tests. This study's methodology was classified into two the Diabetes Prediction Approach and the Proposed System Architecture Design. The Diabetes Prediction Approach uses a novel approach, Light Gradient Boosting Machine (LightGBM), to ensure a faster diagnosis. The Proposed System Architecture Design has been combined into seven modules; the Answering Question Module is a natural language processing Chabot that can answer all kinds of questions related to diabetes. The Doctor Consultation Module ensures free treatment related to diabetes. In this research, 90% accuracy was obtained by performing K-fold cross-validation on top of the K nearest neighbor's algorithm (KNN) & LightGBM. To evaluate the model's performance, Receiver Operating Characteristics (ROC) Curve and Area under the ROC Curve (AUC) were applied with a value of 0.948 and 0.936, respectively. This manuscript presents some exploratory data analysis, including a correlation matrix and survey report. Moreover, the proposed solution can be adjustable in the daily activities of a diabetic patient. 

<a href="https://www.techscience.com/cmc/v72n1/46912">Download Full Paper</a>

### Deployment Architecture 

![arch](https://user-images.githubusercontent.com/54431128/193549116-df1493f9-fcdf-4994-b895-9abbdc9e374c.PNG)

Model deployment for Machine Learning involves a pipeline that begins with data collection and continues with exploratory data analysis (EDA) and model application in the real world. We choose Heroku Server because to its free plan for learning and getting started. Heroku is a platform that helps developers hone their abilities to create applications with numerous features. The experience will benefit developers because they will have access to useful resources for accelerating critical development processes. The free edition of Heroku is appropriate for smaller software projects. Additionally, developers may choose from a variety of tiered packages that are optimally matched to the different needs of major businesses. The Heroku platform's user-friendly interface permits scaling, management, and application monitoring. We chose this server for this research because it can be used mostly for free with a variety of modules, despite the fact that Heroku offers many more platforms as alternatives. After deploying the Flask API, the following steps must be completed for our Flask Application Programming Interface (API) to connect with the Java Client. Flask is a Python web framework that contains tools for developing web applications, such as support for handling HTTP requests and template rendering. The most common alternatives to Flask include Django, Tornado, Express JS, Node.js, and React. According to us, the greatest advantage of the flask is its design, which is both lightweight and modular. In addition, it features outstanding community support and documentation for developers. Flask's compliance with Web Server Gateway Interface (WSGI) makes it straightforward to deploy in production.



### Framework/Language

* [Python](python)
* [Flask](flask)


<!-- GETTING STARTED -->
## Getting Started

To access this project, first Clone the repository and extract in your local PC. 

### Prerequisites

This is the list of things you need to use the software and how to install them.
* Python
```
Version python 3.8 >
```
* Pandas
* sklearn
* numpy
* matplotlib
* flask

### Installation
 
1. Clone the repository 
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

Your Name - Elias Hossain 

Project Link: [https://github.com/eliashossain001/DiabetesModel_Deployment](https://diabetes-prediction01.herokuapp.com/)


## References
* Stackoverflow
* flask
* Medium/Towards data science
