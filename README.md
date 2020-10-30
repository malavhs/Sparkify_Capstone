# Sparkify_Capstone

The medium article related to the project is linked as follows:
# Medium article link: https://malavhirenshah.medium.com/training-a-spark-model-for-predicting-user-churn-4f275b5a571a

This README file intends to comminute the information about the libraries used in the code, the motivation of the project as well as the descriptions of the files present in this repository.

## 1. Libraries 

The libraries used in this project include:
* Pyspark
* Tabulate
* Seaborn
* Numpy
* Pandas
* Matplotlib
* PysparkML
Threading libs

## 2. Project Motivation:

This project is part of the Udacity Data Scientist Nanodegree. In this project, we predict churn for users of a particular music streaming application. In general, we have a lot of user data from any application and we can use that to predict user patterns and this is one such example wherein we have a lot of data about their interaction with a music streaming application and this can then be used to predict which users churned and what caused them to churn etc. This project includes using SparkML to create a machine learning model to create new features from existing features and using that to predict churn of users of a music streaming application. In addition to this, we deploy the solution to the IBM cloud in order to use the entire data set, which is bigger in size in order to train the model. 

## 3. File Descriptions:

a. **Sparkify.ipynb** - This notebook contains code which performs various steps like Cleaning the data, pre processing as well as training the model on the "small" data set that we have been given. It also contains a lot of visualizations that help me understand the relationships between various features.

b. **Sparkify_Large.ipynb** - This notebook contains code which performs various steps like Cleaning the data, pre processing as well as training the model on the "Large" data set that we have been given and that is trained on IBM Watson using the instructions in the Capstone. It also contains a lot of visualizations that help me understand the relationships between various features.

c. **mini_sparkify_event_data.json** - The json file for the "small" dataset (Given by Udacity -- not on here due to size restrictions)

d. **Sparkify.html** - The html version of the notebook in (a)

e. **Sparkify_Large.html** - The html version of the notebook in (b)
