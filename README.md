# Azure Machine Learning Part I - ML Model

## Story

Cars R Us have invested in a new machine learning model to help them with pricing vehicles.

They have a simple web front end and a poorly trained Linear Regression pricing algorithm which has learnt its information from some sample car data they have.

The dealership could really use your help to get their web app into a Dev-Ops CI/CD pipeline, deploy their machine learning model and have the web app package itself up with the latest version of the model as currently it is cumbersome and fraught with difficulties when trying to do a release.

They have also realised that their model is not quite as accurate as it could be and they are certain they are losing money hand over fist.

It has also been requested a new model is trained up and deployed without adversely affecting their business.

## Technology  
Their front end is a Python Flask Web application which they wish to keep, the Machine Learning Model was developed using Azure Notebooks. For an AI application like this, there are always two streams of work, Data Scientists building machine learning models and App developers building the application and exposing it to end users to consume and test.

The overall target is to build a continuous integration pipeline for an AI application. 

## Getting Started  
* Import the Jupyter Notebooks into Azure Notebooks and run through the pre created scenarios to Generate our Machine Learning Model and test Data which is crucial to the Web App in part II.
* The model creation and push to blob storage are the most important elements in here.

## Goal  
* Create a ML model file and test data files using the notebooks that are provided
* Push the Model file and associated test data files into a Blob storage account
* Part II Web app should now be able to consume the files produced in this step

## Change Scenario  
The model is around 85 - 87% accurate.... these are rookie numbers, can you increase this model so Cars R Us dont lose as much money?
