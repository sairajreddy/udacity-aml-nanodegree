## Project Overview

Carnegie Learning's Math Tutor (Mathia So ware ITS) is intented to help high school students learn Math better. PSLC Datashop platform is meant for Education Data Scientists to look for learning analytics' data. From a research point of view, the methods to achieve low prediction error on unseen education data is still at early stages. Sophisticated ML models could be saving millions of hours of students’ time (and effort) in learning. And we have the potential to influence lesson design, improving retention, increasing student engagement, reducing wasted time, and increasing transfer to future lessons. This project aims to experiment with such an approach.

## Problem Statement

Students who used the Mathia Tutor to solve problems -- their interactions were recorded as logs. This log data was mined to get insights. The aim was to predict students' correct first attempt (CFA) while solving the math. CFA is a feature in the dataset which is recorded in terms of bit or boolean (0 or 1). Therefore, precise problem domain involved is classification.

Probability can be calculated by sklearn. We can find some models or methods at Sklearn Home and sklearn.svm.libsvm.predict_proba() So, we can get model’s performance metric like log loss on unseen data for measurement.

## Datasets 

Download the data from http://pslcdatashop.web.cmu.edu/KDDCup/downloads.jsp

| Data set            	| Students 	| Steps     	| File                  	|
|---------------------	|----------	|-----------	|-----------------------	|
| Algebra I 2008-2009 	| 3,310    	| 9,426,966 	| algebra_2008_2009.zip 	|


Stamper, J., Niculescu-Mizil, A., Ritter, S., Gordon, G.J., & Koedinger, K.R. (2010). Algebra I 2008-2009. Challenge data set from KDD Cup 2010 Educational Data Mining Challenge. 

Move the dataset into root or primary directory of this project.
Working in Anaconda Virtual Environment is recommended. 

## Requirements

* Python3.6
* numpy 
* pandas 
* matplotlib
* pickle
* itertools
* sklearn
* catboost 

Everything can be installed as pip install <package names>

#### Catboost installation and examples :
https://github.com/catboost/catboost
https://github.com/catboost/catboost/tree/master/catboost/tutorials
