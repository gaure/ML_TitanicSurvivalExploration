# ML_TitanicSurvivalExploration
Created as part of the Udacity Machine Learning Engineer Nanodegree.

Explore a subset of the Titanic passenger manifest to determine which features best predict whether someone survived or did not survive.

The ML_TitanicSurvivalExploration is an educational project; its purposes is to illustrate the theory behind the operation of a machine learning classification algorithms.
The project consists of:

1. A jupyter notebook, some auxiliary code and an HTML file (notebook HTML representation.)
2. The project was coded in python 2.6.
3. The source data of the project is also in the repository; this consists of a dataset contained information about the Titanic passengers manifest and demographic data about them as a feature that tells if the particular passenger survives or not. What follows is a description of the dataset.

    Survived: Outcome of survival (0 = No; 1 = Yes)
    Pclass: Socio-economic class (1 = Upper class; 2 = Middle class; 3 = Lower class)
    Name: Name of passenger
    Sex: Sex of the passenger
    Age: Age of the passenger (Some entries contain NaN)
    SibSp: Number of siblings and spouses of the passenger aboard
    Parch: Number of parents and children of the passenger aboard
    Ticket: Ticket number of the passenger
    Fare: Fare paid by the passenger
    Cabin Cabin number of the passenger (Some entries contain NaN)
    Embarked: Port of embarkation of the passenger (C = Cherbourg; Q = Queenstown; S = Southampton)


I learned two fundamental concepts of Machine Learning during the execution of this project. The first one was the used of jupyter notebook and a method to explore data using python's pandas and numpy modules; the second concept is related with the creation of a data prediction model and how to measure the accuracy of the model.

During this exercise I programmed two primary functions:

1. The "accurate" function compares the prediction results versus the expected values; then it counts the ones that match and calculate its media. The result is the most basic measure of accuracy used in a machine learning classification model.

2. The "prediction" function, this is a set of conditional operators that based on my selection of features tries to predict which passengers survived versus the one that did not. The purpose of this function is to emulate the output that a machine learning classification model would have produced. It is important to note that none of the machine learning prediction models work as this function under the hood. Machine Learning prediction models as Random Forrest, Bayes Networks, Support Vector Machine, Neural Networks, etc.; are functionally different from this code, nonetheless as a system to illustrate how accuracy and prediction work together the function is useful. 

