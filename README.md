# Disaster-Response-


Part of Udacity's Data Science Nano Degree

Pipelines
* ETL Pipeline
* NLP Pipeline
* ML Pipeline


### Language:
Python

### Platform: 
Jupyter Notebook

Libraries:
* Pandas
* re
* nltk
* sklearn
* sqlalchemy
* pickle

### Project motivation

The aim of this project is to build a ML-NLP model that classifies disaster messages into certain given categories.
I've analyzed disaster data from Figure Eight to build model off Random Forest Classifier to classifies disaster messages.
With the help of a web app, a user can get their input messages classified into several categories.


### File descriptions

Readme.md (this file)

* ETL Pipeline Preparation.ipynb (python Jupyter-Notebook for ETL pipeline)

* ML Pipeline Preparation.ipynb (python Jupyter-Notebook for ML pipeline)

* disaster_ETL.db (saved ETL data)

* disaster_model.pkl (model saved in a pickle file)  --  not included (file size restrictions)


data.zip file containing 
* messages.csv
* categories.csv

Misc files (to run on the web app)
* app
* data
* model



### Instructions

To execute the web app follow the instructions:

Run the following commands in the project's root directory to set up your database and model.

To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl
Run the following command in the app's directory to run your web app. python run.py

Go to http://0.0.0.0:3001/


### Acknowledgement 
UDACITY

FIGURE EIGHT (APPEN)
