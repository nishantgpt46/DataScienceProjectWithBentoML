Project Description:- Iris Flower Classification using BentoML 

This project is a basic implementation of the Iris Flower Classification using the BentoML framework. The objective is to develop and deploy a machine learning model that classifies iris flowers based on their physical features. Initially, the model is hosted on a local machine, with plans for deployment on a cloud platform at a later stage. The project uses Swagger UI and API integration to make the model accessible for interactive predictions and testing.

Dataset Overview :-
The Iris Dataset is a well-known dataset in machine learning, consisting of 150 records of iris flowers across three species:

1-Setosa

2-Versicolor

3-Virginica 

Each record contains information on the flower's physical features.

Key Features :-
The dataset includes four features that describe the physical characteristics of each flower:

  1-Sepal Length (in centimeters)
  
  2-Sepal Width (in centimeters)
  
  3-Petal Length (in centimeters)
  
  4-Petal Width (in centimeters)

Target Variable :-
The target variable in this dataset is the species of the iris flower, which can be one of the three species mentioned above. The goal of this project is to use the four features to predict the species of an iris flower.

Predictive Task:-
The predictive task for this dataset is to classify each flower into one of the three species based on its sepal and petal measurements. This makes it a multiclass classification problem.

Technology Stack:-

  1-BentoML for model serving and deployment.
  
  2-Swagger UI for interactive API documentation.
  
  3-Machine Learning Model trained on the Iris dataset.


This project demonstrates how to create a simple machine learning service using BentoML and provides an interactive interface via Swagger UI to test the model’s predictions. The initial local hosting will later be transitioned to a cloud platform for wider accessibility.
