## Comparison of baseline and top solutions for household poverty prediction

Basiline and top performing model are compared in terms of transparency, fairness and accuracy. 
Use case considered is prediction of houshold poverty level in Costa Rica.


Inspired by increasing importance of responsible development of Data Science project, 
and classical approach to creating a solution starting from a baseline and iteratively moving to a sophisticated one.

All neccessary data can be found in the [data](https://github.com/OlehLuk/responsible-prediction-analysis/tree/master/data) folder, as well as work done in jupyter notebooks in [src](https://github.com/OlehLuk/responsible-prediction-analysis/tree/master/src). Main tool used for investigation of responsible development aspects was [SHAP](https://github.com/slundberg/shap) library.

As main part of the work is analysis of the observed results and investigated cases, please address our [technical report](https://github.com/OlehLuk/responsible-prediction-analysis/tree/master/report) as an integral part of the project results.


### Abstract of the report
This project is dedicated to comparison of models of different complexity in context of fairness and transparency. Prediction of the family’s poverty level in Costa Rica was chosen as the use case for consideration. The corresponding Kaggle competition resulted in several baseline models as well as top performing ones. In this work baseline and sophisticated solutions are investigated from the point of view of responsible data science. This creates a precedent of model selection and tuning based not only on quality metrics, but meta conditions, caused by developers responsibility. In addition, application of existing tools, in particular SHAP, to ease decision making for both types of models is discussed. Results and conclusions of the investigation are described in this report.


References:
* [Problem formulation](https://www.kaggle.com/c/costa-rican-household-poverty-prediction)
* [Solution analyzed](https://www.kaggle.com/willkoehrsen/a-complete-introduction-and-walkthrough)
* [SHAP](https://github.com/slundberg/shap)
